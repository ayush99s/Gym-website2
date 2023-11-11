# Gym-website2
the basic front end

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZENITH.com</title>
    <link rel="stylesheet" type="text/css" href="zenith.css">
    <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Smooth scroll functionality for anchor links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    
                    const targetId = this.getAttribute('href').substring(1);
                    const targetElement = targetId === 'home' ? document.documentElement : document.getElementById(targetId);
    
                    if (targetElement) {
                        targetElement.scrollIntoView({
                            behavior: 'smooth'
                        });
                    }
                });
            });
        });
        function scrollToTop() {
        window.scrollTo({
            top: 0,
            behavior: 'smooth'
        });
    }
    </script>
</head>
<body>

    <nav id="home" >
        <div class="logo">
            <img src="zenith2.png" height="80" class="h">
            <span id="pink">ZENITH</span>
            
            </div>
            <div class="menu">
                <a href="#"onclick="scrollToTop()">HOME</a>
                <a href="#about">ABOUT</a>
                <a href="#services">SERVICE</a>
                <a href="#signup">CLIENT</a>
                <a href="#work">WORK</a>
                <a href="#footer">CONTACT</a>
                
            </div>
            <div class="icon">
                 <img src="fb.png">
                    <img src="bird2.png"><img src="insta.2.png">
                
            </div>
    </nav>

    <div class="container">
        <div class="left">
            <img src="fornt.jpg" height="400"  >
        </div>
        <div class="right">
            <p>HI!!</p>
            <h1>Welcome to ZENITH</h1>
            <p>“The body achieves what the mind believes."</p>
            <p>Stay fit with us</p>
            
                <button class="but">
                    Login
                </button>
            
        </div>
    </div>

<section id="about">
    <div class="About-row">
        <div class="about-left-col">
            <h1>About <span id="blue">US</span></h1>
            <p id="p">
                At Gym and Fitness, we believe that fitness and wellbeing are the cornerstones of a full and vibrant life. Establish in 2023, we began our journey as a family-owned business dedicated to providing exceptional gym equipment at affordable prices. But, we dreamed bigger than just being an ordinary fitness equipment supplier; we aspired to lead the industry.
            
                
                </p>
                <p>
                    Join us in our mission to improve lives through fitness and wellness, because at Gym and Fitness, your health is our passion.
                </p>
                <button class="btn1">Read More</button>
        </div>
        <div class="about-right-col">
            <img src="banner.png"  >
        </div>
    </div>
</section>
<section id="signup">
    <div class="signup-row">
        <div class="signup-left-col">
            <img src="service.jpg" height="400">
        </div>
        <div class="signup-right-col">
            <h1>BEING <span id="blue"> BODY</span></h1>
            <h2>BUILDER</h2>
            <!-- <button class="btn1">Signup</button> -->
            <button><span></span>
                <a class="btn1" href="signup.html">Sign Up </a></button>
        </div>
    </div>
</section>
<section id="services">
    <div class="info">
        <h1>Our <span id="blue">Services</span></h1>
        <p>What we Provide?</p>
    </div>
    <div class="services-row">
        <div class="services-box">
            <i class="fa-solid fa-heart-circle-bolt"></i>
            
            <h2>Cardio</h2>
            <p>Cardio is good for healthy life,It help you to increase stamina </p>
        </div>
        <div class="services-box">
            <i class="fa-solid fa-dumbbell"></i>
            
            <h2>Best GYM</h2>
            <p>Gym is good for healthy life but a good  GYM is more important for best outcome of your physique</p>
        </div>
        <div class="services-box">
            <i class="fa-solid fa-video"></i>
            
            <h2>Tutorial Videos</h2>
            <p>Best videos according to the body parts.</p>
        </div>
        <div class="services-box">
            <i class="fa-solid fa-suitcase"></i>
            
            <h2>Membership with offer</h2>
            <p>Gym is good for healthy life but a good  GYM is more important for best outcome of your physique</p>
        </div>
        <div class="services-box">
            <i class="fa-solid fa-suitcase"></i>
            
            <h2>Best Trainer</h2>
            <p>Gym is good for healthy life but a good  GYM is more important for best outcome of your physique</p>
        </div>
        <div class="services-box">
            <i class="fa-solid fa-suitcase"></i>
            
            <h2></h2>
            <p>Gym is good for healthy life but a good  GYM is more important for best outcome of your physique</p>
        </div>
      
        
    </div>
</section id="Goals">
    <div class="info">
        <h1>Our <span id="blue">Goals</span></h1>
        <p>What our Goals?</p>
        <p>
            By providing information, inspiration, and support, the website can help people get started on their fitness journey and stay motivated.
        </p>
    </div>
</section>

<section id="work">
    <div class="info">
        <h1>Our <span id="blue">Work</span></h1>
        <p>What our works?</p>
    </div>
    <div class="services-row  hju">
        <div class="yu">
            <img src="ex1.jpg"class="worka">
            <img src="ex2.jpg" class="workb">
            <img src="ex3.jpg"class="workc">
            <img src="ex4.jpg"class="workd">
            <img src="ex5.jpg"class="worke">
            <img src="ex6.jpg"class="workf">
        </div>
    
    </div>
</section>

