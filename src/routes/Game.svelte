<script>
  import Grid from "./Grid.svelte";

</script>

<div class="game">
    <div class="info"/>
    
    <div class="grid-container">
    <Grid />
    </div>

    <div class="info"/>

</div>


<style>
    .game{
        display: flex; 
        flex-direction: column; 
        justify-content: center;
        align-items: center;
        height: 100%;
        font-size: min(1vmin, 0.1rem);
    }

    .info{
        width: 80vmin;
        height: 10vmin; 
        background: purple;

    }

    .grid-container{
        width: 80vmin;
        height: 80vmin;
        background: turquoise;
    }
</style>