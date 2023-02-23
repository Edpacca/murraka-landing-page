<script lang="ts">
    import CogAnimation from "./animations/CogAnimation.svelte";
import Button from "./common/Button.svelte";
</script>

<main>
	<Button content="Isle of Murraka" onClick={() => {console.log("clicked")}}/>
    <CogAnimation/>
</main>

<style>
    main {
        width: 100vw;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }
</style>