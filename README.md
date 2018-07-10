<!doctype>
<html>
<head>
</head>
<body>
<div onmousedown="mDown(this)" onmouseup="mUp(this)" style="background-color:pink;
width:180px;height:50px;color:white;">请点击</div>
<script>
function mDown(obj)
{
obj.style.backgroundColor="pink";
obj.innerHTML="请释放"
}

function mUp(obj)
{
obj.style.backgroundColor="yellow";
obj.innerHTML="请点击"
}
</script>
</body>
</html>
