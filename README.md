<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PERSONAL PORTFOLIO WEBSITE</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/9cebcab26d.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="/image/WhatsApp Image 2022-10-15 at 10.02.46 PM.jpeg" class="logo">
                <ul>
                    <li><a href="#header">HOME</a></li>
                    <li><a href="#about">ABOUT</a></li>
                    <li><a href="#services">SERVICES</a></li>
                    <li><a href="#Portfolio">PORTFOLIO</a></li>
                    <li><a href="#contact">CONTACT</a></li>
                    
                </ul>
                
            </nav>

            <div class="header-text">
                <p>WEBSITE DESIGNER</p>
                <h1>Hi, I'm <span>dhyey</span> <br>khanpara From India</h1>
            </div>
        </div>
    </div>
    <!-------------ABOUT------------->
    <div id="about">
        <div class="container">
            <div class="ROW">
                <div class="about-col-1">
                    <img src="/image/ori.jpeg" height="650px">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me</h1>
                    
                    <br>
                    <br>
                    <p>
                    <ul>
                        <li>
                            MY SELF DHYEY KHANPARA ,I AM STUDING IN COMPUTER ENGNEERING IN LDRP-ITR I COMPLETE MY
                            SCOOLING IN GENIUS INTERNATIONAL SCHOOL.
                        </li>
                    </ul>
                    </p>
                    <div class="tab-titles">
                        <p class="tab-links active-link"onclick="opentab('skills')" >SKILLS</p>
                        <p class="tab-links "onclick="opentab('experience')">EXPERIENCE</p>
                        <p class="tab-links"onclick="opentab('education')">EDUCATION</p>
                    </div>

                    <div class="tab-contents active-tab" id="skills" >
                        <ul>
                            <li>
                                <span>WEB DEVLOPER</span><br>Designing WEB/APP interface
                            </li>
                            <li>
                                <span>WEB DEVLOPMENT</span><br>Web app Devlopment
                            </li>
                            <li>
                                <span>APP DEVELOPMENT</span><br>Building Android apps
                            </li>
                        </ul>
                    </div>
                    <!------------exp------------>

                    <div class="tab-contents" id="experience" >
                        <ul>
                            <li>
                                <span>2022 - current</span><br>STUDING WEB DEVELOPMENT AT LDRP-ITR
                            </li>
                            <li>
                                <span>2021 - 2022</span><br>STUDING COMPUTER ENGNEERING AT LDRP-ITR
                            </li>
                            <li>
                                <span>2020 - 2021</span><br>STUDING 12TH SCIENCE
                            </li>
                        </ul>
                    </div>
                    <!----------education----------->
                    <div class="tab-contents" id="education" >
                        <ul>
                            <li>
                                <span>2025</span><br>PASS OUT LDRP-ITR
                            </li>
                            <li>
                                <span>2021 - 2022</span><br>STUDING COMPUTER ENGNEERING AT LDRP-ITR
                            </li>
                            <li>
                                <span>2020 - 2021</span><br>STUDING 12TH SCIENCE
                            </li>
                        </ul>
                    </div>

                </div>
            </div>
        </div>
    </div>
    <!-------------services--------------->
   <div id="services">
    <div class="container">
        <h1 class="sub-title">My services</h1>
        <div class="services-list">
            <div>
                <i class="fa-solid fa-code"></i>
                <h2>WEB DESIGN</h2>
                <p>
                    Web design is a multi-disciplinary job, where you'd need not only knowledge in design (typography, color theory) but also skills in developing a website (HTML, CSS, JavaScript). Some web designers are also involved in interaction design when they code for animations and interactions using CSS and/or JavaScript.
                </p>
                <a href="https://www.geeksforgeeks.org/web-development/">Learn more</a>
            </div>
            <div>
                <i class="fa-solid fa-mobile"></i>
                <h2>FRAMEWORK ANDROID/IOS</h2>
                <p>
                    It is a streamlined framework used for developing apps for Android, Windows, and iOS with the help of C# and . Net, instead of JS libraries and HTML. It allows the developers to use 90% of the code for building an app for three distinct platforms.
                </p>
                <a href="https://www.geeksforgeeks.org/top-10-mobile-application-development-frameworks-in-2020/">Learn more</a>
            </div>
            <div>
                <i class="fa-solid fa-database"></i>
                <h2>DATA BASE MANAGMENT</h2>
                <p>
                    A database management system (or DBMS) is essentially nothing more than a computerized data-keeping system. Users of the system are given facilities to perform several kinds of operations on such a system for either manipulation of the data in the database or the management of the database structure itself.
                </p>
                <a href="https://www.geeksforgeeks.org/what-is-database/#:~:text=A%20database%20is%20a%20collection,data%20in%20a%20structured%20form.">Learn more</a>
            </div>
        </div>
    </div>
   </div>
   <!---------portfolio---------->
   <div id="Portfolio">
    <div class="container">
        <h1 class="sub-title">My Work</h1>
        <div class="work-list">
            <div class="work">
                <img src="/image/work-1.png">
                <div class="layer">
                    <h3>Social Media App</h3>
                    <p>The app connects you yo the talented people around the world.
                        Download it from play store.
                    </p>
                    <a href="https://www.instagram.com/"><i class="fa-sharp fa-solid fa-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="/image/work-2.png">
                <div class="layer">
                    <h3>Music App</h3>
                    <p>The app connects you yo the talented people around the world.
                        Download it from play store.
                    </p>
                    <a href="https://www.spotify.com/in-en/"><i class="fa-sharp fa-solid fa-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="/image/work-3.png">
                <div class="layer">
                    <h3>Online Shopping App</h3>
                    <p>The app connects you yo the talented people around the world.
                        Download it from play store.
                    </p>
                    <a href="
                    https://www.amazon.in/
                    "><i class="fa-sharp fa-solid fa-up-right-from-square"></i></a>
                </div>
            </div>
        </div>
        <a href="#" class="btn">See more</a>
    </div>
