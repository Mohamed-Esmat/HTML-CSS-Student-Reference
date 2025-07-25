## HTML Code

```html
<!DOCTYPE html>
<!-- How to add smooth scroll in html? // By adding CSS scroll-behavior property -->
<html lang="en" style="scroll-behavior: smooth">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Frontend Mentor Project</title>
    <link rel="stylesheet" href="css/main.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"
    />
  </head>
  <body>
    <!-- ======= Header ======= -->
    <header class="header">
      <div class="header__overlay"></div>

      <nav class="header__nav clearfix">
        <div class="header__logo">
          <img src="img/logo-light.png" alt="The engage website logo" />
        </div>
        <ul class="header__links">
          <li class="header__link"><a href="#">Home</a></li>
          <li class="header__link"><a href="#">About</a></li>
          <li class="header__link"><a href="#">Services</a></li>
          <li class="header__link"><a href="#">Portfolio</a></li>
          <li class="header__link"><a href="#">Contact</a></li>
        </ul>
      </nav>

      <div class="header__content">
        <p class="header__subtitle--small">Welcome to</p>
        <h1 class="header__title">Engage Agency</h1>
        <p class="header__subtitle">
          We're the biggest, best equipped and most advanced Web Agency in the
          greater Los Angeles area.
        </p>
        <a href="#" class="header__btn">Learn More</a>
      </div>
    </header>

    <!-- ======= Main Content ======= -->
    <main>
      <section class="recent-work">
        <div class="container">
          <!-- Section Title -->
          <div class="section-heading">
            <h3 class="heading-title">Recent Work</h3>
            <p class="heading-subtitle">
              Check out some of our latest projects
            </p>
            <div>
              <h3>Lorem ipsum dolor sit.</h3>
              <h3>Lorem ipsum dolor sit.</h3>
            </div>
            <h3>Lorem, ipsum dolor.</h3>
          </div>

          <!-- Filters -->
          <ul class="portfolio-filters">
            <li class="filter active">Show all</li>
            <li class="filter">Design</li>
            <li class="filter">Graphics</li>
            <li class="filter">Mockups</li>
            <li class="filter">Other</li>
            <li class="filter">Photography</li>
            <li class="filter">Planning</li>
          </ul>

          <h3>Lorem, ipsum.</h3>

          <!-- Portfolio Items -->
          <div class="portfolio-wrapper">
            <!-- Portfolio Item -->
            <div class="portfolio-item">
              <div class="portfolio-img">
                <img src="img/product-1.jpg" alt="Product 1" />

                <div class="overlay">
                  <div class="overlay-icons">
                    <span><i class="fa fa-search-plus"></i></span>
                    <span><i class="fa fa-link"></i></span>
                  </div>
                </div>
              </div>

              <div class="portfolio-caption">
                <h4>Cool Bag</h4>
                <p>A stylish and functional bag for everyday use.</p>
              </div>
            </div>

            <!-- Portfolio Item -->
            <div class="portfolio-item">
              <div class="portfolio-img">
                <img src="img/product-1.jpg" alt="Product 1" />

                <div class="overlay">
                  <div class="overlay-icons">
                    <span><i class="fa fa-search-plus"></i></span>
                    <span><i class="fa fa-link"></i></span>
                  </div>
                </div>
              </div>

              <div class="portfolio-caption">
                <h4>Cool Bag</h4>
                <p>A stylish and functional bag for everyday use.</p>
              </div>
            </div>

            <!-- Portfolio Item -->
            <div class="portfolio-item">
              <div class="portfolio-img">
                <img src="img/product-1.jpg" alt="Product 1" />

                <div class="overlay">
                  <div class="overlay-icons">
                    <span><i class="fa fa-search-plus"></i></span>
                    <span><i class="fa fa-link"></i></span>
                  </div>
                </div>
              </div>

              <div class="portfolio-caption">
                <h4>Cool Bag</h4>
                <p>A stylish and functional bag for everyday use.</p>
              </div>
            </div>

            <!-- Portfolio Item -->
            <div class="portfolio-item">
              <div class="portfolio-img">
                <img src="img/product-1.jpg" alt="Product 1" />

                <div class="overlay">
                  <div class="overlay-icons">
                    <span><i class="fa fa-search-plus"></i></span>
                    <span><i class="fa fa-link"></i></span>
                  </div>
                </div>
              </div>

              <div class="portfolio-caption">
                <h4>Cool Bag</h4>
                <p>A stylish and functional bag for everyday use.</p>
              </div>
            </div>

            <div class="portfolio-item">
              <div class="portfolio-img">
                <img src="img/product-1.jpg" alt="Product 1" />

                <div class="overlay">
                  <div class="overlay-icons">
                    <span><i class="fa fa-search-plus"></i></span>
                    <span><i class="fa fa-link"></i></span>
                  </div>
                </div>
              </div>

              <div class="portfolio-caption">
                <h4>Cool Bag</h4>
                <p>A stylish and functional bag for everyday use.</p>
              </div>
            </div>

            <div class="portfolio-item">
              <div class="portfolio-img">
                <img src="img/product-1.jpg" alt="Product 1" />

                <div class="overlay">
                  <div class="overlay-icons">
                    <span><i class="fa fa-search-plus"></i></span>
                    <span><i class="fa fa-link"></i></span>
                  </div>
                </div>
              </div>

              <div class="portfolio-caption">
                <h4>Cool Bag</h4>
                <p>A stylish and functional bag for everyday use.</p>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>

    <div>
      <form action="">
        <input type="text" placeholder="Search..." />
      </form>
    </div>
  </body>
</html>

```

