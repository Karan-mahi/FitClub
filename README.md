Abstract
The purpose of Gym Website is to automate the existing manual system by the help of computerized equipment and full-fledged computer software, fulfilling their requirements, so that their valuable data/information can be stored for a longer period with easy accessing and manipulation of the same. The required software and hardware are easily available and easy to work with.

Gym Website, as described above, can lead to error free, secure, reliable, and fast management system. It can assist the user to concentrate on their other activities rather to concentrate on the record keeping. Thus, it will help organization in better utilization of resources. The organization can maintain computerized records without redundant entries. That means that one need not be distracted by information that is not relevant, while being able to reach the information.

The aim is to automate its existing manual system by the help of computerized equipment and full-fledged computer software, fulfilling their requirements, so that their valuable data/information can be stored for a longer period with easy accessing and manipulation of the same. Basically, the project describes how to manage for good performance and better services for the clients.

User interface/Features:
•	Interactive and user-friendly design
•	Anyone can find the best suited plan for them
•	24/7 customer support available
•	Fully responsive design
 

Components:
Header: Header section contains logo of website and an unordered list to navigate throughout the website and join now button is present.
Hero: Hero section contain main highlights of our website it has cool animation and background image of our poster boy.
Program: This section contains the information about the programs our website provides there are four programs strength training, cardio training, fat burning, health fitness user can choose from any of these three four programs.
Reason: reason section contains why should user choose our website over other website and it also have information about our partners.
Plans: This component contain or all plans. We have three plans users can choose any of these three plan and we have our bestselling plan in middle.
Testimonials: This section contain reviews of our customers which are showed using a cool animation.
Join: This section contains a fully functioning contact box through which user can contact to us.
Footer: This is the last section of our website which contain our Instagram handle GitHub link and LinkedIn profile user can contact through any of these.
 

User manual:
	Minimum Requirements: -
•	OS: Windows 7 64-bit
•	Processor: Intel® Core™ i5-6600K / AMD FX-6300
•	Memory: 2GB
•	Graphics: Integrated
•	Disk: 512 MB (free)
Note: - Recommended to use Chrome or Firefox latest browser for best experience

FAQ
Q: - Why website not working?
A: - Some old browsers do not support JavaScript if your browser support JavaScript then enable it in settings.

Q: - Will this website could be used from mobile device.
A: - Yes, this website uses responsive web design so it could adapt in any screen size.
 
 

Code Section: - 
•	index.html

•	<!DOCTYPE html>
•	<html lang="en">
•	  <head>
•	    <meta charset="utf-8" />
•	    <link rel="icon" href="%PUBLIC_URL%/favicon.ico" />
•	    <meta name="viewport" content="width=device-width, initial-scale=1" />
•	    <meta name="theme-color" content="#000000" />
•	    <meta
•	      name="description"
•	      content="Web site created using create-react-app"
•	    />
•	    <link rel="apple-touch-icon" href="%PUBLIC_URL%/logo192.png" />
•	    <!--
•	      manifest.json provides metadata used when your web app is installed on a
•	      user's mobile device or desktop. See https://developers.google.com/web/fundamentals/web-app-manifest/
•	    -->
•	    <link rel="manifest" href="%PUBLIC_URL%/manifest.json" />
•	    <link rel="preconnect" href="https://fonts.googleapis.com" />
•	    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
•	    <link
•	      href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap"
•	      rel="stylesheet"
•	    />
•	    <style>
•	      * {
•	        font-family: "Inter", sans-serif;
•	      }
•	    </style>
•	    <!--
•	      Notice the use of %PUBLIC_URL% in the tags above.
•	      It will be replaced with the URL of the `public` folder during the build.
•	      Only files inside the `public` folder can be referenced from the HTML.
•	
•	      Unlike "/favicon.ico" or "favicon.ico", "%PUBLIC_URL%/favicon.ico" will
•	      work correctly both with client-side routing and a non-root public URL.
•	      Learn how to configure a non-root public URL by running `npm run build`.
•	    -->
•	    <title>React App</title>
•	  </head>
•	  <body>
•	    <noscript>You need to enable JavaScript to run this app.</noscript>
•	    <div id="root"></div>
•	    <!--
•	      This HTML file is a template.
•	      If you open it directly in the browser, you will see an empty page.
•	
•	      You can add webfonts, meta tags, or analytics to this file.
•	      The build step will place the bundled scripts into the <body> tag.
•	
•	      To begin the development, run `npm start` or `yarn start`.
•	      To create a production bundle, use `npm run build` or `yarn build`.
•	    -->
•	  </body>
•	</html>•	•	

•	index.css

•	body {
•	  margin: 0;
•	  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen',
•	    'Ubuntu', 'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue',
•	    sans-serif;
•	  -webkit-font-smoothing: antialiased;
•	  -moz-osx-font-smoothing: grayscale;
•	}
•	
•	code {
•	  font-family: source-code-pro, Menlo, Monaco, Consolas, 'Courier New',
•	    monospace;
•	}•	•	

•	index.js

import React from 'react';
import ReactDOM from 'react-dom/client';
import './index.css';
import App from './App';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
    <App />
);

