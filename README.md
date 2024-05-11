<!DOCTYPE html>
<html lang="en">
<!-- 

DIVYA KAURANI
Reference by Vinod Jangid
What are you doing here?! you sneaky developer...
-->

<head>


  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="robots" content="index, follow" />
  <meta name="theme-color" content="#000" />
 






  <!-- <meta name="twitter:image:src" content="https://i.ibb.co/5Kq2bqF/Preview-Card.png" />
  <meta name="twitter:site" content="@Portfolio" />
  <meta name="twitter:card" content="summary" />
  <meta name="twitter:title" content="Divya Kaurani | Portfolio" />
  <meta name="twitter:description"
  content="
  Absolutely, let's craft a compelling "About Me" section for your portfolio:
  
  Hey there! I'm Divya Kaurani, a passionate MERN developer with a flair for graphic design. I thrive on bringing ideas to life through captivating designs and seamless user experiences. With over 5 projects under my belt in frontend development, I've honed my skills in crafting intuitive interfaces that leave a lasting impression.
  
  Graphic design isn't just my job; it's my creative playground. From conceptualization to execution, I pour my heart into every pixel, ensuring each design tells a story that resonates with its audience.
  
  While my journey in backend development is relatively new, my enthusiasm and dedication are unwavering. I'm constantly pushing myself to learn and grow, eager to expand my skill set and tackle new challenges head-on.
  
  Whether it's coding elegant solutions or crafting visually stunning designs, I'm driven by a relentless passion for creating and innovating. Let's collaborate and bring your ideas to life!
  
  ." /> -->
  <title>Divya Kaurani | Portfolio</title>

  <meta name="description"
  content="Divya Kaurani | Portfolio, Visit and know about me & my projects/designs. I value simple content structure, clean design patterns, and thoughtful interactions." />
<meta name="keywords"
  content="Divya Kaurani,Divya Kaurani portfolio,Divya Kaurani Portfolio,divyakaurani,Divya Kaurani site,Divya Kaurani Site,Divya Kaurani me,Divya Kaurani web,Divya Kaurani github,divyakaurani site,divyakaurani uiverse,uiverse,Divya Kaurani uiverse,Divya Kaurani frontend developer,frontend developer,Divya Kaurani jaipur,Divya jaipur" />
  <meta property="og:url" content="https://divya-kaurani.vercel.app/" />
  <meta property="og:title" content="Divya Kaurani | Portfolio" />
  <meta property="og:description"
  content="Hi! My name is Divya. I'm a Mern Stack developer experienced over 8+ projects. Visit and know about me & my projects/designs. I value simple content structure, clean design patterns, and thoughtful interactions." />
  <meta property="og:type" content="website">
  <meta property="og:image" content="https://i.ibb.co/5Kq2bqF/Preview-Card.png" />
<meta name="author" content="Divya Kaurani" />
  <link rel="icon" type="image/x-icon" href="src/png/main-favicon.ico" />
  <!-- aos cdn -->
  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
  <!-- stylesheet -->
  <link rel="stylesheet" href="style.css" />
  <!-- google fonts-->
  <link rel="stylesheet"
    href="https://fonts.googleapis.com/css2?family=Passions+Conflict&family=Orbitron&family=Fira+Code&family=Six+Caps" />
<style>
  /* 
██╗░░░██╗██╗███╗░░██╗░█████╗░██████╗░
██║░░░██║██║████╗░██║██╔══██╗██╔══██╗
╚██╗░██╔╝██║██╔██╗██║██║░░██║██║░░██║
░╚████╔╝░██║██║╚████║██║░░██║██║░░██║
░░╚██╔╝░░██║██║░╚███║╚█████╔╝██████╔╝
░░░╚═╝░░░╚═╝╚═╝░░╚══╝░╚════╝░╚═════╝░
░░░░░██╗░█████╗░███╗░░██╗░██████╗░██╗██████╗░
░░░░░██║██╔══██╗████╗░██║██╔════╝░██║██╔══██╗
░░░░░██║███████║██╔██╗██║██║░░██╗░██║██║░░██║
██╗░░██║██╔══██║██║╚████║██║░░╚██╗██║██║░░██║
╚█████╔╝██║░░██║██║░╚███║╚██████╔╝██║██████╔╝
░╚════╝░╚═╝░░╚═╝╚═╝░░╚══╝░╚═════╝░╚═╝╚═════╝░ */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

*::selection {
    background-color: transparent;
}

*::-moz-selection {
    background: transparent;
}
 
* {
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;

}

* {
    -webkit-tap-highlight-color: transparent;
}

html {
    font-size: 62.5%;
    scroll-behavior: smooth;
    text-rendering: optimizeLegibility;
    -webkit-font-smoothing: antialiased;

}
:root{
    font-family: Whitney, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif;
    cursor:default;
    --color-white: #fff;
    --color-black: #000;
    --color-dark-mode:#11111b;
    --color-light-mode:#ece7e1;
    --color-ddd-color: #ddd;
    --color-gray: #c4c4c4;
    --color-purple: #8000ff;
    --color-light-purple: #cf59e6;
    --color-light-blue: #6bc5f8;
    --color-navbarBorder-dark:#e2e2e207;
    --color-shadowDark:rgba(0, 0, 0, 0.137);
    --static-heading-gradient-blue: #b0f3f1;
    --static-heading-gradient-pink: #ffcfdf;
    --tech-stack-box-first-color:#1a1a29;
    --tech-stack-box-second-color:rgba(27, 27, 40, 0);
    --tech-stack-box-border-color: #292929;
}
::-webkit-scrollbar{
    width: 5px;
}
::-webkit-scrollbar-track {
    background: #0a0a10;
}
::-webkit-scrollbar-thumb{
   background-color: #8000ff;
   /* border-radius: 20px; */

}
body{
    background-color: var(--color-dark-mode);
    overflow-x: hidden;
    /* cursor: none; */
}


.cursor-inner{
    width: 8px;
    height: 8px;
    background-color: var(--color-light-blue);
}
.cursor-outer{
    width: 35px;
    height: 35px;
    border: 2px solid white;
}
.cursor-inner,
.cursor-outer{
    position: fixed;
    top: 0;
    left: 0;
    transform: translate(-50%, -50%);
    border-radius: 50%;
    z-index: 9999;
    pointer-events: none;
}
.cursor-inner.hover{
    width: 25px;
    height: 25px;
    transition: all .2s;
    mix-blend-mode: difference;
}
.cursor-outer.hover{
    width: 50px;
    height: 50px;
    transition: all .2s;
}


/* for light mode */
.light-mode{
    --color-dark-mode:#ece7e1;
    --color-black: #fff;
    --color-white: #000;
    --color-ddd-color: rgb(31, 31, 31);
    --color-navbarBorder-dark:#d1d6eb;
    --static-heading-gradient-blue: #0f7878;
    --static-heading-gradient-pink: #f09bb9;
    --color-shadowDark:#e2ddd7;
    --tech-stack-box-first-color:#e7e2db;
    --tech-stack-box-second-color:#ece7e100;
    --tech-stack-box-border-color: #dad5cf;
}
.setting-container{
    width: 60px;
    height: 50px;
    margin-left:50px;
    display: flex;
    align-items: center;
    transform-origin: left;
    transition-duration: .5s;
    gap: 30px;
    padding: 20px 0px;
   
}
#labelforsetting{
    width: 40px;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
        padding: 0px 20px;
        background-image: url(src/svg/settings-svgrepo-com.svg);
        background-size: 60%;
        background-repeat: no-repeat;
        background-position: center;
        transition-duration: .5s;
        cursor: pointer;
}
.invertsettinglabel{
    filter: invert(1);
}
.settingactivate{
    transform-origin: left;
    width: 200px;
    transition-duration: .5s;

}
.visualmodetogglebuttoncontainer{
    width: fit-content;
    height: fit-content;
    display: flex;
    align-items: center;
    justify-content: center;
    transform:translate(-50px)scale(0);
    transition-duration: .3s;
}
.visualmodeshow{
    transition-duration: .3s;
    transform: translate(0px)scale(1);
}
#switchforsetting{
    display: none;
}
#switchforsetting:checked+#labelforsetting { 
    transform: rotate(180deg);
    transition-duration: .5s;

}

#labelforvisualmode {
    position: relative;
    width: 40px;
    height: 40px;
    background-image: url(src/png/crescent-moon\ \(1\).png);
    background-size:50%;
    background-repeat: no-repeat;
    background-position: center;
    transition-duration: .5s;
    cursor: pointer;
}

#switchforvisualmode{
    display: none;
}
#switchforvisualmode:checked+#labelforvisualmode { 
    transform: rotate(360deg);
    transition-duration: .5s;
    background-image: url(src/png/sun.png);
    background-size:60%;
    background-repeat: no-repeat;
    background-position: center;

}
/* for sound */
.soundtogglebuttoncontainer{
    width: fit-content;
    height: fit-content;
    display: flex;
    align-items: center;
    justify-content: center;
    transform: translate(-130px)scale(0);
    transition-duration: .3s;
}
.soundmodeshow{
    transition-delay: .1s;
    transition-duration: .5s;
    display: inline-block;
    transform:translate(0px)scale(1);

}
#labelforsound {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 40px;
    height: 40px;
    background-image: url(src/svg/Mute_Icon.svg);
    background-size:60%;
    background-repeat: no-repeat;
    background-position: center;
    cursor: pointer;
    transition-duration: .5s;
}
.invertapplied{
   filter: invert(1);
}
#switchforsound{
    display: none;
}

