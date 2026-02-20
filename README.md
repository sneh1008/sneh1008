<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Full Image Banner</title>
  <style>

    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
    }

    /* Banner Styles */
    .banner {
      width: 100%;
      height: 500px; /* Change height as needed */
      background-image: url("https://drive.google.com/uc?export=view&id=1Apzp16MiL7q4zLMa6VecS7eCRl1thb88");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    /* Optional semi-transparent overlay */
    .banner::after {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.5);
    }

    /* Banner text */
    .banner-content {
      position: relative;
      color: #fff;
      text-align: center;
      z-index: 1;
    }

    .banner-content h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }

    .banner-content p {
      font-size: 20px;
    }

  </style>
</head>
<body>

  <!-- Banner Section -->
  <section class="banner">
    <div class="banner-content">
      <h1>Welcome to My Website</h1>
      <p>Your subtitle or tagline here</p>
    </div>
  </section>

</body>
</html>
