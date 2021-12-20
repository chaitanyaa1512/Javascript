# Javascript
<html>
<body>
	<div style="width: 600px; height:  400px";
	  background-color:"yellow;">
	<h1 id="h1">Enter Age:</h1>
	<input type="text" name="" id="ip" oninput="perform()">
	<p id="res"></p>
</div>
	<script type="text/javascript">
		function perform(){
             var ip= document.getElementById("ip");
             if(Number(ip.value)>=18){
             	document.getElementById("res").innerHTML ="You are eligible for vote";
             }
             else{
             	document.getElementById("res").innerHTML ="You are not eligible for vote";
             }
         }
             
             
	</script>
</body>
</html>
