Auto-Typer
==========

Any auto-typing software for various typing websites such as Typingraces.tk
<html>
<head>
<title>Making an autotyper</title>
<script>
var charset=0;
var text="This is a tutorial!";

function type()
{
	   var a=document.getElementByld('auto');
	   if(a.innerHTML !=text)
	   {
		      a.innerHTML=text.substring(0,charset);
		      charset++;
		      var b=setTimeout("type();",30);
	    }
	    else
	    {
		      clearTimeout(b)'
		      charset=0;
	     }
}
</script>

</head>

<body onload="type();">

<p id="auto"></p>

</body>

</html>


