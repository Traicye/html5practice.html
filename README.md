<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=>, initial-scale=1.0">
    <title>Document</title>
<!--
<script> 
function allowDrop(ev) {
    ev.preventDefault();
}
function drag(ev) {
    ev.dataTransfer.setData ("text");
    ev.target.appendChild(document.getElemenById(data));
}</script> (i think these particular lines of code is causing my browser to load more slowly and it's causing 
it to hang. I tried creating draggable images. at this point in time, it's draggable even without putting this script in the head tag
At this current moment i do not have an understanding of java script. My question is: what is the relevance of these lines of code and what does it do)
-->
</head>
<body>
   <header> 
       <h1>most important and bigger writings</h1>
       <h3>Less important heading</h3>
   </header> 
   <nav>
       <ul><li><a href="www.aboutme.com">About us</a></li>
        <li><a href="www.dontdisturbme.com"> Fees</a></li>
        <li><a href="www.weareamazing.org">Financials</a></li>
    </ul>
   </nav>
   <article><h1> How your natural hair teaches you to love yourself</h1>
<p>There has been an increasing acceptance of the African hair into society</p>
</article>
<article>
    <h1> Heading</h1>
    <p>content or image</p></article>

    <article><h1> Gifts for everyone</h1>
    <p>This website will be the best place for choosing amazing gifts for your loved ones</p></article>
<aside><p>Gifts will be delivered to you within 24 hours</p></aside>
<audio src="audio.mp3" controls> Audio element not supported by your browser</audio> <br />

<audio controls autoplay><source src="audio.mp3" type="audio/mpeg"> <source src="audio.ogg" type="audio/ogg"></audio> <br />
<audio controls autoplay loop><source src="audio.mp3" type="audio/mpeg">
<source src="audio.ogg" type="audio/ogg"> Audio element 1is not supported by your browser</audio><br />
<video controls autoplay loop> <source src="video.mp4" type="video/mp4"> 
<source src="video.ogg" type="video/ogg"> Video is not supported by your browser</video> <br />
status:<progress min="0" max="100" value="35"></progress> 
<!--localStorage.setItem("key1", "value1")
//this will print the value
alert(localStorage.getItem("key1"));
localStorage.clear(); this is a comment. this particular code to create a local storage is deploying on the webpage as a text after the video embedded-->
<br />

 <!-- (what is being defined here and how do i create draggable images.
    What function does draggable images hold in a webpage. why should i create them?)
    <div id="box" ondrop="drop(event)"
ondragover="allowDrop(event)"
style="border:1px  solid black; width:200px; height:200px"></div> -->
<img id="image"  src="c:\Users\HELLO\Pictures\adidas.png"  draggable="true" 
ondragstart="drag(event)" width= "150" height= "150" 
 alt = "this is a picture of a logo" /> <!--this particular image is dragging, but it's not dropping anywhere-->

 <img src="c:\Users\HELLO\Pictures\adidas.png" alt="" height="300"/>
 <svg width="2000" height="2000"><circle cx="80" cy="80" r="50" fill="green" /> <svg />

 <!-- (this partcular shape is not showing in the browser. what could be the problem with the line of code)<svg width="2000" height="2000>
     <rect width="300" height="100" x="20" y="20" fill="green"/>
 </svg>-->

 <svg width="400" height="410">
     <line x1="10" y1="10" x2="200" y2="100"
     style="stroke:#000000; stroke-linecap: round; stroke-width: 20;" />
 </svg>

 <!--why are the svg properties displaying on each other in the browser?-->

 <svg width="2000" height="500"><polyline style="stroke-linejoin:miter; stroke: black; 
stroke-width: 12; fill: none;" points="100 100, 150 150, 200 100" /></svg>

<svg height="500" width="1000">
    <ellipse cx="200" cy="100" rx="150" ry="70" style="fill: green;"/>
</svg>
<svg width="2000" height="2000">
    <polygon points="100 100, 200 200, 300 0" style="fill: green; stroke: black;"/>
</svg>
</body>
<footer> <a href="www.myprivacypolicy.com">privacy policy</a></footer>
</html>
