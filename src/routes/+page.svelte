<script>

</script>

<svelte:head>
    <title>Hello</title>
    <meta name="description" content="Remember whats on this page"/>
</svelte:head>

<div class="fullpage">
	<div class="centerflex">
	<h1>Remember to be nice</h1>
	</div>
</div>


<style>
    .fullpage {
        height: 100vh;
        width: 100vw;
        position: fixed;
		background-color: oklab(0.78 0.07 0);
    }
	
	.centerflex {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100%;
	}

    h1 {
        z-index: 20;
        font-family: "Courier New", monospace;
        font-size: 4rem;
        color: oklab(0.32 0 0.06);
    }

    @media only screen and (max-width: 750px) {
        h1 {
            font-size: 1.5rem;
        }
    }

    :global(body) {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        overflow: hidden;
    }
</style>
