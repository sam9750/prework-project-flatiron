# prework-project
<!DOCTYPE html>
<html>
<head>
</head>
<body>

<h2>Welcome to Color Toggle!</h2>
<p>Toggle colors below.</p>

<button onclick="aFunction()">Red</button>
<button onclick="bFunction()">Orange</button>
<button onclick="cFunction()">Yellow</button>
<button onclick="dFunction()">Green</button>
<button onclick="eFunction()">Blue</button>
<button onclick="fFunction()">Purple</button>
<button onclick="gFunction()">Violet</button>


<script>
function aFunction() {
   var element = document.body;
   element.classList.toggle("red");
}
function bFunction() {
   var element = document.body;
   element.classList.toggle("orange");
}
function cFunction() {
   var element = document.body;
   element.classList.toggle("yellow");
}
function dFunction() {
   var element = document.body;
   element.classList.toggle("green");
}
function eFunction() {
   var element = document.body;
   element.classList.toggle("blue");
}
function fFunction() {
   var element = document.body;
   element.classList.toggle("indigo");
}
function gFunction() {
   var element = document.body;
   element.classList.toggle("violet");
}

</script>

</body>
</html>
