# Front-end Style Guide
<!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
  </style>
## Layout
 <input type="checkbox" id="check">
    <label for="check" class="checkbtn">
      <img src="/images/icon-hamburger.svg" alt="">
    </label>
    <div class="logo-head">
      <img src="/images/logo.svg" alt="">
    </div>
    <div class="nav-item">
      <nav>
        <a class="a-w" href="#">HOW WE WORK</a>
        <a class="a-w" href="#">BLOG</a>
        <a class="a-w" href="#">ACCOUNT</a>
        <a class="a-v" href="#">VIEW PLANS</a>
      </nav>
    </div>
The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Dark Violet: hsl(256, 26%, 20%)
- Grayish Blue: hsl(216, 30%, 68%)

### Neutral

- Very Dark Violet: hsl(270, 9%, 17%)
- Dark Grayish Violet: hsl(273, 4%, 51%)
- Very Light Gray: hsl(0, 0%, 98%)

## Typography

### Body Copy

- Font size: 16px

### Headings

- Family: [DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display)
- Weights: 400

### Body

- Family: [Karla](https://fonts.google.com/specimen/Karla)
- Weights: 400, 700

## Icons
@media (max-width: 950px) {
    label.logo{
        font-size: 15px;
        padding-left: 30px;
    }
    nav ul li a{
        font-size: 20px;
    }
}
@media (max-width: 800px) {
    .checkbtn {
        display: block;
    }
    ul {
        position: fixed;
        width: 100%;
        height: 100vh;
        background-color: grey;
        top: 80px;
        left: 1000px;
        text-align: center;
        transition: all .5s;
    }
    nav ul li {
        display: block;
        margin: 50px 0;
        line-height: 30px;
    }
    nav ul li a {
        font-size: 20px;
    }
    a:hover,a.active {
        background-color: none;
        color: #000;
    }
    #check:checked ~ ul{
        left: 0;
    }
}

@media (max-width: 700px) {
    * {
        box-sizing: border-box;
        padding: 0;
        margin: 0 2.5%;
        text-decoration: none;
        list-style: none;
    }
    h1 {
        width: 100%;
        font-size: 2rem;
        padding: 0 40px;
        line-height: 1;
        color: #fff;
    }
    .dif-text{
        padding-top: 40px;
        font-size: 3.5rem;
        line-height: 1;
        color: #000;
    }
    h2 {
        font-size: 3rem;
        width: 58%;
        color: #fff;
    }
    h3 {
        padding-top: 20px;
        font-size: 1.5rem;
    }
    h5 {
        color: grey;
        padding: 20px 0;
    }
    .p-text {
        padding: 10px 0 0;
        width: 100%;
        font-size: 1rem;
        color: #fff;
    }
    p {
        padding-top: 20px;
        font-size: 1rem;
        width: 100%;
        word-spacing: 1px;
        color: grey;
    }
    hr {
        margin-top: 20px;
        margin-bottom: 5px;
    }
    nav {
        background-color: #fff;
        height: 50px;
        width: 100%;
        padding: 0 20px;
    }
    label.logo {
        line-height: 70px;
        padding: 0; 
        margin: 0;
    }
    .container {
        padding: 0 2%;
    }
    .image0 {
        display: block;
        width: 100%;
        height: 100%;
        text-align: center;
        margin: 0;
    }
    .grey {
        display: none;
    }
    .section1 {
        background: hsl(256, 26%, 20%);
        height: auto;
        display: block;
        width: 100%;
        padding: 50px 20px 18px;
        text-align: center;
    }
    .section1 .human .btn1 {
        color: #fff;
        padding: 8px 20px;
        margin: 15px 0;
        background-color: transparent;
        border: 1px #fff solid;
        border-radius: 5px;
        cursor: pointer;
    }
    .backlined1, .backlined2 {
        display: none;
    }
    .backlinem1 {
        transform: rotate(25deg);
        position: absolute;
        top: 120px;
        right: 0;
        z-index: 0;
    }
    .backlinem2 {
        position: absolute;
        top: 0;
    }
    .section1 .image1 {
        display: none;
    }
    .seA {
        position: none;
    }
    
    .backline1, .backline2, .backline3 .grey {
        display: none;
    }
}
You can use either use the social icons provided or load in a font icon library. Some library suggestions can be found below:

- [Font Awesome](https://fontawesome.com)
- [IcoMoon](https://icomoon.io)
- [Ionicons](https://ionicons.com)
 View plans

  We’re different

  Snappy Process

  Our application process can be completed in minutes, not hours. Don’t get 
  stuck filling in tedious forms.

  Affordable Prices

  We don’t want you worrying about high monthly costs. Our prices may be low, 
  but we still offer the best coverage possible.

  People First

  Our plans aren’t full of conditions and clauses to prevent payouts. We make 
  sure you’re covered when you need it.

  Find out more about how we work

  How we work

  

  Help me

  FAQ
  Terms of use
  Privacy policy
  Cookies

  Contact

  Sales
  Support
  Live chat

  Others

  Careers
  Press
  Licenses

  
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="#">Your Name Here</a>.
  </div>