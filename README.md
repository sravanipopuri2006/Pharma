# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
home.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - PharmaCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">PharmaCompany</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="home.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Welcome to PharmaCompany</h1>
        <p>Welcome to pharma, where our unwavering commitment to healthcare drives every aspect of our work. With a legacy of innovation spanning decades, we have earned a reputation for excellence in the pharmaceutical industry. Our journey began with a vision to transform healthcare through groundbreaking research and development, and today, we continue to uphold that vision with passion and dedication.

          At pharma, our diverse portfolio of products and services encompasses a wide range of therapeutic areas, from oncology and immunology to cardiovascular health and beyond. Each product is meticulously developed and rigorously tested to meet the highest standards of safety, efficacy, and quality. Our state-of-the-art facilities and cutting-edge technologies enable us to deliver innovative solutions that address unmet medical needs and improve patient outcomes.
          
          Behind every breakthrough is a team of talented scientists, researchers, and healthcare professionals who are driven by a shared mission to make a positive impact on the world. Collaboration and partnership are at the core of our approach, as we work closely with healthcare providers, institutions, and organizations to advance medical science and patient care s we look to the future, our commitment to innovation remains steadfast. We continue to invest in research and development, exploring new frontiers in medicine and pioneering new treatment modalities.elopment, exploring new frontiers in medicine and pioneering new treatment modalities. Through ongoing collaboration.</p>
      </div>
      <div class="col-md-4">
        
      </div>
    </div>
  </div>
  <body background="back pharma img.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>DESIGNED AND DEVELOPED BY ANUBHARATHI SS(212223040017)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</htm/>

about.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About PharmaCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">PharmaCompany</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            About
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#vision">Vision</a>
            <a class="dropdown-item" href="#equipment">equipment</a>
            <a class="dropdown-item" href="#usage">usage</a>
            <a class="dropdown-item" href="#research">research</a>
            <!-- Add more subheadings as needed -->
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </ul>
    <ul class="navbar-nav ml-auto">
      <li class="nav-item">
        <a class="nav-link" href="#">Login</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Register</a>
      </li>
    </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>About PharmaCompany</h1>
        <div id="vision">
          <h2>Vision</h2>
          <p>To revolutionize healthcare by providing innovative pharmaceutical solutions that improve patient outcomes and quality of life on a global scale.</p>
        </div>
        <div id="equipments">
          <h2>equipments</h2>
          <p>Our pharmacy is equipped with cutting-edge technology, including automated medication dispensing systems, compounding equipment.</p>
        </div>
        <div id="usage">
          <h2>uage</h2>
          <p>Our equipment is utilized to optimize medication dispensing and identify opportunities for intervention to optimize therapy outcomes.
        </div>
        <div id="researches">
            <h2>researches</h2>
            <ul>
              <li>Clinical Trials*: Testing new drugs for safety and effectiveness.</li>
              
              <li>Pharmacological Research*: Studying how drugs work in the body.</li>
              <li>Patient-Centered Research*: Understanding patient needs for better treatments.
              <li>Health Outcomes Research*: Evaluating the real-world impact of treatments</li>
            </li>
            </ul>
          </div>
        </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>
  <body background="back pharma img.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>DESIGNED AND DEVELOPED BY ANUBHARATHI SS(212223040017)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

product.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products - PharmaCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">PharmaCompany</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="product.html">Products <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>Our Products</h1>
        <div class="card-deck">
          <div class="card">
            <img src="PRODUCT 01.jpg" class="card-img-top" alt="Product 1" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">PRODUCT NO : 01</h5>
              <p class="card-text">✔ IMMUNITY BOOST WITH PRE & PROBIOTICS: Probiotics in our Multivitamins for Women & Men help Boost immunity.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="PRODUCT 02.jpg" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">PRODUCT NO : 2</h5>
              <p class="card-text">✔ CHOLESTROL BALANCE: used along with a proper diet to help lower "bad" cholesterol and raise "good" cholesterol  in the blood.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="PRO 03.jpg" class="card-img-top" alt="Product 3" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">PRODUCT NO : 03</h5>
              <p class="card-text">✔ABDOMINAL RELIEF: used to treat abdominal pain, dysmenorrhea (period pain).</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>DESIGNED AND DEVELOPED BY ANUBHARATHI SS(212223040017)</p>
  </footer>
  <body background="back pharma img.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - PharmaCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">PharmaCompany</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="contact.html">Contact <span class="sr-only">(current)</span></a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Contact Us</h1>
        <p>For any inquiries or feedback or any doubt or consultant and research information or further details and any equipments or chemicals or liquid based material purchase, please fill out the correct details below and we will get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name">Your Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>

          <div class="form-group">
            <label for="email">Your Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          
          <div class="form-group">
            <label for="need">Your need</label>
            <input type="need" class="form-control" id="location" placeholder="Message">
          </div>
        
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4"><br>
        <h2>Pharma Company</h2><br><br>
        <address>
          <strong>Company</strong><br>
          SANOFI@PHARMA<br><br>
          <strong>Address:</strong><br>
          No;84 pyara street 
          PONDI
          6023748
          TN,India<br><br>
          <strong>Email:</strong><br>
          sanofipharma@gmail.com<br><br>
          <strong>Phone:</strong><br>
          +1030987697<br>
        </address>
      </div>
    </div>
  </div>
  <body background="back pharma img.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>DESIGNED AND DEVELOPED BY ANUBHARATHI SS(212223040017)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```


## OUTPUT:
![image](https://github.com/sravanipopuri2006/Pharma/assets/139778301/b64c3105-d55e-49dc-a516-1b3f04699bdc)
![image](https://github.com/sravanipopuri2006/Pharma/assets/139778301/c679d3ff-016a-402c-b032-4b4447948093)
![image](https://github.com/sravanipopuri2006/Pharma/assets/139778301/464644d0-148e-49d1-8f66-1b2e8b539a0c)
![image](https://github.com/sravanipopuri2006/Pharma/assets/139778301/5c93dcf3-6163-42d0-824e-23035317a281)






## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
