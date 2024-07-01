<script>
    import { Card, Button, A } from 'flowbite-svelte';
    import { ArrowRightOutline } from 'flowbite-svelte-icons';
    import Background from '$lib/assets/projectimg1.png';
    import Background2 from '$lib/assets/projectimg2.png';
    let vCard = false;
  </script>

<div class="flex flex-col sm:flex-row justify-center gap-4">
    <Card img={Background} reverse={vCard}>
      <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Pokedex </h5>
      <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 leading-tight">This pokedex was a project to learn more about Svelte. It uses the PokeAPI to get all the data.</p>
      <Button>
        <a href="teampokedex.netlify.app/">See my project</a> <ArrowRightOutline class="w-6 h-6 ms-2 text-white" />
      </Button>
    </Card>
    <Card img={Background2} reverse={vCard}>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Meeet homepage </h5>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 leading-tight">This is a front-end project for a front page named "Meeet" It is designed to provide a modern look to a frontpage with mobile first in mind</p>
        <a href="https://vandepieterman.net/projects/meeetfrontpage/"><Button>
         See my project <ArrowRightOutline class="w-6 ms-2 text-white" />
        </Button></a>
    </Card>
</div>