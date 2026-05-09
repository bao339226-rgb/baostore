<section class="cyber-landing">
  <div class="container">
    <div class="product-showcase">
      <div class="product-image">
        <img src="your-image-url.jpg" alt="Cyberpunk Sticker">
        <div class="badge">LIMIT EDITION</div>
      </div>
      <div class="product-info">
        <h1 class="neon-text">CYBERPUNK AVATAR <br><span>STICKER PACK</span></h1>
        <p class="description">
          Nâng cấp góc làm việc của bạn với bộ sticker phong cách Futuristic. 
          Chống nước tuyệt đối, bền màu, chuẩn gu "Hội Thất Nghiệp".
        </p> 
        <div class="price-tag">
          <span class="old-price">150.000đ</span>
          <span class="new-price">99.000đ</span>
        </div>
        <button class="btn-cyber">
          <span class="btn-text">MUA NGAY - GIẢM 35%</span>
          <span class="btn-glitch"></span>
        </button>
      </div>
    </div>
  </div>
</section>
<style>:root {
  --neon-cyan: #00f5ff;
  --neon-pink: #ff00ff;
  --bg-dark: #0b0e14;
}

.cyber-landing {
  background-color: var(--bg-dark);
  color: white;
  font-family: 'Segoe UI', Roboto, sans-serif;
  padding: 50px 20px;
}

/* Hiệu ứng chữ Neon */
.neon-text {
  font-size: 3rem;
  text-transform: uppercase;
  color: #fff;
  text-shadow: 0 0 10px var(--neon-cyan), 0 0 20px var(--neon-cyan);
}

.neon-text span {
  color: var(--neon-pink);
  text-shadow: 0 0 10px var(--neon-pink);
}

/* Nút bấm phát sáng */
.btn-cyber {
  background: transparent;
  border: 2px solid var(--neon-cyan);
  color: var(--neon-cyan);
  padding: 15px 30px;
  font-weight: bold;
  cursor: pointer;
  position: relative;
  transition: 0.3s;
  overflow: hidden;
  box-shadow: 0 0 15px rgba(0, 245, 255, 0.3);
}

.btn-cyber:hover {
  background: var(--neon-cyan);
  color: black;
  box-shadow: 0 0 30px var(--neon-cyan);
}

/* Hiệu ứng ảnh sản phẩm */
.product-image img {
  border: 1px solid var(--neon-cyan);
  border-radius: 8px;
  filter: drop-shadow(0 0 15px rgba(0, 245, 255, 0.2));
}
</style>
