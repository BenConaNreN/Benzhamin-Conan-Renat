<meta charset="utf-8">
<script>

var name = prompt("Name");
var otvet ="";
var verno = 0;
otvet = prompt("Висит груша нельзя скушать");
if(otvet == "лампочка"){
	alert("Верно");
	verno = verno + 1;
}else{
	alert("Неверно");
}
otvet = prompt("Зимой и летом одним цветом");
if(otvet == "ёлка"){
	alert("Верно");
	verno = verno + 1;
}else{
	alert("Неверно");
}
otvet = prompt("Кто его раздевает, тот сам слёзы проливает");
if(otvet == "лук"){
	alert("Верно");
	verno = verno + 1;
}else{
	alert("Неверно");
}
alert(name + ", у тебя " + verno + " верных ответов " );
if((verno > 0) && (verno < 2)){
	alert("Неплохо сыграно");
}else if((verno > 1) && (verno < 3)){
	alert("Хорошо сыграно");
}else if(verno > 2) {
	alert("Прекрасно сыгранно");
}else if(verno < 1) {
	alert("Ужасно сыгранно");
}

</script>