<section id="footer">
        <h1>ZEN<span id="blue">ITH</span></h1>
        <p>&copy;2023 zenith a gym website</p>
        <img src="bird2.png"><img src="insta.2.png">  <img src="fb.png">
    </div>
    <div class="contact-row" >
        <div class="contact-left-col">
            <div class="contact-right-col">
                <h2><i class="fa-solid fa-envelope"></i>E-mail</h2><p>ayushshukla9540@gmail.com</p>
                <h2><i class="fa-solid fa-mobile"></i>Mobile</h2><p>958487585</p>
                <h2><i class="fa-solid fa-location-dot"></i>Address</h2><p>nearghaziabad,NCR Delhi</p>
                
            </div>
        </div>
    </div>
</section>
<script src="./singup.js"></script>
    
</body>
</html>



#Css part


*{padding: 0; margin: 0; box-sizing: border-box; font-family: sans-serif;}
.container{
    width: 100%;
    height: 100vh;
    background:black ;
    clip-path: polygon(0% 0%,100% 0%,100% 100%,50% 75.5% ,0% 100%);
    
}
nav{
    width: 100%;
    height: 100px;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    color: white;
    position: sticky;
    top: 0px;
    z-index: 100;
    background: black;
    
}
nav {
    position: sticky;
    top: 0;
    background: linear-gradient(to right, #1b0f12, #00a1ff); /* Replace with your desired gradient colors */
    z-index: 100;
  }
  
  .logo #blue {
    background: -webkit-linear-gradient(#242222, #00a1ff);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
  

#pink{
    position: relative;
   
    bottom: 20px;
    color:rgb(81, 173, 150)

}
.logo
{
    font-size: 50px;
    font-weight: bold;
    letter-spacing: 5px;
}
#blue{
    color: #74b9ff;
    
}
.menu a{
    text-decoration: none;
    color:white;
    font-size: 20px;
    font-weight: bold;
    padding: 10px;
    margin: 10px;
}
.menu a:first-child{
    border-bottom: 1px solid;
    
    background: #74b9ff;
    position:relative;
    
}

.container{
    width: 100%;
    display: flex;justify-content: center;
    align-items: center;
    color: white;
    
}
.left{
    flex-basis: 50%;

}
.right{
    flex-basis: 50%;
    max-width: 400px;
}
.right h1{
    color: #74b9ff;
    font-size: 40px;
}
.right p{
    font-size: 25px;
    margin: 10px 0px;
}
.but
{
    background: transparent;
    padding: 10px 20px;
    color: aqua;
    border: 1px solid #74b9ff;
    border-radius: 8px;
}
#about
{
    padding: 100px 0px;
}
.about-row
{
    width: 100%;
    display:flex;
    justify-content: space-around;
    align-items: center;
}
.about-left-col{
    flex-basis: 50%;
}
.about-right-col{
    flex-basis: 50%;
    text-align:right;
    
}
.about-right-col img
{
width: 40%;
text-align: right;
}
.about-left-col{
    max-width: 400px;
    margin:auto;
}

.about-left-col h1{
    font-size: 50px;
}
.about-left-col p{
    font-size: 20px;
    text-align: justify;
    margin: 15px 0px;
}
.btn1{
    padding: 10px;
    margin: 10px 0px;
    color: white;
    border: none;
    background: #74b9ff;
}

#signup{
    padding-top:50px ;
    padding-bottom: 20px;
    background: rgba(0,0,0,0.03);
    clip-path: polygon(0% 0%,100% 0%,100% 100%,80% 80% ,0% 100%);
}
.signup-row{
    display: flex;
    justify-content: space-around;
    align-items: center;
}
.signup-left-col{
    flex-basis: 50%;
    text-align: center;
}
.signup-right-col{
    flex-basis: 50%;
}
.signup-right-col h1{
    font-size: 90px;
}
.signup-right-col h2{
    font-size: 45px;
    letter-spacing:60px;
    color:rgba(0,0,0,0.3);
    margin: 10px 0px;
}
#services{
    padding: 50px 0px;
}
.info{
    text-align: center;

}
.info h1{
    font-size: 50px;
} 
.info p{
    font-size: 25px;
    font-weight: bold;
}
.services-row{
    display: grid;
    grid-template-columns: repeat(3,200px);
    grid-auto-rows: minmax(150px,auto);
    grid-gap: 3em;
    justify-content: center;
    padding-top: 20px;
}
.services-box{
    box-shadow:2px 3px 5px hotpink;
    padding: 10px;
    text-align: center;
}
.services-box i{
    background: black;
    color: white;
    font-size: 20px;
    padding: 10px;
    margin-top:-20px;

}

#Goals{
    padding: 100px;
    text-align: center;
    font-size: 30px;
    
}
#work{
    padding-top:50px ;
    padding-bottom:200px ;
    background: rgba(0,0,0,0.03);
}
.work-box{
    box-shadow: 2px 3px 5px hotpink;

}

.yu{
 
    width: 100%;
    position: relative;
}
.worka{
    width: 200px;
    position:absolute;
    margin:20px;
}
.workb{
    width: 200px;
    position:absolute;
    margin:20px;
    
    left:250px;
}
.workc{
    width: 200px;
    position:absolute;
    margin:20px;
    
    left:500px;
}
.workd{
    width: 200px;
    position:absolute;
    top: 200px;
    margin:20px;
 
}
.worke{
    width: 200px;
    position:absolute;
    top: 200px;
    left:250px;
    margin:20px;
    height:110px
}
.workf{
    width: 200px;
    position:absolute;
    top: 200px;
    left:500px;
    margin:20px;
    height:110px;
}

#footer{
    background: black;
    color:white;
    padding: 10px;
    display: flex;
    justify-content: space-around;
    align-items: center;

}

   
    
   
    
