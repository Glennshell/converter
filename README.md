converter
=========
<!DOCtype html>

<html>
  <title>MPG->KPL Converter</title>
	
<script type="text/javascript">

function convert()
{
	var result =0;
	var milespergallon =prompt("Enter a number in MPG that you would like to onvert to KPL", 0);

	result = milespergallon * .42505303;


	alert(milespergallon + " MPG = " + result + " KPL ");
}


</script>
	<h2>Convert Miles per Gallon to Kilometers per Liter</h2>
	<body>
		<p>
			<ol>1. Click the Convert button and enter the value (in MPG) you would like converted</ol>
			<ol>2. Click the Ok button and recive you answer in KPL!</ol>
			<form>
			<input type="button" onclick="convert();" value="CONVERT THAT SUCKA">
			</form>
		</p>
	</body>
</html>
