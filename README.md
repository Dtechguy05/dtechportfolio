# dtechportfolio
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My Portfolio</title>
        <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    </head>
<body>
    <link rel="stylesheet" href="style.css">
    <header class="header">
        <a href="#home" class="logo">My <span> Portfolio </span></a>
    
        <nav class="navbar">
        <a href="#home" class="active">Home</a>
        <a href="#About">About</a>
        <a href="#services">Services</a>
        <a href="#Contacts">Contact</a>
        <a href="#Projects">Project</a>
    </nav>
    </header>

    <section class="home" id="home">
        <div class="home-img">
            <img src="uiux.jpg" alt="">
        </div>

        <div class="home-content">
            <h1> Hi It's <span>Olowookere Daniel</span></h1>
            <h3 class="text-animation">Involved in <span></span></h3>
            <p>I'm a UI/UX designer, Living in Lagos, Nigeria; Collaborating with amazing people around the world to create experiences for the most ambitious brands in the world.</p>

            <div class="social-icons">
                <a href="#"><i class='bx bxl-linkedin'></i></a>
                <a href="#"><i class='bx bxl-github' ></i></a>
                <a href="#"><i class='bx bxl-instagram-alt' ></i></a>
                <a href="#"><i class='bx bxl-twitter'></i></a>
            </div>
        
        <a href="#" class="btn">Hire Me</a>
        </div>
    </section>

    <section class="about" id="About">
        <div class="about-content">
            <h2 class="heading">About <span>Me</span></h2>
            <h3 class="text-animation">
                <span></span>
            </h3>
            <p>As a UI UX designer, the designer is always striving to create interfaces that are easy to use and look beautiful. so, as a ui/ux designer I take into account the user's needs wants when designing interfaces,and always aims to create a positive user experience</p>
            <a href="#" class="btn">Read More</a>
        </div>

        <div class="about-img">
            <img src="uiux.jpg" alt="">
        </div>
    </section>

    <section class="services" id="services">

        <h2 class="heading">Services</h2>

        <div class="services-container">

           
            <div class="service-box">
                <div class="service-info">
                    <h4>UI PROTOTYPING</h4>
                    <p>A UI prototype is a high-fidelity visual representation of a final product,It demonstrates the product's design and functionality to stakeholders, clients, and potential users during the design and development process.</p>
                </div>
            </div>

            <div class="service-box">
                <div class="service-info">
                    <h4>DESIGN RESEARCH</h4>
                    <p>Design research is the process of gathering, analyzing and interpreting data and insights to inspire, guide and provide context for designs. It’s a research discipline that applies both quantitative and qualitative research methods to help make well-informed design decisions.</p>
                </div>
            </div>

            <div class="service-box">
                <div class="service-info">
                    <h4>INTERACTIVITY AND ANIMATION</h4>
                    <p>Unlike traditional animation, interactive animation allows viewers to interact and engage with your design. In interactive animation, a computer application generates animation in real-time based on user inputs like hovering, clicking, scrolling, or other prompts.</p>
                </div>
            </div>
           
            <div class="service-box">
                <div class="service-info">
                    <h4>BRANDING & GRAPHICS DEVELOPMENT</h4>
                    <p>Graphic design plays a crucial role in visually representing brands. It ensures that your brand stands out from competitors. Specific design elements are strategically used to integrate branding into broader marketing activities, such as social media or print ads</p>
                </div>
            </div>
        </div>
    </section>
    <Section class="contact" id="Contacts">
        <h2 class="heading"> <span>Contact <span>Me</span></h2>

        <form action="#">
            <div class="input-box">
                <input type="text" placeholder="Full Name">
                <input type="email" placeholder="Email">
            </div>

            <div class="input-box">
                <input type="number" placeholder="Phone Number">
                <input type="text" placeholder="Subject">
                </div>

                <textarea name="" id="" cols="30" rows="10" placeholder="">Your Message</textarea>
                <input type="submit" value="Send Message" class="btn">
        </form>
    </Section>

    <footer class="footer">
        <div class="social">
            <a href="#"><i class='bx bxl-linkedin'></i></a>
            <a href="#"><i class='bx bxl-github' ></i></a>
            <a href="#"><i class='bx bxl-instagram-alt' ></i></a>
            <a href="#"><i class='bx bxl-twitter'></i></a>        
        </div>

        <ul class="list">
            <li>
                <a href="#">FAQ</a>
            </li>

            <li>
                <a href="#">Services</a>
            </li>

            <li>
                <a href="#">About Me</a>
            </li>

            <li>
                <a href="#">Contact</a>
            </li>
        </ul>
        <p class="copyright">Olowookere Daniel | All Rights Reserved</p>
    </footer>
    <script src="script.js"></script>
    </body>
    </html>
    

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    border: none;
    outline: none;
    scroll-behavior: smooth;
    font-family: "Poppins", sans-serif;
}
:root {
    background-color: #080808;
    --second-background-color: #080808;
    text-decoration-color: white;
    background: #080808;
}
html {
    font-size: 62.5%;
    overflow-x: hidden;
}
body {
    background: var(background-color);
    color: var(text-decoration-color);
}
.header{
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 3rem 9%;
    background:  rgba(0, 0, 0, 0.6);
    backdrop-filter: blur(10px);
    display: flex;
    align-items: center;
    justify-content: space-between;
    z-index: 100;
}
.logo{
    font-size: 3rem;
    color: greenyellow;
    font-weight: 800;
    cursor: pointer;
    transition: 0.3s ease-in-out;
    color: greenyellow;
}
.logo:hover{
    transform: scale(1.1);
}
.logo span{
    text-shadow: 0 0 25px greenyellow;
}
.navbar a{
    font-size: 1.8rem;
    color: var(text-decoration-color);
    margin-left: 4rem;
    font-weight: 500;
    transition: 0.3s ease;
    border-bottom: 3px solid transparent;
    color: #fff;
}
.navbar a:hover,
.navbar a.active{
    color: var(-moz-text-declaration-color);
    border-bottom: 3px solid greenyellow;
}
.header a i{
    padding: 10px;
    color: #fff;
    font-size: 10px;
    margin-left: 10%;
}
section{
    min-height: 100vh;
    padding: 10rem 9% 10rem;
}
.home{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 15rem;
}
.home-content{
    display: flex;
    flex-direction: column;
    align-items: baseline;
    text-align: left;
    justify-content: center;
    margin-top: 3rem;
}
span{
    color:greenyellow;
}
.logo span{
    color:#fff
}
.home-content h3{
    margin-bottom: 2rem;
    margin-top: 1rem;
    font-size: 3.5rem;
    color: #fff;
}
.home-content h1{
    font-size: 7rem;
    font-weight: 700;
    margin-top: 1.5rem;
    line-height: 1;
    color: #fff;
}
.home-img {
    border-radius: 50%;
}
.home-img img{
    position: relative;
    top: 3rem;
    width: 34vw;
    border-radius: 50%;
    box-shadow: 0 0 25px ;
    cursor: pointer;
    transition: 0.4s ease-in-out;
}
.home-img img:hover{
    box-shadow: 0 0 25px greenyellow,
                0 0 50px greenyellow,
                0 0 100px greenyellow;
}
.home-content p{
    font-size: 1.5rem;
    font-weight: 500;
    max-width: 1000px;
    color: #fff;
}
.social-icons a{
    padding: 10px;
    display: inline-flex;
    justify-content: center;
    width: 4.5rem;
    height: 4.5rem;
    background: transparent;
    border: 0.2rem solid greenyellow;
    font-size: 2.5rem;
    border-radius: 1rem;
    color:greenyellow;
    margin: 3rem 1.5rem 3rem 0;
    transition: 0.3s ease-in-out;
}
.social-icons a:hover{
    color: var(#fff);
    transform: scale(1.3) translateY(-5px);
    box-shadow: 0 0 25px black;
    background-color: black;
}
.btn{
    display: inline-block;
    padding: 1rem 2.8rem;
    background: greenyellow;
    box-shadow: 0 0 14px greenyellow;
    border-radius: 4rem;
    font-size: 1.6rem;
    color:black;
    border: 2px solid transparent;
    letter-spacing: 0.1rem;
    font-weight: 600;
    transition: 0.3s ease-in-out;
    cursor: pointer;
}
.btn:hover{
    transform: scale(1.05);
    box-shadow: 0 0 50px greenyellow;
}
.text-animation{
    font-size: 34px;
    font-weight: 600;
    min-width: 280px;
}
.text-animation span{
    position: relative;
}
.text-animation span::before{
    content: "UI/UX DESIGNER";
    color: greenyellow;
    animation: words 20s infinite;
}
.text-animation span::after{
    content:"";
    background-color: black;
    position: absolute;
    width: calc(100%+8px);
    height: 100%;
    border-left: 3px solid black;
    right: -8px;
    animation: cursor 0.7s infinite, typing 20s steps(14) infinite;
}
@keyframes words {
    0%,
    20%{
        content:"UI Prototyping";
    }
    21%,
    40%{
        content: "Branding and Graphics Development";
    }
    41%,
    60%{
        content:"Design Research";
    }
    61%,
    80%{
        content:"Product Structure and Strategy";
    }
    81%,
    100%{
        content:"Interactivity and Animation";
    }
    }
    @keyframes typing{
        10%,
        15%,
        30%,
        35%,
        50%,
        55%,
        70%,
        90%,
        95%{
            width: 0;
        }
        5%,
        20%,
        40%,
        45%,
        60%,
        65%,
        80%,
        85%{
            width: calc(100%+8px);
        }
    }

.about{
    display:flex;
    justify-content: center;
    align-items: center;
    gap:10rem;
    background: var(--second-background-color);
    color:#fff
}
.about h2 span{
    color: greenyellow;
    text-shadow: 0 0 50px greenyellow;
}
.about-img{
    border-radius: 50%;
}
.about-img img{
    position: relative;
    width: 32vw;
    border-radius: 50;
    box-shadow: 0 0 25px greenyellow;
    top: 1rem;
    cursor: pointer;
    transition: 0.4s ease-in-out;
}
.about-img img:hover{
    box-shadow: 0 0 25px greenyellow,
                0 0 50px greenyellow,
                0 0 100px greenyellow;
}
.heading{
    text-align:center;
    font-size: 8rem;
}
.about-content h2{
    text-align: left;
    line-height: 1.5;
    color: #fff;
}
.about-content h3{
    font-size: 2.6rem;
}
.about-content p{
    font-size: 1.6rem;
    margin: 2rem 0 3rem;
    color: #fff;
}
.about-content .text-animation span::before{
    content: "UI/UX DESIGNER";
    color: rgba(172, 255, 47, 0.795);
    animation: words 20s infinite;
}
.about-content .text-animation span::after{
    content:"";
    background-color: black;
    position: absolute;
    width: calc(100%+8px);
    height: 100%;
    border-left: 3px solid black;
    right: -8px;
    animation: cursor 0.7s infinite, typing 20s steps(14) infinite;
}
::-webkit-scrollbar{
    width: 15px;
}
::-webkit-scrollbar-thumb{
    background-color: rgba(172, 255, 47, 0.651);
}
::-webkit-scrollbar-track{
    background-color: #080808;
    width: 50px;
}
.services{
    background: black;
    color: #fff;
}
.services h2{
    margin-bottom: 1rem;
    color: rgba(172, 255, 47, 0.714);
}
.services-container{
    display: grid;
    grid-template-rows: repeat(2,1fr);
    align-items: center;
    gap: 2.5rem;
    padding: 10px;
    box-sizing: calc(100 +8px);
}
.service-box{
    background-color: rgba(172, 255, 47, 0.712);
    height: 120px;
    border-radius: 3rem;
    border: 5px solid transparent;
    cursor: pointer;
    transition: 0.3s ease-in-out;
    grid-template-rows: repeat(2,1fr);
}
.service-box:hover{
    background: #fff;
    color: black;
    border: 2px solid greenyellow;
    transform: scale(1.03);
}
.service-box .service-info{
    display: flex;
    flex-direction: column;
    text-align: left;
    max-height: 100px;
    justify-content: center;
    align-items: baseline;
    padding: 25px;
    box-sizing: border-box;
}
.service-info h4{
    font-size: 15px;
    font-weight: bold;
    margin-bottom: 0.5rem;
    gap: 2.5rem;
}
.service-info h3{
    font-size:12px;
    font-weight: bold;
    margin-bottom:0.5rem;
    gap:2.5rem;
}
.service-info p{
    font-size: 12px;
    font-weight: bold;
    max-height: 50px;
    margin: auto;
}
.contact{
    background-color: black;
}
.contact h2{
    margin-bottom: 3rem;
    color:rgba(172, 255, 47, 0.533);
}
.contact form{
    max-width: 70rem;
    margin: 1rem auto;
    text-align: center;
    margin-bottom: 3rem;
}
.contact form .input-box{
    display:flex;
    justify-content: center;
    flex-wrap: wrap;
}
.contact form .input-box input,
.contact form textarea{
    width: 100%;
    padding:1.5rem;
    font-size: 1.6rem;
    color:#fff;
    background-color: #080808;
    border-radius: 0.8rem;
    border: 2px solid greenyellow;
    margin: 1rem 0;
    resize: none;
}
.contact form .btn{
    margin-top: 2rem;
}
.footer{
    position: relative;
    bottom: 0;
    width: 100%;
    padding: 40px 0;
    background-color: greenyellow;
}
.footer .social{
    text-align: center;
    padding-bottom: 25px;
    color: #080808;
}
.footer .social a{
    font-size: 25px;
    color:#080808;
    border: 2px solid #080808;
    width: 42px;
    height: 42px;
    line-height: 42px;
    display:inline-block;
    text-align: center;
    border-radius: 50%;
    margin: 0 10px;
    transition: 0.3s ease-in-out;
}
.footer .social a:hover{
    transform:scale(1.2) translateY(-10px);
    background-color: #080808;
    color:greenyellow;
}
.footer ul{
    margin-top: 0;
    padding: 0;
    font-size: 18px;
    line-height: 1.6;
    margin-bottom: 0;
    text-align: center;
}
.footer ul li a{
    color:black;
   border-bottom: 3px solid transparent;
    transition: 0.3s ease-in-out;
}
.footer ul li a:hover{
    border-bottom: 3px solid #080808;
}
.footer ul li{
    display:inline-block;
    padding: 0 15px;
}
.footer .copyright{
    margin-top: 50px;
    text-align: center;
    font-size: 16px;
    color: #080808;
}


@media(max-width:1285px){
    html{
        font-size: 55%;
    }
    .services-container{
        padding-bottom: 7rem;
        grid-template-columns: repeat(1,1fr);
        margin: 0.5rem;
    }
}

@media(max-width:991px){
    header{
        padding: 2rem 3%;
    }
    section{
        padding: 10rem 3% 2rem;
    }
    .services{
        padding-bottom: 7rem;
    }
    .footer{
        padding: 2rem 3%;
    }
}
@media(max-width:895px){
    #menu-icon{
        display: block;
    }
    .navbar{
        position: absolute;
        top:100%;
        right: 0;
        width: 50%;
        padding: 1rem 3%;
        background: rgb(0, 0, 0, 0.9);
        backdrop-filter: blur(20px);
        border-bottom-left-radius: 2rem;
        border-left: 2px solid greenyellow;
        border-bottom: 2px solid greenyellow;
        display:none;
    }
    .navbar.active{
        display:block;
    }
    .navbar a{
        display: block;
        font-size: 2rem;
        margin: 3rem 0;
        color: #fff;
    }
    .home{
        flex-direction: column;
        margin: 5rem 4rem;
    }
    .home-content h3{
        font-size: 2.6rem;
    }
    .home-content h1{
        font-size: 8rem;
        margin-top: 0 auto;
    }
    .home-img img{
        width: 56vw;
        margin-top: -2rem;
    }
    .about img{
        margin-top: 1rem;
        margin-bottom: 3rem;
    }
    .services h2{
        margin-bottom: 3rem;
    }
    .services-container{
        grid-template-columns: repeat(1,1fr);
    }

}

let menuicon = document.querySelector('#menu-icon');
let navbar = document.querySelector('.navbar');
let sections = document.querySelectorAll('section');
let navlinks = document.querySelectorAll('header nav a');

window.onscroll = () => {
    sections.forEach(sec => {
        let top = window.scrollY
        let offset = sec.offsetTop - 150;
        let height = sec.offset;
        let id = sec.getAttribute('id');
})}

if(top >= offset && top < offset + height){
    navlinks.forEach(links => {
        links.classList.remove('active');
        document.querySelector('header nav a [href*=' + ']').classList.add ('active');
})}

menuicon.onclick = () =>{
    menuicon.classList.toggle('bx-x');
    navbar.classList.toggle('active');
}
