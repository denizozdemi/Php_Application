//Php ile yazılan basit üniversite notlarının harf karşılığını veren uygulama !!!

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
	<meta charset="utf-8">
</head>
<body>

<?php
$sayi=$_POST['not'];
if ($sayi>=90) {
	echo "AA ile başarılı";
}elseif ($sayi>=80) {
	echo "BA ile başarılı";
}elseif ($sayi>=75) {
	echo "BA ile başarılı";
}elseif ($sayi>=70) {
	echo "CB ile başarılı";
}elseif ($sayi>=60) {
	echo "CC ile başarılı";
}elseif ($sayi>=50) {
	echo "DC ile koşullu başarılı";
}elseif ($sayi>=40) {
	echo "DD ile başarısız";
}elseif ($sayi>=30) {
	echo "FD ile başarısız";
}else {
	echo "FF ile başarısız";
}

?>
<form action=""method="post">
	Notunuzu Giriniz <input type="number" max="100" name="not">
	<input type="submit" name="notunuz">
</form>

</body>
</html>