#switchforsound:checked+#labelforsound { 
    transition-duration: .5s;
    background-image: url(src/svg/Speaker_Icon.svg);
    background-size:50%;
    background-repeat: no-repeat;
    background-position: center ;
   
}
header{
    width: 100%;
    height: 115px;
    display: flex;
    align-items: flex-end;
    justify-content: center;
}
#preloader{
    background-color:white;
    height: 100%;
    width: 100%;
    position: fixed;
    z-index: 99999;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow-y: hidden;
    background-image: url(src/svg/Pulse-0.4s-200px.svg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: 10%;
    filter: invert(1);

}
noscript{
    position: fixed;
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: var(--color-dark-mode);
    font-size: 4rem;
    color: white;
    z-index:999999;
}
.fakenavbar{
    height: 0px;
    width: 0%;
    background-color: transparent;
}
.navbar{
    background-image: linear-gradient(to bottom right,var(--tech-stack-box-first-color), var(--tech-stack-box-second-color));
    /* border: 1px solid var(--tech-stack-box-border-color); */
    backdrop-filter: blur(10px);
    height: 80px;
    width: 80%;
    display: flex;
    align-items: center;
    padding: 0px 20px;
    justify-content: space-between;
    position:fixed;
    z-index: 999;
    border: 1px solid var(--color-navbarBorder-dark);
    
    border-radius: 50px;
    overflow: hidden;
}
.navbar-tabs{
    display: flex;
    height: 100%;
    width: 80%;
    align-items: center;
}
.navbar-tabs-ul{
    height: 100%;
    width: 100%;
    display: flex;
    list-style: none;
    align-items: center;
    justify-content:flex-end;
    gap: 80px;
    color: var(--color-white);
}
.navbar-tabs-ul li{
    width: fit-content;
    height: 30px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.5rem;
    position: relative;
    font-family: fira code;
}

.navbar-tabs-ul li:hover:before{
    content: "";
    background-color: var(--color-white);
    position: absolute;
    height: 10px;
    width: 10px;
    border-radius: 5px;
    left: -20px;
    z-index: -1;
}
.navbar-tabs-ul a{
    text-decoration: none;
    color: var(--color-white);
    font-weight: 100;
}
.logo{
    position: relative;
    width: 10%;
    height: 100%;
    transition-duration: 1s;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    overflow: hidden;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;

}
.hey{
    color: white;
    position: absolute;
    font-size: 2.5rem;
    font-weight: 300;
    background-color: #20222e;
    padding: 5px 10px;
    border-radius: 20px;
    left: 120px;
    bottom: 80px;
    opacity: 0;
}
.popup{
   animation: pop-up 3s linear;
}
@keyframes pop-up {
    from{
        bottom: -50px;
        left: 50px;
        opacity: 1;
    }
    to{
        opacity: 0;
    }
}
.logo-top{
    width: 100%;
    height:100%;
    display: flex;
    align-items: center;
    justify-content: center;
    transform-origin: bottom;
    position: relative;
}

.logo-top img{
    height: 100%;
    z-index: 2;
    /* opacity: 0.2; */
    
}
.face{
    content: "";
    position: absolute;
    width: 100%;
    height: 74%;
    bottom: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 5px;
    z-index: 1;

    padding-left: 1px;
}
.eye{
   width: 8px;
   height: 8px;
   border-radius: 50%;
   display: flex;
   align-items: center;
   justify-content: center;
   background-color: white;
   overflow: hidden;


}
.left-eye{
    box-shadow: -1px -2px 2px rgba(0, 0, 0, 0.589) inset;
}
.right-eye{
    box-shadow: 1px 3px 2px rgba(0, 0, 0, 0.589) inset;
}
.pupil{
    width:3.5px;
    height:3.5px;
    background: rgb(36, 16, 16);
    border-radius: 50%;
}
/* .eye:after { 
    position: absolute;
    width: 4px;
    height: 4px;
    left: .7px;
    top: 0;
    background: #000;
    border-radius: 50%;
    content: " ";
  } */

.logo:hover{
    transform: translateY(200px);
    transition-duration: 1s;
}


.activeThistab{
    color: var(--color-white);
}
.activeThistab:before{
    content: "";
    background-color: var(--color-white);
    position: absolute;
    height: 10px;
    width: 10px;
    left: -20px;
    border-radius: 50%;
    z-index: -1;

}
/* navbar code ends here */

/* landing page code starts from here */
.main{
    width: 100%;
    height: fit-content;
    position: relative;
    overflow-x: hidden;
}

/* blob */
.blob{
    position: absolute;
    right: -15%;
    top: 0;
    background-color: var(--color-light-purple);
    width: 600px;
    height: 100vh;
    border-radius: 50%;
    filter: blur(300px);
    opacity: .3;
    animation: breath 1s linear infinite alternate-reverse;
}
@keyframes breath{
    from{
        opacity: 0.3;
        
    }
    to{
        opacity: 0.5;
    }
}

.landing-page-container{
    width: 100%;
    height: calc(100vh - 115px);
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
}
.text-content{
    display: flex;
    flex-direction: column;
    width: 60%;
    height: 100%;
    align-items: flex-start;
    justify-content: center;
    /* padding-left: 300px; */
}
#hello-friend{
    font-size: 3.5rem;
    font-weight: 600;
    width:fit-content;
    display: flex;
    align-items: flex-end;
    color: var(--color-white);
    font-family: fira code;
}

@-webkit-keyframes vibrate-1 {
    0% {
      -webkit-transform: translate(0);
              transform: translate(0);
    }
    20% {
      -webkit-transform: translate(-2px, 2px);
              transform: translate(-2px, 2px);
    }
    40% {
      -webkit-transform: translate(-2px, -2px);
              transform: translate(-2px, -2px);
    }
    60% {
      -webkit-transform: translate(2px, 2px);
              transform: translate(2px, 2px);
    }
    80% {
      -webkit-transform: translate(2px, -2px);
              transform: translate(2px, -2px);
    }
    100% {
      -webkit-transform: translate(0);
              transform: translate(0);
    }
  }
  @keyframes vibrate-1 {
    0% {
      -webkit-transform: translate(0);
              transform: translate(0);
    }
    20% {
      -webkit-transform: translate(-2px, 2px);
              transform: translate(-2px, 2px);
    }
    40% {
      -webkit-transform: translate(-2px, -2px);
              transform: translate(-2px, -2px);
    }
    60% {
      -webkit-transform: translate(2px, 2px);
              transform: translate(2px, 2px);
    }
    80% {
      -webkit-transform: translate(2px, -2px);
              transform: translate(2px, -2px);
    }
    100% {
      -webkit-transform: translate(0);
              transform: translate(0);
    }
  }
  
  /* #name:hover{
    -webkit-animation: vibrate-1 0.3s linear both;
    animation: vibrate-1 0.3s linear both;
}
   */
#name{
    font-size: 8rem;
    font-weight:700;
    width:fit-content;
    display: flex;
    align-items: flex-start;
    background: -webkit-linear-gradient(135deg,var(--color-light-blue),var(--color-light-purple),var(--color-light-blue),var(--color-light-purple));
    background: linear-gradient(-45deg,var(--color-light-blue),var(--color-light-purple),var(--color-light-blue),var(--color-light-purple));
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-size: 400% 400%;
    -webkit-animation: gradient 3s ease infinite;
    animation: gradient 3s ease infinite;

}
@keyframes gradient {
    0% {
        background-position: 0 50%;
    }
    50% {
        background-position: 100% 50%;
    }
    
    100% {
        background-position: 0 50%;
    }
}

#work{
    font-size: 8rem;
    font-weight:700;
    width:fit-content;
    display: flex;
    align-items: flex-start;
    color: var(--color-white);
    flex-wrap: wrap;
    
}
#work div{
    display: flex;
	margin: 0px 12px 0px 0px;
}
.jello:hover{
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-color:  #03e6ff;
    -webkit-animation: jello-vertical 0.9s both;
	        animation: jello-vertical 0.9s both;
}

 @-webkit-keyframes jello-vertical {
    0% {
      -webkit-transform: scale3d(1, 1, 1);
              transform: scale3d(1, 1, 1);
    }
    30% {
      -webkit-transform: scale3d(0.75, 1.25, 1);
              transform: scale3d(0.75, 1.25, 1);
    }
    40% {
      -webkit-transform: scale3d(1.25, 0.75, 1);
              transform: scale3d(1.25, 0.75, 1);
    }
    50% {
      -webkit-transform: scale3d(0.85, 1.15, 1);
              transform: scale3d(0.85, 1.15, 1);
    }
    65% {
      -webkit-transform: scale3d(1.05, 0.95, 1);
              transform: scale3d(1.05, 0.95, 1);
    }
    75% {
      -webkit-transform: scale3d(0.95, 1.05, 1);
              transform: scale3d(0.95, 1.05, 1);
    }
    100% {
      -webkit-transform: scale3d(1, 1, 1);
              transform: scale3d(1, 1, 1);
    }
  }
  @keyframes jello-vertical {
    0% {
      -webkit-transform: scale3d(1, 1, 1);
              transform: scale3d(1, 1, 1);
    }
    30% {
      -webkit-transform: scale3d(0.75, 1.25, 1);
              transform: scale3d(0.75, 1.25, 1);
    }
    40% {
      -webkit-transform: scale3d(1.25, 0.75, 1);
              transform: scale3d(1.25, 0.75, 1);
    }
    50% {
      -webkit-transform: scale3d(0.85, 1.15, 1);
              transform: scale3d(0.85, 1.15, 1);
    }
    65% {
      -webkit-transform: scale3d(1.05, 0.95, 1);
              transform: scale3d(1.05, 0.95, 1);
    }
    75% {
      -webkit-transform: scale3d(0.95, 1.05, 1);
              transform: scale3d(0.95, 1.05, 1);
    }
    100% {
      -webkit-transform: scale3d(1, 1, 1);
              transform: scale3d(1, 1, 1);
    }
  }
  
#info-para{
    width: 75%;
    font-size: 2rem;
    font-weight: 400;
    padding-top: 30px;
    color: var(--color-ddd-color);
    line-height: 20px;
}
.contact-btn-div{
    width: 100%;
    padding-top: 50px;
    height: fit-content;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}
