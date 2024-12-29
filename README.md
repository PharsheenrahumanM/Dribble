# Project Responsive Web Design using Bootstrap
## Date:29/12/24

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
    <title>Dribbble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <body>
    <nav class="navbar navbar-expand-lg bg-light shadow-sm">
        <div class="container">
            <a class="navbar-brand fw-bold text-primary" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item"><a class="nav-link text-dark" href="#">Discover</a></li>
                    <li class="nav-item"><a class="nav-link text-dark" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link text-dark" href="#">Projects</a></li>
                </ul>
                <input type="search" class="form-control w-auto me-3" placeholder="Search">
                <a class="btn btn-outline-primary me-2" href="#">Sign in</a>
                <a class="btn btn-primary" href="#">Sign Up</a>
            </div>
        </div>
    </nav>
    <header class="bg-primary text-white py-5">
        <div class="container text-center">
            <h1 class="display-4 fw-bold">Showcase Your Creativity</h1>
            <p class="lead">Find inspiration, connect with creatives, and share your designs with the world.</p>
            <a href="#popular" class="btn btn-light btn-lg">Explore Now</a>
        </div>
    </header>
    <header class="bg-dark text-white py-3">
        <div class="container text-center">
            <h1>Dribbble</h1>
            <p>Discover the world’s top designers & creatives</p>
        </div>
    </header>

    <main class="container my-4">
        <div class="row">
            
            <div class="col-md-4">
                <div class="card">
                    <img src="101.jpeg" class="card-img-top" alt="Design 1">
                    <div class="card-body">
                        <h5 class="card-title">Aesthetic Sweatshirts</h5>
                        <a href="#" class="btn btn-danger">View More</a>
                    </div>
                </div>
            </div>

            
            <div class="col-md-4">
                <div class="card">
                    <img src="102.jpeg" class="card-img-top" alt="Design 2">
                    <div class="card-body">
                        <h5 class="card-title">Combos</h5>
                        <a href="#" class="btn btn-danger">View More</a>
                    </div>
                </div>
            </div>

            
            <div class="col-md-4">
                <div class="card">
                    <img src="103.jpeg" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <h5 class="card-title">Sneakers</h5>
                        <a href="#" class="btn btn-danger">View More</a>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="104.jpeg" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <h5 class="card-title">Boys Accessories</h5>
                        <a href="#" class="btn btn-danger">View More</a>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="105.jpeg" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <h5 class="card-title">Hoodies</h5>
                        <a href="#" class="btn btn-danger">View More</a>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="106.jpeg" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <h5 class="card-title">Crocs</h5>
                        <a href="#" class="btn btn-danger">View More</a>
                    </div>
                </div>
            </div>

            
    </main>

    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2024 Dribbble. All Rights Reserved.<br>
                   Designed by PharsheenRahumanM.</p>
    </footer>
</body>
</html>

```

## OUTPUT:
![webp1](https://github.com/user-attachments/assets/edb0e834-1765-4fd5-9e47-c391e7ab63f8)

![webp2](https://github.com/user-attachments/assets/088b7bec-1cda-4db0-9fa7-6b5f9a191ad0)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
