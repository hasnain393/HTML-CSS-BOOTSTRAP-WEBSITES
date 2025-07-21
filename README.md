# HTML-CSS-BOOTSTRAP-WEBSITES
## 🎯 Project Overview

In this project, you’ll build a series of small, production-like websites:

1. **Product Design Page** using Bootstrap  
2. **Bike Repair Website** with booking logic  
3. **Logo Portfolio** with branding carousel  
4. **Responsive Profile Page** with accessibility features  

### By the end, you’ll know:
- How to turn a Figma wireframe into code
- Best practices for accessibility and responsiveness
- How to use Bootstrap grid, cards, and navbars
- CSS resets and alignment tricks
- Presenting yourself professionally with a personal site

---
## 📐 Wireframing the Idea (Figma + Paper)

Sketch your layout with:
- Header + Logo
- Nav links / burger menu
- Hero image + text
- Services grid
- Testimonials
- Footer

---

## 🧰 Tools & Setup

- **VS Code** with Live Server
- **FontAwesome** for icons
- **Bootstrap 4+ CDN**
- **Google Fonts** (Roboto, Playfair, Abril Fatface)

---

## 📋 Step-by-Step: Bike Service Website

### 1. Project Setup
```bash
mkdir bike-service
cd bike-service
touch index.html style.css
```

### 2. Link Fonts & Stylesheets
```html
<link rel="stylesheet" href="style.css" />
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap" rel="stylesheet" />
<script src="https://kit.fontawesome.com/YOUR-KIT.js" crossorigin="anonymous"></script>
```

### 3. Build the Header
```html
<header>
  <div class="logo">
    <img src="images/logo-roar-bikes.png" alt="Roar Bikes Logo" />
  </div>
  <nav>
    <a href="#">Book</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>
</header>
```

### ✅ Accessibility Tip
Use `alt` text for images and proper heading levels.

---

### 4. Hero Section
```html
<main>
  <section class="content1">
    <h1>Mobile bike repairs.</h1>
    <p>We come to your office or home. Fast. Reliable. Up-front pricing.</p>
    <a href="#" class="mybtn">Book Now</a>
  </section>
  <section class="content2">
    <img src="images/image-bike-repair-service.jpg" alt="Bike Repair Service" />
  </section>
</main>
```

---

### 5. Service Cards
```html
<div class="cards">
  <div class="card1">
    <i class="fas fa-motorcycle"></i>
    <h2>Book Online</h2>
    <p>Instant booking for home or office bike service.</p>
  </div>
</div>
```

---

## ✨ Bonus Project: Product Design Page

Use Bootstrap’s:
- `navbar`
- `container`
- `jumbotron`
- `card-deck`

Make it accessible and responsive with:
- `img-fluid`
- `sr-only` for screen readers
- Semantic tags (`section`, `article`, `footer`)

---

## 💡 Design Tips

- Use **CSS reset** to standardize appearance
- Center using:
```css
.centered {
  display: flex;
  justify-content: center;
  align-items: center;
}
```
- Burger menus can be built with JS toggle or jQuery

---

## 🧪 Troubleshooting Tips

| Issue | Fix |
|-------|-----|
| Fonts not loading | Check Google Fonts link |
| Navbar breaks on mobile | Use `navbar-expand-*` |
| Image sizing issues | Use `img-fluid` or set `max-width: 100%` |

---

## 🌱 Bonus Challenges

- Add dark/light mode switch
- Store booking preferences in `localStorage`
- Animate sections on scroll (AOS.js)
- Add contact form with validation

* d-flex justify-content-end | mr-auto | ml-auto | text-center text-md-left  are useful property in botstrap
* [Bootstrap 4.3](https://getbootstrap.com/docs/4.3/getting-started/introduction/)
* Starter template  for Bootstrap 4.3
```
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
      <!-- Google Font API  -->
      <link
      href="https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Open+Sans:wght@300;700&display=swap"
      rel="stylesheet"
    />

    <link
    href="https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap"
    rel="stylesheet"
  />
  <link
    href="https://fonts.googleapis.com/css2?family=Playfair+Display&family=Roboto:wght@300&display=swap"
    rel="stylesheet"
  />
  <!-- Fontawesome  -->
  <script
    src="https://kit.fontawesome.com/74c60922f2.js"
    crossorigin="anonymous"
  ></script>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

    <title>Hello, world!</title>
    <style>
    
    </style>
  </head>
  <body>
    <div class="container">


      <!-- fontawesome  -->
      <i class="fas fa-cog"></i>



      <!-- Nav  -->


  
      <!-- Carousel  -->
    



    </div>



    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  </body>
</html>
```
