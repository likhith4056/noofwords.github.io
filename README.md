<html>
<head>
<script type="text/javascript">
function countWCL(){
var textarea=document.getElementById("tarea");
var text=textarea.value;
value="words"+(text.split(/\b\S+\b/).length-1)+"characters:"+text.replace(/\s/g,"").length+"/"+text.replace(/\n/g,"").length+"lines"+text.split("/n").length;
alert(value);
}
</script>
</head>
<form name="cwl">
enter multiline text<br>
<textarea name="string" id="tarea" rows=50 cols=300></textarea>
<input type="button" name="sub" value="count" onClick="countWCL()">
</form>
</html>

