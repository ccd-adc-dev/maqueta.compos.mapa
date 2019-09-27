<script>
    import Agrupacion from "./Agrupacion.svelte";
    import BotonCerrar from "../botones/BotonCerrar.svelte";
    import Flecha from "../iconos/Flecha.svelte";

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
        position: relative;
        left: 285px;
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
        margin: 0.2em;
    }

    .Principal {
        text-align: center;
        font-weight: 600;
        font-size: 44px;
        line-height: 53px;
        text-align: center;
        color: #E6AA30;
        margin: 0.2em;
    }

    .Saber {
        width: 105px;
        height: 26px;
        position: relative;
        left: 5px;
        border: 1px solid #E6AA30;
        box-sizing: border-box;
        border-radius: 15px;
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

    .Flecha {
        width: 44px;
        height: 22px;
        position: relative;
        left: 300px;
        top: 45px;
        border: 1px solid #C9C9C9;
    }

   
/* Cambiar estos valores en global.css */
/* TO DO Agregar font Fira Sans en estilos global en proyecto mapa interactivo */
    button {
        padding: 0 0.4em;
	    margin: 0 0 1em 0;
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

    <div class="Slider">
    </div>

    <article class="Contenedor-1">
        <div class="Flecha">
            <Flecha/>
        </div>
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

</article>

