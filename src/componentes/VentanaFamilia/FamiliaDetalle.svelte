<script>
    import Ocultar from "../iconos/Ocultar.svelte";

</script>

<style>
    * {
        outline: 1px solid blue;
    }

    section {
        width: 100%
    }

        
    .Detalle {
        width: 200%;
        padding: 0 1.5em;
        /* float: right; */
        background-color: #fff;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        flex-wrap: nowrap;
        justify-content: space-between;
    }

    .Texto {
        max-height: 46.5rem;
        background:#fff;
        font-size: 1rem;
        line-height: 2rem;
        overflow-y: auto;
        text-align: justify;
        color: #454344;
    }

</style>


<section class="Detalle">
    <i class="Ocultar">icono ocultar</i>
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