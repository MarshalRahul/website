<!DOCTYPE html>
<html>
<head>
    <title> About </title>
    <link rel="stylesheet" href="CSS/About.css" type="text/css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Ubuntu&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Ubuntu&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css" integrity="sha512-5A8nwdMOWrSz20fDsjczgUidUBR8liPYU+WymTZP1lmY9G6Oc7HlZv156XqnsgNUzTyMefFTcsFH/tnJE/+xBg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <!-- Header -->
    <header>
        <nav>
            <a href="index.html">
                <img src="Images/logo.png">
            </a>
            <div class="navigation-bar" id="myNav">
                <i class="fa fa-times" onclick="closeMenu()"></i>
                <ul>
                    <li><a href="index.html">   Home    </a></li>
                    <li><a href="About.html">   About   </a></li>
                    <li><a href="Course.html">  Course  </a></li>
                    <li><a href="Blog.html">    Blog    </a></li>
                    <li><a href="Contact.html"> Contact </a></li>
                </ul>
            </div>
            <i class="fa fa-bars" onclick="showMenu()"></i>
        </nav>
        <div class="text-box">
            <h1> About Us </h1>
        </div>
    </header>
    <main>
    <!-- About us -->
    <section id="testimonials-section">
        <p id="testimonials-heading"> Founders </p>
        <h3> Meet Our Team Members </h3>
        <p id="testimonials-desc">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quisquam, laboriosam? Iure
            sunt tenetur quaerat dolores.</p>
        <div id="testimonials-wrapper">
            <div class="testimonial-item">
                <img src="Images/Faculty02.jpg" />
                <p class="testimonial-message">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dicta, nisi ea.
                    Quaerat eaque sit ullam voluptas nisi libero magni odio ipsa. Fuga vero facilis possimus.</p>
                <h3 class="testimonial-by">Name </h3>
                <p class="job-role"> Faculty </p>
            </div>
            <div class="testimonial-item">
                <img src="Images/Faculty01.jpg" />
                <p class="testimonial-message">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dicta, nisi ea.
                    Quaerat eaque sit ullam voluptas nisi libero magni odio ipsa. Fuga vero facilis possimus.</p>
                <h3 class="testimonial-by"> Name </h3>
                <p class="job-role"> Developer </p>
            </div>
            <div class="testimonial-item">
                <img src="Images/Faculty03.jpg" />
                <p class="testimonial-message"> Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dicta, nisi
                    ea. Quaerat eaque sit ullam voluptas nisi libero magni odio ipsa. Fuga vero facilis possimus.</p>
                <h3 class="testimonial-by"> Name </h3>
                <p class="job-role"> Administrator </p>
            </div>
        </div>
    </section>
    <section id="follow-section">
        <div id="left-section">
            <img src="Images/About.jpg" alt="classroom" />
        </div>
        <div id="right-section">
            <div id="text-wrapper">
                <h3>Follow Us</h3>
                <p>Various Courses; Beginner, Advanced, and Professional Courses.</p>
                <input id="subscribe-email" placeholder="Your Email" />
                <input id="subscribe-btn" type="submit" value="Subscribe" />
            </div>
        </div>
    </section>
    <section id="stats-section">
        <div id="stats-wrapper">
            <div class="stats-item">
                <h3>1000k</h3>
                <p>Stydent Experiences</p>
            </div>
            <div class="stats-item">
                <h3>500k</h3>
                <p>Happy Students </p>
            </div>
            <div class="stats-item">
                <h3>1000k</h3>
                <p>Success</p>
            </div>
            <div class="stats-item">
                <h3>1000k</h3>
                <p>Placement
                </p>
            </div>
        </div>
    </section>
