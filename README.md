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