---

## CSS Code

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
}

img {
  width: 100%;
}

/* .clearfix {
  clear: both;
} */

/* Pseudo elements */
.clearfix::after {
  content: "";
  display: inline-block;
  clear: both;
}

/* Header Styles */
.header {
  position: relative;
  background-image: url("../img/full-8-1.jpeg");
  background-size: cover;
  background-position: center;
  height: 100vh;
  color: #fff;
}

/* Overlay */
.header__overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.6);
  z-index: 1;
}

/* nav */
.header__nav {
  width: 90%;
  margin: 0 auto;
  padding: 20px 0;
  position: relative;
  z-index: 2;
}

.header__logo {
  float: left;
}

.header__logo img {
  height: 40px;
}

.header__links {
  float: right;
  list-style: none;
}

.header__links li {
  display: inline-block;
  margin-left: 20px;
  padding: 10px 0;
}

.header__links a:link,
.header__links a:visited {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s ease;
}

.header__links a:hover,
.header__links a:active {
  color: #00bcd0;
}

.header__content {
  /* position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  z-index: 2; */
  width: 60%;
  margin: 0 auto;
  text-align: center;
  position: relative;
  z-index: 2;
  margin-top: 20vh;
}

.header__content h1 {
  font-size: 3rem; /* 3rem means 48px (3*16) */
  margin-bottom: 20px;
}

.header__content p {
  font-size: 1.2rem; /* 1.2rem means 19.2px (1.2*16) */
  margin-bottom: 30px;
}

.header__content a:link,
.header__content a:visited {
  display: inline-block;
  padding: 12px 24px;
  background-color: #00bcd0;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  transition: all 0.3s ease;
}

.header__content a:hover,
.header__content a:active {
  background-color: #008c9e;
  transform: translateY(-5px);
}

.recent-work {
  padding: 60px 0;
  background-color: #fff;
}

.container {
  width: 90%;
  margin: 0 auto;
  overflow: hidden;
}

.section-heading {
  text-align: center;
  margin-bottom: 40px;
}

.section-heading h3 {
  font-size: 26px;
  margin-bottom: 10px;
}

.section-heading p {
  font-size: 14px;
  color: #777;
}

.portfolio-filters {
  text-align: center;
  list-style: none;
  margin: 0 0 30px;
  padding: 0;
}

.portfolio-filters li {
  display: inline-block;
  margin: 0 10px;
  cursor: pointer;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.portfolio-filters li.active {
  background-color: #00bcd0;
  color: #fff;
  border-color: #00bcd0;
}

.portfolio-filters li:last-child {
  margin-right: 0;
}

.portfolio-filters li:first-child {
  margin-left: 0;
}

.portfolio-wrapper {
  overflow: hidden;
}

.portfolio-item {
  width: 30.66%;
  margin: 1%;
  float: left;
  background: #f8f8f8;
  position: relative;
  transition: all 0.3s ease;
}

.portfolio-img {
  position: relative;
  overflow: hidden;
}

.portfolio-img img {
  transition: all 0.4s ease;
}

.overlay {
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.6);
  opacity: 0;
  visibility: hidden;
  transition: all 0.4s ease;
}

.portfolio-img:hover .overlay {
  opacity: 1;
  visibility: visible;
}