</div>
<!--------------contect----------->
<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p><i class="fa-solid fa-envelope"></i>dhyey2112004@gmail.com</p>
                <p><i class="fa-solid fa-phone"></i>9737794277</p>
                <div class="social-icons">
                    <a href="https://www.instagram.com/_dhyey_21/"><i class="fa-brands fa-instagram"></i></a>
                    <a href="https://github.com/dhyeykhanpara21"><i class="fa-brands fa-github"></i></a>
                    <a href="https://www.linkedin.com/in/dhyey-khanpara-678791204/"><i class="fa-brands fa-linkedin"></i></a>
                    <a href="https://twitter.com/khanpara_dhyey"><i class="fa-brands fa-twitter"></i></a>
                </div>
                <a href="/CV.pdf" download class="btn btn2">Download Cv</a>
            </div>
            <div class="contact-right">
                <form name="submit-to-google-sheet">
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <input type="email" name="Email" placeholder="Your Email" required>
                    <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                    <button type="Submit" class="btn btn2">Submitbutton>
                </form>
                <span id="msg"> </span>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>copyright.Made with<i class="fa-solid fa-heart"></i>by DHYEY KHANPARA</p>
    </div>
</div>    
    <script>

        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");

        function opentab(tabname)
        {
            for(tablink of tablinks){
                tablink.classlist.remove("active-link");
            }
            for(tabcontent of tabcontents){
                tabcontent.classlist.remove("active-tab");
            }
            event.currentTarget.classlist.add("active-link");
            document.getElementById(tabname).classlist.add("active-tab"); 
        }
        
    </script>
<script>
    const scriptURL = 'https://script.google.com/macros/s/AKfycbyUCnBZZeDZ5o1-zZI_hNpUDhZISx4lRag9m9uskbL-ofQmtV9hhzZod7_msKrFGt6s/exec'
    const form = document.forms['submit-to-google-sheet']
    const mag =document.getElementById("msg")
  
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => {
            msg.innerhtml="message sent successfully"
            setTimeout(function(){
                msg.innerhtml=""
            },5000)
            form.reset()
        })
        .catch(error => console.error('Error!', error.message))
    })
  </script>
</body>

</html>
