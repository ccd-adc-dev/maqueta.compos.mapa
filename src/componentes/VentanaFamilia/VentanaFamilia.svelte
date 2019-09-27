<script>
    import Agrupacion from "./Agrupacion.svelte";
    import BotonCerrar from "../botones/BotonCerrar.svelte";

</script>

<style>

    article {
        max-width: 640px;
        max-height: 1617px;
        overflow-y: hidden;
	}

    .Familia {
        background: #F7F7F7;
        border-radius: 10px;
	    display: flex;
	    justify-content: center;
        align-items: center;
        flex-direction: column;
        flex-wrap: nowrap;
        justify-content: space-between;
    }

    .Cerrar {
        left: 285px;
        position: relative;
    }

    img {
		width: 580px;
		height: 455px;
        object-fit: cover;
        box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
        border-radius: 5px;
    }
    
    .Titulo {
        text-align: center;
        font-weight: 200;
        font-size: 24px;
        line-height: 29px;
        letter-spacing: 0.2em;
        color: #454344;
    }

    .Principal {
        text-align: center;
        font-weight: 600;
        font-size: 44px;
        line-height: 53px;
        text-align: center;
        color: #E6AA30;
        padding: 0;
    }

    .Saber {
        width: 105px;
        height: 26px;
        border: 1px solid #E6AA30;
        box-sizing: border-box;
        border-radius: 15px;
        left: 5px;
        position: relative;
        color: #E6AA30;
    }
    

    /* .Cerrar {
        height:20px;
        width:20px;
        border-radius:20px / 20px;
        border: 1px solid #878787;
        box-sizing: border-box;
    } */

    .TitulosLista {
        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
        justify-content: space-between;
        margin: 1em;
    }

    .TextoFotos {
        position: relative;
        top: -102px;
        left: -220px;
        color: #fff;
    }

    .Contenedor-1 {
        background: #F7F7F7;
    }

</style>

<article class="Familia">
    <div class="Cerrar">
        <BotonCerrar/>
    </div>
    <header>
        <p class="Titulo">
            Familia
        </p>
        <h1 class="Principal">
            Yuto-nahua
        </h1>
    </header>
        <button class="Saber">
            Saber más
        </button>
         <!-- <img src="http://fakeimg.pl/244x80?text=logo" alt="img" /> -->
	<img class="Imagen" src={`http://unsplash.it/300/${100+Math.floor(Math.random()*500)}`} alt="img"/>
        <div class="TextoFotos">
            <p>
                Titulo Foto
            </p>
            <p>
                Descripción
            </p>
        </div>
</article>

<div class="Slider">
</div>

<i>Flecha</i>

<article class="Contenedor-1">
<header class="TitulosLista">
    <h4>
        Agrupaciones Lingüísticas
    </h4>
    <h4>
        Riesgo de desaparición
    </h4>
</header>
    <section>
        <ul>
        <Agrupacion/>
        <Agrupacion/>
        <Agrupacion/>
        </ul>
    </section>

</article>