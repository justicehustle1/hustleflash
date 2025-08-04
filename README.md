<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>HustleFlash</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: url('https://images.unsplash.com/photo-1554224154-22dec7ec8818?auto=format&fit=crop&w=1400&q=80') no-repeat center center fixed;
      background-size: cover;
      font-family: Arial, sans-serif;
      color: white;
      height: 100vh;
      position: relative;
    }

    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      height: 100%;
      width: 100%;
      background-color: rgba(0, 0, 0, 0.6); /* Dark overlay */
      z-index: 1;
    }

    .content {
      position: relative;
      z-index: 2;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
      padding: 20px;
    }

    h1 {
      font-size: 3rem;
      text-transform: uppercase;
      letter-spacing: 2px;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.2rem;
      max-width: 600px;
    }
  </style>
</head>
<body>
  <div class="overlay"></div>
  <div class="content">
    <h1>HustleFlash</h1>
    <p>Smartphone Hustles | Affiliate Marketing | Money Tips for Broke Youths</p>
  </div>
</body>
</html>
