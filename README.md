# car-insurance<html>
<head>
 <title>Vehicle Insurance</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <style>
    /* Remove the navbar's default margin-bottom and rounded borders */ 
    .navbar {
      margin-bottom: 0;
      border-radius: 0;
    }
    
    /* Set height of the grid so .sidenav can be 100% (adjust as needed) */
    .row.content {height: 450px}
    
    /* Set gray background color and 100% height */
    .sidenav {
      padding-top: 20px;
      background-color: #f1f1f1;
      height: 100%;
    }
    
    /* Set black background color, white text and some padding */
    footer {
      background-color: #555;
      color: white;
      padding: 15px;
    }
    
    /* On small screens, set height to 'auto' for sidenav and grid */
    @media screen and (max-width: 767px) {
      .sidenav {
        height: auto;
        padding: 15px;
      }
      .row.content {height:auto;} 
    }
hr { 
  display: block;
  margin-top: 1.5em;
  margin-bottom: 1.5em;
  margin-left: auto;
  margin-right: auto;
  border-style: inset;
  border-width: 5px;
} 
  </style>
</head>
<body bgcolor="gray">


  <nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#">Logo</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Home</a></li>
        <li><a href="#">Insurance Types</a></li>
        <li><a href="#">Policies</a></li>
        <li><a href="#">Claims</a></li>
		<li><a href="#">Plans</a></li>
		<li><a href="#">My Account</a></li>
      </ul>
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#"><span class="glyphicon glyphicon-log-in"></span> Login</a></li>
		<li><a href="#"><span class="glyphicon glyphicon-log-in"></span> Sign Up</a></li>
      </ul>
    </div>
  </div>
</nav>
  
<div class="container-fluid text-center">    
  <div class="row content">
    <div class="col-sm-2 sidenav">
      <p><a href="#">Liability Insurance</a></p>
      <p><a href="#">Collision Insurance</a></p>
      <p><a href="#">Personal Injury</a></p
	  <p><a href="#">Comprehensive Insurance</a></p>
	  
    </div>
    <div class="col-sm-8 text-left"> 
      <h1><center><u>VEHICLE INSURANCE MANAGEMENT</u>&#10004;</center></h1>
      <p>Your car gives you two things –  independence and freedom of movement. To further make your driving experience,
	  we also give you the third ingredient, peace of mind. With our car insurance stay protected and cruise without worries.
	  Loss of or Damage to the Vehicle Insured - The Company will indemnify the Insured against loss or damage to the vehicle insured hereunder 
	  and/or its accessories whilst thereon: (i) by fire, explosion self-ignition or lightning; (ii) by burglary, housebreaking or theft; 
	  (iii) by riot and strike; (iv) by earthquake (Fire and Shock Damage); (v) by flood, typhoon, hurricane, storm, tempest, inundation,
	  cyclone, hailstorm, frost; (vi) by accidental external means; (vii) by malicious act; (viii) by terrorist activity; 
	  (ix) whilst in transit by road rail inland - waterway lift elevator or air;(x) by landslide, rockslide. Subject to deduction 
	  for depreciation at the rates mentioned in policy wordings in respect of parts replaced<br><br><br><br><br>
	  </p>
<hr>
      <h3>Dashboard</h3>
	  <form>
   Recent Policy:<input type='text' name="Recent Policy">&nbsp 
   Product:<input type="text" name="Product">&nbsp 
   IDV:<input type="text" name="IDV"><br><br><br>
   <label for="birthday">Expiry Date:</label>
  <input type="date" id="Expiry Date" name="expiry date">
   <center><input type="submit" value="submit"></submit></center>
   </form>
      <hr>
      <h3>Buy a new policy</h3>
	  <form>
   Car Type:<input type='text' name="Car Type">&nbsp 
   Car Reg.no:<input type="text" name="Car Reg.no">&nbsp 
   Select Policy:<input type="text" name="Select Policy"><br><br><br>
   <center><input type="submit" value="submit"></submit></center>
   </form>
    </div>
    <div class="col-sm-2 sidenav">
      <div class="well">
        <img src="1.jpg" alt="1" style="width:200px;height:200px;">
      </div>
      <div class="well">
        <p><img src="2.jpg" alt="2" style="width:200px;height:200px;"></p>
      </div>
    </div>
  </div>
</div>

<footer class="container-fluid text-left">
  <p>About Us:</p>
  <p>Founder:NANDU KANAN<br>
  Co-Founder:DEEPAK PRADAN<br>
  General Manager:ABDURABB<br>
  Address:7th ARRONDISSEMENT, PARIS, FRANCE<br>
  Ph:+09998887776<br>
  e-mail:vehicleinsurance@management.com
  </footer>
</body>
</html>
