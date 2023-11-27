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
