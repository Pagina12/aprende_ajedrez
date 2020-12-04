# aprende_ajedrez
<!DOCTYPE html>
<html lang="es">

<head>
	<meta charset="utf-8">
	<meta name="keywords" content="Ajedrez">
	<meta name="description" content="Aprender a jugar ajedrez para competir con otras personas">
	<meta name="author" content="Luis Gustavo">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title> Aprendo ajedrez </title>

	<link rel="icon" type="image/jpg" href="https://cdn.pixabay.com/photo/2017/08/01/16/32/tie-2566434_960_720.jpg" />

	<style>

		body {
			margin: 0.5%;
			background: #BFC9CA;
		}

		abbr {
			text-decoration: none;
		}

		h1, h2 {
			text-align: center;
			font-family: algerian, sans serif;
			color: #E74C3C;
		}

		figure {
			text-align: center;
		}

		table, th, td {
			border: 4px solid black;
			border-collapse: collapse;
			border-color: red;
		}

		th, td {
			padding: 8px;
		}

		p {
			font-style: 18px;
			font-family: georgia, sans serif;
		}

		ul, ol, figcaption, th, td {
			font-family: georgia, sans serif;
		}

		h3 {
			font-family: lucida fax, sans serif;
			color: #229954;
		}

		.boton {
			padding: 0;
			margin: 12px;
			text-align: center;
		}

		.boton { 
			display: block;
			text-decoration: none;
			background: #cc2b2b;
			color: #F1C40F;
			width: 340px;
			height: 30px;
			text-align: center;
			font-family: geogia, sans serif;
			font-size: 20px;
			padding: 12px 30px;
			letter-spacing: 1px;
			transition: all 500ms ease;
		}

		.jugar :hover {
			background: #F1C40F;
			color: #cc2b2b;
		}

		#contenedor {
			width: 90%;
			height: 350px;
			margin: auto;
			padding: 0.3em;
		}

		img {
			width: 300px;
			height: 300px;
		}

		#blancas {
			height: 100%;
			width: 42%;
			border-radius: 1em;
			float: left;
			margin: 0em;
		}

		#negras {
			height: 100%;
			width: 42%;
			border-radius: 1em;
			float: right;
			margin: 0em;
		}

		.global {
			width: 94%;
			height: 94%;
			margin: auto;
		}

		footer {
			border: 1px solid #8E44AD;
			height: 40px;
			width: 100%;
			background-color: #8E44AD;
			margin-top: 35px;    /* margen superior */
			color: #fff;
			font-weight: 800;
			font-size: 17px;
			letter-spacing: 2px;
			text-align: center;
			padding-top: 20px;	/* ayuda a que quede bien centrado el texto */
			font-family: Georgia, sans-serif;
			position: relative;
		}

	</style>

</head>

