<DOCTYPE html>
<html lang="pt-br">

	<head>
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<meta charset="utf-8">
		<link rel="stylesheet" href="style.css" href="./images">
		<title>HTML na prática!</title>
		<!--Essa página foi criada com o intuito de exibir as tags html em que aprendi! - Vanessa Zac -->
	</head>
	
	<body">
		
		<!-----------------------APRENDENDO HTML NA PRÁTICA----------------------->
		<h1 >APRENDENDO HTML <sup>na prática</sup>
		<img src="images/ok.png" alt="texto alternativo da imagem" width="200" height="200"></h1>
		<br>
		
		<!-----------------------SUMÁRIO----------------------->
		<h1>Sumário</h1>
		<br>
		<ul">
		<li><a href="#cabecalhos">Cabeçalhos</a></li>
		<li><a href="#paragrafos">Parágrafos</a></li>
		<li><a href="#links">Links</a></li>
		<li><a href="#imagens">Imagens</a></li>
		<li><a href="#formatacao">Elementos de Formatação</a></li>
		<li><a href="#citacoes">Elementos de Citações</a></li>
		<li><a href="#abreviacoes">Abreviações</a></li>
		<li><a href="#tabelas">Tabelas</a></li>
		<li><a href="#contato">Informações de Contato</a></li>
		</ul>

		<!-----------------------HIERARQUIA DOS TÍTULOS----------------------->
		<h2 id="cabecalhos">Cabeçalhos</h2>
		
		<h1>Acima de tudo guarde o seu coração, 
		pois dele depende toda a sua vida.</h1>
		
		<h2>Afaste da sua boca as palavras peversas;
		fique dos lábios, longe, a maldade.</h2>
		
		<h3>Olhe sempre para a frente,
		mantenha o olhar fixo no que está adiante de você.</h3>
		
		<h4>Veja bem por onde anda,
		e os seus passos serão seguros.<h4>
		
		<h5>Não se desvie nem para a direita, 
		nem para a esquerda;</h5>
		
		<h6>Afaste seus pés da maldade.</h6>
		
		<!-----------------------PARAGRÁFOS----------------------->
		
		<h2>Paragráfos</h2>
		
		<p>"Os parágrafos servem para escrever textos na página."</p>
		
		<pre>
		<h3>Exagerado <br>		
		Canção de Cazuza</h3>

		<cite>	
		"Amor da minha vida
		Daqui até a eternidade
		Nossos destinos foram traçados na maternidade
		Paixão cruel, desenfreada
		Te trago mil rosas roubadas
		Pra desculpar minhas mentiras, minhas mancadas
		
		Exagerado
		Jogado aos teus pés, eu sou mesmo exagerado
		Adoro um amor inventado
		Eu nunca mais vou respirar
		Se você não me notar
		Eu posso até morrer de fome
		Se você não me amar
		Por você eu largo tudo
		Vou mendigar, roubar, matar
		Até nas coisas mais banais
		Pra mim é tudo ou nunca mais
		
		Exagerado
		Jogado aos teus pés, eu sou mesmo exagerado
		Adoro um amor inventado
		E por você eu largo tudo
		Carreira, dinheiro, canudo
		Até nas coisas mais banais
		Pra mim é tudo ou nunca mais
		
		Exagerado
		Jogado aos teus pés, eu sou mesmo exagerado
		Adoro um amor inventado
		Jogado aos teus pés com mil rosas roubadas
		
		Exagerado
		Eu adoro um amor inventado
		Jogado aos teus pés, baby baby
		Eu sou mesmo exagerado
		Adoro um amor inventado."
		</cite>

			<img src="images/seduzindo.png" alt="seduzindo" style="float=left; width:300; height=350;">
		</pre>
		<!-----------------------LINKS----------------------->
		<h2 id="links">Links</h2>
		<a href="headers-pink.html"> Clique aqui para ver o fundo mudar para Rosa. :) </a>
		
		<!-----------------------IMAGENS----------------------->
		<h2 id="imagens">Imagens</h2>
				
		<img src="https://media.giphy.com/media/3Q1qZRCN4oXzW/giphy.gif" alt="bmo" style="width:400px; height:300px;">
		<img src="https://media.giphy.com/media/VN36z61tPoXsY/giphy.gif" alt="bmo" style="width:400px; height:300px;">
		<img src="https://media.giphy.com/media/pO4UHglOY2vII/giphy.gif" alt="bmo" style="width:400px; height:300px;">
		
		<h3> Mapa de Imagens</h3>
		<p>Clique nos personagens para conhece-los melhor!</p> 
		<img src="images/dbz.jpg" style="width: 601px; higth: 343px;" alt="Dragon Ball Z" usemap="#dbzmap">
		<map name="dbzmap">
			<area shape="rect" coords="52,53,207,284" alt"Chaos, Tenshinhan, Mestre Kame, Kuririn" href="dbzleft.html" target="_blank">
			<area shape="rect" coords="419,56,534,290" alt"Pual, Yamcha, Bulma, Oolong" href="dbzright.html" target="_blank">
			<area shape="circle" coords="253,78,391,260" alt"Goku" href="dbzcenter.html" target="_blank">
			</map>
		
		<!-----------------------FORMATAÇÕES----------------------->

		<h2 id="formatacao">Elementos de Formatação</h2>
		<p><b>-"Amor igual ao seu eu nunca mais terei;
		   	Amor que eu nunca vi igual, eu nunca mais verei."
		</b><br>
		
		<strong>-Texto importante </strong><br>
		<i> - Texto em itálico </i><br>
		<em> - Texto enfatizado </em><br>
		<mark> - texto marcado </mark><br>
		<small> - Texto menor </small><br>
		<del> - Texto excluído </del><br>
		<ins> - Texto inserido </ins><br>
		<sub> - Texto subscrito </sub><br>
		<sup> - Texto sobrescrito </sup>
		
		<!-----------------------CITAÇÕES----------------------->
		
		<h2 id="citacoes">Elementos de Citações</h2>
		<p><strong>Essa é uma citação de outro website:</strong></p>
		<blockquote cite="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/blockquote">
		<p>O Elemento HTML de citação de bloco indica que o texto incluído é uma longa citação. Normalmente, este é processado visualmente pelo recuo. A URL para a fonte da citação pode ser dada usando o atributo cite, enquanto uma representação de texto da fonte pode ser dada usando o 'cite' elemento.</p></blockquote>
		
		<p><strong>Essa é uma citação curta:</strong></p>
		<p>O site https://developer.mozilla.org/ diz: <q>O elemento 'q' pode ser usado tanto para citações em linha quanto para citações de origem.</q><br>
		Essa tag acrescenta aspas no texto.</p>
		
		<!-----------------------ABREVIAÇÕES----------------------->
		
		<h2 id="abreviacoes">Abreviações</h2>
		<p>As abreviações de marcação, no <abbr title="Linguagem de Marcação de HiperTexto">HTML</abbr>, podem fornecer informações úteis para navegadores, sistemas de tradução e mecanismos de pesquisa.

