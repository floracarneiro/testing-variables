# testing-variables
<meta charset="UTF-8">

<script>
	var pulaLinha = function() {
		document.write("<br> <hr> <br>");
	}
	var mostra = function(frase){
		document.write("<big>"); document.write(frase);document.write("</big>");
		pulaLinha(); 
	}
	var ano = 2020

	mostra("Eu nasci em " + (ano - 22));
	mostra("Anny nasceu em " + (ano - 23));
	mostra("Camilly nasceu em " + (ano - 16));

</script>
