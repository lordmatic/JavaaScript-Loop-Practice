# JavaScript-Loop-Practice
<!DOCTYPE html>
<html lang="en">
<head>
     <meta charset="utf-8">
	<title> Anto and Liberty intro </title>
</head>
<body>
	<h3> Working with Loops in JavaScript</h3>
	<P id ="demo"> This is a replacement methods</P>

 
 
 <script>
		var  sisters = ["Emilia", "Elisha", "Marry", "Hannah", "Monica"];  
		var text = "";
        for (i=0; i < sisters.length; i++) {
        
        text += sisters [i] + "<br>";
} 	
	
  </script>
  
  
	   <button type="button"
		onclick = "document.getElementById('demo').innerHTML = text">
	   Click Me </button>
	   
</body>