.portfolio-img:hover > img {
  transform: scale(1.1);
}

.overlay-icons {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.overlay-icons i {
  color: #fff;
  font-size: 18px;
  margin: 0 8px;
  cursor: pointer;
  transform: translateY(20px);
  transition: all 0.4s ease;
}

.overlay-icons i:hover {
  color: #00bcd0;
}

.portfolio-img:hover .overlay-icons i {
  transform: translateY(0);
}

.portfolio-caption {
  padding: 15px;
  text-align: center;
}

.portfolio-caption h4 {
  margin: 0 0 5px;
  font-size: 18px;
  color: #333;
}

.portfolio-caption p {
  margin: 0;
  color: #999;
  font-size: 13px;
}

/* =========================
   RESPONSIVE MEDIA QUERIES
*/

/* 
Large Desktops max-width: 1200px
Desktops max-width: 992px
Tablets max-width: 768px
Large Phones max-width: 576px
Small Phones max-width: 480px
*/

/* ===============================
   RESPONSIVE MEDIA QUERIES
   =============================== */

/* <= 1200px */
@media (max-width: 1200px) {
}

/* <= 992px */
@media (max-width: 992px) {
}

/* <= 768px */
@media (max-width: 768px) {
}

/* <= 576px */
@media (max-width: 576px) {
  .header {
    height: 85vh;
  }

  .header__nav {
    padding: 10px 0;
  }

  .header__logo {
    float: none;
  }

  .header__logo img {
    height: 25px;
    width: auto;
  }

  .header__links {
    display: none;
    float: none;
  }

  .header__content {
    width: 70%;
    margin: 0 auto;
    margin-top: 3vh;
  }

  .header__content h1 {
    font-size: 1.5rem; /* 1.5rem means 24px (1.5*16) */
    margin-bottom: 20px;
  }

  .header__content p {
    font-size: 0.9rem; /* 0.9rem means 14.4px (0.9*16) */
    margin-bottom: 15px;
  }

  .header__content a:link,
  .header__content a:visited {
    padding: 8px 20px;
    border-radius: 5px;
    font-size: 0.9rem; /* 0.9rem means 14.4px (0.9*16) */
  }
}

/* <= 480px */
@media (max-width: 480px) {
}

/* 
=========================
    SELECTORS IN CSS
=========================

1- Universal Selector (*)
2- Type Selector (Tag)
3- Class Selector (.classname)
4- ID Selector (#idname)
5- Attribute Selector ([attribute])
6- Pseudo-class Selector (:pseudo-class)
7- Pseudo-element Selector (::pseudo-element)
8- Descendant Selector (parent child) 
9- Child Selector (parent > child)
10- Adjacent Sibling Selector (element + sibling)
11- General Sibling Selector (element ~ sibling)
12- Grouping Selector (selector1, selector2, ...)
13- Combinator Selector (selector1 selector2)
14- Negation Selector (:not(selector))
15- Attribute Value Selector ([attribute="value"])
16- Attribute Starts With Selector ([attribute^="value"])
17- Attribute Ends With Selector ([attribute$="value"])
18- Attribute Contains Selector ([attribute*="value"])
19- Attribute Hyphenated Selector ([attribute|="value"])
20- Lang Selector (:lang(language))
21- Functional Pseudo-class Selector (:nth-child(n), :nth-of-type(n), :first-child, :last-child, etc.)
22- Custom Properties (CSS Variables) (--variable-name)
23- Media Query Selector (@media)
24- Keyframes Selector (@keyframes)
25- Import Rule (@import)
26- Font-face Selector (@font-face)
27- Viewport Units (vw, vh, vmin, vmax)

*/

/* Descendant Selector
.section-heading h3 {
  color: red;
} */

/* Child Selector [Only direct children] */
/* .section-heading > h3 {
  color: red;
} */

/* Adjacent Sibling Selector [Only next sibling] */
/* .section-heading + h3 {
  color: red;
} */

/* General Sibling Selector [All siblings] */
/* .section-heading ~ h3 {
  color: red;
} */

::selection {
  background: yellow;
  color: #000;
}

form {
  width: 100%;
  max-width: 600px;
  margin: 0 auto;
  padding: 20px;
  background-color: #f9f9f9;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  text-align: center;
}

input {
  width: 50%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 16px;
  margin-bottom: 20px;
}

input[type="text"] {
  width: 100%;
}

input::placeholder {
  color: gray;
  font-style: italic;
}



```
