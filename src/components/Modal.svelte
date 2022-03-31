<script>
    // imports
    // import "../styles.css";

    // variables
    export let showModal = false;

    // functions
</script>

{#if showModal}
    <div class="backdrop" on:click|self>
        <div class="modal">
            <slot />
        </div>
    </div>
{/if}

<style>
    .backdrop {
        width: 100%;
        height: 100%;
        position: fixed;
        background: rgba(0, 0, 0, 0.9);
        z-index: 1000;
        /* margin: 0; */
        /* padding: 0; */
    }

    .modal {
        padding: 10px;
        border-radius: 10px;
        max-width: 500px;
        margin: 20px auto;
        text-align: center;
        background: white;
    }
</style>
