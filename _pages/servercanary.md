---
layout: archive
title: "Server Canary"
permalink: /servercanary/
author_profile: false
sitemap: false
header: 
   image: "/assets/images/server-canary-header-background.jpg" 
---

<style>
* {box-sizing: border-box;}
body {font-family: Verdana, sans-serif;}
.mySlides {display: none;}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  height: 10px;
  width: 10px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 4s;
  animation-name: fade;
  animation-duration: 4s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}
</style>

<p style="font-size:0.80em; margin-top:0; margin-bottom: 0;">
Server Canary monitors your server(s) and notifies any assigned contacts as soon as we detect that your server is unresponsive.
This could be useful for when your website becomes unreachable on the internet.
Getting notified as soon as possible, so that you can take action, which can be misson critical for your business!
</p>

<h2>Contents</h2>
<ul style="font-size:0.80em;">
  <li><a href="#1">Details</a></li>
  <li><a href="#2">Screenshots</a></li>
</ul>

<br>
<hr>

<div id="1"></div>
<h4>Details</h4>
<p style="font-size:0.80em; margin-top:0; margin-bottom: 0;">
The Global Anomaly Project Hub is a place where people can report / analyse data on all manner of anomalous events.
Types of data / anomalies covered are: - 
- Animal Mutilations 
- Cryptids 
- Ghosts & Hauntings 
- Military Bases 
- Nuclear Facilities 
- UFO & Alien Encounters 
- Urban Legends 
</p>
<ul style="font-size:0.80em;">
    <li>Free to use</li>
    <li>Filterable data to narrow down results</li>
    <li>Ability to add you own anomalous event</li>
    <li>Forum to encourage discussions and to bring community togther</li>
    <li>Merchandise</li>
</ul>

<div id="2"></div>
<h4>Screenshots</h4>

<div class="slideshow-container">

<div class="mySlides fade"><div class="numbertext">1 / 8</div><img src="/assets/slideshows/servercanary/slide-1.png" style="width:100%"><div class="text"></div></div>
<div class="mySlides fade"><div class="numbertext">2 / 8</div><img src="/assets/slideshows/servercanary/slide-2.png" style="width:100%"><div class="text"></div></div>
<div class="mySlides fade"><div class="numbertext">3 / 8</div><img src="/assets/slideshows/servercanary/slide-3.png" style="width:100%"><div class="text"></div></div>
<div class="mySlides fade"><div class="numbertext">4 / 8</div><img src="/assets/slideshows/servercanary/slide-4.png" style="width:100%"><div class="text"></div></div>
<div class="mySlides fade"><div class="numbertext">5 / 8</div><img src="/assets/slideshows/servercanary/slide-5.png" style="width:100%"><div class="text"></div></div>
<div class="mySlides fade"><div class="numbertext">6 / 8</div><img src="/assets/slideshows/servercanary/slide-6.png" style="width:100%"><div class="text"></div></div>
<div class="mySlides fade"><div class="numbertext">7 / 8</div><img src="/assets/slideshows/servercanary/slide-7.png" style="width:100%"><div class="text"></div></div>
<div class="mySlides fade"><div class="numbertext">8 / 8</div><img src="/assets/slideshows/servercanary/slide-8.png" style="width:100%"><div class="text"></div></div>

</div>

<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 4000); // Change image every 2 seconds
}
</script>
