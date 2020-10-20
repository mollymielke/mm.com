
<!DOCTYPE html>
<html lang="en">
<head>

  <!-- Basic Page Needs
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <meta charset="utf-8">
  <title>Molly Mielke</title>
  <meta name="description" content="Molly Mielke is a product designer."
  <meta name="author" content="">

  <!-- Mobile Specific Metas
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- CSS
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  
  <link rel="stylesheet" href="skeleton.css">
  <link rel="stylesheet" href="main.css">
  <link rel="stylesheet" href="animate.css">
  <link rel="stylesheet" href="normalize.css">

  <!-- Favicon
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <link rel="icon" type="image/png" href="Favicon 32.png">

  <!-- jsQuery
    –––––––––––––––––––––––––––––––––––––––––––––––––– -->

</head>
<body>
  <div class="container">

  <!-- Primary Page Layout
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
     <!-- Draggable DIV 1 -->
     <!-- 
     <div id="mydiv">
      <div id="mydivheader"></div>
      <img src="Favicon 256.png" alt="NYC" width="50" height="50">
    </div>

  <!-- Draggable js
<script>
    dragElement(document.getElementById("mydiv"));

    function dragElement(elmnt) {
      var pos1 = 0, pos2 = 0, pos3 = 0, pos4 = 0;
      if (document.getElementById(elmnt.id + "header")) {
        // if present, the header is where you move the DIV from:
        document.getElementById(elmnt.id + "header").onmousedown = dragMouseDown;
      } else {
        // otherwise, move the DIV from anywhere inside the DIV: 
        elmnt.onmousedown = dragMouseDown;
      }
    
      function dragMouseDown(e) {
        e = e || window.event;
        e.preventDefault();
        // get the mouse cursor position at startup:
        pos3 = e.clientX;
        pos4 = e.clientY;
        document.onmouseup = closeDragElement;
        // call a function whenever the cursor moves:
        document.onmousemove = elementDrag;
      }
    
      function elementDrag(e) {
        e = e || window.event;
        e.preventDefault();
        // calculate the new cursor position:
        pos1 = pos3 - e.clientX;
        pos2 = pos4 - e.clientY;
        pos3 = e.clientX;
        pos4 = e.clientY;
        // set the element's new position:
        elmnt.style.top = (elmnt.offsetTop - pos2) + "px";
        elmnt.style.left = (elmnt.offsetLeft - pos1) + "px";
      }
    
      function closeDragElement() {
        // stop moving when mouse button is released:
        document.onmouseup = null;
        document.onmousemove = null;
      }
    }
  </script>
–––––––––––––––––––––––––––––––––––––––––––––––––– -->

<!-- Nav bar
<div class="navbar">
  <img src="Favicon 32.png" alt="NYC" width="14" height="14">
  <h3>Molly Mielke</h3>
  <h3>Writing</h3>
</div>
–––––––––––––––––––––––––––––––––––––––––––––––––– -->

<body class="night">
  <div class="spacer48"></div>


  <div class="six columns">
    <div class="animated fadeIn one">
    <h4>Hello, I'm</h4>
  </div>
</div>

  <div class="six columns">
    <div class="animated fadeIn one">
    <div class="myDIV"><div id = "jumbo header">Molly Mielke.</div></div>
    <div class="hide">
      <div id = "self">
        </div>
    </div>
  </div>

  </div>
<div class = "four columns offset-by-two">
  <div class="animated fadeIn two">
      <h2><a href="https://www.twitter.com/mollyfmielke" target="_blank" id = "hover">Twitter</a></h2>
      <br>
      <h2><a href="linkedin.com/in/mollymielke" target="_blank" id = "hover">LinkedIn</a></h2>
      <br>
      <h2><a href="https://medium.com/@mollymielke" target="_blank" id = "hover">Medium</a></h2>
      <br>
      <div class="spacer48"></div>
      <div class="spacer48"></div>
      <div class="spacer48"></div>
      <div class="spacer48"></div>
</div>

</div>

<div class="six columns">
  <div class="animated fadeIn three">

    <p>I&#x27;m a product designer driven by a passion for untangling complex problems and exploring how systems, strategy, and thoughtfulness can craft tools that empower us to create. 
         
        <br> <br>
        
        I&#x27;m presently studying digital media &amp; entrepreneurship at UCLA, writing my thesis on creativity + digital tools, and living in Sonoma. In my logged off hours, I enjoy directing films and tinkering with electronics and code.
         <br> 
         <p>
        Want to chat? Drop me a note m@mollymielke.com</p></div></div>

<div class = "four columns offset-by-two">
    <div class="animated fadeIn three">    
      <h2><a href="https://figma.com/" target="_blank" id="hover">Figma</a></h2> <br>
      <h4>intern, former fellow</h4>
    </div>

    <div class="animated fadeIn three">      
      <h2><a href="https://peakdesign.com/" target="_blank" id="hover">Peak Design</a></h2> <br>
      <h4>junior graphic designer</h4>
    </div>

    <div class="animated fadeIn three">      
      <h2 id = "no">Something new</a></h2> <br>
      <h4>product design intern</h4>
    </div>

    <div class="animated fadeIn three">      
      <h2><a href="https://discovery.com/" target="_blank" id="hover">Discovery</a></h2> <br>
      <h4>product design intern</h4>
    </div>

    <div class="animated fadeIn three">      
      <h2><a href="https://theentireworld.com/" target="_blank" id="hover">Entireworld</a></h2> <br>
      <h4>graphic design intern</h4>
    </div>

    <div class="animated fadeIn three">      
      <h2><a href="https://volitionbeauty.com/" target="_blank" id="hover">Volition Beauty</a></h2> <br>
      <h4>designer</h4>
    </div>
</div>

      <div class="spacer48"></div>

</div>
</body>

<!-- Copy and past
<script type="text/javascript" src="https://milankyncl.github.io/jquery-copy-to-clipboard/jquery.copy-to-clipboard.js"></script>
<script>
$('input#coup-field').val('m@mollymielke.com');
$("input#coup-field").prop('readOnly', true);
$('input#coup-field').css( 'cursor', 'text' );

$(document).ready(function() {
  $('#copy-btn').CopyToClipboard();
  $('.copy-btn').click(function(){
    $('.copy-btn').html('Copied!');
    $('.copy-btn').css('background-color', '#');
    setTimeout(function() { 
      $('.copy-btn').html('Email')
      $('.copy-btn').css('background-color', '#')
    }, 2000);
  });
});
</script>
–––––––––––––––––––––––––––––––––––––––––––––––––– -->





<!-- End Document
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
</body>
</html>
