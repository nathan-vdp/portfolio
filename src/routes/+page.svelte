<script>
    import Header from '$lib/Header.svelte';
    import Background from '../lib/assests/future.png';
    import Projects from '$lib/Projects.svelte';
</script>

<main>
    <div style="position: relative; width: 100%; height: 100vh;">
        <img src={Background} alt="background" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; z-index: 0; object-fit: cover;" />
        <div style="position: relative; z-index: 1;" class="flex items-center justify-center">
            <Header />
        </div>
    </div>
    <Projects />
</main>

<style>
    main {
        overflow: hidden;
    }
    img {
        background-size: cover;
        background-color: #6819fe;
        background-attachment: fixed;
    }
</style>

