<style>

    article {
        max-width: 640px;
        max-height: 1617px;
        overflow-y: hidden;
	}

    .Familia {
        background: #F7F7F7;
        border-radius: 10px;
    }

    .Imagen {
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
        left: 10px;
        top: 5px;
        border: 1px solid #E6AA30;
        box-sizing: border-box;
        border-radius: 15px;
        align-items: center;
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

	    <img class="Imagen" src={`http://unsplash.it/300/${100+Math.floor(Math.random()*500)}`} alt="img"/>
            <p>
                Titulo Foto
            </p>
            <p>
                Descripcion
            </p>
</article>

<article class="Contenedor-1">



</article>