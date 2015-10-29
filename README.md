# Css-challenge-10-29-15
#css
h1{
	color:blue;
	background-color: blue;


}
.green {
	height:100px;
	width:800px;
	background: green;
	float:left;
	margin: 5px;
}

.purple {
	height:50px;
	width:110px;
	background: purple;
	margin-left: 345px;
	margin-top: 75px;
}
 .red {
 	height:200px;
 	width:800px;
 	background: red;
 	float: left;
 	margin: 5px;

 }

 .white {
 	height: 900px;
 	width: 800px;
 	margin: 5px;
 	
 }
 .yellow {
 	height:400px;
 	width:25%;
 	background: yellow;
 	float:left;
 	display: inline-block;

 	
 }
 .orange {
 	height:400px;
 	width: 25%;
 	background: orange;
 	float:left;
 	display: inline-block;
 }

  .blue { 
  	height:400px;
  	width:50%;
  	background: blue;
  	float:left;
  	display: inline-block;
  	
  }
  .black {
  	height:150px;
  	width:800px;
  	background: black;
  	float: left;
  	margin-top: 5px;
  }
  .wrap {
  	height: 300px;
  }



  @media only screen and (max-width: 700px) {
  	.yellow {
  		width: 100%;
  		height: 100px;
  	}

  	.blue {
  		width: 100%;
  		height: 150px;
  	}

  	.orange { 
  		width: 100%;
  		height: 100px;
  	}
  }
#html
<html>
	<head>
		<link rel="stylesheet" type="text/css" href="new.css">

		
			
		
	</head>
	<body>
		<!-- <div class = "purple"> 
		</div> -->
	<div class = "wrap">
		<div class = "green">
		</div>
		<div class = "red"> <div class = "purple">
		</div>
		</div>
	</div>
	<div class = "white">
		<div class = "yellow">
		</div>
		<div class = "blue">
		</div>
		<div class = "orange" >
		</div>
		<div class = "black">
	</div>
	</body>
</html>
