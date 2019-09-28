<script>
    import Ocultar from "../iconos/Ocultar.svelte";

</script>

<style>
    /* article {
        max-width: 420px;
        background: #FFFFFF;
        border-radius: 0px;
    } 
    article {
        max-width: 420px;

        overflow-y: auto;

    }

    .Detalle {
        max-width: 420px;
        background: #fff;
	    display: flex;
	    justify-content: center;
        align-items: center;
        flex-direction: column;
        flex-wrap: nowrap;
        justify-content: space-between;
        max-height: 850px;
        overflow-y: auto;
        outline: 1px solid blue;
    }

    .Texto {
        display: flex;
        flex-direction: column;
        flex-wrap: nowrap;
        max-width: 350px;
        max-height: 850px;
    }

    .Ocultar {
        position: relative;
        top: -21px;
        left: 180px;
    }
*/
    .Ocultar {
        margin-left: 290px;
        margin-top: -10px;
    }
        
    .Detalle {
        max-width: 350px;
        max-height: 850px;
        padding: 0 1.5em;
        float: right;
        background:#fff;
        
    }
    .Texto {
        max-height: 720px;
        overflow-y: auto;
        background:#fff;
    }

</style>


<section class="Detalle">
    <figure class="Ocultar">
        <Ocultar/>
    </figure>
    <section class="Texto">
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente quod quidem delectus hic aspernatur sit eum rem laborum sequi, recusandae similique ut totam, dolores dignissimos veniam. Voluptatem error ipsam ipsa!
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Assumenda veritatis hic illo dolore a voluptate perspiciatis, beatae nisi odit distinctio maiores reiciendis corporis obcaecati veniam, illum possimus at? Delectus, vitae.
        </p>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit maxime quisquam optio quis aut nihil vero, ex fugiat non totam quidem modi, suscipit laboriosam molestiae placeat eligendi vel qui perspiciatis!
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit maxime quisquam optio quis aut nihil vero, ex fugiat non totam quidem modi, suscipit laboriosam molestiae placeat eligendi vel qui perspiciatis!
        </p>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo consequuntur autem repudiandae ducimus nobis possimus facere sunt sint vero laudantium ex aperiam ipsa a, beatae neque, nostrum dolor animi sit!
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo consequuntur autem repudiandae ducimus nobis possimus facere sunt sint vero laudantium ex aperiam ipsa a, beatae neque, nostrum dolor animi sit!
        </p>
        <p>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eius consequuntur commodi sed amet cum quasi minima voluptatum placeat est necessitatibus. Atque repudiandae laboriosam illum ea, magnam voluptatum sapiente architecto amet!
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eius consequuntur commodi sed amet cum quasi minima voluptatum placeat est necessitatibus. Atque repudiandae laboriosam illum ea, magnam voluptatum sapiente architecto amet!
        </p>
    </section>
</section>