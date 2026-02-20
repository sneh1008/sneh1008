<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Image Banner</title>

<style>
body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
}

/* Banner Section */
.banner {
  width: 100%;
  height: 500px;
  background-image: url("https://drive.google.com/uc?export=view&id=1Apzp16MiL7q4zLMa6VecS7eCRl1thb88");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
}

/* Dark overlay */
.banner::after {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.5);
  top: 0;
  left: 0;
}

/* Content */
.banner-content {
  position: relative;
  color: white;
  text-align: center;
  z-index: 2;
}

.banner-content h1 {
  font-size: 50px;
  margin-bottom: 20px;
}

.banner-content p {
  font-size: 20px;
  margin-bottom: 25px;
}

.banner-content a {
  padding: 12px 30px;
  background: #ff6600;
  color: white;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
  transition: 0.3s;
}

.banner-content a:hover {
  background: #e65c00;
}

/* Responsive */
@media (max-width: 768px) {
  .banner {
    height: 350px;
  }
  .banner-content h1 {
    font-size: 32px;
  }
  .banner-content p {
    font-size: 16px;
  }
}
</style>

</head>
<body>

<section class="banner">
  <div class="banner-content">
    <h1>Welcome to My Website</h1>
    <p>Your subtitle or tagline goes here</p>
    <a href="#">Learn More</a>
  </div>
</section>

</body>
</html>
