<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio-Abhishek Paul</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/0b20992b2d.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="images/paul-logo (Custom).png" alt="logo" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <i class="fa-solid fa-circle-xmark" onclick="closeMenu()"></i>
                </ul>
                <i class="fa-solid fa-bars" onclick="openMenu()"></i>
            </nav>
            <div class="header-text">
                <p>Frontend Developer</p>
                <h1>Hi,I am <span>Abhishek</span><br>Paul from India</h1>
            </div>
        </div>
    </div>
    <!-- -------------about me------------->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="images/About-me.jpg" alt="About pic">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About me</h1>
                    <p>Hi,I am Abhishek Paul from India.I'm currently a Btech student completing my graduation from BVCOE college.I am aspiring to be a full stack developer.As of right now,I am at the level of a frontend developer having skills and conceptual knowledge of html,css,javascript and bootstrap.This is my first project as a frontend developer,creating my own personal Portfolio.</p>
                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                        <p class="tab-links" onclick="opentab('experience')">Experience</p>
                        <p class="tab-links"onclick="opentab('education')">Education</p>
                    </div>
                    <div class="tab-contents active-tab" id="skills">
                        <ul><li><span>C++</span><br>Software Development</li>
                        <ul><li><span>HTML</span><br>Web Designing</li>
                        <ul><li><span>CSS</span><br>Web Designing</li>
                        <ul><li><span>Bootstrap</span><br>Website Designing</li>
                        <ul><li><span>Javascript</span><br>Website Functionality</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="experience">
                        <ul><li><span>2022-Current</span><br>Competitive Coding</li>
                        <ul><li><span>2023</span><br>Google Drive Frontend</li>
                        <ul><li><span>2022</span><br>Google Drive Frontend</li>
                        <ul><li><span>2023</span><br>Personal Portfolio project</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="education">
                        <ul><li><span>2022</span><br>C++ Course from SkillUp</li>
                        <ul><li><span>2022</span><br>Udemy Course for HTML</li>
                        <ul><li><span>2022</span><br>Udemy Course for CSS</li>
                        <ul><li><span>2022</span><br>Udemy Course for Bootstrap</li>
                        <ul><li><span>2023</span><br>Javascript Course from Meta via Coursera</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- -----------------services-------------------->
    <div id="services">
        <div class="container">
            <h1 class="sub-title">My Services</h1>
            <div class="services-list">
                <div>
                    <i class="fa-brands fa-codepen fa-spin-pulse fa-xl" style="color: #ed5807;"></i>
                    <h2>Web Design</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem fugiat adipisci rem odit laudantium assumenda?</p>
                    <a href="#">Learn more</a>
                </div>
            
                <div>
                    <i class="fa-brands fa-uncharted fa-beat-fade fa-xl" style="color: #00f552;"></i>
                    <h2>Software Development</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem fugiat adipisci rem odit laudantium assumenda?</p>
                    <a href="#">Learn more</a>
                </div>
            
                <div>
                    <i class="fa-brands fa-app-store fa-flip fa-xl" style="color: #006eff;"></i>
                    <h2>Project Making</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem fugiat adipisci rem odit laudantium assumenda?</p>
                    <a href="#">Learn more</a>
                </div>
            </div>
        </div>
    </div>
    <!-- -----------------------Portfolio------------------->
    <div id="portfolio">
        <div class="container">
            <h1 class="sub-title">My Work</h1>
            <div class="work-list">
                <div class="work">
                    <img src="images/work-1.png" alt="Work-1">
                    <div class="layer">
                        <h3>Personal Portfolio</h3>
                        <p>I created my personal portfolio website for my very first project</p>
                        <a href="#"><i class="fa-solid fa-square-arrow-up-right fa-xl" style="color: #ff004f;"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/work-2.png" alt="Work-2">
                    <div class="layer">
                        <h3>Google Drive Clone</h3>
                        <p>I created a frontend clone of google drive for my second project</p>
                        <a href="#"><i class="fa-solid fa-square-arrow-up-right fa-xl" style="color: #ff004f;"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="images/work-3.png" alt="Work-3">
                    <div class="layer">
                        <h3>To be filled</h3>
                        <p>This section will be filled soon with my upcoming projects</p>
                        <a href="#"><i class="fa-solid fa-square-arrow-up-right fa-xl" style="color: #ff004f;"></i></a>
                    </div>
                </div>
            </div>
            <a href="#" class="btn">See more</a>
        </div>
    </div>
    <!-- --------------------contact------------ -->
    <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title">Contact Me</h1>
                    <p><i class="fa-solid fa-paper-plane" style="color: #09a0e1;"></i>abhishekpaul5648@gmail.com</p>
                    <p><i class="fa-solid fa-phone" style="color: #00db42;"></i>+91 8076835907</p>
                    <div class="social-icons">
                        <a href=""><i class="fa-brands fa-facebook"></i></a>
                        <a href="https://www.instagram.com/abhishekpaul.7/"><i class="fa-brands fa-instagram"></i></a>
                        <a href="https://www.linkedin.com/in/abhishek-paul-aa6257250/"><i class="fa-brands fa-linkedin"></i></a>
                    </div>
                    <a href="images/my-cv.pdf" download class="btn btn2">Download CV</a>
                </div>
                <div class="contact-right">
                    <form>
                        <input type="text" name="Name" placeholder="Your Name" required>
                        <input type="email" name="Email" placeholder="Your Email" required>
                        <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                        <button type="submit" class="btn btn2">Submit</button>
                    </form>
                </div>
            </div>
        </div>
        <div class="copyright">
            <p>copyright © Paul Made by Abhishek Paul <i class="fa-regular fa-futbol" style="color: #bfe114;"></i></p>
        </div>
    </div>
    <script>
        var tablinks=document.getElementsByClassName('tab-links');
        var tabcontents=document.getElementsByClassName('tab-contents');
        function opentab(s){
            for(items of tablinks){
                items.classList.remove("active-link");
            }
            for(items of tabcontents){
                items.classList.remove("active-tab");
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(s).classList.add("active-tab");
        }
        var sidemenu=document.getElementById('sidemenu');
        function openMenu(o){
            sidemenu.style.right="0";
        }
        function closeMenu(o){
            sidemenu.style.right="-200px";
        }
    </script>
</body>
</html>