<b>**Dica</b>: passe o mouse sobre a abreviatura no texto acima para saber o seu significado.</p>

		<!-----------------------TABELAS----------------------->
		
		<h2 id="tabelas">Tabelas</h2>
		<table>
			<h3>Minhas músicas preferidas</h3>
			<tr>
				<th style="text-align:left">Música:</th>
				<th style="text-align:left">Quem canta:</th>
				<th style="text-align:left">Ouça:</th>
			</tr>
			<tr>
				<td>Losing my religion</td>
				<td>R.E.M</td>
				<td><audio controls autoplay>
				    <source src="music/losingMyReligion.mp3" type="audio/mp3">		
				</td>
			</tr>
			<tr>
				<td>Otherside</td>
				<td>Red Hot Chili Peppers</td>
				<td><audio controls autoplay>
				    <source src="music/otherside.mp3" type="audio/mp3">		
				</td>
			</tr>
			<tr>
				<td>Lanterna dos Afogados</td>
				<td>Paralamas do Sucesso</td>
				<td><audio controls autoplay>
				    <source src="music/lanternaDosAfogados.mp3" type="audio/mp3">		
				</td>
			</tr>
			<tr>
				<td>Primeiros erros</td>
				<td>Capital inicial</td>
				<td><audio controls autoplay>
				    <source src="music/primeirosErros.mp3" type="audio/mp3">		
				</td>
			</tr>
			<tr>
				<td>Sugar</td>
				<td>Maron 5</td>
				<td><audio controls autoplay>
				    <source src="music/sugar.mp3" type="audio/mp3">		
				</td>
			</tr>
			<tr>
				<td>Amei te Ver</td>
				<td> Tiago York</td>
				<td><audio controls autoplay>
				    <source src="music/ameitever.mp3" type="audio/mp3">		
				</td>
			</tr>
			<tr>
				<td>Sutilmente</td>
				<td>Skank</td>
				<td><audio controls autoplay>
				    <source src="music/sutilmente.mp3" type="audio/mp3">		
				</td>
			</tr>
			<tr>
				<td>I'm yours</td>
				<td>Jason Mraz</td>
				<td><audio controls autoplay>
				    <source src="music/I'mYours.mp3" type="audio/mp3">		
				</td>
			</tr>
			<tr>
				<td>Just the Way You Are</td>
				<td>Bruno Mars</td>
				<td><audio controls autoplay>
				    <source src="music/justTheWayYouAre.mp3" type="audio/mp3">		
				</td>
			</tr>
			<tr>
				<td>Mais uma vez</td>
				<td>Legião Urbana</td>
				<td><audio controls autoplay>
				    <source src="music/MaisUmaVez.mp3" type="audio/mp3">		
				</td>
			</tr>
			</table>
		<!-----------------------IFRAME----------------------->
		
		<h2 id="contato">Iframe</h2>
		<iframe width="645" height="363" src="https://www.youtube.com/embed/7AQbqSTbSPo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

		<iframe width="645" height="363" src="https://www.youtube.com/embed/tgbNymZ7vqY?controls=0">
		</iframe>

		
		<!-----------------------FORMULÁRIOS---------------------->
		<h2 id="formulario">Formulários</h2>

		<form action="action_page.php" target="_blank">
		<label for="primeironome">Nome:</label><br>
		<input type="text" id="primeironome" name="primeironome"><br>
		<label for="sobrenome">Sobrenome:</label><br>
		<input type="text" id="sobrenome" name="sobrenome"><br>
		<label for="idade">Idade:</label><br>
		<input type="number" id="idade" name="idade" min="1" max="99"><br>
		<label for="datanascimento">Data de Nascimento:</label><br>
		<input type="date" id="datanascimento" name="datanascimento"><br>
		<label for="sexo">Sexo:</label><br>
		<select id="sexo" name="sexo">
		<option value="masculino">Masculino</option>
		<option value="feminino">Feminino</option>
		<option value="outros">outros</option>
		<input type="submit" value="Enviar">
		</select><br><br>

		<button type="button" onclick="alert("Formulário em manuntenção")>Enviar Formulário!</button>		
		</form>

		<!-----------------------SVG---------------------->
		
		<h2 id="svg">SVG da bandeira do Brasil</h2>
		<svg width="300" height="200">
			<rect width="500" height="300" style="fill:green;"/> 	
		<svg width="300" height="200">
  			<svg width="300" height="200">
  			<polygon points="150,5 5,100 150,195 295,100 295,100"
 			 style="fill:yellow;fill-rule:evenodd;" />
 		<svg width="300" height="200">
  			<circle cx="150" cy="100" r="70" fill="blue" />
		</svg>	

		<!-----------------------INFORMAÇÕES DE CONTATO----------------------->
		
		<h2 id="contato">Informações de Contato</h2>
			<p>As informações de contato podem ser um endereço de e-mail, URL, endereço físico, número de telefone, identificador de 				mídia social, etc.</p>
		<address>
			Visite-me em: <br>
			<a href="http://vanessazac.dev.br/" target="_blank">vanessazac.dev.br</a> <br>
			<a href="mailto:vanessadeborbanuneszaccani@gmail.com">Fale comigo por e-mail</a> <br>
			Imbé, RS
			Brasil
			</address>	
						
	</body>
</html>	