.letsTalkBtn {
    position: relative;
    background-color: transparent;
    border: none;
    width: 180px;
    height: 40px;
    border-radius: 0px;
    cursor: pointer;
    transition: all .3s;

  }
  
  .letsTalkBtn-text {
    width: 100%;
    height: 100%;
    background-color: rgba(230, 230, 230, 0.466);
    border: none;
    border-radius: 7px;
    backdrop-filter: blur(5px);
    color: rgb(0, 0, 0);
    display: flex;
    align-items: center;
    justify-content: center;
    letter-spacing: 0.8px;
    font-weight: 700;
  }
  
  .letsTalkBtn-BG {
    position: absolute;
    width: 100%;
    height: 100%;
    background-image: linear-gradient(150deg, #71cbff, #8000ff);
    z-index: -1;
    left: 6px;
    top: 6px;
    border-radius: 7px;
    pointer-events: none;
    transition: all .3s;
  }
  
  .letsTalkBtn:hover {
    transform: translateY(-2px) translateX(-2px);
  }
  
  .letsTalkBtn:hover .letsTalkBtn-BG {
    transform: translateY(2px) translateX(2px);
  }
  
  .letsTalkBtn:active {
    transform: translateY(7px) translateX(7px);
  }
  
  .letsTalkBtn:active .letsTalkBtn-BG {
    transform: translateY(-7px) translateX(-7px);
  }
.resume-btn {
    margin-top: 25px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    width: 45px;
    height: 45px;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    overflow: hidden;
    transition-duration: .3s;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.199);
    background: linear-gradient(
    82.3deg,
    rgba(150, 93, 233, 1) 10.8%,
    rgba(99, 88, 238, 1) 94.3%
  );
  position: relative;
  }
  
  /* plus sign */
  .sign {
    width: 100%;
    transition-duration: .3s;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .sign svg {
    width: 17px;
  }
  
  .sign svg path {
    fill: white;
  }
  /* text */
  .text {
    position: absolute;
    right: 0%;
    width: 0%;
    opacity: 0;
    color: white;
    font-size: 1em;
    font-weight: 600;
    transition-duration: .3s;
  }
  /* hover effect on button width */
  .resume-btn:hover {
    width: 130px;
    border-radius: 40px;
    transition-duration: .3s;
  }
  
  .resume-btn:hover .sign {
    width: 30%;
    transition-duration: .3s;
    padding-left: 20px;
  }
  /* hover effect button's text */
  .resume-btn:hover .text {
    opacity: 1;
    width: 70%;
    transition-duration: .3s;
    padding-right: 10px;
  }
  /* button click effect*/
  .resume-btn:active {
    transform: translate(2px ,2px);
  }
/* landing page code ends here */

/* about section starts from here */
.about-section-container{
    width: 100%;
    height:fit-content;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding-top: 200px;

}
.about-section{
    width: 60%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.section-heading{
    width: 100%;
    display: flex;
    align-items: center;
    gap: 10px;
}
.section-heading-article{
    font-size:3rem;
    font-family: fira code;
    font-weight: 500;
    background-image: -webkit-gradient(linear,left top,right top,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: -webkit-linear-gradient(left,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: linear-gradient(90deg,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
.sectionHeadingP{
    width: 300px;
    height: 1px;
    background-image: -webkit-gradient(linear,left top,right top,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: -webkit-linear-gradient(left,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: linear-gradient(90deg,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
}

.info-dp-section{
    width: 100%;
    display: flex;
    margin-top: 30px;
    
}
.about-info{
    width: 60%;
    display: flex;
    flex-direction: column;
}
.about-info p{
    font-size: 2rem;
    font-weight: 400;
    line-height: 25px;
    color: var(--color-white);
}
.dp{
    width: 40%;
    display: flex;
    align-items: flex-start;
    justify-content:center;
    position: relative;
    transition-duration: .5s;
}
.dp img{
    width: 300px;
}
.dp::before{
    content: "";
    background-color: transparent;
    height: 300px;
    width: 300px;
    position: absolute;
    z-index: -2;
    box-shadow: 2px 2px 0px inset #8000ff,
                -2px -2px 0px inset transparent;
                transition-duration: .5s;

}
.dp::after{
    content: "";
    background-color: transparent;
    height: 300px;
    width: 300px;
    position: absolute;
    z-index: -2;
    box-shadow: 2px 2px 0px inset transparent,
                -2px -2px 0px inset #8000ff;
                transition-duration: .5s;

}
/* hover effect on dp */
.dp:hover::after{
    transform: translate(20px,20px);
    transition-duration: .5s;
}
.dp:hover::before{
    transform: translate(-20px,-20px);
    transition-duration: .5s;
}
/* about section ends
 */
 /* skills section starts */
.skills-section-container{
    padding-top: 150px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
}
.skills-section{
    width: 60%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.skills-heading{
    width: 100%;
    display: flex;
    align-items: center;
    gap: 10px;
}
.skills-heading-article{
    font-size:3rem;
    font-family: fira code;
    font-weight: 500;
    background-image: -webkit-gradient(linear,left top,right top,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: -webkit-linear-gradient(left,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: linear-gradient(90deg,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
.skillsHeadingP{
    width: 300px;
    height: 1px;
    background-image: -webkit-gradient(linear,left top,right top,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: -webkit-linear-gradient(left,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: linear-gradient(90deg,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));

}

.language-speak{
    width: 100%;
    display: flex;
    align-items: center;
    height: 50px;
    justify-content: center;
}
.language-speak article{
    font-size: 2rem;
    font-weight: 600;
    font-family: fira code;
    color: var(--color-white);
}
.frontend-dev-section{
    width: 100%;
    margin-top: 50px;
}
.frontend-dev-heading{
    width: 100%;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 3rem;
    font-weight: 900;
    height: 100px;
    letter-spacing: 5px;
    background-image: -webkit-gradient(linear,left top,right top,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: -webkit-linear-gradient(left,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: linear-gradient(90deg,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
.tech-stack-wrapper{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    gap:50px;
    margin-top: 50px;

}
.tech-stack-box{
    width: 160px;
    height: 160px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 30px;
    background-image: linear-gradient(to bottom right,var(--tech-stack-box-first-color), var(--tech-stack-box-second-color));
    border: 1px solid var(--tech-stack-box-border-color);
    /* box-shadow: 0px 10px 20px var(--color-shadowDark); */
    position: relative;
}
.tech-stack-box img{
    width: 80%;
}
.tech-stack-box:hover .tooltip {
    opacity: 1;
    transition-duration: .3s;
  }
.tooltip {
    position: absolute;
    top: -20px;
    opacity: 0;
    background: linear-gradient(to bottom right,var(--tech-stack-box-first-color), var(--tech-stack-box-second-color));
    border: 1px solid var(--tech-stack-box-border-color);
    color: white;
    padding: 5px 10px;
    border-radius: 5px;
    display: flex;
    align-items: center;
    justify-content: center;
    transition-duration: .2s;
    pointer-events: none;
    letter-spacing: 0.5px;
    font-size: 1.6rem;
    backdrop-filter: blur(5px);
    font-weight: 500;
  }
  


/* skills section ends */
/* ######################################################## */
/* projects section starts */
.projects-section-container{
    padding: 150px 0;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
}
.projects-section-div{
    width: 60%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.projects-heading{
    width: 100%;
    display: flex;
    align-items: center;
    gap: 10px;
}
.projects-heading-article{
    font-size:3rem;
    font-family: fira code;
    font-weight: 500;
    background-image: -webkit-gradient(linear,left top,right top,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: -webkit-linear-gradient(left,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: linear-gradient(90deg,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
.projectsHeadingP{
    width: 300px;
    height: 1px;
    background-image: -webkit-gradient(linear,left top,right top,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: -webkit-linear-gradient(left,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
    background-image: linear-gradient(90deg,var(--static-heading-gradient-blue),var(--static-heading-gradient-pink));
}
.project-boxes-div{
    width: 100%;
    height: fit-content;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 50px;
    padding: 50px;
}
.project-box-wrapper{
    width: 100%;
}
.project-box{
    /* background-color: rgba(255, 255, 255, 0.005); */
    background-image: linear-gradient(to bottom right, var(--tech-stack-box-first-color),var(--tech-stack-box-second-color));
    width: 100%;
    height: 400px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    transition-duration: .3s;
    position: relative;
    /* box-shadow: 0px 10px 20px var(--color-shadowDark); */
    border-radius: 30px;
    border: 1px solid var(--tech-stack-box-border-color);
    overflow: hidden;
}

.info-div{
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    gap: 20px;
    padding: 0 40px;
}
.faviconforProject{
    width: 30px;
    border-radius: 50%;
}
.faviconforProjectAquaregia{
    width: 20px;
}
.image-div{
    width: 50%;
    height: 100%;
    overflow: hidden;
    padding-top: 70px;
    padding-left: 10px;
   
}
.image-div img{
    height: 100%;
    border-top-left-radius:30px;
}
.ProjectHeading{
    color: var(--color-white);
    font-size: 3.4rem;
    font-weight: 700;
}
.ProjectDescription{
    color: gray;
    font-size: 1.7rem;
    font-weight: 400;
}
/* Project visit button */
.project-buttons{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    gap: 20px;
}
.github-redirect{
 text-decoration: none;    
 width: 50px;
}
.github-redirect img{
    width: 45px;
    height: auto;
    transition: all .3s;
    filter: brightness(2);
}
.github-redirect:hover img{
    filter: brightness(4);
}
.cta {
    position: relative;
    padding: 12px 18px;
    transition: all 0.2s ease;
    border: none;
    background: none;
    cursor: pointer;
    text-decoration: none;
    display: flex;
    align-items: center;
    justify-content: flex-start;
   }
   
   .cta::before {
    content: "";
    position: absolute;
    left: 0;
    display: block;
    border-radius: 50px;
    background: #2b2f4e;
    /* background-color: var(--color-navbarBorder-dark); */
    width: 45px;
    height: 45px;
    transition: all 0.3s ease;
   }
   
   .cta span {
    position: relative;
    /* font-family: "Ubuntu", sans-serif; */
    font-size: 1.8rem;
    font-weight: 600;
    letter-spacing: 0.05em;
    /* color: #234567; */
    color: var(--color-light-blue);
   }
   
   .cta svg {
    position: relative;
    top: 0;
    margin-left: 10px;
    fill: none;
    stroke-linecap: round;
    stroke-linejoin: round;
    /* stroke: #234567; */
    stroke: var(--color-light-blue);
    stroke-width: 2;
    transform: translateX(-5px);
    transition: all 0.3s ease;
   }

   .cta:hover:before {
    width: 100%;
    /* background: #b1dae7; */
   }
   .cta:hover span{
    color:white;
   }
   .cta:hover svg{
    stroke:white;
   }
   
   .cta:hover svg {
    transform: translateX(0);
   }
   
   .cta:active {
    transform: scale(0.95);
   }
/* Project visit button */

/* projects ends */



#backtotopbutton{
    
    position: fixed;
    right: 10px;
    bottom: 0px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    border: none; 
    width:3rem;
    height:15rem;
    z-index: 101;
    text-align: center;
    transition: all .4s;
    background-color: transparent;
    display: none;
}
#backtotopbutton article{

    font-size: 1.5rem;
    color: var(--color-white);
    font-weight: 400;
    /* width: 200px; */
    /* transform: rotate(90deg); */
     
    writing-mode:vertical-rl;
     font-family: Whitney, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif;
     mix-blend-mode: difference;
}


#backtotopbutton:hover{
    transform: translate(0px,-20px);
    text-decoration: line-through var(--color-white);
}
/* footer starts */
footer{
    width: 100%;
    position: relative;
    height: fit-content;
    border-top: 1px solid var(--tech-stack-box-border-color);
    /* border-top-left-radius: 50px;
    border-top-right-radius: 50px; */
    overflow: hidden;
}
.footer-background{

    width: 100%;
    height: 100vh;
    background-color: #0b0b0b;
    display: flex;
    align-items: flex-end;
    justify-content: center;
    z-index: 1;
}
.footer-blob{
    width: 100%;
    height: 200px;
    background-color: var(--color-light-purple);
    border-radius: 50%;
    filter: blur(100px);
    opacity: 0.7;
}
.footer-foreground{
    position: absolute;
    top: 0;
    width:100%;
    height: 100vh;
    display: flex;
    align-items: flex-end;
    justify-content: center;
    backdrop-filter: blur(10px);
}

.footercontainer{
   width: 100%;

   display: flex;
   flex-direction: column;
   align-items: center;
   justify-content: flex-end;
}
.two-words{
   color: rgb(179, 179, 179);
   width: 100%;
   display: flex;
   align-items: center;
   justify-content: center;
   height: 100px;
}
.two-words article{
   font-size: 3rem;
   font-family: fira code;
}
.social-media-container{
   display: flex;
   flex-direction: column;
   align-items: center;
   justify-content: center;
   width: 100%;
   
}
.social-media-container a{
   width: 60px;
   height: 60px;
   display: flex;
   align-items: center;
   justify-content: center;
   text-decoration: none;
   padding: 10px;
   border-radius: 50%;
   border: 2px solid rgb(226, 222, 222);
   transition-duration: .3s;
       position: relative;
       box-shadow: 0px 0px 0px #8000ff inset;
       transition-duration: .3s;
}
.getintouch-heading{
   width: 100%;
   height: 80px;
   display: flex;
   align-items: center;
   justify-content: center;
   
}
.getintouch-heading article{
   font-size: 2rem;
   background: -webkit-linear-gradient(135deg,var(--color-light-blue),var(--color-light-purple),var(--color-light-blue),var(--color-light-purple));
   background: linear-gradient(-45deg,var(--color-light-blue),var(--color-light-purple),var(--color-light-blue),var(--color-light-purple));
   background-clip: text;
   -webkit-background-clip: text;
   -webkit-text-fill-color: transparent;
   font-weight: 700;
   font-family: fira code;
}
.logos{
   display: flex;
   width: 100%;
   gap: 30px;
   justify-content: center;
   align-items: center;
   height: 80px;
}
.SocialHandle{
   fill: white;
   width: 60%;
}
#GmailLogo{
   height: 70%;
   fill: white;
}
.social-media-container a:hover{
   box-shadow: 0px 0px 50px 100px #8000ff inset;
   transition-duration: 1s;
   border: none;
}
.social-media-container a::before{
   position: absolute;
   content: "";
   width: 100%;
   height: 100%;
   left: 0;
   border-radius: 50%;
   transform: scale(0);
   background-color: #8000ff;
   background-color: transparent;
   transition-duration: .3s;
   z-index: -1;
}
.social-media-container a:hover::before{
   transform: scale(1);
   transition-duration: .3s;
}
.footer-avatar-container{
    width: 220px;
    /* background-color: red; */
    margin-top: 20px;
    position: relative;
    display: flex;
    align-items: flex-end;
    justify-content: center;
}

.footer-avatar-img{
    width: 100%;
    z-index:2;
    /* opacity: .2; */
}
.footer-avatar-face{
    position: absolute;
    width: 100%;
    height: 97%;
    z-index: 1;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 18px;
    padding-left: 5px;
}
.footer-avatar-eye{
    width: 50px;
    height: 50px;
    background-color: rgb(223, 210, 210);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    
}
.footer-pupil{
    width: 20px;
    height: 20px;
    background-color: black;
    border-radius: 50%;
    border: 5px solid rgb(65, 51, 51);
    filter: blur(0.6px);
}

.footer-right-eye{
    box-shadow: 15px 15px 5px rgba(0, 0, 0, 0.233) inset,
    10px 10px 5px rgba(41, 33, 33, 0.644) inset;
    position: relative;
}
.footer-left-eye{
    box-shadow: -10px -15px 5px rgba(0, 0, 0, 0.349) inset;
    position: relative;

}
.footer-avatar-eye::before{
    position: absolute;
    content: "";
    width: 2px;
    height: 5px;
    border-radius: 50%;
    background-color: rgba(214, 214, 214, 0.726);
    z-index: 2;
    filter: blur(.2px);
    left: 15px;
    transform: rotate(45deg);
}
.footer-bottom{
    background-color: #0b0b0b;
   width: 100%;
   display: flex;
   align-items: center;
   justify-content: center;
   height: 80px;
   z-index: 3;
}
.footer-bottom article{
   color: rgb(176, 176, 176);
   font-size: 1.5rem;
   font-family: fira code;
}
.fa-copyright{
   font-size: 1.5rem;
   color: rgb(176, 176, 176);
}
/* footer enda */
.mobiletogglemenu{
    display: none;
}
.hamburger{
    display: none;
}
.tonechange{
    color: black;
}

/* responsive code below*/
@media screen and (max-width:1920px) {
    html {
        font-size: 60%;
    }
  }
  @media screen and (max-width:1400px) {
    html {
        font-size: 60%;
    }
   
  }
  @media screen and (max-width:1300px) {
   
  }

  @media screen and (max-width:1200px) {
    html {
        font-size: 60%;
    }
    .text-content{
        width: 80%;
    }
    .about-section{
        width: 80%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    .logo:hover{
        transform: translateY(200px);
        transition-duration: 1s;
    }
    .skills-section{
        width: 80%;
    }
    .projects-section-div{
        width: 80%;
    }
    
  }
  @media screen and (max-width:1150px) {
    html {
        font-size: 60%;
    }
   
    
  }
  @media screen and (max-width:998px) {
    html {
        font-size: 55%;
    }
    .blob{
        display: none;
    }
    .cursor-inner,
    .cursor-outer{
        display: none;
    }
    .navbar-tabs-ul{
    display: none;
    }
    .stopscrolling{
        overflow: hidden;
    }
  .hamburger{
    /* display: block; */
    position: fixed;
    top: 0px;
    /* right: 0; */
    width: 100vw;
    height: 115px;
    display: flex;
    align-items: flex-end;
    justify-content: center;
    z-index: 9998;
    background-color:transparent;

}
.hamburgerbase{
    width: 80%;
    height: 80px;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    padding: 20px;
}
#hamburger-button{
    font-size: 3rem;
    font-weight: 800;
    width: 4.5rem;
    height: 3.5rem;
    background-color: transparent;
    border: none;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
}
#burger-bar1{
    width: 60%;
    height:3px;
    border-radius: 0px;
    transition-duration: .3s;
}
#burger-bar2{
    width: 100%;
    height:3px;
    border-radius: 0px;
    transition-duration: .3s;

}
#burger-bar3
{
    width: 60%;
    height:3px;
    border-radius: 0px;
    transition-duration: .3s;

}
.burger-bar{
    background-color: var(--color-white);
}

.hamburger-animation1{
    transform: rotate(45deg) scaleX(1.7);
    transition-duration: .3s;
    transform-origin: left;
    background-color: var(--color-white);

} 
.hamburger-animation2{
   transform: scaleX(0);
    background-color: var(--color-white);

    
}
.hamburger-animation3{
    transform: rotateZ(-45deg) scaleX(1.7);
    transform-origin: left;
    transition-duration: .3s;
    background-color: var(--color-white);


}
.mobiletogglemenu{
  background-color:transparent;
  z-index: 9990;
  height: 100%;
  width: 100%;
  position: fixed;
  top: 0;
  right: 0;
  text-decoration: none;
  list-style: none;
  font-size: 2rem;
  cursor: pointer;
  /* display: none; */
  display: flex;
transform: translate(1000px);
transition-duration: 1s;
 
}
.show-toggle-menu{
    transform: translate(0);
    transition-duration: .6s;
}

.mobile-navbar-tabs-ul{
    background-color: var(--color-dark-mode);
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 70px;
    box-shadow: -0px 0px 30px rgba(0, 0, 0, 0.176);
}
.mobile-navbar-tabs-ul a{
    text-decoration: none;
    color: var(--color-white);
}
.mobile-navbar-tabs-li{
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.8rem;
    font-weight: 600;
    position: relative;
    cursor: pointer;
    font-family: fira code;

    height: 30px;
    width: fit-content;
}
.info-dp-section{
    width: 100%;
    display: flex;
    flex-direction: column;
    margin-top: 30px;
    gap: 30px;
}
.about-info{
    width: 100%;
    display: flex;
    flex-direction: column;
}
.dp{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content:center;
}
.activeThismobiletab{
    color: var(--color-white);
    
}
.activeThismobiletab:before{
    content: "";
    background-color: var(--color-white);
    position: absolute;
    height: 10px;
    width: 10px;
    left: -20px;
    border-radius: 50%;

}
.projects-section-div{
    width: 80%;
}
.project-box{

    flex-direction: column;
    height:800px;
}
.info-div{
    width: 100%;
    height: 50%;

}
.image-div{
    padding: 0;
    width: 100%;
    height: 50%;
    padding-left: 80px;
}
  }
  
  @media screen and (max-width:768px) {
    html {
        font-size: 50%;
    }
    .text-content{
        padding-left: 0px;
        width:80%;
    }
    #hello-friend{
        height: 100px;
        font-size: 3.5rem;
    }
    #name,#work{
        font-size: 5.5rem;
    }
    #info-para{
        width: 100%;
    }
    .contact-btn-div{
        height: 140px;
        display: flex;
        flex-direction: column-reverse;
        align-items: flex-start;
        justify-content: flex-start;
        gap: 20px;
    }
    .setting-container {
        margin-left: 0px;
    }
    .dp::before{
        display: none;
    }
    .dp::after{display: none;}

    .logo{
        width: 18%;
    }
    .logo:hover{
    transform: translateY(200px);
    transition-duration: 1s;
}
 .language-name{
        width: 100%;
     } 

.projects-section-div{
    width: 80%;
}
.project-boxes-div{
    padding: 40px 0;
}
  }
  
  @media screen and (max-width:500px) {
    html {
        font-size: 45%;
    }
    .navbar{
        height: 70px;
    }
    #hamburger{
        margin-right:20px ;
        height: 115px;
        align-items: flex-end;
    }
    .hamburgerbase{
        height: 70px;
    }
    .two-words article{
        font-size: 2.5rem;
    }
    .hey{
        left: 70px;
    }
    .logo:hover{
        transform: translateY(200px);
        transition-duration: 1s;
    }
    #hello-friend{
        font-size: 2.5rem;
    }
    
    .landing-page-container{
        height: 85vh;
    }
    .text-content{
        justify-content: flex-start;
    }
    .project-box{
        height: 550px;

    }
    .info-div{
        height: 60%;
    }
    .image-div{
        height: 40%;
        padding-left: 50px;
    }
    .image-div img{
        border-top-left-radius: 10px;
    }
    .tech-stack-wrapper{
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 20px;
    }
    .tech-stack-box{
        width: 100%;
        height: calc(76vw/2);

    }
    

  }
  @media screen and (max-width:430px) {
    html {
        font-size: 45%;
    }
    .skills-section,.about-section,.projects-section-div{
        width: 80%;
    }
    .info-div{
        padding: 0 30px;
    }
    .two-words article{
        font-size: 2.2rem;
    }
  }
  
  @media screen and (max-width:375px) {
    html {
        font-size: 42%;
    }
    .dp img{
        width: 200px;
    }
    .two-words{
        height: 50px;
    }
    .two-words article{
        font-size: 2rem;
    }
   
    .footer-bottom article{
        font-size: 1.3rem;
    }
    .logos{
        gap: 20px;
    }
     /* https://github.com/vinodjangid07 */
  }
  @media screen and (max-width:300px) {
    html {
        font-size: 42%;
    }
    .language-name article{
        text-align: center;

    }
    .two-words{
        align-items: flex-end;
        height: 50px;
    }
    .two-words article{
        font-size: 1.5rem;
    }
   
    .footer-bottom article{
        font-size: 1rem;
    }
    .social-media-container a{
        width: 50px;
        height: 50px;
    }
    .logos{
        gap: 20px;
    }
  }
  /* https://github.com/vinodjangid07 */
  /* responsive code above */
/*   

  @media screen and (min-height: 900px) and (max-width: 600px) {

    .text-content{
        justify-content: flex-start;
    }
  } */
</style>
<body class="body">
  <audio loop="" id="audioPlayer" style="display: none">
    <source src="src/mp3/preloader.mp3" type="audio/mp3" />
  </audio>
  <div id="preloader"></div>
  <noscript>Allow Javascript</noscript>

  <header>
    <div class="cursor-inner" id="cursor-inner"></div>
    <div class="cursor-outer" id="cursor-outer"></div>

    <div class="navbar" id="navbar">
      <div class="hey">Hey!</div>
      <div class="logo" tabindex="0" aria-label="Divya Kaurani logo">
        <div class="logo-top">
          <img src="src/png/avatar.png" alt="animation-head" id="nav-avatar"/>
        </div>
      </div>
      <div class="navbar-tabs" id="navbar-tabs">
        <ul class="navbar-tabs-ul">
          <li class="home activeThistab" class="navbar-tabs-li" data-aos="fade-down" data-aos-delay="100">
            <a href="#home" tabindex="0" aria-label="Home menu button">
              &#60;/Home&#62;
            </a>
          </li>

          <li class="about" class="navbar-tabs-li" data-aos="fade-down" data-aos-delay="300">
            <a href="#about" aria-label="about menu button">
              &#60;/AboutMe&#62;
            </a>
          </li>

          <li class="skills" class="navbar-tabs-li" data-aos="fade-down" data-aos-delay="500">
            <a href="#skills" aria-label="skills menu button">
              &#60;/Skills&#62;
            </a>
          </li>

          <li class="projects" class="navbar-tabs-li" data-aos="fade-down" data-aos-delay="700">
            <a href="#projects" aria-label="projects menu button">
              &#60;/Projects&#62;
            </a>
          </li>

          <li class="resume" class="navbar-tabs-li" data-aos="fade-down" data-aos-delay="700">
            <a target="_blank" href="https://drive.google.com/file/d/1fwCf30EciDvHFFCBuoQxY5x8j_i9dxbw/view?usp=sharing" aria-label="projects menu button">
              &#60;/Resume&#62;
            </a>
          </li>
          
            <div class="setting-container" id="setting-container">
              <input type="checkbox" id="switchforsetting" onclick="settingtoggle()" />
    
              <label for="switchforsetting" class="needtobeinvert" id="labelforsetting" tabindex="0"
                aria-label="settings for sound and appearance"></label>
    
              <div class="visualmodetogglebuttoncontainer" id="visualmodetogglebuttoncontainer">
                <!-- <input type="checkbox" id="switchforvisualmode" onclick="visualmode()" /> -->
                <label for="" id="" tabindex="0"
                  aria-label="switch appearance"></label>
              </div>
    
              <div class="soundtogglebuttoncontainer" id="soundtogglebuttoncontainer">
                <input type="checkbox" id="switchforsound" onclick="playpause()" />
                <label for="switchforsound" id="labelforsound" tabindex="0" aria-label="switch sound"
                  class="needtobeinvert"></label>
              </div>
            </div>
        
        </ul>
      </div>
      <!-- navbar tabs ends -->
    </div>
  </header>
  <!-- header ends here -->

  <main>
    <!-- hamburger -->
    <div class="hamburger" id="hamburger" data-aos="fade">
      <div class="hamburgerbase">
        <button id="hamburger-button" onclick="hamburgerMenu()" tabindex="0" aria-label="Menu Button">
          <span class="burger-bar" id="burger-bar1"></span>
          <span class="burger-bar" id="burger-bar2"></span>
          <span class="burger-bar" id="burger-bar3"></span>
        </button>
        
      </div>
      
    </div>
    
    <!-- hamburger -->
    <div class="mobiletogglemenu" id="mobiletogglemenu">
      <ul class="mobile-navbar-tabs-ul" id="mobile-ul">
        <li id="home-mobile-tab" class="mobile-navbar-tabs-li home activeThismobiletab" onclick="hidemenubyli()">
          <a href="#home" tabindex="0" aria-label="Home menu button">
            &#60;/Home&#62;
          </a>
        </li>

        <li id="aboutme-mobile-tab" class="mobile-navbar-tabs-li about" onclick="hidemenubyli()">
          <a href="#about" tabindex="0" aria-label="about menu button">
            &#60;/AboutMe&#62;
          </a>
        </li>
        <li id="skills-mobile-tab" class="mobile-navbar-tabs-li skills" onclick="hidemenubyli()">
          <a href="#skills" tabindex="0" aria-label="skills menu button">
            &#60;/Skills&#62;
          </a>
        </li>
        <li id="projects-mobile-tab" class="mobile-navbar-tabs-li projects" onclick="hidemenubyli()">
          <a href="#projects" tabindex="0" aria-label="projects menu button">
            &#60;/Projects&#62;
          </a>
        </li>
        <li id="projects-mobile-tab" class="mobile-navbar-tabs-li projects" onclick="hidemenubyli()">
          <a target="_blank" href="https://drive.google.com/file/d/1fwCf30EciDvHFFCBuoQxY5x8j_i9dxbw/view?usp=sharing" tabindex="0" aria-label="projects menu button">
            &#60;/Resume&#62;
          </a>
        </li>
        
      </ul>
      
    </div>
    <!-- mobile toggle menu ends -->

    <section class="landing-page-container" id="home">
      <div class="blob"></div>

      <div class="text-content">
        <article id="hello-friend" data-aos="fade-up" data-aos-delay="0">
          <p class="jello">H</p>
          <p class="jello">e</p>
          <p class="jello">l</p>
          <p class="jello">l</p>
          <p class="jello">o</p>
          &nbsp;
          <p class="jello">j</p>
          <p class="jello">i</p>
          <p class="jello">i</p>
          <p class="jello">(</p>
          <p class="jello">)</p>
          <p class="jello">;</p>
          &nbsp;
          <p class="jello">I</p>
          <p class="jello">'</p>
          <p class="jello">m</p>
        </article>
        <article id="name" data-aos="fade-up" data-aos-delay="200">
          <p class="jello">D</p>
          <p class="jello">i</p>
          <p class="jello">v</p>
          <p class="jello">y</p>
          <p class="jello">a</p>
          &nbsp;
          <p class="jello">K</p>
          <p class="jello">a</p>
          <p class="jello">u</p>
          <p class="jello">r</p>
          <p class="jello">a</p>
          <p class="jello">n</p>
          <p class="jello">i</p>
          <p class="jello">.</p>
        </article>

        <article id="work" data-aos="fade-up" data-aos-delay="400">
          <div>
            <p class="jello">I</p>
          </div>
          <div>
            <p class="jello">d</p>
            <p class="jello">e</p>
            <p class="jello">s</p>
            <p class="jello">i</p>
            <p class="jello">g</p>
            <p class="jello">n</p>
          </div>
          <div>
            <p class="jello">&</p>
          </div>
          <div>
            <p class="jello">c</p>
            <p class="jello">o</p>
            <p class="jello">d</p>
            <p class="jello">e</p>
          </div>
          <div>
            <p class="jello">f</p>
            <p class="jello">o</p>
            <p class="jello">r</p>
          </div>
          <div>
            <p class="jello">w</p>
            <p class="jello">e</p>
            <p class="jello">b</p>
            <p class="jello">.</p>
          </div>
        </article>
        <p id="info-para" data-aos="fade-up" data-aos-delay="600">
          As a skilled MERN stack developer, I specialize in crafting sleek interfaces that prioritize collaboration and user engagement.<br />
          <br />
          With a focus on simplicity and elegance, I strive to create impactful digital experiences. Let's team up to bring your vision to life!
        </p>
        <div class="contact-btn-div" data-aos="fade-up" data-aos-delay="800">
          <a href="#footer" tabindex="-1">
            <button class="letsTalkBtn">
              <p class="letsTalkBtn-text">Let's Talk!</p>
              <span class="letsTalkBtn-BG"></span>
            </button></a>
           
          <!-- <div class="setting-container" id="setting-container">
            <input type="checkbox" id="switchforsetting" onclick="settingtoggle()" />

            <label for="switchforsetting" class="needtobeinvert" id="labelforsetting" tabindex="0"
              aria-label="settings for sound and appearance"></label>

            <div class="visualmodetogglebuttoncontainer" id="visualmodetogglebuttoncontainer">
              <input type="checkbox" id="switchforvisualmode" onclick="visualmode()" />
              <label for="switchforvisualmode" id="labelforvisualmode" tabindex="0"
                aria-label="switch appearance"></label>
            </div>

            <div class="soundtogglebuttoncontainer" id="soundtogglebuttoncontainer">
              <input type="checkbox" id="switchforsound" onclick="playpause()" />
              <label for="switchforsound" id="labelforsound" tabindex="0" aria-label="switch sound"
                class="needtobeinvert"></label>
            </div>
          </div> -->
          <!-- setting div ends -->
          
        </div>
        <!-- contact-btn-div -->
        
      </div>
     
    </section>
    <!-- landing page ends here -->
    <section class="about-section-container" id="about" data-aos="fade-up">
      <div class="about-section">
        <div class="section-heading">
          <h2 class="section-heading-article" tabindex="0" aria-label="About me heading">
            &#60;/AboutMe&#62;
          </h2>
          <p class="sectionHeadingP"></p>
        </div>

        <div class="info-dp-section">
          <div class="about-info">
            <p tabindex="0">
              Hey there! I'm Divya Kaurani, a passionate MERN developer and creative graphic designer driven by the desire to create impactful digital solutions that resonate with users.
                       </p>
            <br />
            <p tabindex="0">
              My journey in technology is fueled by a commitment to innovation and problem-solving. Whether I'm crafting elegant user interfaces or diving into the depths of backend development, I'm always on the lookout for opportunities to push boundaries and make a difference.
            </p>
            <br />
            <p tabindex="0">
              In my quest for excellence, I thrive on exploring new technologies and staying ahead of industry trends. Currently, I'm immersed in some exciting projects that promise to redefine digital experiences, and I can't wait to share them with you.
            </p>
            <br />
            
             <!-- Resume button -->
      <button class="resume-btn" id="resume-btn" onclick="openURL()">
        <div class="sign">
          <svg viewBox="0 0 640 512">
            <path
              d="M144 480C64.5 480 0 415.5 0 336c0-62.8 40.2-116.2 96.2-135.9c-.1-2.7-.2-5.4-.2-8.1c0-88.4 71.6-160 160-160c59.3 0 111 32.2 138.7 80.2C409.9 102 428.3 96 448 96c53 0 96 43 96 96c0 12.2-2.3 23.8-6.4 34.6C596 238.4 640 290.1 640 352c0 70.7-57.3 128-128 128H144zm79-167l80 80c9.4 9.4 24.6 9.4 33.9 0l80-80c9.4-9.4 9.4-24.6 0-33.9s-24.6-9.4-33.9 0l-39 39V184c0-13.3-10.7-24-24-24s-24 10.7-24 24V318.1l-39-39c-9.4-9.4-24.6-9.4-33.9 0s-9.4 24.6 0 33.9z" />
          </svg>
        </div>

        <div class="text">Resume</div>
      </button>
          </div>

          <div class="dp" data-aos="fade-up">
            <img src="src/png/Divya.jpg" alt="Divya Kaurani" tabindex="0" aria-label="image of Divya" />
          </div>
        </div>
      </div>
    </section>
    <!-- about section ends  -->

    <section class="skills-section-container" id="skills">
      <div class="skills-section">
        <div class="section-heading" data-aos="fade-up">
          <h2 class="section-heading-article" tabindex="0" aria-label="skills heading">
            &#60;/Skills&#62;
          </h2>
          <p class="sectionHeadingP"></p>
        </div>

        <div class="frontend-dev-section">
          <h3 class="frontend-dev-heading" data-aos="fade-up" tabindex="0"
            aria-label="As a frontend a developer these are the skills i have">
            Tech Stack
          </h3>
          <ul class="tech-stack-wrapper">
            <li class="tech-stack-box" data-aos="fade-up">
              <img src="./src/png/htmllogo.png" alt="Html skill" class="tech-stack-logo" />
              <span class="tooltip">HTML</span>
            </li>

            <li class="tech-stack-box css" data-aos="fade-up">
              <img src="./src/png/csslogo.png" alt="css skill" class="tech-stack-logo" />
              <span class="tooltip">CSS</span>
            </li>

            <li class="tech-stack-box js" data-aos="fade-up">
              <img src="./src/png/jslogo.png" alt="js skill" class="tech-stack-logo" />
              <span class="tooltip">JS</span>
            </li>

            <li class="tech-stack-box react" data-aos="fade-up">
              <img src="./src/png/reactlogo.png" alt="react skill" class="tech-stack-logo" />
              <span class="tooltip">REACT</span>
            </li>

            <li class="tech-stack-box node" data-aos="fade-up">
              <img src="./src/png/nodejs.png" alt="bootstrap skill" class="tech-stack-logo nodejs" />
              <span class="tooltip">NodeJS</span>
            </li>

            <li class="tech-stack-box next" data-aos="fade-up">
              <img src="./src/png/nextjs.1024x1024.png" alt="nextjs skill" class="tech-stack-logo nodejs" />
              <span class="tooltip">NextJS</span>
            </li>

            <li class="tech-stack-box ts" data-aos="fade-up">
              <img src="./src/png/typescript-icon.1024x1024.png" alt="typescript skill" class="tech-stack-logo nodejs" />
              <span class="tooltip">Typescript</span>
            </li>
            
            <li class="tech-stack-box mb" data-aos="fade-up">
              <img src="./src/png/mongodb.png" alt="mongodb skill" class="tech-stack-logo" />
              <span class="tooltip">MongoDB</span>
            </li>

            <li class="tech-stack-box git" data-aos="fade-up">
              <img src="./src/png/gitlogo.png" alt="git skill" class="tech-stack-logo" />
              <span class="tooltip">GIT</span>
            </li>

            <li class="tech-stack-box github" data-aos="fade-up">
              <img src="./src/png/githublogo.png" alt="github skill" class="tech-stack-logo needtobeinvert" />
              <span class="tooltip">GITHUB</span>
            </li>


            <li class="tech-stack-box c" data-aos="fade-up">
              <img src="./src/png/clogo.png" alt="c language skill" class="tech-stack-logo" />
              <span class="tooltip">C</span>
            </li>

            <li class="tech-stack-box cpp" data-aos="fade-up">
              <img src="./src/png/cpplogo.png" alt="c++ language skill" class="tech-stack-logo" />
              <span class="tooltip">C++</span>
            </li>           

            <li class="tech-stack-box java" data-aos="fade-up">
              <img src="./src/png/java.png" alt="adobe illustrator skill" class="tech-stack-logo" />
              <span class="tooltip">Java</span>
            </li>

            <li class="tech-stack-box python" data-aos="fade-up">
              <img src="./src/png/python.png" alt="python skill" class="tech-stack-logo" />
              <span class="tooltip">Python</span>
            </li>

            <li class="tech-stack-box gpt" data-aos="fade-up">
              <img src="./src/png/chatgpt.png" alt="chatgpt skill" class="tech-stack-logo" />
              <span class="tooltip">ChatGPT</span>
            </li>

            <li class="tech-stack-box tailwind" data-aos="fade-up">
              <img src="./src/png/tailwind.png" alt="tailwind skill" class="tech-stack-logo" />
              <span class="tooltip">Tailwind</span>
            </li>

            <li class="tech-stack-box mysql" data-aos="fade-up">
              <img src="./src/png/mysql.png" alt="mysql skill" class="tech-stack-logo" />
              <span class="tooltip">Mysql</span>
            </li>

            <li class="tech-stack-box sass" data-aos="fade-up">
              <img src="./src/png/sass.png" alt="sass skill" class="tech-stack-logo" />
              <span class="tooltip">Sass</span>
            </li>
            
            <li class="tech-stack-box canva" data-aos="fade-up">
              <img src="./src/png/canvalogo.png" alt="canva skill" class="tech-stack-logo" />
              <span class="tooltip">CANVA</span>
            </li>

            <li class="tech-stack-box figma" data-aos="fade-up">
              <img src="./src/png/figmalogo.png" alt="figma skill" class="tech-stack-logo" />
              <span class="tooltip">FIGMA</span>
            </li> 
            
          </ul>
        </div>
      </div>
    </section>
    <!-- skills section ends -->
    <section class="projects-section-container" id="projects">
      <div class="projects-section-div">
        <div class="section-heading" data-aos="fade-up">
          <h2 class="section-heading-article" tabindex="0" aria-label="My projects starts from here">
            &#60;/Projects&#62;
          </h2>
          <p class="sectionHeadingP"></p>
        </div>
        
        <div class="project-boxes-div">
          <div data-aos="fade-up" class="project-box-wrapper">
            <div class="project-box project-box2" id="project-box2">
              <div class="info-div">
                <img src="src/png/logoCus.png" alt="pexelicon website favicon" class="faviconforProject" />
                <article class="ProjectHeading">Xenesis - 2024</article>
                <p class="ProjectDescription">
                  🌟 Build a college tech-event website with intuitive event registration and ticket management functionalities, complemented by an appealing UI.
                </p>
                <div class="project-buttons">
                  
                  <a href="https://www.linkedin.com/posts/divyakaurani_xenesis2024-gratitude-learningjourney-activity-7171822398990663680-hRli?utm_source=share&utm_medium=member_desktop" target="_blank" class="cta"
                    aria-label="Visit Xenesis Live">
                    <span>Live view</span>
                    <svg viewBox="0 0 13 10" height="10px" width="15px">
                      <path d="M1,5 L11,5"></path>
                      <polyline points="8 1 12 5 8 9"></polyline>
                    </svg>
                  </a>
                </div>
              </div>
              <div class="image-div">
                <img src="src/webp/xenesis.webp" alt="Xenesis website preview image" />
              </div>
            </div>
          </div>
          <div class="project-box-wrapper" data-aos="fade-up">
            <div class="project-box project-box5" id="project-box5">
              <div class="info-div">
                <img src="src/png/visio.png" alt="visio website favicon"
                  class="faviconforProject" />
                <article class="ProjectHeading">VisioBrain</article>
                <p class="ProjectDescription">
                  🌟 VisioBrain revolutionizes data analysis, democratizing insights with one-click automation. Break free from technical barriers, unleash hidden potentials, and transform raw data into actionable intelligence effortlessly. Join the data revolution today.
                </p>
                <div class="project-buttons">
                  <a href="https://github.com/KauraniDivya/visio" target="_blank" class="github-redirect"
                    aria-label="Visit Visio on GitHub">
                    <img src="src/svg/github.svg" alt="github redirect button" />
                  </a>
                  <a href="https://github.com/KauraniDivya/visio" target="_blank" class="cta" aria-label="Visit Visio live">
                    <span>Live view</span>
                    <svg viewBox="0 0 13 10" height="10px" width="15px">
                      <path d="M1,5 L11,5"></path>
                      <polyline points="8 1 12 5 8 9"></polyline>
                    </svg>
                  </a>
                </div>
              </div>
              <div class="image-div">
                <img src="src/png/visiobrain.jpeg" alt="Pexelicon website preview image" />
              </div>
            </div>
          </div>
          <div class="project-box-wrapper" data-aos="fade-up">
            <div class="project-box project-box5" id="project-box5">
              <div class="info-div">
                <img src="src/png/sankalp.png" alt="sankalp website favicon"
                  class="faviconforProject" />
                <article class="ProjectHeading">3rd-Prize</article>
                <p class="ProjectDescription">
                  🥉Secured 3rd prize in a State Level Poster Competition by presenting our innovative idea through an engaging poster.
                </p>
                <div class="project-buttons">
                 
                  <a href="https://www.linkedin.com/posts/divyakaurani_teamwork-achievementunlocked-unitebharat-ugcPost-7165752486736117760-qmgl/?utm_source=share&utm_medium=member_desktop" target="_blank" class="cta" aria-label="Visit sankalp live">
                    <span>Live view</span>
                    <svg viewBox="0 0 13 10" height="10px" width="15px">
                      <path d="M1,5 L11,5"></path>
                      <polyline points="8 1 12 5 8 9"></polyline>
                    </svg>
                  </a>
                </div>
              </div>
              <div class="image-div">
                <img src="src/png/vsitr.png" alt="sankalp website preview image" />
              </div>
            </div>
          </div>

          <!-- ---------------------- -->
          <div class="project-box-wrapper" data-aos="fade-up">
            <div class="project-box project-box2" id="project-box2">
              <div class="info-div">
                <img src="src/svg/unitebharat.svg" alt="Aquaregia website favicon"
                  class="faviconforProjectUnitebharat" />
                <article class="ProjectHeading">Unite-Bharat</article>
                <p class="ProjectDescription">
                  🌟Our team emerged as SIH Finalist🚀 and developed an innovative project repository website💯.
                </p>
                <div class="project-buttons">
                  
                  <a href="https://unite-bharat.vercel.app/" target="_blank" class="cta"
                    aria-label="Visit Unite Live">
                    <span>Live view</span>
                    <svg viewBox="0 0 13 10" height="10px" width="15px">
                      <path d="M1,5 L11,5"></path>
                      <polyline points="8 1 12 5 8 9"></polyline>
                    </svg>
                  </a>
                </div>
              </div>
              <div class="image-div">
                <img src="src/png/unite-bharat.png" alt="Aquaregia website preview image" />
              </div>
            </div>
          </div>
          <!-- ---------------------- -->
          <div class="project-box-wrapper" data-aos="fade-up">
            <div class="project-box project-box4" id="project-box4">
              <div class="info-div">
                <img src="src/png/collegpt_logo.png" alt="Qr generator website favicon" class="faviconforProject" />
                <article class="ProjectHeading">ColleGPT</article>
                <p class="ProjectDescription">
                  🌟Founder, Developer and Content Creator at ColleGPT ~ Get Prepared Together.
                </p>
                <div class="project-buttons">
                  
                  <a href="https://www.collegpt.com/" target="_blank" class="cta"
                    aria-label="Visit ColleGPT live">
                    <span>Live view</span>
                    <svg viewBox="0 0 13 10" height="10px" width="15px">
                      <path d="M1,5 L11,5"></path>
                      <polyline points="8 1 12 5 8 9"></polyline>
                    </svg>
                  </a>
                </div>
              </div>
              <div class="image-div">
                <img src="src/png/collegpt.png" alt="qr generator website preview image" />
              </div>
            </div>
          </div>

          <!-- ---------------------- -->
          <div class="project-box-wrapper" data-aos="fade-up">
            <div class="project-box project-box3" id="project-box3">
              <div class="info-div">
                <img src="src/png/logo-m.png" alt="netflix website favicon" class="faviconforProject" />
                <article class="ProjectHeading">NPTEL</article>
                <p class="ProjectDescription">
                  🌟Successfully completed and achieved qualification in NPTEL's examinations in 4 courses of Programming Domain of
DSA with Java, DBMS, Machine Learning, and Programming in Java.
                </p>
                <div class="project-buttons">
                  
                  <a href="https://www.linkedin.com/in/divyakaurani/" target="_blank" class="cta"
                    aria-label="Visit netflix clone live">
                    <span>Live view</span>
                    <svg viewBox="0 0 13 10" height="10px" width="15px">
                      <path d="M1,5 L11,5"></path>
                      <polyline points="8 1 12 5 8 9"></polyline>
                    </svg>
                  </a>
                </div>
              </div>
              <div class="image-div">
                <img src="src/png/NPTEL.png" alt="netflix clone website preview image" />
              </div>
            </div>
          </div>

          <!-- ---------------------- -->

          <div class="project-box-wrapper" data-aos="fade-up">
            <div class="project-box project-box1" id="project-box1">
              <div class="info-div">
                <img src="src/png/ssiplogo.png" alt="Axocean website favicon" class="faviconforProject" />
                <article class="ProjectHeading">SSIP-22</article>
                <p class="ProjectDescription">
                  🌟Our team emerged as Finalists in the SSIP Hackathon, where we successfully developed the E-Challan Collection System to address a real-life problem.
                </p>
                <div class="project-buttons">
                  <a href="https://github.com/DPS21302/SSIP-HACKATHON.com" target="_blank" class="github-redirect"
                    aria-label="Visit ssip on GitHub">
                    <img src="src/svg/github.svg" alt="github redirect button" />
                  </a>
                  <a href="https://www.youtube.com/watch?v=DFTcb2DXvHE&t=8s" target="_blank" class="cta"
                    aria-label="Visit ssip live">
                    <span>Live view</span>
                    <svg viewBox="0 0 13 10" height="10px" width="15px">
                      <path d="M1,5 L11,5"></path>
                      <polyline points="8 1 12 5 8 9"></polyline>
                    </svg>
                  </a>
                </div>
              </div>
              <div class="image-div">
                <img src="src/png/e-cssip.png" alt="Axocean website preview image" />
              </div>
            </div>

          </div>
          <!-- ---------------------- -->
          <div class="project-box-wrapper" data-aos="fade-up">
            <div class="project-box project-box1" id="project-box1">
              <div class="info-div">
                <img src="src/png/BTBLOGO.png" alt="Axocean website favicon" class="faviconforProject" />
                <article class="ProjectHeading">BTB-22</article>
                <p class="ProjectDescription">
                  🌟Winner of National Level Hackathon, our team has built effective and fully functional College Canteen Automation Website.                </p>
                <div class="project-buttons">
                  <a href="https://github.com/tancreates/THE-HIDE-OUT" target="_blank" class="github-redirect"
                    aria-label="Visit btb on GitHub">
                    <img src="src/svg/github.svg" alt="github redirect button" />
                  </a>
                  <a href="https://www.youtube.com/watch?v=It482zYm8hg&t=10s" target="_blank" class="cta"
                    aria-label="Visit btb live">
                    <span>Live view</span>
                    <svg viewBox="0 0 13 10" height="10px" width="15px">
                      <path d="M1,5 L11,5"></path>
                      <polyline points="8 1 12 5 8 9"></polyline>
                    </svg>
                  </a>
                </div>
              </div>
              <div class="image-div">
                <img src="src/png/btbw.png" alt="Axocean website preview image" />
              </div>
            </div>
          </div>
          <!-- ---------------------- -->
          <div class="project-box-wrapper" data-aos="fade-up">
            <div class="project-box project-box1" id="project-box1">
              <div class="info-div">
                <img src="src/png/google_cloud.png" alt="Axocean website favicon" class="faviconforProject" />
                <article class="ProjectHeading">Google Cloud</article>
                <p class="ProjectDescription">
                  🌟 Proud to showcase my 💫 Google Cloud Arcade swags, symbolizing my journey of immersive learning in cloud technology with Google Cloud and Qwiklabs. 🚀                
                  <div class="project-buttons">                  
                  <a href="https://www.linkedin.com/posts/divyakaurani_google-googlecloud-arcade-activity-7122633372379623424-Iz_P?utm_source=share&utm_medium=member_desktop" target="_blank" class="cta"
                    aria-label="Visit axocean live">
                    <span>Live view</span>
                    <svg viewBox="0 0 13 10" height="10px" width="15px">
                      <path d="M1,5 L11,5"></path>
                      <polyline points="8 1 12 5 8 9"></polyline>
                    </svg>
                  </a>
                </div>
              </div>
              <div class="image-div">
                <img src="src/png/swags.jpeg" alt="Axocean website preview image" />
              </div>
            </div>
          </div>
          <!-- ---------------------- -->
        </div>
      </div>
    </section>
  </main>
  <!-- main ends here -->

  <footer id="footer">
    <button class="fas" id="backtotopbutton" onclick="scrolltoTopfunction()">
      <article aria-label="Back to top">&#8592;BACK TO TOP</article>
    </button>
    <div class="footer-background">
      <div class="footer-blob"></div>
    </div>
    <div class="footer-foreground">
      <div class="footercontainer">
        <div class="two-words">
          <article tabindex="0" aria-label="Learning, Living, and Leveling Up, my quote">
            "Learning, Living, and Leveling Up."
          </article>
        </div>
        <div class="social-media-container">
          <div class="getintouch-heading">
            <article>GetinTouch();</article>
          </div>
          <ul class="example-2">
  <li class="icon-content">
    <a
      href="https://www.linkedin.com/in/divyakaurani/"
      aria-label="LinkedIn"
      data-social="linkedin"
    >
      <div class="filled"></div>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="16"
        height="16"
        fill="currentColor"
        class="bi bi-linkedin"
        viewBox="0 0 16 16"
        xml:space="preserve"
      >
        <path
          d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z"
          fill="currentColor"
        ></path>
      </svg>
    </a>
    <div class="tooltip">LinkedIn</div>
  </li>
  <li class="icon-content">
    <a href="https://github.com/KauraniDivya" aria-label="GitHub" data-social="github">
      <div class="filled"></div>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="16"
        height="16"
        fill="currentColor"
        class="bi bi-github"
        viewBox="0 0 16 16"
        xml:space="preserve"
      >
        <path
          d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27s1.36.09 2 .27c1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.01 8.01 0 0 0 16 8c0-4.42-3.58-8-8-8"
          fill="currentColor"
        ></path>
      </svg>
    </a>
    <div class="tooltip">GitHub</div>
  </li>
  <li class="icon-content">
    <a
      href="https://www.instagram.com/divya_kaurani20/"
      aria-label="Instagram"
      data-social="instagram"
    >
      <div class="filled"></div>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="16"
        height="16"
        fill="currentColor"
        class="bi bi-instagram"
        viewBox="0 0 16 16"
        xml:space="preserve"
      >
        <path
          d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.9 3.9 0 0 0-1.417.923A3.9 3.9 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.9 3.9 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.9 3.9 0 0 0-.923-1.417A3.9 3.9 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599s.453.546.598.92c.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.5 2.5 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.5 2.5 0 0 1-.92-.598 2.5 2.5 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233s.008-2.388.046-3.231c.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92s.546-.453.92-.598c.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92m-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217m0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334"
          fill="currentColor"
        ></path>
      </svg>
    </a>
    <div class="tooltip">Instagram</div>
  </li>
  <li class="icon-content">
    <a
      href="https://hashnode.com/@DK2003"
      aria-label="LinkedIn"
      data-social="linkedin"
    >
      <div class="filled"></div>
      <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="800px" height="800px" viewBox="0 0 256 256" version="1.1">
        <g fill-rule="evenodd">
            <path d="M17.5913461,85.5328619 C-5.86378203,108.98799 -5.86378203,147.01185 17.5913461,170.464766 L85.5337714,238.409404 C108.9889,261.862319 147.01276,261.862319 170.465675,238.409404 L238.410313,170.464766 C261.863229,147.009638 261.863229,108.985777 238.410313,85.5328619 L170.465675,17.5904365 C147.010547,-5.86247884 108.986687,-5.86247884 85.5337714,17.5904365 L17.5913461,85.5328619 Z M157.724673,157.725976 C174.143262,141.307386 174.143262,114.690241 157.724673,98.2738645 C141.308296,81.8552748 114.691151,81.8552748 98.274774,98.2738645 C81.8561843,114.692454 81.8561843,141.307386 98.274774,157.725976 C114.693364,174.142353 141.308296,174.142353 157.726886,157.725976 L157.724673,157.725976 Z" fill="#ffffff">
    
    </path>
        </g>
    </svg>
    </a>
    <div class="tooltip">Hashnode</div>
  </li>
  <li class="icon-content">
    <a href="https://www.youtube.com/channel/UCSdls-ZlC1jv5tWtJDYIcqw" aria-label="Youtube" data-social="youtube">
      <div class="filled"></div>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="16"
        height="16"
        fill="currentColor"
        class="bi bi-youtube"
        viewBox="0 0 16 16"
        xml:space="preserve"
      >
        <path
          d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.01 2.01 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.01 2.01 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31 31 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.01 2.01 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A100 100 0 0 1 7.858 2zM6.4 5.209v4.818l4.157-2.408z"
          fill="currentColor"
        ></path>
      </svg>
    </a>
    <div class="tooltip">Youtube</div>
  </li>
  <li class="icon-content">
    <a href="https://twitter.com/d_kaurani61801" aria-label="GitHub" data-social="github">
      <div class="filled"></div>
      <svg xmlns="http://www.w3.org/2000/svg" enable-background="new 0 0 72 72" viewBox="0 0 72 72" id="twitter-x"><switch fill="#ffffff"><g><path d="M42.5,31.2L66,6h-6L39.8,27.6L24,6H4l24.6,33.6L4,66    h6l21.3-22.8L48,66h20L42.5,31.2z M12.9,10h8l38.1,52h-8L12.9,10z" fill="#ffffff"/></g></switch></svg>
    </a>
    <div class="tooltip">Twitter</div>
  </li>
  
  <li class="icon-content">
    <a
      href="https://t.me/+919558059911"
      aria-label="LinkedIn"
      data-social="linkedin"
    >
      <div class="filled"></div>
      <svg version="1.1" viewBox="0 0 100 100">
        <path
          d="M95,9.9c-1.3-1.1-3.4-1.2-7-0.1c0,0,0,0,0,0c-2.5,0.8-24.7,9.2-44.3,17.3c-17.6,7.3-31.9,13.7-33.6,14.5  c-1.9,0.6-6,2.4-6.2,5.2c-0.1,1.8,1.4,3.4,4.3,4.7c3.1,1.6,16.8,6.2,19.7,7.1c1,3.4,6.9,23.3,7.2,24.5c0.4,1.8,1.6,2.8,2.2,3.2  c0.1,0.1,0.3,0.3,0.5,0.4c0.3,0.2,0.7,0.3,1.2,0.3c0.7,0,1.5-0.3,2.2-0.8c3.7-3,10.1-9.7,11.9-11.6c7.9,6.2,16.5,13.1,17.3,13.9  c0,0,0.1,0.1,0.1,0.1c1.9,1.6,3.9,2.5,5.7,2.5c0.6,0,1.2-0.1,1.8-0.3c2.1-0.7,3.6-2.7,4.1-5.4c0-0.1,0.1-0.5,0.3-1.2  c3.4-14.8,6.1-27.8,8.3-38.7c2.1-10.7,3.8-21.2,4.8-26.8c0.2-1.4,0.4-2.5,0.5-3.2C96.3,13.5,96.5,11.2,95,9.9z M30,58.3l47.7-31.6  c0.1-0.1,0.3-0.2,0.4-0.3c0,0,0,0,0,0c0.1,0,0.1-0.1,0.2-0.1c0.1,0,0.1,0,0.2-0.1c-0.1,0.1-0.2,0.4-0.4,0.6L66,38.1  c-8.4,7.7-19.4,17.8-26.7,24.4c0,0,0,0,0,0.1c0,0-0.1,0.1-0.1,0.1c0,0,0,0.1-0.1,0.1c0,0.1,0,0.1-0.1,0.2c0,0,0,0.1,0,0.1  c0,0,0,0,0,0.1c-0.5,5.6-1.4,15.2-1.8,19.5c0,0,0,0,0-0.1C36.8,81.4,31.2,62.3,30,58.3z"
          fill="currentColor"
        ></path>
      </svg>
    </a>
    <div class="tooltip">Telegram</div>
  </li>
</ul>

        </div>
        <div class="footer-avatar-container">
          <p data-aos="fade-right" data-aos-duration="1000" class="left-text">Let's</p>
          <img data-aos="fade-up" data-aos-delay="100" data-aos-duration="2000" src="src/png/avatar.png" alt="animation-head" class="footer-avatar-img" id="footer-wala-avatar" />
          <p data-aos="fade-left" data-aos-duration="1000" class="right-text">Talk</p>
      </div>
      
        <!-- after image div  -->
        <!-- <div class="footer-avatar-face">
            <div class="footer-avatar-eye footer-left-eye">
              <div class="footer-pupil"></div>
            </div>
            <div class="footer-avatar-eye footer-right-eye">
              <div class="footer-pupil"></div>
            </div>
          </div> -->
        <div class="footer-bottom">
          <article>
            Design & Built by Divya Kaurani
            &#169; twentytwentyfour
          </article>
        </div>
      </div>
    </div>
  </footer>
  <!-- footer ends here -->

  <script src="main.js"></script>

  <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>

  <script>
    function openURL() {
      var url = "src/pdf/Divya Kaurani.pdf";

      window.open(url, "_blank");
    }
  </script>

  <script>
    const cursorInner = document.getElementById("cursor-inner");
    const cursorOuter = document.getElementById("cursor-outer");
    const links = document.querySelectorAll("a,label,button");

    document.addEventListener("mousemove", function (e) {
      const posX = e.clientX;
      const posY = e.clientY;

      cursorInner.style.left = `${posX}px`;
      cursorInner.style.top = `${posY}px`;

      // cursorOuter.style.left = `${posX}px`;
      // cursorOuter.style.top = `${posY}px`;

      cursorOuter.animate(
        {
          left: `${posX}px`,
          top: `${posY}px`,
        },
        { duration: 500, fill: "forwards" }
      );

      links.forEach((link) => {
        link.addEventListener("mouseenter", () => {
          cursorInner.classList.add("hover");
          cursorOuter.classList.add("hover");
        });
        link.addEventListener("mouseleave", () => {
          cursorInner.classList.remove("hover");
          cursorOuter.classList.remove("hover");
        });
      });
    });
  </script>
  <!-- <script data-name="BMC-Widget" data-cfasync="false" src="https://cdnjs.buymeacoffee.com/1.0.0/widget.prod.min.js" data-id="Divya.Kaurani07" data-description="Support me on Buy me a coffee!" data-message="" data-color="#BD5FFF" data-position="left" data-x_margin="18" data-y_margin="18"></script> -->
</body>

</html>