</main>
    <!-- Footer -->
    <Footer>
        <h3> About Us </h3>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus consectetur odio eveniet
            <br>
            dolores error hic quasi labore esse amet, quaerat tempore mollitia libero molestias reiciendis.
        </p>
        <div class="icons">
            <i class="fa fa-facebook-official"></i>
            <i class="fa fa-instagram"></i>
            <i class="fa fa-linkedin"></i>
            <i class="fa fa-twitter"></i>
        </div>
        <p>
            <i class="fa fa-copyright"> Copyright </i>
        </p>
    </Footer>
    <!-- Script -->
    <script>
        var myNav = document.getElementById("myNav");
        function showMenu() {
            myNav.style.right = "0";
        }
        function closeMenu() {
            myNav.style.right = "-150px";
        }
    </script>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    font-family: 'Ubuntu', sans-serif;
}

/* Header */
header {
    min-height: 50vh;
    width: 100%;
    background-image: linear-gradient(rgba(3, 16, 44, 0.7), rgba(3, 16, 44, 0.7)),
    url('../images02/bg005.png');
    background-position: center;
    background-size: cover;
    position: relative;
}

nav {
    display: flex;
    padding: 12px 50px;
    justify-content: space-between;
    align-items: center;
}

nav img {
    width: 100px;
}

.navigation-bar {
    flex: 1;
    text-align: right;
}

.navigation-bar ul li {
    list-style: none;
    display: inline-block;
    padding: 15px;
    position: relative;
}

.navigation-bar ul li a {
    color: white;
    text-decoration: none;
    font-size: 15px;
}

.navigation-bar ul li::after {
    content: '';
    width: 0%;
    height: 2px;
    background: white;
    display: block;
    margin: auto;
    transition: 0.5s;
}

.navigation-bar ul li:hover::after {
    width: 100%;
}

.navigation-bar a:hover {
    color: #00AFEF;
}

.text-box {
    width: 100%;
    color: white;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
}

.text-box h1 {
    font-size: 60px;
}

nav .fa {
    display: none;
}

/* Responsive */
@media (max-width: 700px) {
    .text-box h1 {
        font-size: 40px;
    }
    .text-box p {
        margin: 10px;
        font-size: 10px;
        color: white;
        line-height: 15px;
    }
    .navigation-bar ul li {
        display: block;
    }
    .navigation-bar {
        position: fixed;
        background: #0387bb;
        height: 100vh;
        width: 150px;
        top: 0;
        right: -150px;
        text-align: left;
        z-index: 2;
        transition: 1s;
    }
    nav .fa {
        display: block;
        color: white;
        margin: 10px;
        font-size: 20px;
        cursor: pointer;
    }
    .navigation-bar ul {
        padding: 30px;
    }
}
/* ......................... */

/* About us */
#testimonials-section {
    width: 100%;
    padding-top: 50px;
    padding-bottom: 75px;
    text-align: center;
}

#testimonials-heading {
    color: #0387bb;
    font-size: 24px;
    margin: 0;
    margin-top: 35px;
    margin-bottom: 30px;
}

#testimonials-section > h3 {
    font-size: 44px;
    font-weight: 600;
    margin: 0;
    margin-bottom: 8px;
}

#testimonials-desc {
    max-width: 700px;
    font-size: 16px;
    font-weight: 500;
    margin: 0 auto;
    color: #8b8b99;
    letter-spacing: 0.5px;
    margin-bottom: 55px;
    display: flex;
}

#testimonials-wrapper {
    width: 100%;
    max-width: 1140px;
    margin: 0 auto;
    display: flex;
}

.testimonial-item {
    width: 25%;
    text-align: center;
    background-color: #f5f6fb;
    padding: 40px 30px;
    margin: 16px auto;
    border-top-left-radius: 45px;
    border-bottom-left-radius: 45px;
    border-bottom-right-radius: 45px;
    transition: box-shadow 0.3s;
}

.testimonial-item:hover {
    box-shadow: 0 12px 16px 0 rgba(0, 0, 0, 0.3);
}

