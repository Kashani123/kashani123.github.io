<!DOCTYPE html>
<html>
<head>
	<title>Resume of Javed Kashani page 1</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<style>
.body {
   background-color: green; 
    
}
/* Header section styling */
#header h1 {
    text-align: center;
}
/* Header section styling */
#header h2 {
    text-align: center;
}
/* Header section styling */
.header {
	text-align: center;
}

/* Container div  */
.container {
	
    background-color: #FFFFFF; 
    display: flex;
    justify-content: center;
    text-align: center;
	width: 100%;
    height: 100vh;
	border: 1px solid black;

	
}
	
	
/* left div */
.Left-div {
	background-color: #FFC0CB;
	border: 1px solid black;
}
/* center div */
.center-div{
	background-color: #FF0000;  
border: 1px solid black;	
}

/* right div */
.right-div {
    background-color: #FFFF00;
	border: 1px solid black;
}


/* email styling */
.email {
	text-align: center;
	border: 1px solid black;
}
/* Use a media query to add a breakpoint at 575px: */
	@media screen and (max-width: 575px) {
	.container {
		display: block;
        height: auto;
		
	}
	
		
	}
/* Use a media query to add a breakpoint at 575px: */
	@media screen and (max-width: 575px) {
	.Left-div, .center-div, .right-div {
	float: none;	
    width: 90%; /* The width is 90%, when the viewport is 800px or smaller */
    text-align: center;
	margin: auto;
	border: 1px solid black;
  }
	}
  
  
  


	
</style>

<body>

	<!-- Header div -->
    <div id="header">
        <h1> 
		
		Resume of Javed Kashani
		
		</h1>
    </div>

	<!-- Navigation links -->
    <div id="nav">
        <a href="work.html" Work Experience</a>
        <a href="education.html" Educational Experience</a>
        <a href="skills.html" Related Awards and Skills</a>
    </div>

	<div class="buffer-div"> 
	
	<div class="container">
		<div class="Left-div">Work Experience
		<h1>Other pages</h1>
		
		<ul>
                    <li><a href="work.html" title= "Work Page" >Work Experience</a></li>
                    <li><a href="education.html" title= "Education" >Educational Experience</a></li>
                    <li><a href="skills.html" title= "Skills">Related Awards and Skills</a></li>
                </ul>
		</div>
		
		<div class="center-div">Placeholder for EDU
		<h1>Education</h1>
                <p>Placeholder text for Education Details.</p>
                
		</div>
		
		<div class="right-div"> Placeholder for Skills
		
		<h1>Skills</h1>
            <p>Placeholder text for skills and abilities.</p
		
		</div>
		
	</div>
	</div>
	
	<div class = "email">
	<a href="mailto:jkashani@albany.edu">Email me</a>
	</div>

</body>



</html>
