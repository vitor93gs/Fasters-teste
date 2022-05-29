<script></script>

<template>
	<section>
		<div class="title">
			<h2>Elegante é ter um</h2>
			<h1>ALFAIATE</h1>
			<h2 class="title_h2">para chamar de seu.</h2>
		</div>
		<div class="description">
			<h3>
				COMPRE HOJE, <b>PAGUE EM ATÉ 3X COM 12% DE DESCONTO</b> E TENHA
				10 MESES PARA CONFECCIONAR!
			</h3>
		</div>
		<button>FAÇA JÁ UM ORÇAMENTO</button>
	</section>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,300;1,300&family=Playfair+Display:ital@1&display=swap');
section {
	height: 660px;
	background-image: url(../assets/Banner.svg);
	background-position: center;
	background-repeat: no-repeat;
	background-size: cover;
	width: 100%;
	padding: 0px;
	margin-top: 0px;
	color: white;
}
h1 {
	margin: 0px;
	padding: 0px;
	font-style: normal;
	font-size: 90.03px;
	line-height: 120px;
	line-height: 100%;
	vertical-align: top;
	fill: solid;
	color: rgba(2, 75, 104, 0.68);
	font-weight: 400;
}
h2 {
	margin: 0px;
	padding: 0px;
	font-family: 'Playfair Display', serif;
	font-style: Italic;
	font-size: 32.56px;
	line-height: 43.41px;
	line-height: 100%;
	vertical-align: center;
	fill: solid;
	color: #be9667;
	font-weight: 400;
}
h3 {
	font-family: 'Lato', sans-serif;
	font-style: Mixed;
	font-size: 24px;
	line-height: 31px;
	line-height: 131%;
	vertical-align: top;
	fill: solid;
	color: #e5e5e5;
	font-weight: 200;
}

.title {
	position: absolute;
	top: 28.07%;
	left: 7.17%;
}
.title_h2 {
	text-align: right;
}
.description {
	position: absolute;
	top: 55.4%;
	left: 7.17%;
	height: 93px;
	width: 410px;
}
button {
	fill: solid;
	background-color: #014561;
	color: #e5e5e5;
	position: absolute;
	top: 75.4%;
	left: 7.17%;
	height: 50px;
	width: 300px;
	font-family: Lato;
	font-style: light;
	font-size: 18px;
	line-height: 22px;
	line-height: 100%;
	vertical-align: top;
	transition: 0.3s;
	border-radius: 3px;
	border: 1px solid #090a0c;
}
button:hover {
	background-color: #090a0c;
	border: 1px solid #be9667;
}
</style>
