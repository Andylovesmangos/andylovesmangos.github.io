---
layout: default
title: Gallery
---

<button class = "butt" onclick="one()">1</button>
<button class = "butt" onclick="two()">2</button>
<button class = "butt" onclick="four()">4</button>

<br>
<div class = "row">
    <div class = "col">
        <img src='assets/images/howitbe.jpeg'>
        <img src='assets/images/andy.jpeg'>
    </div>
    <div class = "col">
        <img src='assets/images/Prom.jpeg'>
        <img src='assets/images/lewk.jpeg'>
    </div>
</div>


<script>
// Get the elements with class="column"
var elements = document.getElementsByClassName("col");

// Declare a "loop" variable
var i;

// Full-width images
function one() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.width = "100%";
  }
}

// Two images side by side
function two() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.width  = "70%";
  }
}

// Four images side by side
function four() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.width = "50%";
  }
}
</script>
