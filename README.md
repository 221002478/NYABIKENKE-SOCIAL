<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nyabikenke Hospital</title>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

<style>
body { font-family: Arial, sans-serif; }
.navbar { background-color: #0d6efd; }
.hero {
    background: url('https://images.unsplash.com/photo-1586773860418-d37222d8fce3') no-repeat center center/cover;
    color: white;
    padding: 100px 20px;
    text-align: center;
}
.section { padding: 60px 20px; }
.footer {
    background: #0d6efd;
    color: white;
    text-align: center;
    padding: 20px;
}
.btn-whatsapp {
    position: fixed;
    bottom: 20px;
    right: 20px;
}
</style>
</head>

<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg navbar-dark">
<div class="container">
<a class="navbar-brand" href="#">Nyabikenke Hospital</a>
<button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#nav">
<span class="navbar-toggler-icon"></span>
</button>
<div class="collapse navbar-collapse" id="nav">
<ul class="navbar-nav ms-auto">
<li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
<li class="nav-item"><a class="nav-link" href="#about">About</a></li>
<li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
<li class="nav-item"><a class="nav-link" href="#doctors">Doctors</a></li>
<li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
</ul>
</div>
</div>
</nav>

<!-- HERO -->
<section class="hero" id="home">
<h1>Welcome to Nyabikenke Hospital</h1>
<p>Providing Quality Healthcare for Our Community</p>
<a href="#contact" class="btn btn-light">Book Appointment</a>
</section>

<!-- ABOUT -->
<section class="section bg-light" id="about">
<div class="container">
<h2>About Us</h2>
<p>Nyabikenke Hospital is committed to delivering high-quality healthcare services to the community. We focus on compassion, professionalism, and patient-centered care.</p>
</div>
</section>

<!-- SERVICES -->
<section class="section" id="services">
<div class="container">
<h2>Our Services</h2>
<div class="row">
<div class="col-md-4">
<h5>Maternity</h5>
<p>Safe and professional maternal care services.</p>
</div>
<div class="col-md-4">
<h5>Laboratory</h5>
<p>Modern diagnostic and testing services.</p>
</div>
<div class="col-md-4">
<h5>Emergency</h5>
<p>24/7 emergency medical support.</p>
</div>
<div class="col-md-4">
<h5>Outpatient</h5>
<p>General consultations and treatments.</p>
</div>
<div class="col-md-4">
<h5>Pharmacy</h5>
<p>Affordable and quality medicines.</p>
</div>
</div>
</div>
</section>

<!-- DOCTORS -->
<section class="section bg-light" id="doctors">
<div class="container">
<h2>Our Doctors</h2>
<div class="row">
<div class="col-md-4">
<h5>Dr. Jean</h5>
<p>General Practitioner</p>
</div>
<div class="col-md-4">
<h5>Dr. Aline</h5>
<p>Maternity Specialist</p>
</div>
<div class="col-md-4">
<h5>Dr. Eric</h5>
<p>Laboratory Specialist</p>
</div>
</div>
</div>
</section>

<!-- CONTACT -->
<section class="section" id="contact">
<div class="container">
<h2>Contact & Appointment</h2>
<form onsubmit="submitForm(event)">
<div class="mb-3">
<input type="text" class="form-control" placeholder="Your Name" required>
</div>
<div class="mb-3">
<input type="tel" class="form-control" placeholder="Phone Number" required>
</div>
<div class="mb-3">
<select class="form-control">
<option>Select Service</option>
<option>Maternity</option>
<option>Consultation</option>
<option>Laboratory</option>
</select>
</div>
<div class="mb-3">
<input type="date" class="form-control" required>
</div>
<button class="btn btn-primary">Submit</button>
</form>

<p class="mt-3"><strong>Location:</strong> Nyabikenke, Rwanda</p>
<p><strong>Phone:</strong> +250 7XX XXX XXX</p>
</div>
</section>

<!-- FOOTER -->
<div class="footer">
<p>© 2026 Nyabikenke Hospital. All Rights Reserved.</p>
</div>

<!-- WHATSAPP BUTTON -->
<a href="https://wa.me/250780375475" class="btn btn-success btn-whatsapp">Chat on WhatsApp</a>

<script>
function submitForm(e){
e.preventDefault();
alert("Appointment submitted successfully!");
}
</script>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
