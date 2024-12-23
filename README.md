# Project Responsive Web Design using Bootstrap
## Date:23/12/24

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero {
      background: linear-gradient(to right, #6a11cb, #2575fc);
      color: white;
      padding: 100px 0;
    }
    .hero h1 {
      animation: fadeIn 2s ease-in-out;
    }
    .hero p {
      animation: fadeIn 2.5s ease-in-out;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .navbar {
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    footer {
      background: #f8f9fa;
    }
  </style>
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
  <div class="container">
    <a class="navbar-brand fw-bold" href="#">Dribbble</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#">About</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Explore</a></li>
        <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#">Sign Up</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="hero text-center">
  <div class="container">
    <h1 class="display-4">Discover Top Designers</h1>
    <p class="lead mt-3">Join the world's leading creative community and showcase your projects.</p>
    <a href="#" class="btn btn-lg btn-light text-primary mt-4">Get Started for Free</a>
  </div>
</div>

<div class="container my-5">
  <h2 class="text-center mb-4">Featured Projects</h2>
  <div id="projectCarousel" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="thumb1.webp" class="d-block w-100" alt="Project 1">
      </div>
      <div class="carousel-item">
        <img src="thumb2.webp" class="d-block w-100" alt="Project 2">
      </div>
      <div class="carousel-item">
        <img src="thumb3.webp" class="d-block w-100" alt="Project 3">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#projectCarousel" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#projectCarousel" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
    </button>
  </div>
</div>

<div class="container my-5">
  <h2 class="text-center mb-4">Contact Us</h2>
  <form>
    <div class="row">
      <div class="col-md-6 mb-3">
        <input type="text" class="form-control" placeholder="Your Name" required>
      </div>
      <div class="col-md-6 mb-3">
        <input type="email" class="form-control" placeholder="Your Email" required>
      </div>
    </div>
    <div class="mb-3">
      <textarea class="form-control" rows="4" placeholder="Your Message"></textarea>
    </div>
    <div class="text-center">
      <button type="submit" class="btn btn-primary">Submit</button>
    </div>
  </form>
</div>

<footer class="text-center py-4">
  <div class="container">
    <p class="mb-2">&copy; 2024 Dribbble Clone. All rights reserved.</p>
    <p>Designed by Harshul SL</p>
  </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:
![alt text](image.png)
![alt text](image-2.png)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
