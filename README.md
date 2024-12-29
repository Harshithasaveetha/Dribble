# Project Responsive Web Design using Bootstrap
## Date:29.12.2024

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
    <title>Innovative Studio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg" style="background-color: #2a9d8f;">
        <div class="container">
            <a class="navbar-brand text-white" href="#">Innovative Studio</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link text-white" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="#services">Services</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="#portfolio">Projects</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="#team">Our Team</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="text-center text-white" style="background: linear-gradient(45deg, #264653, #2a9d8f); padding: 70px 0;">
        <div class="container">
            <h1 class="display-4">Welcome to Innovative Studio</h1>
            <p class="lead">Unleashing creativity, one design at a time</p>
            <a href="#portfolio" class="btn btn-light btn-lg">Discover More</a>
        </div>
    </header>

    <div id="services" class="container my-5">
        <h2 class="text-center mb-4">Our Expertise</h2>
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col">
                <div class="card border-0 shadow">
                    <div class="card-body text-center">
                        <h5 class="card-title">UI/UX Design</h5>
                        <p class="card-text">Crafting intuitive and visually appealing user experiences.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card border-0 shadow">
                    <div class="card-body text-center">
                        <h5 class="card-title">App Development</h5>
                        <p class="card-text">Building innovative and high-performance mobile applications.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card border-0 shadow">
                    <div class="card-body text-center">
                        <h5 class="card-title">Digital Marketing</h5>
                        <p class="card-text">Empowering brands with impactful digital campaigns.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div id="portfolio" class="text-center text-white py-5" style="background-color: #e76f51;">
        <div class="container">
            <h2 class="mb-4">Our Recent Work</h2>
            <div class="row row-cols-1 row-cols-md-3 g-4">
                <div class="col">
                    <div class="card border-0">
                        <img src="i.jpeg" class="card-img-top" alt="Project A">
                        <div class="card-body">
                            <h5 class="card-title">Project Alpha</h5>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card border-0">
                        <img src="123.jpg" class="card-img-top" alt="Project B">
                        <div class="card-body">
                            <h5 class="card-title">Project Beta</h5>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card border-0">
                        <img src="i2.jpeg" class="card-img-top" alt="Project C">
                        <div class="card-body">
                            <h5 class="card-title">Project Gamma</h5>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div id="team" class="container my-5">
        <h2 class="text-center mb-4">Our Dedicated Team</h2>
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col">
                <div class="card border-0 shadow text-center">
                    <img src="e1.jpeg" class="card-img-top rounded-circle mx-auto mt-3" style="width: 100px; height: 100px;" alt="Team Member 1">
                    <div class="card-body">
                        <h5 class="card-title">Alex Johnson</h5>
                        <p class="card-text">Creative Head</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card border-0 shadow text-center">
                    <img src="e2.jpeg" class="card-img-top rounded-circle mx-auto mt-3" style="width: 100px; height: 100px;" alt="Team Member 2">
                    <div class="card-body">
                        <h5 class="card-title">Sophia Lee</h5>
                        <p class="card-text">Tech Lead</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card border-0 shadow text-center">
                    <img src="e3.jpeg" class="card-img-top rounded-circle mx-auto mt-3" style="width: 100px; height: 100px;" alt="Team Member 3">
                    <div class="card-body">
                        <h5 class="card-title">Ethan Walker</h5>
                        <p class="card-text">Strategy Expert</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p>&copy; 2024 develpoed by Harshitha</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot (115).png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