// If you want to start measuring performance in your app, pass a function
// to log results (for example: reportWebVitals(console.log))
// or send to an analytics endpoint. Learn more: https://bit.ly/CRA-vitals


•	App.js

import './App.css';
import Footer from './components/Footer/Footer';
import Hero from './components/Hero/Hero'
import Join from './components/Join/Join';
import Plans from './components/Plans/Plans';
import Programs from './components/Programs/Programs';
import Reasons from './components/Reasons/Reasons';
import Testimonials from './components/Testimonials/Testimonials';

function App() {
  return (
    <div className="App">
          <Hero/>
          <Programs/>
          <Reasons/>
          <Plans/>
          <Testimonials/>
          <Join/>
          <Footer/>
    </div>
  );
}

export default App;


•	App.css

/* make variables */
:root {
  --lightgray: #D9D9D9;
  --gray: #9c9c9c;
  --orange: #f48915;
  --darkGrey: #464D53;
  --caloryCard: #656565;
  --planCard: linear-gradient(210.41deg, #fa5042 1.14%, #ffa739 100.75%);
  --appColor:  #3c3f45;
}

.App {
  background-image: url(data:image/png;base64,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);
  mix-blend-mode: overlay;
  background-color: var(--appColor);
  display: flex;
  flex-direction: column;
  gap: 6rem;
  overflow: hidden;
}
::-webkit-scrollbar{
  display: none;
}
.stroke-text{
  color: transparent;
  font-family: Arial, Helvetica, sans-serif;
  -webkit-text-stroke-width: 1px;
  -webkit-text-stroke-color: white;
}

.btn{
  background-color: white;
  padding: 0.5rem;
  font-weight: bold;
  border: 4px solid transparent;
  transition: 300ms all;
  display: flex;
  align-items: center;
  justify-content: center;
}
.btn:hover{
  cursor: pointer;
}
.blur{
  background-color: rgba(253, 120, 43, 0.269);
  position: absolute;
  border-radius: 50%;
  filter: blur(150px);
  z-index: -9;

}


•	Footer
o	Jsx

•	import React from "react";
•	import "./Footer.css";
•	import Github from "../../assets/github.png";
•	import Instagram from "../../assets/instagram.png";
•	import LinkedIn from "../../assets/linkedin.png";
•	import Logo from "../../assets/logo.png";
•	const Footer = () => {
•	  return (
•	    <div className="Footer-container">
•	      <hr />
•	      <div className="footer">
•	        <div className="social-links">
•	          <img src={Github} alt="" />
•	          <img src={Instagram} alt="" />
•	          <img src={LinkedIn} alt="" />
•	        </div>
•	        <div className="logo-f">
•	          <img src={Logo} alt="" />
•	        </div>
•	      </div>
•	      <div className="blur footer-blur-1"></div>
•	      <div className="blur footer-blur-2"></div>
•	    </div>
•	  );
•	};
•	 
•	export default Footer;•	•	

o	Css

.Footer-container {
    position: relative;

}

.Footer-container>hr {
    border: 1px solid var(--lightgray);

}

.footer {
    padding: 1ren 2rem;
    display: flex;
    flex-direction: column;
    gap: 4rem;
    align-items: center;
    justify-content: center;
    height: 20rem;

}
.social-links{
    display: flex;
    gap: 4rem;

}
.social-links>img{
    width: 2rem;
    height: 2rem;
    cursor: pointer;
}
.logo-f>img{
    width: 10rem;
    
}
.footer-blur-1{
    bottom: 0;
    right: 15%;
    width: 36rem;
    height: 12rem;
    filter: blur(250px);
    background: rgba(255, 0, 0, 0.137);
}
.footer-blur-2{
    bottom: 0;
    left: 15%;
    width: 26rem;
    height: 12rem;
    filter: blur(250px);
    background: rgba(255, 115, 0, 0.16);
}


•	Header
o	JSX
•	import React from "react";
•	import "./Header.css";
•	import Logo from "../../assets/logo.png";
•	import Bars from "../../assets/bars.png";
•	import { Link } from "react-scroll";
•	import { useState } from "react";
•	const Header = () => {
•	  const mobile = window.innerWidth <= 768 ? true : false;
•	  const [menuOpened, setMenuOpened] = useState(false);
•	  return (
•	    <div className="header">
•	      <img src={Logo} alt="" className="logo" />
•	      {menuOpened === false && mobile === true ? (
•	        <div
•	          style={{
•	            backgroundColor: "var(--appColor",
•	            padding: "0.5rem",
•	            borderRadius: "5px",
•	          }}
•	          onClick={() => setMenuOpened(true)}
•	        >
•	          <img
•	            src={Bars}
•	            alt=""
•	            style={{ width: "1.5rem", height: "1.5rem" }}
•	          />
•	        </div>
•	      ) : (
•	        <ul className="header-menu">
•	          <li onClick={() => setMenuOpened(false)}>
•	            <Link
•	              onClick={() => setMenuOpened(false)}
•	              to="home"
•	              span={true}
•	              smooth={true}
•	            >
•	              Home
•	            </Link>
•	          </li>
•	          <li onClick={() => setMenuOpened(false)}>
•	            <Link
•	              onClick={() => setMenuOpened(false)}
•	              to="programs"
•	              span={true}
•	              smooth={true}
•	            >
•	              Programs
•	            </Link>
•	          </li>
•	          <li onClick={() => setMenuOpened(false)}>
•	            <Link
•	              onClick={() => setMenuOpened(false)}
•	              to="reasons"
•	              span={true}
•	              smooth={true}
•	            >
•	              why us
•	            </Link>
•	          </li>
•	          <li onClick={() => setMenuOpened(false)}>
•	            <Link
•	              onClick={() => setMenuOpened(false)}
•	              to="plans"
•	              span={true}
•	              smooth={true}
•	            >
•	              Plans
•	            </Link>
•	          </li>
•	          <li>
•	            <Link
•	              onClick={() => setMenuOpened(false)}
•	              to="testimonials"
•	              span={true}
•	              smooth={true}
•	            >
•	              Testimonials
•	            </Link>
•	          </li>
•	        </ul>
•	      )}
•	    </div>
•	  );
•	};
•	
•	export default Header;•	•	

o	CSS
•	.header{
•	    display: flex;
•	    justify-content: space-between;
•	}
•	.logo{
•	    width: 10rem;
•	    height: 3rem;
•	}
•	
•	.header-menu{
•	    list-style: none;
•	    display: flex;
•	    gap: 2rem;
•	    color: white;
•	}
•	
•	.header-menu>li{
•	   cursor: pointer; 
•	}
•	
•	.header-menu>li:hover{
•	    cursor: pointer; 
•	    color: var(--orange);
•	 }
•	
•	 @media screen and (max-width: 768px){
•	    .header>:nth-child(2){
•	        position: fixed;
•	        right: 2rem;
•	        z-index: 99;
•	    }
•	    .header-menu{
•	        flex-direction: column;
•	        background-color: var(--appColor);
•	        padding: 2rem;
•	    }
•	 }•	
•	Hero
o	JSX
•	import hero_image from "../../assets/hero_image.png";
•	import hero_image_back from "../../assets/hero_image_back.png";
•	import Heart from "../../assets/heart.png";
•	import Calories from "../../assets/calories.png";
•	import React from "react";
•	import Header from "../Header/Header";
•	import { motion } from "framer-motion";
•	import NumberCounter from 'number-counter'
•	import "./Hero.css";
•	const hero = () => {
•	  const transition = { type: "spring", duration: 3 };
•	  const mobile = window.innerWidth<=768 ? true: false;
•	  return (
•	    <div className="hero" id="home">
•	      <div className="blur hero-blur"></div>
•	      <div className="left-h">
•	        <Header />
•	        {/* the best ad */}
•	        <div className="the-best-ad">
•	          <motion.div
•	            initial={{ left: mobile?"150px":"200px"}}
•	            whileInView={{ left: "8px" }}
•	            transition={{ ...transition, type: "linear" }}
•	          ></motion.div>
•	          <span>the best fitness club in town</span>
•	        </div>
•	
•	        {/* Hero Heading */}
•	        <div className="hero-text">
•	          <div>
•	            <span className="stroke-text">Shape </span>
•	            <span>Your</span>
•	          </div>
•	          <div>
•	            <span>Ideal Body</span>
•	          </div>
•	          <div>
•	            <span>
•	              In here we will help you to shape and build your ideallive up your
•	              life to fullest.
•	            </span>
•	          </div>
•	        </div>
•	
•	        {/* figures */}
•	        <div className="figures">
•	          <div>
•	            <span>
•	            <NumberCounter end={140} start={100} delay='4' preFix="+"/>
•	            </span>
•	            <span>expert coachs</span>
•	          </div>
•	          <div>
•	            <span>
•	            <NumberCounter end={978} start={800} delay='4' preFix="+"/>
•	            </span>
•	            <span>member joined</span>
•	          </div>
•	          <div>
•	            <span>
•	            <NumberCounter end={50} start={0} delay='4' preFix="+"/>
•	            </span>
•	            <span>fitness programs</span>
•	          </div>
•	        </div>
•	
•	        {/* hero buttons */}
•	        <div className="hero-buttons">
•	          <button className="btn">Get Started</button>
•	          <button className="btn">Learn More</button>
•	        </div>
•	      </div>
•	      <div className="right-h">
•	        <button className="btn">Join Now</button>
•	        <motion.div
•	          initial={{ right: "-1rem" }}
•	          whileInView={{ right: "4rem" }}
•	          transition={transition}
•	          className="heart-rate"
•	        >
•	          <img src={Heart} alt="" />
•	          <span>Heart Rate</span>
•	          <span>116 bpm</span>
•	        </motion.div>
•	      </div>
•	
•	      {/* hero images */}
•	      <img src={hero_image} alt="" className="hero-image" />
•	      <motion.img
•	      initial={{ right: "11rem" }}
•	      whileInView={{ right: "20rem" }}
•	      transition={transition}
•	       src={hero_image_back} alt="" className="hero-image-back" />
•	      {/* calories */}
•	      <motion.div
•	        initial={{ right: "37rem" }}
•	        whileInView={{ right: "28rem" }}
•	        transition={transition}
•	        className="calories"
•	      >
•	        <img src={Calories} alt="" />
•	        <div>
•	          <span>calories Burned</span>
•	          <span>220</span>
•	        </div>
•	      </motion.div>
•	    </div>
•	  );
•	};
•	
•	export default hero;•	•	
o	CSS
•	.hero{
•	    display: flex;
•	    justify-content: space-between;
•	}
•	
•	.left-h{
•	    padding: 2rem;
•	    padding-top: 1.5rem;
•	    flex: 3;
•	    display: flex;
•	    gap: 2rem;
•	    flex-direction: column;
•	}
•	.right-h{
•	    flex: 1;
•	    position: relative;
•	    background: var(--orange);
•	
•	}
•	.the-best-ad{
•	    margin-top: 4rem;
•	    background-color: #363d42;
•	    transform: skew(20deg);
•	    width: fit-content;
•	    padding: 20px 13px;
•	    text-transform: uppercase;
•	    color: white;
•	    position: relative;
•	    display: flex;
•	    align-items: center;
•	    justify-content: flex-start;
•	}
•	.the-best-ad>span{
•	    transform: skew(-20deg);
•	}
•	
•	.the-best-ad>div{
•	    position: absolute;
•	    background-color: var(--orange);
•	    width: 5.4rem;
•	    height: 80%;
•	    left: 8px;
•	}
•	
•	.hero-text{
•	    display: flex;
•	    flex-direction: column;
•	    gap: 1.5rem;
•	    text-transform: uppercase;
•	    font-size: 4.5rem;
•	    font-weight: bold;
•	    color: white;
•	    text-overflow: inherit;
•	}
•	
•	.hero-text>div:nth-of-type(3){
•	    font-size: 1rem;
•	    font-weight: 200;
•	    text-transform: none;
•	    letter-spacing: 1px;
•	    width: 80%;
•	}
•	.figures{
•	    display: flex;
•	    gap: 2rem;
•	}
•	.figures>div{
•	    display: flex   ;
•	    flex-direction: column;
•	}
•	.figures>div>span:nth-of-type(1){
•	    color: white;
•	    font-size: 2rem;
•	}
•	.figures>div>span:nth-of-type(2){
•	    color: var(--gray);
•	    text-transform: uppercase;
•	}
•	
•	.hero-buttons{
•	    display: flex;
•	    gap: 1rem;
•	   font-weight: normal; 
•	}
•	.hero-buttons>:nth-child(1){
•	    color: white;
•	    background-color: var(--orange);
•	    width: 8rem;
•	}
•	.hero-buttons>:nth-child(2){
•	    color: white;
•	    background-color: transparent;
•	    width: 8rem;
•	    border: 2px solid var(--orange);
•	}
•	.right-h>.btn{
•	    position: absolute;
•	    right: 3rem;
•	    top: 2rem;
•	    color: black;
•	}
•	.heart-rate{
•	    display: flex;
•	    flex-direction: column;
•	    background-color: var(--darkGrey);
•	    width: fit-content;
•	    padding: 1rem;
•	    align-items: start;
•	    border-right: 5px;
•	    position: absolute;
•	    right: 4rem;
•	    top: 7rem;
•	}
•	.heart-rate>img{
•	    width: 2rem;
•	}
•	.heart-rate>span:nth-child(2){
•	    color: var(--gray);
•	
•	}
•	.heart-rate>span:nth-child(3){
•	    color: white;
•	    font-size: 1.5rem;
•	    
•	}
•	
•	.hero-image{
•	    position: absolute;
•	    top: 10rem;
•	    right: 8rem;
•	    width: 23rem;
•	}
•	.hero-image-back{
•	    position: absolute;
•	    top: 4rem;
•	    right: 20rem;
•	    z-index: -1;
•	    width: 15rem;
•	}
•	.calories{
•	    display: flex;
•	    gap: 2rem;
•	    background-color: var(--caloryCard);
•	    border-radius: 5px;
•	    padding: 1rem;
•	    width: fit-content;
•	    position: absolute;
•	    top: 32rem;
•	    right: 28rem;
•	
•	}
•	.calories>img{
•	    width: 3rem;
•	}
•	.calories>div{
•	    display: flex;
•	    flex-direction: column;
•	    justify-content: space-between;
•	}
•	.calories>div>:nth-child(1){
•	    color: var(--gray);
•	}
•	.calories>div>:nth-child(2){
•	    color: white;
•	    font-size: 1.5rem;
•	
•	}
•	.hero-blur{
•	    width: 22rem;
•	    height: 30rem;
•	    left: 0px;
•	}
•	
•	@media screen and (max-width: 768px)
•	{
•	    .hero{
•	        flex-direction: column;
•	    }
•	    .hero-blur{
•	        width: 14rem;
•	
•	    }
•	    .the-best-ad{
•	        margin-top: 0;
•	        font-size: small;
•	        align-self: center;
•	        transform: scale(0.8);
•	    }
•	    .hero-text{
•	        font-size: xx-large;
•	        align-items: center;
•	        justify-content: center;
•	    }
•	    .hero-text>div:nth-of-type(3){
•	        font-size: small;
•	        font-weight: 200;
•	        letter-spacing: 1px;
•	        text-align: center;
•	    }
•	    .hero-buttons{
•	        justify-content: center;
•	
•	    }
•	    .figures>div>span:nth-of-type(1){
•	        font-size: large;
•	    }
•	    .figures>div>span:nth-of-type(2){
•	        font-size: small;
•	    }
•	    .right-h{
•	        position: relative;
•	        background: none;
•	    }
•	    .heart-rate{
•	        left: 1rem;
•	        top: 2rem;
•	
•	    }
•	    .calories{
•	        position: relative;
•	        top: 5rem;
•	        left: 2rem;
•	
•	    }
•	    .calories>img{
•	       width: 2rem;
•	        
•	    }
•	    .calories > div > :nth-child(2){
•	        color: white;
•	        font-size: 1rem;
•	    }
•	    .hero-image{
•	        position: relative;
•	        width: 15rem;
•	        left: 7rem;
•	        top: 4rem;
•	        align-items: center;
•	    }
•	    .hero-image-back{
•	        width: 15rem;
•	        left: 2rem;
•	        top: 35rem;
•	
•	    }
•	}•	

•	Join
o	JSX
•	import React from "react";
•	import { useRef } from "react";
•	import "./Join.css";
•	import emailjs from '@emailjs/browser'
•	const Join = () => {
•	    const form = useRef()
•	    const sendEmail = (e) => {
•	        e.preventDefault();
•	    
•	        emailjs.sendForm('service_oih6s7o', 'template_kd1fft8', form.current, 'xz-o2wBwVztsmnufw')
•	          .then((result) => {
•	              console.log(result.text);
•	          }, (error) => {
•	              console.log(error.text);
•	          });
•	      };
•	  return (
•	    <div className="Join" id="join-us">
•	      <div className="left-j">
•	        <hr />
•	        <div>
•	          <span className="stroke-text">READY TO</span>
•	          <span> LEVEL UP</span>
•	        </div>
•	        <div>
•	          <span> YOUR BODY</span>
•	          <span className="stroke-text"> WITH US?</span>
•	        </div>
•	      </div>
•	      <div className="right-j">
•	        <form ref={form} className="email-container" onSubmit={sendEmail}>
•	            <input type="email" name="user_email" placeholder="Enter your Email address" />
•	            <button className="btn btn-j">Join Now</button>
•	
•	        </form>
•	      </div>
•	    </div>
•	  );
•	};
•	
•	export default Join;•	•	

o	CSS
•	.Join{
•	    display: flex;
•	    padding: 0 2rem;
•	    gap: 10rem;
•	}
•	
•	.left-j{
•	    color: white;
•	    font-size: 3rem;
•	    font-weight: bold;
•	    text-transform: uppercase;
•	    position: relative;
•	}
•	.left-j>hr{
•	    position: absolute;
•	    width: 10.5rem;
•	    border: 3px solid var(--orange);
•	    margin: -10px 0;
•	    transform: skew(60deg);
•	}
•	.right-j{
•	    display: flex;
•	    justify-content: center;
•	    align-items: flex-end;
•	
•	}
•	.email-container{
•	    display: flex;
•	    gap: 3rem;
•	    background-color: gray;
•	    padding: 1rem 2rem;
•	
•	}
•	.email-container>input{
•	    background-color: transparent;
•	    border: none;
•	    outline: none;
•	    color: var(--lightgray);
•	}
•	::placeholder{
•	    color: var(--lightgray);
•	}
•	.btn-j{
•	    color: white;
•	    background-color: var(--orange);
•	}
•	
•	@media screen and (max-width: 768px){
•	    .Join{
•	        flex-direction: column;
•	        gap: 1rem;
•	    }
•	    .left-j{
•	        font-size: x-large;
•	        flex-direction: column;
•	    }
•	    .right-j{
•	        padding: 2rem;
•	    }
•	}•	

•	Plans
o	JSX
•	import React from "react";
•	import { plansData } from "../../data/plansData";
•	import whiteTick from "../../assets/whiteTick.png";
•	import "./Plans.css";
•	const Plans = () => {
•	  return (
•	    <div className="plans-container" id="plans">
•	      <div className="blur plans-blur-1"></div>
•	      <div className="blur plans-blur-2"></div>
•	      <div className="programs-header" style={{ gap: "2rem" }}>
•	        <sapn className="stroke-text">READY TO START</sapn>
•	        <sapn>YOUR JOURNEY</sapn>
•	        <sapn className="stroke-text">NOW WITHUS</sapn>
•	      </div>
•	      {/* plans card */}
•	      <div className="plans">
•	        {plansData.map((plan, i) => (
•	          <div className="plan">
•	            {plan.icon}
•	            <span>{plan.name}</span>
•	            <span>$ {plan.price}</span>
•	            <div className="features">
•	              {plan.features.map((feature, i) => (
•	                <div className="feature">
•	                  <img src={whiteTick} alt="" />
•	                  <span key={3}>{feature}</span>
•	                </div>
•	              ))}
•	            </div>
•	            <div>
•	              <span>See more benefits</span>
•	            </div>
•	            <button className="btn">Join Now</button>
•	          </div>
•	        ))}
•	      </div>
•	    </div>
•	  );
•	};
•	
•	export default Plans;•	•	

o	CSS
•	.plans-container{
•	    margin-top: -4ren;
•	    padding: 0.2rem;
•	    display: flex;
•	    flex-direction: column;
•	    gap: 4rem;
•	    position: relative;
•	
•	}
•	.plans{
•	    display: flex;
•	    align-items: center;
•	    justify-content: center;
•	    gap: 3rem;
•	}
•	.plan{
•	    display: flex;
•	    flex-direction: column;
•	    background: var(--caloryCard);
•	    color: white;
•	    gap: 2rem;
•	    padding: 1.5rem;
•	    width: 15rem;  
•	}
•	.plan:nth-child(2){
•	    background: var(--planCard);
•	    transform: scale(1.1);
•	}
•	.plan>svg{
•	    fill: var(--orange);
•	    width: 2rem;
•	    height: 2rem;
•	
•	}
•	.plan>:nth-child(2)
•	{
•	    font-size: 1rem;
•	    font-weight: bold;
•	}
•	.plan>:nth-child(3)
•	{
•	    font-size: 3rem;
•	    font-weight: bold;
•	}
•	.plan>:nth-child(5)
•	{
•	    font-size: 0.8rem;
•	}
•	.features{
•	    display: flex;
•	    flex-direction: column;
•	    gap: 1rem;
•	}
•	.feature{
•	    display: flex;
•	    align-items: center;
•	    gap: 1rem;
•	}
•	.feature>img{
•	    width: 1rem;
•	}
•	.plans>:nth-child(2)>svg{
•	    fill: white;
•	}
•	.plans>:nth-child(2)>button{
•	    color: var(--orange);
•	}
•	.plans-blur-1{
•	    width: 32rem;
•	    height: 23rem;
•	    top: 6rem;
•	    left: 0rem;
•	}
•	.plans-blur-2{
•	    width: 32rem;
•	    height: 23rem;
•	    top: 10rem;
•	    right: 0rem;
•	}
•	@media screen and (max-width: 768px){
•	    .plans{
•	        flex-direction: column;
•	
•	    }
•	    .plans>:nth-child(2){
•	        transform: none;
•	    }
•	}•	

•	Programs
o	JSX
•	import React from 'react'
•	import './Programs.css'
•	import {programsData} from '../../data/programsData'
•	import RightArrow from '../../assets/rightArrow.png'
•	const Programs = () => {
•	    return (
•	        <div className="Programs" id="programs">
•	            {/* header */}
•	            <div className="programs-header">
•	                <span className='stroke-text'>Explore our</span>
•	              <span>Programs</span>
•	                <span className='stroke-text'>to shape you</span>
•	            </div>
•	        <div className="program-categories">
•	            {programsData.map((program)=>(
•	                <div className="category">
•	                    {program.image}
•	                    <span>{program.heading}</span>
•	                    <span>{program.details}</span>
•	                    <div className="join-now">
•	                        <span>Join Now</span>
•	                        <img src={RightArrow} alt="" />
•	                    </div>
•	                </div>
•	            ))}
•	        </div>
•	        </div>
•	    )
•	}
•	
•	export default Programs•	•	

o	CSS
•	.Programs{
•	    display: flex;
•	    flex-direction: column;
•	    gap: 2rem;
•	    padding: 0 2rem;
•	}
•	.programs-header{
•	    display: flex;
•	    gap: 5rem;
•	    font-weight: bold;
•	    font-size: 3rem;
•	    justify-content: center;
•	    color: white;
•	    text-transform: uppercase;
•	    font-style: italic;
•	}
•	.program-categories{
•	    display: flex;
•	    /* padding: 0px 2rem; */
•	    gap: 1rem;
•	
•	}
•	.category{
•	    display: flex;
•	    flex-direction: column;
•	    background-color: gray;
•	    padding: 2rem;
•	    gap: 1rem;
•	    color: white;
•	    justify-content: space-around;
•	}
•	
•	.category>:nth-child(1){
•	    width: 2rem;
•	    height: 2rem;
•	    fill: white;
•	
•	}
•	.category>:nth-child(2){
•	    font-size: 1rem;
•	    font-weight: bold;
•	}
•	.category>:nth-child(3){
•	    font-size: 0.9rem;
•	    line-height: 25px;
•	}
•	.join-now{
•	    display: flex;
•	    gap: 2rem;
•	    align-items: center;
•	}
•	.join-now>img{
•	    width: 1rem;
•	
•	}
•	.category:hover{
•	    background: var(--planCard); 
•	    cursor: pointer;
•	}
•	
•	@media screen and (max-width: 768px){
•	    .programs-header{
•	        flex-direction: column;
•	        gap: 1rem;
•	        font-size: x-large;
•	        align-items: center;
•	        justify-content: center;
•	        margin-top: 2rem;
•	
•	    }
•	    .program-categories{
•	        flex-direction: column;
•	    }
•	}•	

•	Reasons
o	JSX
•	import React from "react";
•	import "./Reasons.css";
•	import image1 from "../../assets/image1.png";
•	import image2 from "../../assets/image2.png";
•	import image3 from "../../assets/image3.png";
•	import image4 from "../../assets/image4.png";
•	import nb from "../../assets/nb.png";
•	import adidas from "../../assets/adidas.png";
•	import nike from "../../assets/nike.png";
•	import tick from "../../assets/tick.png";
•	
•	const Reasons = () => {
•	  return (
•	    <div className="Reasons" id="reasons">
•	      <div className="left-r">
•	        <img src={image1} />
•	        <img src={image2} />
•	        <img src={image3} />
•	        <img src={image4} />
•	      </div>
•	      <div className="right-r">
•	        <span>some reasons</span>
•	        <div>
•	          <span className="stroke-text">why</span>
•	          <span> choose us?</span>
•	        </div>
•	        <div className="details-r">
•	          <div>
•	            <img src={tick} alt="" />
•	            <span>OVER 140+ EXPERT COACHS</span>
•	          </div>
•	          <div>
•	            <img src={tick} alt="" />
•	            <span>TRAIN SMARTER AND FASTER THAN BEFORE</span>
•	          </div>
•	          <div>
•	            <img src={tick} alt="" />
•	            <span>1 FREE PROGRAM FOR NEW MEMBERS</span>
•	          </div>
•	          <div>
•	            <img src={tick} alt=""></img>
•	            <span>RELIABLE PARTNERS</span>
•	          </div>
•	        </div>
•	        <span
•	          style={{
•	            color: "var(--gray)",
•	            fontWeight: "normal",
•	          }}
•	        >
•	          OUR PARTNERS
•	        </span>
•	        <div className="partners">
•	          <img src={nb} alt="" />
•	          <img src={adidas} alt="" />
•	          <img src={nike} alt="" />
•	        </div>
•	      </div>
•	    </div>
•	  );
•	};
•	
•	export default Reasons;•	•	

o	CSS
•	.Reasons {
•	    padding: 0 2rem;
•	    display: flex;
•	    gap: 2rem;
•	}
•	
•	.left-r {
•	    flex: 1;
•	    display: grid;
•	    grid-template-columns: repeat(3, 1fr);
•	    gap: 1rem;
•	    grid-auto-rows: 1fr;
•	
•	}
•	
•	.left-r>img {
•	    object-fit: cover;
•	}
•	
•	.left-r>:nth-child(1) {
•	    width: 12rem;
•	    grid-row: 1/3;
•	    height: 28rem;
•	}
•	
•	.left-r>:nth-child(2) {
•	    width: auto;
•	    height: 16rem;
•	    grid-column: 2/4;
•	}
•	
•	.left-r>:nth-child(3) {
•	    width: 14rem;
•	    grid-column: 2/3;
•	    grid-row: 2;
•	
•	}
•	
•	.left-r>:nth-child(4) {
•	    width: 10rem;
•	    grid-row: 2;
•	    grid-column: 3/4;
•	    height: 11.2rem;
•	}
•	
•	.right-r {
•	    flex: 1 1;
•	    text-transform: uppercase;
•	    gap: 1rem;
•	    display: flex;
•	    flex-direction: column;
•	
•	}
•	
•	.right-r>span {
•	    font: bold;
•	    color: var(--orange);
•	
•	}
•	
•	.right-r>div {
•	    color: white;
•	    font-size: 3rem;
•	    font-weight: bold;
•	}
•	
•	.details-r {
•	    display: flex;
•	    flex-direction: column;
•	    gap: 1rem;
•	}
•	
•	.details-r>div {
•	    display: flex;
•	    font-size: 1rem;
•	    gap: 1rem;
•	}
•	.details-r>div>img {
•	    width: 2rem;
•	    height: 2rem;
•	}
•	.partners{
•	    display: flex;
•	    gap: 1rem;
•	}
•	.partners>img{
•	    width: 2.5rem;
•	    
•	}
•	@media screen and (max-width: 768px){
•	    .Reasons{
•	        flex-direction: column;
•	    }
•	    .left-r{
•	        grid-auto-rows: auto;
•	        overflow: hidden;
•	    }
•	    .left-r>:nth-child(1){
•	        width: 7rem;
•	        height: 17rem;
•	    }
•	    .left-r>:nth-child(2){
•	        width: 15rem;
•	        height: 10rem;
•	    }
•	    .left-r>:nth-child(3){
•	        width: 7rem;
•	    }
•	    .left-r>:nth-child(4){
•	        width: 7rem;
•	        height: 6rem;
•	    }
•	}•	

•	Testimonials
o	JSX
•	import React from "react";
•	import "./Testimonials.css";
•	import { testimonialsData } from "../../data/testimonialsData";
•	import { useState } from "react";
•	import leftArrow from "../../assets/leftArrow.png";
•	import rightArrow from "../../assets/rightArrow.png";
•	import { motion, transform } from "framer-motion";
•	const Testimonials = () => {
•	  const transition = { type: "spring", duration: 3 };
•	  const [selected, setSelected] = useState(0);
•	  const tLength = testimonialsData.length;
•	  return (
•	    <div className="Testimonials" id="testimonials">
•	      <div className="left-t">
•	        <span>Testimonials</span>
•	        <span className="stroke-text">What they</span>
•	        <span>say about us</span>
•	        <motion.span
•	          key={selected}
•	          initial={{ opacity: 0, x: -100 }}
•	          animate={{ opacity: 1, x: 0 }}
•	          exit={{ opacity: 0, X: 100 }}
•	          transition={transition}
•	        >
•	          {testimonialsData[selected].review}
•	        </motion.span>
•	        <span>
•	          <span style={{ color: "var(--orange)" }}>
•	            {testimonialsData[selected].name}
•	          </span>{" "}
•	          ~{testimonialsData[selected].status}
•	        </span>
•	      </div>
•	      <div className="right-t">
•	        <motion.div
•	          initial={{ opacity: 0, x: -100 }}
•	          transition={{ ...transition, duration: 2 }}
•	          whileInView={{ opacity: 1, x: 0 }}
•	        ></motion.div>
•	        <motion.div
•	          initial={{ opacity: 0, x: 100 }}
•	          transition={{ ...transition, duration: 2 }}
•	          whileInView={{ opacity: 1, x: 0 }}
•	        ></motion.div>
•	        <motion.img
•	          key={selected}
•	          initial={{ opacity: 0, x: 100 }}
•	          animate={{ opacity: 1, x: 0 }}
•	          exit={{ opacity: 0, X: -100 }}
•	          transition={transition}
•	          src={testimonialsData[selected].image}
•	          alt=""
•	        />
•	        <div className="arrows">
•	          <img
•	            onClick={() => {
•	              selected === 0
•	                ? setSelected(tLength - 1)
•	                : setSelected((prev) => prev - 1);
•	            }}
•	            src={leftArrow}
•	            alt=""
•	          />
•	          <img
•	            onClick={() => {
•	              selected === tLength - 1
•	                ? setSelected(0)
•	                : setSelected((prev) => prev + 1);
•	            }}
•	            src={rightArrow}
•	            alt=""
•	          />
•	        </div>
•	      </div>
•	    </div>
•	  );
•	};
•	
•	export default Testimonials;•	•	

o	CSS
•	.Testimonials {
•	    display: flex;
•	    gap: 1rem;
•	    padding: 0 2rem;
•	}
•	
•	.left-t {
•	    display: flex;
•	    flex: 1 1;
•	    gap: 2rem;
•	    flex-direction: column;
•	    text-transform: uppercase;
•	    color: white;
•	}
•	
•	.left-t>:nth-child(1) {
•	    color: orange;
•	    font-weight: bold;
•	}
•	
•	.left-t>:nth-child(2),
•	.left-t>:nth-child(3) {
•	    font-weight: bold;
•	    font-size: 3rem;
•	}
•	
•	.left-t>:nth-child(4) {
•	    text-transform: none;
•	    text-align: justify;
•	    letter-spacing: 2px;
•	    line-height: 48px;
•	
•	}
•	
•	.right-t {
•	    flex: 1;
•	    position: relative;
•	}
•	
•	.right-t>img {
•	    position: absolute;
•	    width: 17rem;
•	    height: 20rem;
•	    object-fit: cover;
•	    right: 8rem;
•	    top: 2rem;
•	
•	}
•	
•	.right-t>:nth-child(1) {
•	    position: absolute;
•	    width: 17rem;
•	    height: 20rem;
•	    border: 2px solid orange;
•	    background-color: transparent;
•	    right: 9rem;
•	    top: 0.9rem;
•	}
•	
•	.right-t>:nth-child(2) {
•	    position: absolute;
•	    width: 17rem;
•	    height: 19rem;
•	    right: 7rem;
•	    top: 4rem;
•	    background: var(--planCard);
•	
•	}
•	
•	.arrows {
•	    display: flex;
•	    gap: 1rem;
•	    position: absolute;
•	    bottom: 1rem;
•	    left: 3rem;
•	
•	}
•	.arrows>img {
•	    width: 1.5rem;
•	    cursor: pointer;
•	}
•	@media screen and (max-width: 768px){
•	    .Testimonials{
•	        flex-direction: column;
•	    }
•	    .left-t>:nth-child(2),.left-t>:nth-child(3){
•	        font-size: xx-large;
•	
•	    }
•	    .right-t{
•	        display: flex;
•	        flex-direction: column;
•	        align-items: center;
•	        justify-content: center;
•	        gap: 2rem;
•	    }
•	    .right-t>div{
•	        position: relative;
•	        display: none;
•	    }
•	    .right-t>img{
•	        top: 0;
•	        right: 0;
•	        position: relative;
•	        align-self: center
•	    };
•	    .right-t>:last-child{
•	        display: block;
•	        bottom: 0;
•	        left: 0;
•	        
•	    }
•	}   •	

