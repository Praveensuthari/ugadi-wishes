<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Happy Ugadi - 2025</title>
  <link rel="stylesheet" href="styles.css" />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet">
</head>
<body>
  <div class="container">
    <img src="ugadi.png" alt="Ugadi Wishes" class="ugadi-img" />
    <h1>🌸 Happy Ugadi! 🌸</h1>
    <p>Wishing you a prosperous and joyful new year ahead. Have a wonderful Ugadi! 🎊</p>
  </div>
</body>
</html>
body {
  background: radial-gradient(circle, #ffecc7, #ffbb91);
  font-family: 'Poppins', sans-serif;
  color: #333;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0;
  padding: 0;
  overflow: hidden;
  text-align: center;
}

.container {
  background: white;
  padding: 2rem;
  border-radius: 1.5rem;
  box-shadow: 0 8px 24px rgba(0,0,0,0.2);
  animation: scaleUp 1s ease-in-out forwards;
}

.ugadi-img {
  width: 200px;
  height: auto;
  border-radius: 1rem;
  margin-bottom: 1rem;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  animation: rotate 10s linear infinite;
}

h1 {
  color: #ff4500;
  margin-bottom: 0.5rem;
  text-shadow: 1px 1px #ffc600;
}

p {
  font-size: 1.2rem;
  color: #555;
}

@keyframes scaleUp {
  from {
    opacity: 0;
    transform: scale(0.8);
  }
  to {
    opacity: 1;
    transform: scale(1);
  }
}

@keyframes rotate {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}
