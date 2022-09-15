# new
#<!DOCTYPE html>
#<html lang="en">

#<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./font-awesome.min.css">
    <link rel="stylesheet" href="./normalize.css">
    <link rel="stylesheet" href="./SpecialDesign.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;700&display=swap" rel="stylesheet">

    <title>Special Design</title>
</head>

<body>

    <!-- Start Setting Box -->

    <div class="setting-box">
        <div class="toggle-settings">
            <i class="fa fa-gear sett"></i>
        </div>
        <div class="setting-container">
            <div class="option-box">
                <h4 style="font-size: 25px;">Colors</h4>
                <ul class="colors-list">
                    <li class="active" data-color="#FF9800"></li>
                    <li data-color="#E91E63"></li>
                    <li data-color="#009688"></li>
                    <li data-color="#03A9F4"></li>
                    <li data-color="#4CAF50"></li>
                </ul>
            </div>
            <div class="option-box">
                <h4> Random Backgrounds </h4>
                <div class="random">
                    <span class="yes active" data-background="yes">Yes</span>
                    <span class="no" data-background="no">No</span>
                </div>
            </div>
            <div class="option-box">
                <h4>Choose Background</h4>
                <div class="imgs-list">
                    <img src="./Data/Background01.jpg" alt="" data-img="Background01.jpg" class="active">
                    <img src="./Data/Background02.jpg" alt="" data-img="Background02.jpg">
                    <img src="./Data/Background03.jpg" alt="" data-img="Background03.jpg">
                    <img src="./Data/Background04.jpg" alt="" data-img="Background04.jpg">
                    <img src="./Data/Background05.jpg" alt="" data-img="Background05.jpg">
                    <img src="./Data/Background06.jpg" alt="" data-img="Background06.jpg">
                </div>
            </div>
            <div class="option-box">
                <h4>Show Bullets</h4>
                <div class="bullets-option">
                    <span class="yes active" data-display="show">Yes</span>
                    <span class="no" data-display="hide">No</span>
                </div>
            </div>
            <button class="reset-option">Reset Options</button>
        </div>
    </div>

    <!-- End Setting Box -->

    <!-- Start NAV Bullets -->

    <div class="nav-bullets">
        <div class="bullet" data-section=".testimonials">
            <div class="tooltip">End</div>
        </div>
        <div class="bullet" data-section=".about-us">
            <div class="tooltip">About US</div>
        </div>
        <div class="bullet" data-section=".skills">
            <div class="tooltip">Our Skills</div>
        </div>
        <div class="bullet" data-section=".gallery">
            <div class="tooltip">Our Gallery</div>
        </div>
        <div class="bullet" data-section=".timeline">
            <div class="tooltip">Timeline</div>
        </div>
        <div class="bullet" data-section=".header-area">
            <div class="tooltip">Top</div>
        </div>
    </div>

    <!-- End NAV Bullets -->

    <!-- Start Landing page -->

    <div class="landing-page">
        <div class="overlay"></div>
        <div class="container">
            <div class="header-area">
                <div class="logo"></div>
                <div class="links-container">
                    <ul class="links">
                        <li> <a href="#" data-section=".about-us">About US</a> </li>
                        <li> <a href="#" data-section=".skills">Skills</a> </li>
                        <li> <a href="#" data-section=".gallery">Gallery</a> </li>
                        <li> <a href="#" data-section=".timeline">Timeline</a> </li>
                        <li> <a href="#" data-section=".features">Features</a> </li>
                        <li> <a href="#" data-section=".testimonials">Testimonials</a> </li>
                    </ul>
                    <button class="toggle-menu">
                        <span></span>
                        <span></span>
                        <span></span>
                    </button>
                </div>
            </div>
        </div>
        <div class="introduction-text">
            <h1> We are <span> Creative </span> Agency </h1>
            <p> Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nostrum ipsum dolor sit amet consectetur
                adipisicing elit. Ad, enim Quod?
            </p>
        </div>
    </div>

    <!-- End Landing page  1920*1080 -->

    <!-- Start Our Skills -->

    <div class="skills">
        <div class="container">
            <h2>Our Skills</h2>
            <div class="skill-box">
                <div class="name">HTML</div>
                <div class="skill-progress">
                    <span data-progress="80%"></span>
                </div>
            </div>
            <div class="skill-box">
                <div class="name">CSS</div>
                <div class="skill-progress">
                    <span data-progress="70%"></span>
                </div>
            </div>
            <div class="skill-box">
                <div class="name">JavaScript</div>
                <div class="skill-progress">
                    <span data-progress="90%"></span>
                </div>
            </div>
            <div class="skill-box">
                <div class="name">Python</div>
                <div class="skill-progress">
                    <span data-progress="80%"></span>
                </div>
            </div>
            <div class="skill-box">
                <div class="name">PHP</div>
                <div class="skill-progress">
                    <span data-progress="90%"></span>
                </div>
            </div>
            <div class="skill-box">
                <div class="name">MySQL</div>
                <div class="skill-progress">
                    <span data-progress="70%"></span>
                </div>
            </div>
        </div>
    </div>

    <!-- Start Our Skills -->

    <!-- Start Testimonials -->

    <div class="testimonials">
        <div class="container">
            <h2>Testimonials</h2>
            <div class="ts-box">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi porro hic explicabo atque unde
                    optio, minima quos</p>
                <div class="person-info">
                    <img src="./Data/Personal.jpg" alt="">
                    <h4>Mario Shawky</h4>
                    <p>CEO at Company</p>
                </div>
            </div>
            <div class="ts-box">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi porro hic explicabo atque unde
                    optio, minima quos</p>
                <div class="person-info">
                    <img src="./Data/Personal02.jpg" alt="">
                    <h4>Mario Shawky</h4>
                    <p>CEO at Company</p>
                </div>
            </div>
            <div class="ts-box">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi porro hic explicabo atque unde
                    optio, minima quos</p>
                <div class="person-info">
                    <img src="./Data/Personal03.jpg" alt="">
                    <h4>Mario Shawky</h4>
                    <p>CEO at Company</p>
                </div>
            </div>
        </div>
        <div class="clearfix"></div>
    </div>

    <!-- End Testimonials -->

    <!-- Start Our Gallery -->

    <div class="gallery">
        <div class="container">
            <h2>Our Gallery</h2>
            <div class="images-box">
                <img src="./Data/Background01.jpg" alt="Image One">
                <img src="./Data/Background02.jpg" alt="Image Two">
                <img src="./Data/Background03.jpg" alt="Image Three">
                <img src="./Data/Background04.jpg" alt="Image Four">
                <img src="./Data/Background05.jpg" alt="Image Five">
                <img src="./Data/Background06.jpg" alt="">
                <img src="./Data/Background07.jpg" alt="">
                <img src="./Data/Background08.jpg" alt="">
                <img src="./Data/Background09.jpg" alt="">
                <img src="./Data/Background10.jpg" alt="">
                <img src="./Data/Background11.jpg" alt="">
                <img src="./Data/Background12.jpg" alt="">
                <img src="./Data/Background13.jpg" alt="">
                <img src="./Data/Background14.jpg" alt="">
                <img src="./Data/Background15.jpg" alt="">
            </div>
        </div>
    </div>

    <!-- End Our Gallery -->

    <!-- Start Time Line -->

    <div class="timeline">
        <div class="container">
            <div class="timeline-content">
                <div class="year">2018</div>
                <div class="left">
                    <div class="content">
                        <h3>Testing Heading</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis fuga adipisci unde
                            facere iste aliquid hic modi recusandae sunt, neque impedit sapiente aperiam suscipit, cum,
                            sint voluptatum. Quam, rem repudiandae.</p>
                    </div>
                </div>
                <div class="clearfix"></div>
                <div class="right">
                    <div class="content">
                        <h3>Testing Heading</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis fuga adipisci unde
                            facere iste aliquid hic modi recusandae sunt, neque impedit sapiente aperiam suscipit, cum,
                            sint voluptatum. Quam, rem repudiandae.</p>
                    </div>
                </div>
                <div class="clearfix"></div>
                <div class="year">2016</div>
                <div class="left">
                    <div class="content">
                        <h3>Testing Heading</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis fuga adipisci unde
                            facere iste aliquid hic modi recusandae sunt, neque impedit sapiente aperiam suscipit, cum,
                            sint voluptatum. Quam, rem repudiandae.</p>
                    </div>
                </div>
                <div class="clearfix"></div>
                <div class="left">
                    <div class="content">
                        <h3>Testing Heading</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis fuga adipisci unde
                            facere iste aliquid hic modi recusandae sunt, neque impedit sapiente aperiam suscipit, cum,
                            sint voluptatum. Quam, rem repudiandae.</p>
                    </div>
                </div>
                <div class="clearfix"></div>
            </div>
        </div>
    </div>

    <!-- End Time Line -->

    <!-- Start Features -->

    <div class="features">
        <div class="overlay"></div>
        <h2>Our Features</h2>
        <div class="container">
            <div class="feat-box">
                <img src="./Data/feature06.jpg" alt="">
                <h4>Development</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus sunt, vero minima, consequatur
                    fugiat est ex deserunt illo facilis, amet nam! Dolor omnis, vero veniam cum magni accusantium iure
                    maiores.</p>
            </div>
            <div class="feat-box">
                <img src="./Data/feature01.jpg" alt="">
                <h4>Development</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus sunt, vero minima, consequatur
                    fugiat est ex deserunt illo facilis, amet nam! Dolor omnis, vero veniam cum magni accusantium iure
                    maiores.</p>
            </div>
            <div class="feat-box">
                <img src="./Data/feature02.jpg" alt="">
                <h4>Development</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus sunt, vero minima, consequatur
                    fugiat est ex deserunt illo facilis, amet nam! Dolor omnis, vero veniam cum magni accusantium iure
                    maiores.</p>
            </div>
            <div class="feat-box">
                <img src="./Data/feature03.jpg" alt="">
                <h4>Development</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus sunt, vero minima, consequatur
                    fugiat est ex deserunt illo facilis, amet nam! Dolor omnis, vero veniam cum magni accusantium iure
                    maiores.</p>
            </div>
            <div class="feat-box">
                <img src="./Data/feature04.jpg" alt="">
                <h4>Development</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus sunt, vero minima, consequatur
                    fugiat est ex deserunt illo facilis, amet nam! Dolor omnis, vero veniam cum magni accusantium iure
                    maiores.</p>
            </div>
            <div class="feat-box">
                <img src="./Data/feature05.jpg" alt="">
                <h4>Development</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus sunt, vero minima, consequatur
                    fugiat est ex deserunt illo facilis, amet nam! Dolor omnis, vero veniam cum magni accusantium iure
                    maiores.</p>
            </div>
            <div class="clearfix"></div>
        </div>
    </div>

    <!-- End Features -->

    <!-- Start About Us -->
    <div class="container">
        <div class="about-us">
            <div class="info-box">
                <h2>About Us</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam id dolore cum ipsam neque accusamus
                    pariatur nam explicabo. Aperiam laudantium deleniti accusantium ea? Eius quidem deleniti sit neque
                    provident corporis.</p>
            </div>
            <div class="image-box">
                <img class="new-style" src="./Data/illustration.jpg" alt="">
            </div>
        </div>
    </div>

    <!-- End About Us -->

    <!-- Start Contact Us -->

    <div class="contact">
        <div class="overlay"></div>
        <div class="container">
            <h2>Contact US</h2>
            <form action="">
                <div class="left">
                    <input type="text" placeholder="Your Name" name="username">
                    <input type="text" placeholder="Your Phone" name="phone">
                    <input type="email" placeholder="Your Email" name="email">
                    <input type="text" placeholder="Subject" name="subject">
                </div>
                <div class="right">
                    <textarea name="message" placeholder="Your Message"></textarea>
                    <input type="submit" value="send">
                </div>
            </form>
        </div>
    </div>

    <!-- End Contact Us -->

    <!-- Start Footer -->

    <div class="footer">Created By Mero SH</div>

    <!-- End Footer -->

    <script src="./SpecialDesign.js"></script>
</body>

</html>
