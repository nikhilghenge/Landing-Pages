<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yoga Landing Page</title>
    <link rel="stylesheet" href="style.css">

</head>
<body>
    <!-- Landing Page -->
    <div class="top-banner">
        <div class="container">
            <div class="small-bold-text banner-text">🥳 New to Yoga Care? Sign Up and get upto <i><b>40% off!</b></i></div>
        </div>
    </div>

    <!-- nav bar -->
    <nav>
        <div class="container main-nav flex">
            <a href="#" class="company-logo">
                <img src="logo.jpg" alt="company logo">
            </a>
            <div class="nav-links" id="nav-links">
                <ul class="flex">
                    <li><a href="#" class="hover-link">Products</a></li>
                    <li><a href="#" class="hover-link">Customer</a></li>
                    <li><a href="#" class="hover-link">Pricing</a></li>
                    <li><a href="#" class="hover-link">Resources</a></li>
                    <li><a href="#" class="hover-link secondary-button">Sign in</a></li>
                    <li><a href="#" class="hover-link primary-button">Sign up</a></li>
                </ul>
            </div>
            <a href="#" class="nav-toggle hover-link" id="nav-toggle">
                <i class="fa-solid fa-bars"></i>
            </a>
        </div>
    </nav>

    <!-- header section -->
    <header>
        <div class="container header-section flex">
            <div class="header-left">
                <h1>Yoga Care</h1>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Unde, hic. Nesciunt, corrupti deleniti! Ratione fugiat exercitationem est repellat suscipit illo.</p>
                <a href="#" class="primary-button get-started-btn">Get Started</a>
            </div>
            <div class="header-right">
                <img class="yoga" src="yoga.jpg" alt="hero image">
            </div>
        </div>
    </header>
    <!-- main -->
    <main>
        <section>
            <img class="yoga1" src="yoga1.jpg" alt="poses1">
        </section>
        <section>
            <img class="yoga1" src="yoga2.jpg" alt="poses2">
        </section>
    </main>

    <!-- footer -->

    <footer>
        <div class="container flex footer-container">
            <a href="#" class="company-logo">
                <img src="logo.jpg" alt="company logo">
            </a>
            <div class="link-column flex">
                <h4>Product</h4>
                <a href="#" class="hover-link">Overview</a>
                <a href="#" class="hover-link">Pricing</a>
                <a href="#" class="hover-link">Usability Hub</a>
                <a href="#" class="hover-link">Customers Page</a>
                <a href="#" class="hover-link">Status Page</a>
            </div>
            <div class="link-column flex">
                <h4>Methodology</h4>
                <a href="#" class="hover-link">Overview</a>
                <a href="#" class="hover-link">Pricing</a>
                <a href="#" class="hover-link">Usability Hub</a>
                <a href="#" class="hover-link">Customers Page</a>
                <a href="#" class="hover-link">Status Page</a>
            </div>
            <div class="link-column flex">
                <h4>Resources</h4>
                <a href="#" class="hover-link">Overview</a>
                <a href="#" class="hover-link">Pricing</a>
                <a href="#" class="hover-link">Usability Hub</a>
                <a href="#" class="hover-link">Customers Page</a>
                <a href="#" class="hover-link">Status Page</a>
            </div>
        </div>
    </footer>

    <!-- subfooter -->

    <div class="subfooter">
        <div class="container flex subfooter-container">
            <a class="hover-link" href="#">Privacy policy</a>
            <a class="hover-link" href="#">Terms & Condition</a>
            <a class="hover-link" href="#">Security Information</a>
            <a class="hover-link" href="#"><i class="fa-brands fa-facebook"></i></a>
            <a class="hover-link" href="#"><i class="fa-brands fa-twitter"></i></a>
        </div>
    </div> 
    
</body>
</html>




<!-- style.css -->
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500&family=Roboto:wght@400;700&display=swap');
/* resets */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary-text-color: #183b56;
    --secondary-text-color: #577592;
    --accent-color: #2294ed;
    --accent-color-dark: #1d69a3;
    --padding-inline-section: 20px;
}

body {
    font-family: 'Poppins', sans-serif;
    color: var(--primary-text-color);
}

h1 {
    font-size: 3rem;
}

h2 {
    font-size: 2rem;
}

h3 {
    font-size: 1.5rem;
}

p {
    font-family: 'Roboto', sans-serif;
    font-size: 1.25rem;
    color: var(--secondary-text-color);
    line-height: 1.8rem;
}

a {
    text-decoration: none;
    display: inline-block;
}

ul {
    list-style: none;
}

/* utility classes */

.small-bold-text {
    font-size: 1rem;
    font-weight: 700;
}

.container {
    max-width: 1180px;
    margin-inline: auto;
    padding-inline: var(--padding-inline-section);
    overflow: hidden;
}

.flex {
    display: flex;
    align-items: center;
}

.hover-link {
    color: var(--primary-text-color);
    transition: 0.2s ease-out;
}

.hover-link:hover {
    color: var(--accent-color);
}

.primary-button {
    background-color: var(--accent-color);
    border-radius: 6px;
    font-weight: 700;
    color: white !important;
    padding: 12px 24px;
    box-shadow: 0 0 2px var(--secondary-text-color);
    transition: 0.2s ease-out;
    text-align: center;
}

.primary-button:hover {
    background-color: var(--accent-color-dark);
}

.secondary-button {
    border: 0.5px solid var(--secondary-text-color);
    border-radius: 6px;
    font-weight: 700;
    color: var(--primary-text-color) !important;
    padding: 12px 24px;
    transition: 0.2s ease-out;
}

.secondary-button:hover {
    border-color: var(--accent-color);
    color: var(--accent-color) !important;
}

/* top banner */

.top-banner {
    background-image: url('./assets/asset\ 30.png');
    background-color: #4fb3d4;
    background-size: 300px;
}

.banner-text {
    color: white;
    padding: 15px 30px;
    text-align: center;
}

/* nav bar */

.main-nav {
    margin-top: 20px;
    justify-content: space-between;
}

.company-logo img {
    width: 400px;
    height: 170px;
}

.nav-links {
    flex-basis: 730px;
}

.nav-links ul {
    justify-content: end;
    gap: 40px;
}

.nav-toggle {
    display: none;
}

/* header section */

header {
    padding: 0px var(--padding-inline-section) 0;
}

.header-section {
    justify-content: center;
    gap: 0px;
}

.header-left {
    max-width: 40vw;
    margin-right: 80px;
}

.header-left h1 {
    margin-top: 20px;
}

.get-started-btn {
    margin-top: 20px;
}

.header-right img {
    height:60vh;
    width: 100%;
}
/* main */
.yoga1{
    width: 100%;
    height: 100%;
}
/* footer */

footer {
    padding-block: 80px;
    background-color: #ebf2fa;
}

.link-column {
    flex-direction: column;
    align-items: flex-start;
    gap: 20px;
}

.footer-container {
    align-items: flex-start;
    justify-content: space-between;
}

/* subfooter */

.subfooter {
    background-color: #b9cde4;
    padding: var(--padding-inline-section);
}

.subfooter-container {
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
}
