# JEE-NEET-COACHING

//HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,200;0,300;0,400;0,500;1,100&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.1/css/fontawesome.min.css">
    <link rel="stylesheet" href="MyAcademy.css">
    <script src="https://kit.fontawesome.com/696ae4e2a9.js" crossorigin="anonymous"></script>
    <title>My Academy</title>
</head>
<body>

    <section class="header">
        <nav>
            <a href="img/coachinglogo1.png"><img src="img/coachinglogo1.png" alt=""></a>
            <div class="nav-links" id="navLinks">
                <i class="fa fa-times" id="nav1" onclick="hideMenu()"></i>
                
                <ul>
                    <li><a href="">HOME</a></li>
                    <li><a href="">ABOUT</a></li>
                    <li><a href="">COURSE</a></li>
                    <li><a href="">BLOG</a></li>
                    <li><a href="">CONTACT</a></li>
                </ul>
                
            </div>
            <i class="fa fa-bars" id="nav2" onclick="showMenu()"></i> 
        </nav>
        <div class="text-box">
            <h1>India's Best Coaching Institute</h1>
            <p>It is India's best coaching institute founded by IITIANS. <br><br>Come to learn</p>
            <a href="" class="hero-btn">Visit Us to Know More</a>

        </div>

    </section>

    <script>
        var navLinks=document.getElementById("navLinks");

        function showMenu(){
            navLinks.style.right="0";
        }
        function hideMenu(){
            navLinks.style.right="-200px";
        }

    </script>

    <!-- Courses -->
    <section class="course">
        <h1>Courses We Offer</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum, corporis?</p>

       <div class="row">
          <div class="course-col">
            <h3>FIRST YEAR (11th)</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore animi similique fuga sapiente cumque, vitae perferendis explicabo. Illo, id soluta.</p>
          </div>

          <div class="course-col">
            <h3>INTERMEDIATE (12th)</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore animi similique fuga sapiente cumque, vitae perferendis explicabo. Illo, id soluta.</p>
          </div>

          <div class="course-col">
            <h3>DROPPER (13th)</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore animi similique fuga sapiente cumque, vitae perferendis explicabo. Illo, id soluta.</p>
          </div>
       </div>
    </section>

    <!-- Center -->
    <section class="center">
        <h1>Our Offline Centers</h1>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Reiciendis, ut.</p>

        <div class="row">
            <div class="center-col">
                <img src="img/center6.jpg">
                <div class="layer">
                    <h3>DELHI</h3>
                </div>
            </div>

            <div class="center-col">
                <img src="img/center2.jpg">
                <div class="layer">
                    <h3>KANPUR</h3>
                </div>
            </div>

            <div class="center-col">
                <img src="img/center7.jpg">
                <div class="layer">
                    <h3>LUCKNOW</h3>
                </div>
            </div>

        </div>

    </section>
    <!-- Facilities -->

    <section class="facilities">
        <h1>OUR facilities</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit, deleniti.</p>
        <div class="row">
            <div class="facilities-col">
                <img src="img/classrroms.webp" alt="">
                <h3>HIGH TECH CLASSROOMS</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores, iure!</p>
            </div>
            <div class="facilities-col">
                <img src="img/assessment.webp" alt="">
                <h3>REGULAR ASSESSMENT</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores, iure!</p>
            </div>
            <div class="facilities-col">
                <img src="img/hostel.jpg" alt="">
                <h3>BEST HOSTELS</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores, iure!</p>
            </div>
        </div>
    </section>

    <!-- testimonials -->
    <section class="testimonials">
        <h1>What Our Students Says</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid, facilis.</p>
        <div class="row">
            <div class="testimonials-col">
                 <img src="img/p3.jpg" >
                 <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                 <h3>Swati Singh</h3>
                 <i class="fa-solid fa-star"></i>
                 <i class="fa-solid fa-star"></i>
                 <i class="fa-solid fa-star"></i>
                 <i class="fa-solid fa-star"></i>
                 <i class="fa-solid fa-star"></i>
            </div>
            <div class="testimonials-col">
                <img src="img/p2.webp" >
                <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque, suscipit!</p>
                <h3>Pawan Kumar</h3>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star-half"></i>
           </div>
        </div>

    </section>

    <!-- Call to action -->
    <section class="cta">
        <h1>Enroll for Our Various Online Courses.<br> Anywhere from the World
        </h1>
        <a href="" class="hero-btn">CONTACT US</a>

    </section>

    <!-- Footer -->

    <section class="footer">
        <h4>About Us</h4>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.<br>Saepe laudantium quisquam ipsa distinctio harum illum nihil exercitationem, magnam provident corrupti.</p>
        <div class="icons">
        <i class="fa-brands fa-linkedin"></i>
        <i class="fa-brands fa-facebook"></i>
        <i class="fa-brands fa-square-instagram"></i>
        <i class="fa-brands fa-twitter"></i>
        </div>

        <p>Made With <i class="fa-solid fa-heart"></i> by Ram Mohan Patel</p>

    </section>

    
</body>
</html>

//CSS

*{
    padding: 0;
    margin: 0;
    font-family: 'Poppins', sans-serif;
}

.header{
    min-height: 100vh;
    width: 100%;
    background-image: linear-gradient(rgba(4,9,30,0.7),rgba(4,9,30,0.7)),url(img/coaching1.jpg);
    background-position: center;
    background-size: cover;
    position: relative;
}

nav{
    display:flex;
    padding:2% 6%;
    justify-content:space-between;
    align-items: center;
}

