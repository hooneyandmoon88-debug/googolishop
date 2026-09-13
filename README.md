body {
  background: #fff8fc;
  color: #4b3b47;
  font-family: "Vazirmatn", sans-serif;
}

:root {
  --pink: #f58bb0;
  --light-pink: #ffe4ef;
  --purple: #cbb8f5;
  --cream: #fff7e8;
  --white: #ffffff;
}

.card,
.product,
.box {
  background: var(--white);
  border: 2px solid #f8dce8;
  border-radius: 24px;
  box-shadow: 0 8px 25px rgba(245, 139, 176, 0.12);
  transition: 0.3s ease;
}

.card:hover,
.product:hover {
  transform: translateY(-6px);
  box-shadow: 0 14px 30px rgba(245, 139, 176, 0.2);
}

button {
  background: var(--pink);
  color: white;
  border: none;
  border-radius: 18px;
  padding: 12px 22px;
  font-weight: bold;
  cursor: pointer;
  transition: 0.25s;
}

button:hover {
  background: #ec6d99;
  transform: scale(1.04);
}

header {
  background: rgba(255, 255, 255, 0.9);
  border-bottom: 2px solid #ffe1ec;
  backdrop-filter: blur(10px);
}

h1, h2, h3 {
  color: #d95788;
}

a {
  color: #9b7bd3;
}

.badge {
  background: #ffe4ef;
  color: #d95788;
  border-radius: 50px;
  padding: 7px 14px;
}
<nav class="tabs">
  <a href="#home">خانه 🏠</a>
  <a href="#products">محصولات 👗</a>
  <a href="#categories">دسته‌بندی‌ها 🌸</a>
  <a href="#offers">تخفیف‌ها 🎁</a>
  <a href="#about">درباره ما 💗</a>
  <a href="#contact">تماس با ما 📞</a>
  <a href="#cart">سبد خرید 🛍️</a>
</nav>

<style>
.tabs {
  display: flex;
  justify-content: center;
  gap: 10px;
  flex-wrap: wrap;
  direction: rtl;
  padding: 15px;
  background: #fff8fc;
}

.tabs a {
  text-decoration: none;
  color: #d95788;
  background: #ffe7f0;
  padding: 10px 18px;
  border-radius: 20px;
  font-family: sans-serif;
  font-weight: bold;
  transition: 0.3s;
}

.tabs a:hover {
  background: #f58bb0;
  color: white;
  transform: translateY(-3px);
}
</style>
