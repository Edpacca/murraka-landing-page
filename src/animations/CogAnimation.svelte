<script>
    import Cog1 from "../vectors/Cog1.svelte";
    import Cog2 from "../vectors/Cog2.svelte";


</script>


<div class="animation-container">
    <div class="cog outer">
        <Cog1/>
    </div>
    <div class="cog inner">
        <Cog2/>
    </div>
</div>

<style>
    .animation-container {
        position: relative;
        width: 80vh;
        height: 80vh;
        border: 2px solid yellow;
    }

    .cog {
        position: absolute;
        margin: auto;
        left: 0;
        right: 0;
        top: 0;
        bottom: 0;
    }

    .outer {
        fill: burlywood;
        width: 512px;
        animation: rotate 20s linear infinite;
    }
    
    .inner {
        fill: red;
        width: 332px;
        animation: rotate 26s linear infinite reverse;
    }

    @keyframes rotate {
        0% {
            rotate: 0deg;
        }

        100% {
            rotate: 360deg;
        }
    }

</style>