nav img{
    width: 150px;
}
.nav-links{
    flex: 1;
    text-align:right;
}
.nav-links ul li{
    list-style: none;
    display:inline-block;
    padding: 8px 12px;
    position:relative;
}
.nav-links ul li a{
    color:#fff;
    text-decoration: none;
    font-size: 20px;
}
.nav-links ul li::after{
    content: '';
    width: 0%;
    height: 2px;
    background: #f44336;
    display: block;
    margin:auto;
    transition: 0.5s;   
}
.nav-links ul li:hover::after{ 
    width: 100%;
}
.text-box{
    width: 90%;
    color: #ffff;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    text-align: center;
}
.text-box h1{
    font-size:62px ;
}
.text-box p{
    font-size: 30px;
    margin: 10px 0 40px;
    color: #fff;
}

.hero-btn{
    display: inline-block;
    text-decoration: none;
    color: #fff;
    padding: 12px 34px;
    border: 1px solid #fff;
    font-size: 13px;
    background: transparent;
    position: relative;
    cursor: pointer;
}
.hero-btn:hover{
    border: 1px solid #f44336;
    background: #f44336;
    transition: 1s;
}
#nav1{
    display: none;
}
#nav2{
    display: none;
}


@media(max-width: 700px){
    .text-box h1{
        font-size: 20px;
    }
    .nav-links ul li{
        display: block;
    }
    .nav-links{
        position: absolute;
        background: #f44336;
        height: 100vh;
        width: 200px;
        top: 0;
        right: -200px;
        text-align: left;
        z-index: 2;
        transition: 1s;
    }
    #nav1 {
        display: block;
        color: #fff;
        margin: 10px;
        font-size: 22px;
        cursor: pointer;
    }
    #nav2 {
        display: block;
        color: #fff;
        margin: 10px;
        font-size: 22px;
        cursor: pointer;
    }
    .nav-links ul {
        padding:30px
    }
}
.course{
    width: 80%;
    text-align: center;
    justify-content: space-between;
    margin: auto;
    padding-top: 100px;
}
h1{
    font-size: 36px;
    font-weight: 600;
}
p{
    color: #777;
    font-size: 14px;
    font-weight: 300;
    line-height: 22px;
    padding: 10px;
}
.row{
    margin-top: 5%;
    display: flex;
    justify-content: space-between;
}
.course-col{
    flex-basis: 31%;
    background: #fff3f3;
    border-radius:10px;
    margin-bottom: 5%;
    padding: 20px 12px;
    box-sizing: border-box;
}
h3{
    text-align:center;
    font-weight: 600;
    margin: 10px 0;
}
.course-col:hover{
    box-shadow: 0 0 20px 0px rgba(0,0,0,0.2);
}
@media(max-width:700px){
    .row{
        flex-direction: column;
    }
}
.center{
    width: 80%;
    margin: auto;
    text-align: center;
    padding-top: 50px;
}

.center-col{
    flex-basis: 32%;
    border-radius: 10px;
    margin-bottom: 30px;
    position: relative;
    overflow: hidden;
}

.testimonials-col
{
    flex-direction: column;
    align-items: center;
}

.center-col img{
    width:200%; 
    display: block;
}
.layer{
    background: (transparent);
    height: 100%;
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    transition: 0.5s;
}
.layer:hover{
    background: rgba(226,0,0,0.7);
}
.layer h3{
    width: 100%;
    font-weight: 500;
    color: #fff;
    font-size: 26px;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    position: absolute;
    opacity: 0;
    transition: 0.5s;
}
.layer:hover h3{
    bottom: 49%;
    opacity: 1;
}

/* facilities */

.facilities{
    width: 80%;
    margin: auto;
    text-align: center;
    padding-top: 100px;
}
.facilities-col{
    flex-basis: 31%;
    border-radius: 10px;
    margin-bottom:5% ;
    text-align: left;
}
.facilities-col img{
    width:100%;
    border-radius: 10px;
}
.facilities-col p{
    padding:0;
}
.facilities-col h3{
    margin-top:16px;
    margin-bottom: 15px;
    text-align: left;
}

/* testimonials */

.testimonials{
    width:80%;
    margin: auto;
    text-align: center;
    padding-top: 100px;
}
.testimonials-col{
    flex-basis: 44%;
    border-radius: 10px;
    margin-bottom: 5%;
    text-align: left; 
    background: #fff3f3;
    padding: 25px;
    cursor: pointer;
    display: flex;
}
.testimonials-col img{
    height: 40px;
    margin-left: 5px;
    margin-right: 30px;
    border-radius: 100%;
}
.testimonials-col p{
    padding: 0;
}

.testimonials-col i{
    color: #f44336;
}
@media(max-width:700px){
    
    .testimonials-col h3{
        margin-top: 5px;
        margin-left: 0;
        
    }
    .testimonials-col i{
        display: inline;
    }
}
/* Call to action */
.cta{
    margin:auto;
    width: 80%;
    background-image: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.7)),url(img/cta.jpg);
    background-position: center;
    background-size: cover;
    border-radius: 10px;
    text-align: center;
    padding: 100px 0;
}

.cta h1{
    color:#fff;
    margin-bottom: 40px;
    padding: 0;
}
@media(max-width:700px){
    .cta h1{
        font-size:24px;
    }
}

/* footer */
.footer{
    width: 100%;
    text-align: center;
    padding: 30px 0;
}

.footer h4{
    margin-bottom: 25px;
    margin-top: 20px;
    font-weight: 600;
}
.icons i{
    color: #1f28a1;
    margin: 0 13px;
    cursor: pointer;
    padding: 18px 0;
}
.fa-solid fa-heart{
    color: rgb(255,0,0);
}