.testimonial-item img {
    width: 80px;
    margin-bottom: 25px;
    border-radius: 50%;
}

.testimonial-message {
    font-size: 14px;
    color: #8b8b99;
    letter-spacing: 0.5px;
    font-style: italic;
    margin: 0;
}

.testimonial-item h3 {
    text-transform: uppercase;
    font-size: 16px;
    font-weight: 600;
    margin-top: 24px;
    margin-bottom: 0px;
}

.job-role {
    color: #8b8b99;
    font-size: 12px;
    font-style: italic;
    letter-spacing: 0.5px;
    margin: 0;
}
/* ...................... */


/* .................. */
#follow-section {
    display: flex;
    justify-content: stretch;
}

#left-section {
    width: 67%;
    display: inline-block;
    margin: 0;
}

#left-section img {
    width: 100%;
}

#right-section {
    width: 33.33%;
    margin: 0;
    display: inline-block;
    background-image: url('../Images/Follow.jpg');
    background-position: left;
    background-size: cover;
}

#right-section #text-wrapper {
    margin: 115px;
}

#right-section #text-wrapper h3 {
    font-size: 44px;
    font-weight: 600;
    margin: 0 0 8px;
}

#right-section #text-wrapper p {
    color: #3b3b3b;
    font-size: 16px;
    letter-spacing: 0.5;
    line-height: 1.6;
    margin: 0;
}

#subscribe-email {
    width: 100%;
    box-sizing: border-box;
    border: 0;
    border-radius: 4px;
    font-weight: 500;
    background-color: white;
    padding: 12px;
    color: #8b8b99;
    font-size: 16px;
    margin-top: 60px;
    display: block;
}

#subscribe-btn {
    background-color: #f69dad;
    padding: 16px 42px;
    border-radius: 4px;
    cursor: pointer;
    color: white;
    border: 0;
    font-size: 14px;
    font-weight: 600;
    text-transform: uppercase;
    margin-top: 16px;
}

#subscribe-btn:hover {
    color: #f69dad;
    border: 1px solid #f69dad;
    background-color: transparent;
}

/* ...................... */



/* ...................... */
#stats-section {
    width: 100%;
    background-color: #f6fcfa;
}

#stats-wrapper {
    width: 100%;
    max-width: 1140px;
    padding: 100px 0;
    margin: 0 auto;
    text-align: center;
    display: flex;
    justify-content: stretch;
}

.stats-item {
    width: 25%;
    padding: 0 64px;
}

.stats-item h3 {
    font-size: 44px;
    font-weight: 600;
    margin: 0;
}

.stats-item p {
    color: #57e3b5;
    font-size: 14px;
    letter-spacing: 0.5px;
    font-style: italic;
    margin: 0;
}
/* ...................... */


/* Responsiv */
@media (max-width: 700px) {

#testimonials-section {
    padding: 16px;
    box-sizing: border-box;
}

#testimonials-section > h3 {
   font-size: 28px; 
}

#testimonials-wrapper {
    flex-direction: column;
}

.testimonial-item {
    width: 100%;
    box-sizing: border-box;
}

.testimonial-by {
    font-size: important 18px;
}
/* ..................... */
#follow-section {
    flex-direction: column;
}

#right-section #text-wrapper {
    margin: 16px;
}

#right-section #text-wrapper h3 {
    font-size: 28px;
}

#left-section {
    width: 100%;
}

#right-section {
    width: 100%;
}
/* ..................... */
#stats-wrapper {
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.stats-item {
    padding: 20px;
}
}
/* ..................... */

/* Footer */
footer {
    width: 80%;
    padding: 30px 0;
    text-align: center;
    margin: auto;
}

footer h3 {
    margin: 20px;
}

footer p {
    font-size: 15px;
    color: #525252;
    line-height: 22px;
}

.icons .fa {
    color: #06b8ff;
    padding: 25px 0;
    margin: 0 20px;
    cursor: pointer;
}





