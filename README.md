# RT_8_Tonenchuk
<!DOCTYPE html>
<html>
<head>
<script src="http://code.jquery.com/jquery-latest.js">
</script>

<script>

$(document).ready(function () {

$("input").keypress(function () {
var max = 255;
var min = 0;
	     var c= Math.floor(Math.random() * (max - min + 1)) + min;;
	     var m= Math.floor(Math.random() * (max - min + 1)) + min;;
	     var n= Math.floor(Math.random() * (max - min + 1)) + min;;
	     var ccolor = "rgb("+ c + "," + m + "," + n +")";
             $("input").css("background-color", ccolor); 

})
});
</script>

</head>
<body>
Color: <input type="text" name="fullname"><br>

</body>
</html>
