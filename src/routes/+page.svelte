<script>

</script>

<svelte:head>
    <title>Home</title>
    <meta name="description" content="Under Construction"/>
</svelte:head>

<div class="fullpage">
    <div class="flag">
        <div style="z-index: 14"  class="flagsection pink"></div>
        <div style="z-index: 13"  class="flagsection blue"></div>
        <div style="z-index: 12"  class="flagsection pink"></div>
        <div style="z-index: 11"  class="flagsection white"><h1>Under Construction</h1></div>
        <div style="z-index: 10"  class="flagsection pink"></div>
        <div style="z-index: 09"  class="flagsection blue"></div>
        <div style="z-index: 08"  class="flagsection pink"></div>
        <div style="z-index: 07"  class="flagsection white"><h1>Under Construction</h1></div>
        <div style="z-index: 06"  class="flagsection pink"></div>
        <div style="z-index: 05"  class="flagsection blue"></div>
        <div style="z-index: 04"  class="flagsection pink"></div>
        <div style="z-index: 03"  class="flagsection white"><h1>Under Construction</h1></div>
        <div style="z-index: 02"  class="flagsection pink"></div>
        <div style="z-index: 01"  class="flagsection blue"></div>
    </div>
</div>


<style>
    .fullpage {
        height: 100vh;
        width: 100vw;
        position: fixed;
    }

    h1 {
        z-index: 20;
        font-family: "Courier New", monospace;
        font-size: 4rem;
    }

    .flagsection {
        width: 100%;
        height: 20vh;
        box-shadow: 0 5px 10px 1px;
        position: relative;
        display: flex;
        align-items: center;
        padding: 0 2rem;
    }

    .flag {
        position: relative;
        display: flex;
        height: 280vh;
        flex-direction: column;
        animation-name: scrolldown;
        animation-duration: 4s;
        animation-iteration-count: infinite;
        animation-timing-function: cubic-bezier(.18,.89,.32,1.28);
    }


    .blue {
        background-color: #5BCEFA;
    }

    .pink {
        background-color: #F5A9B8;
    }

    .white {
        background-color: #FFF;
    }

    :global(body) {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        overflow: hidden;
    }

    @keyframes scrolldown {
        from {
            transform: translateY(-20vh);
        }
        80%,
        100% {
            transform: translateY(-180vh);
        }
    }
</style>
