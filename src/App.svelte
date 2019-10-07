<script>
	
	import VentanaFamilia from "./componentes/VentanaFamilia/VentanaFamilia.svelte";
	import VolutaIcono from "./componentes/VolutaIcono.svelte";
	import TwitterIcono from "./componentes/TwitterIcono.svelte";
	import Informacion from "./componentes/Informacion/Informacion.svelte";
	import Cabecera from "./componentes-inali-web/general/Cabecera/Cabecera.svelte";
	import Pie from "./componentes-inali-web/general/Pie/Pie.svelte";

</script>

<style>
	* {
		outline: 1px solid blue;
	}
	
	 .Contenedor-1 {
		/* width: 100%; */
		padding: 0;
		margin: 0;
		display: flex;
		flex-flow: row wrap;
		justify-content: space-between;
		align-content: space-between;
	}

	.VentanaFamilia {
		width: 100px;

		display: flex;
		flex-grow: 1;
		margin: auto;
	}

	.Informacion {
		display: flex;
		margin: auto;

	}

	.IconoVoluta {
		display: flex;
		margin: auto;

	}

	.IconoTwitter {
		display: flex;
		margin: auto;

	}




</style>

<head>
    <script src="https://kit.fontawesome.com/096c98e281.js" crossorigin="anonymous"></script>
</head>
<div class="Contenedor-1">
		<div class="VentanaFamilia">
			<VentanaFamilia/>
		</div>
		<div class="Informacion">
			<Informacion/>
		</div>
		<div class="IconoVoluta">
			<VolutaIcono/>
		</div>
		<div class="IconoTwitter">
			<TwitterIcono/>
		</div>
		<div class="Cabecera">
			<Cabecera/>
		</div>
		
</div>

		<!-- <div class="Cabecera">
			<Cabecera/>
		</div>

		<div class="Pie">
			<Pie/>
		</div> -->


