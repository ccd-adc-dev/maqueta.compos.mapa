<script>
    import Agrupacion from "./Agrupacion.svelte";
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

    img {
		width: 100%;
		height: 12rem;
        object-fit: cover;
        box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
        border-radius: 5px;
    }
    
    .Titulo {
        text-align: center;
    }

    .Principal {
        text-align: center;
    }

    .Saber {
        width: 105px;
        height: 26px;
        border: 1px solid #E6AA30;
        box-sizing: border-box;
        border-radius: 15px;
    }

    .Cerrar {
        height:20px;
        width:20px;
        border-radius:20px / 20px;
        border: 1px solid #878787;
        box-sizing: border-box;
    }



</style>

<article class="Familia">
    <button class="Cerrar">
    </button>
    <header>
        <p class="Titulo">
            Familia
        </p>
        <h1 class="Principal">
            Yuto-Nahua
        </h1>
        <button class="Saber">
            Saber mas
        </button>
    </header>
         <!-- <img src="http://fakeimg.pl/244x80?text=logo" alt="img" /> -->
	<img class="Imagen" src={`http://unsplash.it/300/${100+Math.floor(Math.random()*500)}`} alt="img"/>
        <p>
            Titulo Foto
        </p>
        <p>
            Descripcion
        </p>
</article>

<div class="slider">

</div>
<i>Flecha</i>

<article class="Contenedor-1">
    <h5>
        Agrupaciones Linguisticas
    </h5>
    <h5>
        Riesgo de desaparicion
    </h5>
    <section>
        <ul>
        <Agrupacion/>
        <Agrupacion/>
        <Agrupacion/>
        </ul>
    </section>


</article>