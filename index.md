---
title: 
layout: page
modified: 2014-07-31T13:23:02.362000-04:00
excerpt: 
---

<!--
{% include _scripts.html %}
-->

<!--![x](/images/Einstein.jpg)
-->
<!--
<script type="text/javascript">
var col = new String();
var x=1;var y;

function blink()
{
 if(x%2) 
 {
  col = "rgb(255,0,0)";
 }else{
  col = "rgb(255,255,255)";
 }

 aF.style.color=col;x++;if(x>2){x=1};setTimeout("blink()",500);
}
</script>
-->


<style>
mark { 
    background-color: #D40000;
    color: white;
}
</style>


<script type="text/javascript">
var col = new String();
var x=1;var y;

function blink()
{
 if(x%2) 
 {
  col = "rgb(0,0,0)";
 }else{
  col = "rgb(255,255,255)";
 }

 aF.style.color=col;x++;if(x>2){x=1};setTimeout("blink()",500);
}
</script>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-64829092-1', 'auto');
  ga('send', 'pageview');

</script>




<script type = "text/javascript">
$(document).ready(function(){
  //Take your div into one js variable
  var div = $("#divToShowHide");
  //Take the current position (vertical position from top) of your div in the variable
  var pos = div.position();
  //Now when scroll event trigger do following
  $(window).scroll(function () {
   var windowpos = $(window).scrollTop();
   //Now if you scroll more than 100 pixels vertically change the class to AfterScroll
   // I am taking 100px scroll, you can take whatever you need
   if (windowpos >= (pos.top - 100)) {
     div.addClass("AfterScroll");
   }
   //If scroll is less than 100px, remove the class AfterScroll so that your content will be hidden again 
   else {
     s.removeClass("AfterScroll");
   }
   //Note: If you want the content should be shown always once you scroll and do not want to hide it again when go to top agian, no need to write the else part
 });
});
</script>










<html>



<head>
<style>

html {
  scroll-behavior: smooth;
  height: 100%;
}

#section1 {

  height: 700px;
  line-height: 700px;
  background-color: white;
}

#section2 {
  height: 800px;
  background-color: white;
}
</style>

</head>



<head>


<style>


    body{
      min-height: 100%;
      background: white;
      background-size: cover;
      font-family: 'Trebuchet MS', sans-serif; 
    }
    .container{
      display: inline-block;
    }
    .typed-out{
      overflow: hidden;
      border-right: .15em white;
      white-space: nowrap;
      animation: 
      typing 2s steps(20, end) forwards;
      animation-delay: 1s; 
      blinkTextCursor 500ms;
      font-size: 6rem;
      width: 0;
    }

    .typed-out-2{
      overflow: hidden;
      border-right: .15em white;
      white-space: nowrap;
      animation: 
      animation-delay: 5s; 
      font-size: 2rem;
      width: 0;
    }
    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

  </style>


  <style>

  .BeforeScroll
{
  height: 100px; /*Whatever you want*/
  width: 100%; /*Whatever you want*/
  .
  .
  display: none;
}


/*Use this class when you want your content to be shown after some scroll*/
.AfterScroll
{
  height: 100px; /*Whatever you want*/
  width: 100%; /*Whatever you want*/
  .
  .
  display: block;
}

</style>

  </head>

<body>






<h1> </h1>

<div class="main" id="section1">
  <h1>

  </h1>


<div style="text-align:center">
<div class="container">
  <div class="typed-out">
    From My Pocket,
  </div>
</div>
</div>

</div>






<div class="main" id="section2">

  <h2>  </h2>
  


<div style="text-align:center">
<div class="container">


<div id = "divToShowHide" class = "BeforeScroll">

  <p style="text-align:center">we aim to: </p>


  <br>

  <p style="text-align:center">(1) identify disease status <strong>early</strong>.</p>

  <p style="text-align:center">(2) estimate disease severity <strong>faithfully</strong>.</p>

  <p style="text-align:center">(3) monitor disease changes <strong>longitudinally</strong>.</p>

  <br>

  <p style="text-align:center">So we create <strong>algorithms</strong>, <strong>analyses</strong>, and <strong>apps</strong>.</p>

 <p style="text-align:center">And we address (1)-(3) on small devices <strong>from the pocket.</strong></p>

  <br>
  <p style="text-align:center">One cannot achieve perfection. With diligence, imagination, and some luck, we may get closer to it.</p>

  <!--
  <br>
  <p style="text-align:center">From my pocket</p>
  -->


</div>

</div>

</div>

</div>

</body>

</html>









