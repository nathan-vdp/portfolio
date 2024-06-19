<script>
	import Me from './assests/me.jpg';
    import Techstack from '$lib/Techstack.svelte';
</script>

<div id="about" class="container flex flex-col-reverse md:flex-row justify-center items-center h-screen font-poppins">
    <div class="flex flex-col items-center md:items-start ml-5">
        <h1 class="text-5xl font-bold text-white font-poppins text-center md:text-left">Front-End Developer</h1>
        <p class="text-lg mt-5 text-center md:text-left text-white">Hi, I'm Nathan. A passionate front-end developer <br>
            based in the Netherlands
        </p>
        <div class="flex mt-5">
            <a href="https://github.com/nathan-vdp" class="text-3xl hover:text-purple-500 mt-3 text-white dark:hover:text-purple-500"><i class="bx bxl-github"></i></a>
            <a href="https://www.linkedin.com/in/nathan-van-de-pieterman-869446250/" class="text-3xl hover:text-purple-500 mt-3 text-white dark:hover:text-purple-500"><i class="bx bxl-linkedin-square icon"></i></a>
        </div>
        <Techstack />
    </div>
    <div class="hero-image">
        <img class="w-52 rounded-full" src={Me} alt="Me" />
    </div>
</div>

<style>
    .hero-image img {
        animation: morph 8s ease-in-out infinite;
    }

    @keyframes morph {
    0% {
        border-radius: 60% 40% 30% 70%/60% 30% 70% 40%;
    }

    50% {
        border-radius: 30% 60% 70% 40%/50% 60% 30% 60%;
    }

    100% {
        border-radius: 60% 40% 30% 70%/60% 30% 70% 40%;
    }
}
</style>