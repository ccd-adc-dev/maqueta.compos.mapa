<script>
    import Agrupacion from "./Agrupacion.svelte";
    import BotonCerrar from "../botones/BotonCerrar.svelte";
    import Flecha from "../iconos/Flecha.svelte";
    import Carrousel from "../iconos/Carrousel.svelte";
    import FamiliaDetalle from "./FamiliaDetalle.svelte";



    let elemento = { activo: false };
	const Mostrar = () => {
		elemento.activo = !elemento.activo;
    }
    
</script>

<style>

    article {
        max-width: 100%;
	}

    .Familia {
        max-width: 35%;
        background: #F7F7F7;
        border-radius: 10px;
	    display: flex;
	    justify-content: center;
        align-items: center;
        flex-direction: column;
        flex-wrap: nowrap;
        justify-content: space-between;
        max-height: 48rem;
    }

    .Encabezado {
        margin-top: -3rem;
    }

    .Contenedor-1 {
        display: flex;
        align-items: center;
        flex-direction: column;
        /* flex-wrap: nowrap; */
        /* justify-content: space-between; */
        overflow-y: auto;
        
    }

    .Cerrar {
        margin-left: 36rem;
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
        font-size: 1.5rem;
        line-height: 1rem;
        letter-spacing: 0.5rem;
        color: #454344;
        margin: 0.5rem;
    }

    .Principal {
        text-align: center;
        font-weight: 600;
        font-size: 2.5rem;
        line-height: 3rem;
        text-align: center;
        color: #E6AA30;
        margin: 0.5rem;
    }

    .Saber {
        width: 17%;
        height: 10%;
        border: 1px solid #E6AA30;
        box-sizing: border-box;
        border-radius: 15px;
        color: #E6AA30;
    }

    .TitulosLista {
        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
        justify-content: space-between;
        margin: 1rem;
    }

    .TextoFotos {
        position: relative;
        top: -16%;
        left: -39%;
        color: #fff;
    }

    .Flecha {
        width: 50%;
        margin-top: 3rem;
        margin-left: 16rem;
        margin-bottom: -1.5rem;
    }

    .Carrousel {
        margin-top: -6rem;
    }

    .Contenedor-2 {
        width: 100%;
        margin-top: -6%;
    }

    .FamiliaDetalle {
        position: absolute;
        left: 35%;
        top: 0.6%;
        right: 55%;
    }

    .Lista {
        margin-right: 1rem;
        margin-left: -3.5rem;
    }

   
/* Cambiar estos valores en global.css */
/* TO DO Agregar font Fira Sans en estilos global en proyecto mapa interactivo */
    button {
        padding: 0 0.5rem;
	    margin: 0 0 1rem 0;
    }

</style>

<article class="Familia">
    <figure class="Cerrar">
        <i>Icono cerrar</i>
    </figure>
    <header class="Encabezado">
        <p class="Titulo">
            FAMILIA
        </p>
        <h1 class="Principal">
            Yuto-nahua
        </h1>
    </header>
        {#if elemento.activo}
	    <button class="Saber" on:click={Mostrar}>
	    	Saber más
	    </button>
        <div class="FamiliaDetalle">
	        <FamiliaDetalle/>
        </div>
        {/if}

        {#if !elemento.activo}
	    <button class="Saber" on:click={Mostrar}>
	    	Saber más
	    </button>
        {/if}
        <div class="Contenedor-1">
	        <img class="Imagen" src={`http://unsplash.it/300/${100+Math.floor(Math.random()*500)}`} alt="img"/>
            <div class="TextoFotos">
                <p>
                    Titulo Foto
                </p>
                <p>
                    Descripción
                </p>
            </div>

            <div class="Carrousel">
                <Carrousel/>
            </div>

            <article class="Contenedor-2">
                <figure class="Flecha">
                    <Flecha/>
                </figure>
                <header class="TitulosLista">
                    <h4>
                        Agrupaciones Lingüísticas
                    </h4>
                    <h4>
                        Riesgo de desaparición
                    </h4>
                </header>
                    <section class="Lista">
                        <ul>
                        <Agrupacion/>
                        <Agrupacion/>
                        <Agrupacion/>
                        </ul>
                    </section>
            </article>
        </div>
</article>









