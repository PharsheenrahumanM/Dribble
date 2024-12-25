# Project Responsive Web Design using Bootstrap
## Date:25/12/24

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
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Dribble.io</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  </head>
  <body>
    <nav class="navbar navbar-expand-sm navbar-dark bg-dark">
      <div class="container">
        <a href="#Logo" class="navbar-brand mb-0 h1">
          <img src="logo2.png" width="120" height="30" alt="Logo">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a href="#" class="nav-link active" aria-current="page">Shots</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link">Designer</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link">Sign up</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link">Sign in</a>
            </li>
          </ul>
         
          <div class="ms-auto">
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-primary" type="submit">Search</button>
            </form>
          </div>
        </div>
      </div>
    </nav>

    <section class="text-center py-4 bg-dark text-white">
      <div class="container">
        <p class="lead fw-bold mb-4">What are you working on? Dribbble is show and tell for designers.</p>
        <div class="d-inline-flex gap-2">
          <a href="#" class="btn btn-primary">Learn More</a>
          <a href="#" class="btn btn-outline-danger">Sign Up</a>
        </div>
      </div>
    </section>

    <div class="container py-4">
      <div class="row justify-content-center g-4">
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="101.jpeg" class="card-img-top" alt="Tshirts">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Aesthetic Sweatshirts</h5>
              <a href="#" class="btn btn-primary btn-sm">View</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="102.jpeg" class="card-img-top" alt="">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">combos</h5>
              <a href="#" class="btn btn-primary btn-sm">View</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="103.jpeg" class="card-img-top" alt="">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Shoes</h5>
              <a href="#" class="btn btn-primary btn-sm">View</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="104.jpeg" class="card-img-top" alt="">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Accessories</h5>
              <a href="#" class="btn btn-primary btn-sm">View</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="105.jpeg" class="card-img-top" alt="">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Hoodies</h5>
              <a href="#" class="btn btn-primary btn-sm">View</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="106.jpeg" class="card-img-top" alt="">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Crocs</h5>
              <a href="#" class="btn btn-primary btn-sm">View</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  

    <footer class="bg-dark text-white text-center py-3">
      <h2 class="h6 m-0">Designed by PharsheenRahuman(24006746)</h2>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  </body>
</html>

```

## OUTPUT:
![ex101](https://github.com/user-attachments/assets/c60d64ac-869c-4da7-a1d7-f96b8aafc02f)

![ex102](https://github.com/user-attachments/assets/2a127ea1-6a0f-43cd-8975-d47a298bf88f)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
