<!DOCTYPE html>
	<html lang="en">
		<head><title>SINSOKE.WEB</title>
			<link rel="stylesheet" type="text/css" href="css.css">
				<meta charset="utf-8">
				<meta name ="viewport" content="widht=device-widht, initial-scale=1">
	</haed>

	<body>
		<div class="tgl">
			<div id="demo"></div>

<script>
var d = new Date();
document.getElementById("demo").innerHTML = d.toString();
</script>

</div>
		</div>

		<div class="row">
		<div class="column side"><center>:</center></div>
					<div class="column middle">
						<div class="header">
							<h1><p>SINSOKE.WEB</p></h1>
						</div>

			<div class="topnav">
			<div id="myBtnContainer">
  				<button class="btn active" onclick="filterSelection('all')"> Show all</button>
  				<button class="btn" onclick="filterSelection('Action')"> Action</button>
  				<button class="btn" onclick="filterSelection('Romance')"> Romance</button>
  				<button class="btn" onclick="filterSelection('Comedy')"> Comedy</button>
  				<button class="btn" onclick="filterSelection('Adventure')"> Adventure</button>
  				<button class="btn" onclick="filterSelection('Fantasy')"> Fantasy</button>
			<div class="tan"><a href="index.html"><img src="h.png" width="100%" height="100%"></a></div>
      </div>

			</div>
						

						<div class="column content">
							<p><div class="container">
  								<a href="daftarsl.html"><div class="filterDiv Action Fantasy">
  								<img src="sl.jpg" width="100%" height="100%">Solo leveling</div></a>
  								
  								<a href="daftarts.html"><div class="filterDiv Comedy Fantasy">
                  <img src="ts.jpg" width="100%" height="100%">Tensei Shitara Slime Datta Ken</div></a>
  						
                  <a href="daftartfd.html"><div class="filterDiv Comedy Romance Adventure">
                  <img src="tfd.jpg" width="100%" height="100%">Tales of Demons and Gods</div></a>

                  <a href="cs.html"><div class="filterDiv">
                  <img src="cs.jpg" width="100%" height="100%">Coming Soon</div></a>

                  <a href="cs.html"><div class="filterDiv">
                  <img src="cs.jpg" width="100%" height="100%">Coming Soon</div></a>

                  <a href="cs.html"><div class="filterDiv">
                  <img src="cs.jpg" width="100%" height="100%">Coming Soon</div></a>

                  <a href="cs.html"><div class="filterDiv">
                  <img src="cs.jpg" width="100%" height="100%">Coming Soon</div></a>

                  <a href="cs.html"><div class="filterDiv">
                  <img src="cs.jpg" width="100%" height="100%">Coming Soon</div></a>

                  <a href="cs.html"><div class="filterDiv">
                  <img src="cs.jpg" width="100%" height="100%">Coming Soon</div></a>

                  <a href="cs.html"><div class="filterDiv">
                  <img src="cs.jpg" width="100%" height="100%">Coming Soon</div></a>
                  
                  <a href="cs.html"><div class="filterDiv">
                  <img src="cs.jpg" width="100%" height="100%">Coming Soon</div></a>
                  
                  <a href="cs.html"><div class="filterDiv">
                  <img src="cs.jpg" width="100%" height="100%">Coming Soon</div></a>


              <br>
						<br>

						</div>

<script>
filterSelection("all")
function filterSelection(c) {
  var x, i;
  x = document.getElementsByClassName("filterDiv");
  if (c == "all") c = "";
  for (i = 0; i < x.length; i++) {
    w3RemoveClass(x[i], "show");
    if (x[i].className.indexOf(c) > -1) w3AddClass(x[i], "show");
  }
}

function w3AddClass(element, name) {
  var i, arr1, arr2;
  arr1 = element.className.split(" ");
  arr2 = name.split(" ");
  for (i = 0; i < arr2.length; i++) {
    if (arr1.indexOf(arr2[i]) == -1) {element.className += " " + arr2[i];}
  }
}

function w3RemoveClass(element, name) {
  var i, arr1, arr2;
  arr1 = element.className.split(" ");
  arr2 = name.split(" ");
  for (i = 0; i < arr2.length; i++) {
    while (arr1.indexOf(arr2[i]) > -1) {
      arr1.splice(arr1.indexOf(arr2[i]), 1);     
    }
  }
  element.className = arr1.join(" ");
}

// Add active class to the current button (highlight it)
var btnContainer = document.getElementById("myBtnContainer");
var btns = btnContainer.getElementsByClassName("btn");
for (var i = 0; i < btns.length; i++) {
  btns[i].addEventListener("click", function(){
    var current = document.getElementsByClassName("active");
    current[0].className = current[0].className.replace(" active", "");
    this.className += " active";
  });
}


</script></p>


		</div>
			<div class="column menu">	
			<input type="text" id="myInput" onkeyup="myFunction()" placeholder="Search for names.." title="Type in a name">
      <div class="column menu2">
			<ul id="myUL">
        <li><a href="tfdc2.html">Tales of Demons and Gods vol: 2</a></li>
        <li><a href="tfdc1.html">Tales of Demons and Gods vol: 1</a></li>
        <li><a href="slc3.html">solo Leveling vol: 3</a></li>
        <li><a href="tsc1.html">Tensei Shitara Slime Datta Ken vol: 1</a></li>
        <li><a href="tscprolog.html">Tensei Shitara Slime Datta Ken vol: 0</a></li>
        <li><a href="slc2.html">solo Leveling vol: 2</a></li>
        <li><a href="slc1.html">Solo Leveling vol: 1</a></li>

			</ul>

<script>
function myFunction() {
    var input, filter, ul, li, a, i, txtValue;
    input = document.getElementById("myInput");
    filter = input.value.toUpperCase();
    ul = document.getElementById("myUL");
    li = ul.getElementsByTagName("li");
    for (i = 0; i < li.length; i++) {
        a = li[i].getElementsByTagName("a")[0];
        txtValue = a.textContent || a.innerText;
        if (txtValue.toUpperCase().indexOf(filter) > -1) {
            li[i].style.display = "";
        } else {
            li[i].style.display = "none";
        }
    }
}
</script>
</div>
</div>
</div>
		<div class="column side"><center>:</center></div>
		</div>

		<div class="footer">
		Copyright@WildanIbnuSina
		</div>
	
</body>		
</html>
