# Project Responsive Web Design using Bootstrap
## Date:25.12.2024

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
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Inspiration</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Work</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Learn</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link btn btn-primary text-white" href="#">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="bg-danger py-5">
        <div class="container text-center">
            <h1 class="display-4">Discover the World's Top Designers & Creative Work</h1>
            <p class="lead mt-3">Explore portfolios, get inspired, and showcase your own creative projects.</p>
            <a href="#" class="btn btn-primary btn-lg mt-3">Get Started</a>
        </div>
    </header>

    <!-- Featured Projects -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Featured Projects</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card">
                        <img src="graptheory.webp" class="card-img-top" alt="Project 1">
                        <div class="card-body">
                            <h5 class="card-title">graptheory</h5>
                            <p class="card-text">developers can more easily learn about it.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="nixtio.webp" class="card-img-top" alt="Project 2">
                        <div class="card-body">
                            <h5 class="card-title">nixtio</h5>
                            <p class="card-text">We’re Nixtio - your digital experience partner.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="lisa.webp" class="card-img-top" alt="Project 3">
                        <div class="card-body">
                            <h5 class="card-title">lisa</h5>
                            <p class="card-text">This is the goal of ESA’s future mission.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-light py-4">
        <div class="container text-center">
            <p class="mb-0">&copy; Designed and Developed by Harisudhan S</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<portfolio/portapp/static/Screenshot (136).png>)
![alt text](<portfolio/portapp/static/Screenshot (137).png>)
![alt text](<portfolio/portapp/static/Screenshot (138).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
