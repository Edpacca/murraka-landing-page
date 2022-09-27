<script lang="ts">
    import Button from "./common/Button.svelte";
    import Filters from "../assets/filters.svg";
</script>

<main>
	<Button content="Isle of Murraka" onClick={() => {console.log("clicked")}}/>
    <Filters/>
</main>

<style>
    main {
        width: 100vw;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>