<body>
	<!-- contenedor global -->
	<div class="global">
		<!-- TITULO -->
		<header>
			<hgroup>
				<h1> Mis primeros pasos en ajedrez </h1>
			</hgroup>
		</header>

		<!-- MAPA DE NAVEGACIÓN DE LA PÁGINA -->
		<h3> Escoge un tema espec&iacute;fico del contenido de la p&aacute;gina </h3>
		<nav>
			<ul>
				<li>
					<a style="text-decoration-color: #21618C; color:#21618C; font-size: 18px;" href="#introduccion"> Introducci&oacute;n </a>
				</li>
				<li>
					<a style="text-decoration-color: #21618C; color:#21618C; font-size: 18px;" href="#ubicacion"> Ubicaci&oacute;n de las piezas en el tablero </a>
				</li>
				<li>
					<a style="text-decoration-color: #21618C; color:#21618C; font-size: 18px;" href="#peon"> Datos sobre el pe&oacute;n y jugadas especiales </a>
				</li>
				<li>
					<a style="text-decoration-color: #21618C; color:#21618C; font-size: 18px;" href="#torre"> Datos sobre la torre y jugada especial </a>
				</li>
				<li>
					<a style="text-decoration-color: #21618C; color:#21618C; font-size: 18px;" href="#caballo"> Datos sobre el caballo </a>
				</li>
				<li>
					<a style="text-decoration-color: #21618C; color:#21618C; font-size: 18px;" href="#alfil"> Datos sobre el alfil </a>
				</li>
				<li>
					<a style="text-decoration-color: #21618C; color:#21618C; font-size: 18px;" href="#reyna"> Datos sobre la reyna </a>
				</li>
				<li>
					<a style="text-decoration-color: #21618C; color:#21618C; font-size: 18px;" href="#rey"> Datos sobre el rey </a>
				</li>
				<li>
					<a style="text-decoration-color: #21618C; color:#21618C; font-size: 18px;" href="#jugar"> Jugar ajedrez </a>
				</li>
			</ul>
		</nav>

		<!-- INTRO -->
		<section id="introduccion"> 	
			<h2> INTRODUCCI&Oacute;N </h2>
			<p> El ajedrez se juega en un tablero de 64 casillas (8 x 8), en la cual participan dos personas (oponentes) que disputan su destreza y estrategia que tienen para el juego. </p> 
			<p> Al inicio de la partida cada jugador dispone de 16 piezas cada uno en las cuales se encuentran: 
			<ul>
				<li> 1 rey </li> 
				<li> 1 reyna </li> 
				<li> 2 alfiles </li> 
				<li> 2 caballos </li>
				<li> 2 torres </li> 
				<li> 8 peones </li>
			</ul>
			</p>
			<p> Siendo las piezas de un jugador de color blancas y el otro negras. En donde el jugador que tiene las piezas de color blancas es el que inicia el juego (las piezas que puede mover al <br> empezar son: el peón	o el caballo). </p>

			<h3> El juego puede terminar de las siguientes maneras: </h3>
		
			<ul>
				<li> Victoria: Se obtine la victoria de las siguientes maneras: </li><br>
				<ul style="list-style-type: square;">
					<li> Atacando la posici&oacute;n del rey contrario de modo que no pueda ser protegido, a esta jugada se le conoce como <abbr title="se da cuando se ataca la posición del rey dejando sin posibilidades de que las demás piezas lo puedan proteger"><span style="color:red;"> "hacke mate" </span></abbr> . </li>
					<figure>
						<figcaption> Imagen que hace referencia a un hacke mate </figcaption><br>
						<img src="https://images.chesscomfiles.com/uploads/v1/images_users/tiny_mce/SamCopeland/phpNray9h.gif" alt="hacke mate">
					</figure>
					<li> El aponente abandona la partida. </li><br>
				</ul>
				<li> Empate <span style="color:red;"> "rey ahogado" </span></abbr> </li><br>
				<ul style="list-style-type: square;">
					<li> Es cuando el rey se queda sin movimientos sin haberle hecho jacke mate y adem&aacute;s no hay pieza a la que pueda mover el jugador. Esto mayormente sucede por una mala <br> estragia al momento de atacar al rey.</li>
					<figure>
						<figcaption> Imagen que hace referencia a un empate </figcaption><br>
						<img src="https://proauge.files.wordpress.com/2015/08/50df1-empate2b1.png" alt="empate">
					</figure>
				</ul>
			</ul><br>
		</section>

		<!-- UBICACIÓN DE LAS PIEZAS -->
		<section id="ubicacion">
			<h2> UBICACI&Oacute;N DE LAS PIEZAS DE AJEDREZ </h2>
			<p> Las piezas del ajedrez se ubican de la siguiente manera: </p>
			<figure>
				<img src="https://i.pinimg.com/originals/3a/9c/6e/3a9c6e0e666f94d85bd06537061b62a3.png" alt="ubicación de piezas de ajedrez">
			</figure><br>
			<div id="contenedor" ">
				<!-- UBICACIÓN DE LAS BLANCAS -->
				<div id="blancas">
					<h3 style="text-align: center;"> Ubicaci&oacute;n de las piezas blancas </h3>
					<table width="100%">
						<tbody>
							<tr style="background: gray;">
								<th> NOMBRE DE LA PIEZA </th>
								<th> POSICI&Oacute;N DE LA PIEZA </th>
							</tr>
							<tr>
								<td style="text-align: center;"> Pe&oacute;n </td>
								<td style="text-align: center;"> A2 &nbsp; B2 &nbsp; .... &nbsp; H2 </td>
							</tr>
							<tr>
								<td style="text-align: center;"> Torre </td>
								<td style="text-align: center;"> A1 &nbsp; H1 </td>
							</tr>
							<tr>
								<td style="text-align: center;"> Caballo </td>
								<td style="text-align: center;"> B1 &nbsp; G1 </td>
							</tr>
							<tr>
								<td style="text-align: center;"> Alfil </td>
								<td style="text-align: center;"> C1 &nbsp; F1 </td>
							</tr>
							<tr>
								<td style="text-align: center;"> Reina </td>
								<td style="text-align: center;"> D1 </td>
							</tr>
							<tr>
								<td style="text-align: center;"> Rey </td>
								<td style="text-align: center;"> E1 </td>
							</tr>
						</tbody>
					</table>
				</div>

				<!-- UBICACIÓN DE LAS NEGRAS -->
				<div id="negras">
					<h3 style="text-align: center;"> Ubicaci&oacute;n de las piezas negras </h3>
					<table width="100%">
						<tbody>
							<tr style="background: gray;">
								<th> NOMBRE DE LA PIEZA </th>
								<th> POSICI&Oacute;N DE LA PIEZA </th>
							</tr>
							<tr>
								<td style="text-align: center;"> Pe&oacute;n </td>
								<td style="text-align: center;"> A7 &nbsp; B7 &nbsp; .... &nbsp; H7 </td>
							</tr>
							<tr>
								<td style="text-align: center;"> Torre </td>
								<td style="text-align: center;"> A8 &nbsp; H8 </td>
							</tr>
							<tr>
								<td style="text-align: center;"> Caballo </td>
								<td style="text-align: center;"> B8 &nbsp; G8 </td>
							</tr>
							<tr>
								<td style="text-align: center;"> Alfil </td>
								<td style="text-align: center;"> C8 &nbsp; F8 </td>
							</tr>
							<tr>
								<td style="text-align: center;"> Reina </td>
								<td style="text-align: center;"> D8 </td>
							</tr>
							<tr>
								<td style="text-align: center;"> Rey </td>
								<td style="text-align: center;"> E8 </td>
							</tr>
						</tbody>
					</table>
				</div>
			</div>
		</section><br>

		<!-- DATOS DEL PEÓN -->
		<section id="peon"><br>
			<h2 id="media"> EL PE&Oacute;N </h2>
			<figure>
				<img src="https://s3.amazonaws.com/ichess.es/wp-content/uploads/2014/12/16140000/AdPn-0-e1410867057587.jpg" alt="peón">
			</figure>
			<h3> Datos que tienes que saber sobre el pe&oacute;n </h3>
			<ul>
				<li> El peón es la pieza m&aacute;s numerosa del ajedrez, al comienzo de cada partida cada participante cuenta con 8 peones que est&aacute;n ubicados en la fila 2 y 7 del tablero de ajedrez. </li><br>
				<li> El pe&oacute;n avanza verticalmente por la columna en que se encuentra, es la &uacute;nica pieza que no puede retroceder. En el primer movimiento puede avanzar 1 o 2 casillas y a partir <br> del segundo movimiento avanzara 1 casilla por movimiento. </li><br>
				<li> Captura en diagonal desplazandoze (una casilla) a la columna inmediata, ya sea izquierda o derecha capturando una pieza adversaria. </li>
				<figure>
					<figcaption> Imagen que hace referencia a la captura y movimiento del pe&oacute;n </figcaption><br>
					<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b8/Pawn_%28chess%29_movements.gif/220px-Pawn_%28chess%29_movements.gif" alt="forma en que captura el peón">
				</figure>
			</ul>
			<h3> Jugadas especiales que puedes realizar con el pe&oacute;n </h3>
			<ol>
				<li> Captura de pe&oacute;n al paso </li>
				<ul style="list-style-type: disc;"><br>
					<li> Para realizar est&aacute; jugada se debe de mover uno de los peones 2 casillas, el siguiente movimiento que se debe de hacer despu&eacute;s de que el oponete haya jugado es avanzar <br> el mismo pe&oacute;n una casilla m&aacute;s y si el oponente mueve un pe&oacute;n de la columna adyasente en donde se encuentra tu pe&oacute;n lo puedes capturar como si el peón se hubiera <br> desplazado una casilla a esa captura se le llama  captura de pe&oacute;n al paso. </li>
					<figure>
						<figcaption> Imagen que hace referencia a la captura del pe&oacute;n al paso </figcaption><br>
						<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/09/Ajedrez_animaci%C3%B3n_en_passant.gif/220px-Ajedrez_animaci%C3%B3n_en_passant.gif" alt="captura de peón al paso">
					</figure>
				</ul>
				<li> Coronaci&oacute;n </li>
				<ul style="list-style-type: disc;"><br>
					<li> El pe&oacute;n tiene la posibilidad de <span> "convertirse" </span> en: torre, caballo, alfil o reyna cuando haya llegado a la octava fila por parte de las blancas y la primera fila por parte de las negras. <br> Si el rey adversario se encuentra en la misma l&iacute;nea de coronaci&oacute;n sin ninguna pieza a su costado que lo proteja y al coronar si se escoge la reyna o la torre el rey queda automaticamente en jake. <br>  Al momento de coronar el pe&oacute;n es reemplazado por la pieza elegida y el pe&oacute;n pasa a ser retirado del tablero. </li>
				</ul><br>
				<div>
					<p>
						<figure>
							<figcaption>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Imagen que hace referencia a la coronaci&oacute;n del pe&oacute;n </figcaption><br>
							<img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Ajedrez_animaci%C3%B3n_coronaci%C3%B3n.gif" alt="">
							&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
							<img src="https://img.wattpad.com/a5b1217f2fbd8589640bc7feca1a7445d6ca759a/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f776174747061642d6d656469612d736572766963652f53746f7279496d6167652f324c45494161584741716f6332513d3d2d3432393935363534302e313463613931646232373837303034343735333635333839343333392e676966?s=fit&w=720&h=720">
						</figure>
					</p>
				</div>
			</ol>
		</section>

		<!-- DATOS DE LA TORRE -->
		<section id="torre"><br>
			<h2> LA TORRE </h2>
			<figure>
				<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSXWgSFEtPoV6IPjLlFcoFo2MKbI7EQuOJDsQ&usqp=CAU" alt="torre">
			</figure><br>
			<h3> Datos que tienes que saber sobre la torre </h3>
			<ul>
				<li> Se ubican en las casillas a1 y h1 del lado de las blancas y a8 y h8 del lado de las negras. </li><br>
				<li> Se desplaza y capturan de manera horizontal y vertical. Cuando captura una pieza en su desplazamiento, la torre ocupa el mismo lugar en donde se encontraba la pieza capturada. </li><br>
				<li> No puede saltar las piezas al desplazarse, exepto cuando se utiliza para hacer enroque. </li>
			</ul>
			<h3> Jugada especial que se puede hacer con la torre </h3>
			<ul style="list-style-type: square;">
				<li> Enroque </li><br>
				<ul style="list-style-type: disc;">
					<li> Se le permite a una torre realizar un movimiento especial llamado enroque, el cual consiste en mover al rey desde su posici&oacute;n inicial 2 casillas hacia la derecha o izquierda, <br> en seguida la torre moverla hacia su costado(opuesto al movimiento que hizo el rey) del rey. </li><br>
				</ul>
				<figure>
					<figcaption> Imagen que hace referencia a enroque </figcaption><br>
					<img src="https://i.pinimg.com/originals/a8/ef/ab/a8efabd6b6431319a828eb900cb201d1.gif" alt="enroque">
				</figure><br>
			</ul>
		</section><br>

		<!-- DATOS DEL CABALLO -->
		<section id="caballo">
			<h2> EL CABALLO </h2>
			<figure>
				<img src="https://media.istockphoto.com/photos/chess-knights-isolated-on-white-background-picture-id185078242?k=6&m=185078242&s=612x612&w=0&h=RJscdKT4yGt3G4XDqVBGmb2ROQPpqxECZGWcrDkSumY=">
			</figure>
			<h3> Datos que tienes que saber sobre el caballo </h3>
			<ul>
				<li> Se ubican en las casillas b1 y g1 del lado de las blancas y b8 y g8 del lado de las negras. </li><br>
				<li> Se desplaza avanzando dos casillas hacia adelante y uno hacia el costado formando una "L", captura de la misma forma en que se desplaza y tomando el lugar de la pieza capturada. </li><br>
				<li> Es la única pieza que puede "saltar" piezas al desplazarse. </li>
			</ul>
			<figure>
				<figcaption> Imagen que hace referencia al despazamiento y captura del caballo </figcaption><br>
				<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0b/Knight_%28chess%29_movements.gif/220px-Knight_%28chess%29_movements.gif" alt="captura y despazamiento del caballo">
			</figure>
		</section>

		<!-- DATOS DEL ALFIL -->
		<section id="alfil">
			<h2> EL ALFIL </h2>
			<figure>
				<img src="https://upload.wikimedia.org/wikipedia/commons/1/1d/Chess_piece_-_White_bishop.JPG">
			</figure><br>
			<h3> Datos que tienes que saber sobre el alfil </h3>
			<ul>
				<li> Se ubican en las casillas c1 y f1 por parte de las blancas y c8 y f8 por parte de las negras. </li><br>
				<li> Se desplazan en diagonal y capturan de la misma forma en que se desplazan, ocupando el mismo lugar de la pieza capturada. </li><br>
				<li>  No puede saltar las piezas al desplazarse. </li>
			</ul>
			<figure>
				<figcaption> Imagen que hace referencia al despazamiento y captura del alfil </figcaption><br>
				<img src="https://upload.wikimedia.org/wikipedia/commons/8/86/Bishop_%28chess%29_movements.gif" alt="captura y despazamiento del alfil">
			</figure><br>
		</section>

		<!-- DATOS DE LA REYNA -->
		<section id="reyna">
			<h2> LA REYNA </h2>
			<figure>
				<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d3/Chess_piece_-_Black_queen.JPG/170px-Chess_piece_-_Black_queen.JPG">
			</figure><br>
			<h3> Datos que tienes que saber sobre la reyna </h3>
			<ul>
				<li> Se ubica en d1 por parte de las blancas y d8 por parte de las negras. </li><br>
				<li> Se le considera la pieza más fuerte en el ajedrez. </li><br>
				<li>  Se puede desplazar de tres manera: diagonal, vertical y horizontal y captura de la misma forma en que se desplaza ocupando el mismo lugar de la pieza capturada. </li><br>
				<li> No puede saltar piezas al desplazarse. </li>
			</ul>
			<figure>
				<figcaption> Imagen que hace referencia al despazamiento y captura de la reyna </figcaption><br>
				<img src="https://upload.wikimedia.org/wikipedia/commons/5/55/Queen_%28chess%29_movements.gif" alt="captura y despazamiento de la reyna">
			</figure><br>
		</section>

		<!-- DATOS DEL REY -->
		<section id="rey">
			<h2> EL REY </h2>
			<figure>
				<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS8DUx5fnHCXqOr0f5hW8XiFVet-wGLIjgTuQ&usqp=CAU">
			</figure>
			<h3> Datos que tienes que saber sobre el rey </h3>
			<ul>
				<li> Es la pieza más importante del ajedrez, cuya "captura" es el objetivo del juego. </li><br>
				<li> Al momento en que lo "capturan" al rey termina el juego. </li><br>
				<li> Se ubica en e1 del lado de las blancas y e8 del lado de las negras. </li><br>
				<li> Se desplaza de 1 casilla por movimiento de manera diagonal, horizontal o vertical y captura de la misma forma en que se dezplaza. </li>
			</ul>
			<figure>
				<figcaption> Imagen que hace referencia al despazamiento y captura del rey </figcaption><br>
				<img src="https://upload.wikimedia.org/wikipedia/commons/f/f2/King_%28chess%29_movements.gif" alt="catura y desplazamiento del rey">
			</figure><br>
		</section>

		<!-- REDIRECCIONA A OTRA PÁGINA PARA JUGAR -->
		<section id="jugar">
			<h2> SE LLEGO EL MOMENTO DE PONER EN PR&Aacute;TICA LO APRENDIDO </h2><br>
				<div class="jugar" style="justify-content: center;">
					<a target="_black" href="https://chess.org/" class="boton" style="margin: auto;"> Poner en pr&aacute;ctica lo Aprendido </a>
				</div>
		</section><br>
	</div>

		<footer>
			Luis Gustavo / 2020
		</footer>

</body>

</html>
