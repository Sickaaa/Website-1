<!DOCTYPE html>
    <head>
        <link rel="icon" type="image/x-icon" href="https://seeklogo.com/images/T/the-aa-logo-E684A3BB42-seeklogo.com.png">
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <script src="app.js" type="text\javascript"></script>
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <title>Ahmed's Website</title>
    </head>

    <body>
        <section class="container home-page">
            <header id="header">
                <input type="checkbox" id="check" onclick="myFunction()">
                <label for="check" class="checkBtn">
                    <i class="fa fa-bars" id="bar-icon"></i>
                </label>
                <nav class="nav-bar">         
                    <ul id="list-container">
                        <li><a href="#home" class="nav-link" id="link" onclick="nav_click()">HOME⇩</a></li>
                        <li><a href="#about-me-label" class="nav-link" onclick="nav_click()">ABOUT⇩</a></li>
                        <li><a href="#project-label" class="nav-link" onclick="nav_click()">MY WORK⇩</a></li>
                        <li><a href="#skill-label" class="nav-link" onclick="nav_click()">HOBBIES⇩</a></li>
                        <li><a href="#contact-label" class="nav-link" onclick="nav_click()">FAQ⇩</a></li>
                    </ul>
                </nav>
            </header>

            <div class="title-div" id="home">
                <h1 id="name">Hey, I'm <span class="bold-italic-text">Ahmed</span>!</h1>
                <h1 id="sub-name">A <span class="bold-italic-text title">Photographer, With Many More hobbies!</span></h1>
            </div>
        </section>

        <section class="container bg-gray-light about-me-div">
          <h2 id="about-me-label">ABOUT ME</h2>
            <span class="about-me-content">

                    <p id="about-p">I am an experienced Portrait Photographer who is passionate about capturing unique moments with my signature style. I began my adventure into photography in 2017/2018 and soon became obsessed with the fundamentals that make a great photograph: lighting, balance, composition, and use of space. I like to capture poignant and profound moments with a creative twist. I offer exceptional professional and personal service for each and every one of my clients, so get in touch today and book your session of a photoshoot.<p>

                  <p id="about-p">For years, I have served as a useful source to those seeking inspiration, help, or advice. I finally decided to own that role and be intentional about it. I started taking pictures of my passion, my thoughts, and curious wonderings about our world. I found and created <a href="https://www.instagram.com/ahmedaga__/" target="_blank">@ahmedaga__</a> with a mission to give others a taste of what goes on in my mind, and I have been at it ever since. Take some time to explore the website, read something interesting, and feel free to reach out if you would like to collaborate on a  project together.</p>
                  <br>
                  <p id="about-p">With an interest in technology and art, photography soon became a passion for me, a devoted and underrated Portrait Photographer. I began by shooting photos of family members, friends, and nature, and soon developed my own personal style. I decided to take photography seriously and build a career of it in 2019 and it was the easiest and the best choice I have ever made, and i never looked back. I use some of the best equipment available and hold pre-shot consultations with clients to get a better understanding of their vision and preferences. If you’d like to learn more, please get in touch and contact me if you want to. Visit my Instagram page for more details and informations.</p>
                  <!--Insert mywork here-->

            </span>

            <div class="button btn-showall"><a href="https://github.com/andreww28?tab=repositories" target="_blank">Show all</a></div>
        </section>

        <section class="container bg-gray-light">
            <h2 id="skill-label">SKILLS:</h2>
            <div class="skills-sub-container">
                <p class="language language-html">HTML</p>
                <div class="bar bar-html"></div>
                <p class="bar-percent bar-percent-html">95%</p>

                <p class="language language-css">CSS</p>
                <div class="bar bar-css"></div>
                <p class="bar-percent bar-percent-css">30%</p>

                <p class="language language-javascript">JAVASCRIPT</p>
                <div class="bar bar-javascript"></div>
                <p class="bar-percent bar-percent-javascript">0%</p>

                <p class="language language-python">PYTHON</p>
                <div class="bar bar-python"></div>
                <p class="bar-percent bar-percent-python">0%</p>
            </div>
        </section>

        <footer class="container bg-gray-dark" id="contact-label">
            <h2 id="footer">LET'S WORK TOGETHER...</h2>
            <p>Find me here:</p>
            <div class="social-media-icons">
                <a href="https://m.facebook.com/andrew.sanvictores.01" target="_blank" class="fa fa-facebook icon"></a>
                <a href="https://twitter.com/johnn__andrew" target="_blank" class="fa fa-twitter icon"></a>
                <a href="https://github.com/andreww28" target="_blank" class="fa fa-github icon"></a>
                <a href="https://www.instagram.com/johnandrewsanvictores/" target="_blank" class="fa fa-instagram icon"></a>
            </div>
        </footer>


    </body>
</html>
