<script>
    import { scale } from "svelte/transition";
    export let name;
</script>

<main>
    <div class="karte" transition:scale>
        {name}
    </div>
</main>

<style>
    .karte {
        background-color: lightblue;
        border-radius: 20px;
        padding: 20px;
        margin: 10px 700px;
        font-size: 2em;
    }
</style>
