<script></script>
<template>
	<section>
		<img
			class="img1"
			src="../assets/Tailor.svg"
			alt="Background for testimony"
		/>
		<span>
			<p>
				“Faço roupas com o Renee Trajar há mais de duas décadas, o
				serviço é impecável em todos os detalhes, desde a costura ao
				caimento. O Renee tem uma equipe de mestre!”
			</p>
			<h3>Nelson Garey</h3>
			<h4>Advogado | Nelson Garey Advogados Associados</h4>
		</span>
		<img class="img2" src="../assets/photo1.svg" alt="Foto do advogado" />
		<img
			class="img3"
			src="../assets/fotodoadvogado.svg"
			alt="Outra foto do advogado"
		/>
		<div></div>
	</section>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Cormorant:wght@300;400;500&family=Lato:ital,wght@0,300;1,300;1,400&display=swap');
section {
	height: 360px;
	background-color: #eff7f9;
	padding: 0px;
	margin: 0px;
	display: flex;
	justify-content: space-between;
}
.img1 {
	padding: 0px 0px 0px 0px;
	height: 360px;
	width: 905px;
	margin-left: 8%;
	margin-right: 0;
}
.img2 {
	height: 300px;
	width: 210px;
	position: absolute;
	transform: rotate(7.42deg);
	right: 18%;
	z-index: 1;
	border: 8px solid white;
	margin-top: 20px;
}
path {
	fill: none;
	stroke: black;
	stroke-width: 10px;
	stroke-dasharray: 2, 2;
	stroke-linejoin: round;
}
.img3 {
	height: 360px;
	width: 313px;
}
div {
	height: 360px;
	width: 313px;
	background: #024b68;
	position: absolute;
	right: 0px;
	opacity: 81%;
}
span {
	position: absolute;
	width: 630px;
	margin: 60px 140px;
}
p {
	font-family: lato;
	font-style: Light;
	font-size: 24px;
	line-height: 34px;
	line-height: 141%;
	vertical-align: top;
	color: #828282;
	text-align: center;
	margin-bottom: 50px;
}
h3 {
	font-family: Cormorant;
	font-style: oblique;
	font-size: 28px;
	font-weight: 400;
	font-size: 28px;
	line-height: 40px;
	line-height: 141%;
	vertical-align: top;
	text-align: center;
	color: #014561;
	margin: 0px;
}
h4 {
	font-family: lato;
	font-style: light;
	font-weight: 300;
	font-size: 20px;
	line-height: 28px;
	line-height: 141%;
	vertical-align: top;
	text-align: center;
	color: #be9667;
	margin: 0px;
}
</style>
