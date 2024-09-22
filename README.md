<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Aula CSS 1</title>
</head>

<style>
	.card{
		width:500px; 
		height: fit-content; 
		background-color: aliceblue; 
		border-radius: 25px; 
		border: solid 3px rgb(1, 119, 255); 
		margin: 20px;
	}
	.container{
		margin: 20px 0px 20px 20px;
	}
	.propriedades-img{
		width: 100px; 
			height: 100px; 
			border-radius: 50%;
			margin: 10px;
	}
	img{
		 width: 100%; 
		 height: 100%;
		 margin-top: 20px;
	}
	.texto{
		font-family: Verdana, Geneva, Tahoma, sans-serif;
		font-size: 30px
	}

	p{
		font-size: 15px !important;
	}

	span{
		color: rgb(119, 0, 255);
	}


</style>

<body>

	<div class="card">

		<div class="container">

			<div class="propriedades-img">
				<img src="https://cdn-icons-png.flaticon.com/512/706/706830.png" alt="Imagem da Adriana">
			</div>
			<div>
				<h1 >
					Meu nome é: <span>Adriana</span>
				</h1>
	
				<p class="texto">
					Mensagem: <span >A vida não é um morango!</span>
				</p>
			</div>

		</div>

	</div>

	<div class="card">

		<div class="container">
			<div class="propriedades-img">
				<img  src="https://cdn-icons-png.flaticon.com/256/3681/3681928.png" alt="">
			</div>
	
			<div>
				<h1 class="texto">
					Meu nome é: <span>Hugo</span>
				</h1>
	
				<p class="texto">
					Mensagem: <span>Um dia é da caça, o outro é do caçador.</span>
				</p>
			</div>
		</div>
	</div>

</body>

</html>
