https://jsfiddle.net/ "JSFiddle - Code Playground"
https://www.w3schools.com/howto/default_page6.asp "W3Schools How TO - Code snippets for HTML, CSS and JavaScript"
https://www.w3schools.com/w3css/tryit.asp?filename=tryw3css_templates_parallax&stacked=h "Tryit Editor v3.6"





<div class="titleMessage">

    <div class="heading">

        <p class="main"><span>REALLY REALLY REALLY LONG NAME HERE</span></p>
        <p class="sub"><span>Software Engineer</span></p>

    </div>
</div>

.titleMessage {
    position: absolute;
    width: 100%;
    height: 250px;
    top: 50%;
    z-index: 5;
    text-align: center;
    margin-top: -125px;
}


.titleMessage .heading p{
    color:  #080808;
    text-shadow: 0px 2px 5px rgba(0,0,0,0.4);
    font-weight: 100;
    letter-spacing: 7px;
}
.titleMessage .heading p span{
    background: #F5F5F5; 
    padding: 6px 12px 0;
}
.titleMessage .heading .main{
    font-size: 50px; 
}


.titleMessage .heading .sub{
    font-size: 23px; 
}

-------------------------------------------------

 https://developers.google.com/web/tools/chrome-devtools/javascript/snippets "Run Snippets Of JavaScript On Any Page With Chrome DevTools"
 https://stackoverflow.com/questions/56728055/html-css-adjust-background-rectangle-on-text-so-it-does-not-span-entire-webpa "HTML & CSS: Adjust background rectangle on text so it does not span entire webpage - Stack Overflow"
 https://jsfiddle.net/ "JSFiddle - Code Playground"
 https://css-tricks.com/methods-contrasting-text-backgrounds/ "Methods for Contrasting Text Against Backgrounds | CSS-Tricks"
 https://www.w3.org/Style/Examples/007/center.en.tmpl "CSS: centering things"
 https://www.html5rocks.com/en/tutorials/shapes/getting-started/ "Getting Started with CSS Shapes: Wrapping content around custom paths - HTML5 Rocks"
 https://spin.atomicobject.com/2015/07/14/css-responsive-square/ "How to Create a Responsive Square with CSS"

div {
    text-align:justify;  
    text-justify:auto;
}


<style>
div.a {
  text-align: center;
}

div.b {
  text-align: left;
}

div.c {
  text-align: right;
} 

div.d {
  text-align: justify;
} 
</style>
 https://www.w3schools.com/cssref/tryit.asp?filename=trycss_text-align "Tryit Editor v3.6"




<style>
div.a {
  width: auto;
  border: 1px solid black;
}

div.b {
  width: 150px;
  border: 1px solid black;  
}

div.c {
  width: 50%;
  border: 1px solid black;  
}
</style>
 https://www.w3schools.com/cssref/tryit.asp?filename=trycss_dim_width "Tryit Editor v3.6"


CSS Properties
align-content
align-items
align-self
all

<!DOCTYPE html>
<html>
<head>
<style> 
#main {
  width: 220px;
  height: 300px;
  border: 1px solid black;
  display: flex;
  align-items: flex-start;
}

#main div {
  flex: 1;
}

#myBlueDiv {
  align-self: center;
}
</style>
</head>
<body>

<div id="main">
  <div style="background-color:coral;">RED</div>
  <div style="background-color:lightblue;" id="myBlueDiv">BLUE</div>  
  <div style="background-color:lightgreen;">Green div with more content.</div>
</div>

<p><b>Note:</b> The align-self property overrides the container's align-items property.</p>

<p><b>Note:</b> Internet Explorer 10 and earlier versions do not support the align-self property.</p>

</body>
</html>
 https://www.w3schools.com/cssref/tryit.asp?filename=trycss3_align-self "Tryit Editor v3.6"


 https://www.w3schools.com/cssref/tryit.asp?filename=trycss3_align-self "Tryit Editor v3.6"

 Flex
 https://www.w3schools.com/cssref/playit.asp?filename=playcss_align-content&preval=stretch "Playit"
 https://www.w3schools.com/cssref/tryit.asp?filename=trycss3_align-content "Tryit Editor v3.6"
 https://www.w3schools.com/cssref/css3_pr_align-content.asp "CSS align-content property"
