<!DOCTYPE html>
	<html lang="en">
		<head><title>SINSOKE.WEB</title>
			<link rel="stylesheet" type="text/css" href="css.css">
				<meta name=”viewport” content=”width=device-width; initial-scale=1.0; maximum-scale=1.0;”>
        <meta http-equiv=”Content-Type” content=”text/html; charset=utf-8″ />
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
  				<button class="btn" onclick="filterSelection('Drama')"> Drama</button>
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
  						
                  <a href="daftarol.html"><abbr title="Overloard"><div class="filterDiv Fantasy" style="background-image: url('ol.jpg'); background-size: 100% 100%;"><div class="nama"><b>Overloard</b></div></div></abbr></a>

                  <a href="daftarsl.html"><abbr title="Solo leveling"><div class="filterDiv Action Fantasy" style="background-image: url('sl.jpg'); background-size: 100% 100%;"><div class="nama"><b>Solo leveling</b></div></div></abbr></a>

                  <a href="daftarsyk.html"><abbr title="Kono Yuusha ga Ore Tueee Kuse ni Shinchou Sugiru"><div class="filterDiv Comedy Adventure Fantasy" style="background-image: url('syk.jpg'); background-size: 100% 100%;"><div class="nama"><b>Shinchou Yuusha</b></div></div></abbr></a>

                  <a href="daftartfd.html"><abbr title="Tales of Demons and Gods"><div class="filterDiv Comedy Romance Adventure" style="background-image: url('tfd.jpg'); background-size: 100% 100%;"><div class="nama"><b>Tales of Demons and Gods</b></div></div></a>
                  
                  <a href="daftarts.html"><abbr title="Tensei Shitara Slime Datta Ken"><div class="filterDiv Comedy Fantasy" style="background-image: url('ts.jpg'); background-size: 100% 100%;"><div class="nama"><b>Tensei Shitara Slime Datta Ken</b></div></div></a>

                   <a href="cs.html"><abbr title="Belum Ada Bosqu"><div class="filterDiv" style="background-image: url('cs.jpg'); background-size: 100% 100%;"><div class="nama"><b>Coming Soon</b></div></div></abbr></a>

                   <a href="cs.html"><abbr title="Belum Ada Bosqu"><div class="filterDiv" style="background-image: url('cs.jpg'); background-size: 100% 100%;"><div class="nama"><b>Coming Soon</b></div></div></abbr></a>

                   <a href="cs.html"><abbr title="Belum Ada Bosqu"><div class="filterDiv" style="background-image: url('cs.jpg'); background-size: 100% 100%;"><div class="nama"><b>Coming Soon</b></div></div></abbr></a>

                   <a href="cs.html"><abbr title="Belum Ada Bosqu"><div class="filterDiv" style="background-image: url('cs.jpg'); background-size: 100% 100%;"><div class="nama"><b>Coming Soon</b></div></div></abbr></a>

                   <a href="cs.html"><abbr title="Belum Ada Bosqu"><div class="filterDiv" style="background-image: url('cs.jpg'); background-size: 100% 100%;"><div class="nama"><b>Coming Soon</b></div></div></abbr></a>

                   <a href="cs.html"><abbr title="Belum Ada Bosqu"><div class="filterDiv Drama" style="background-image: url('cs.jpg'); background-size: 100% 100%;"><div class="nama"><b>Coming Soon</b></div></div></abbr></a>

                   <a href="cs.html"><abbr title="Belum Ada Bosqu"><div class="filterDiv" style="background-image: url('cs.jpg'); background-size: 100% 100%;"><div class="nama"><b>Coming Soon</b></div></div></abbr></a>

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
      <div class="k"><center><p>
      <b style="color: black;">..::LIST UPDATE::..</b>
       </p></center></div>
			<input type="search" id="myInput" onkeyup="myFunction()" placeholder="Search for names.." title="Type in a name">
      <div class="column menu2">
			<ul id="myUL">
        <li><a href="olc1.3.html">Overloard vol: 1.3</a></li>
        <li><a href="olc1.2.html">Overloard vol: 1.2</a></li>
        <li><a href="olc1.1.html">Overloard vol: 1.1</a></li>
        <li><a href="sykdc1.html">Shinchou Yuusha: Kono Yuusha ga Ore Tueee Kuse ni Shinchou Sugiru vol: 01</a></li>
        <li><a href="sykcprolog.html">Shinchou Yuusha: Kono Yuusha ga Ore Tueee Kuse ni Shinchou Sugiru vol: 00</a></li>
        <li><a href="tfdc2.html">Tales of Demons and Gods vol: 02</a></li>
        <li><a href="tfdc1.html">Tales of Demons and Gods vol: 01</a></li>
        <li><a href="slc3.html">solo Leveling vol: 03</a></li>
        <li><a href="tsc1.html">Tensei Shitara Slime Datta Ken vol: 01</a></li>
        <li><a href="tscprolog.html">Tensei Shitara Slime Datta Ken vol: 00</a></li>
        <li><a href="slc2.html">solo Leveling vol: 02</a></li>
        <li><a href="slc1.html">Solo Leveling vol: 01</a></li>

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
