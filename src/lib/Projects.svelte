<script>
    import { Card, Button, A } from 'flowbite-svelte';
    import { ArrowRightOutline } from 'flowbite-svelte-icons';
    import Background from '$lib/assets/projectimg1.png';
    import Background2 from '$lib/assets/projectimg2.png';
    let vCard = false;
  </script>

<div id="projects" class="flex flex-col sm:flex-row justify-center gap-10">
    <Card img={Background} reverse={vCard}>
      <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Pokedex </h5>
      <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 leading-tight">This Pokédex project was a team project where I and three other students worked together. It was a good way to learn more about APIs and Svelte.</p>
      <a href="https://teampokedex.netlify.app/"><Button>
        See my project <ArrowRightOutline class="w-6 ms-2 text-white" />
       </Button></a>
    </Card>
    <Card img={Background2} reverse={vCard}>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Meeet homepage </h5>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 leading-tight">This is a front-end project for a front page named "Meeet" It is designed to provide a modern look to a frontpage with mobile first in mind</p>
        <a href="https://vandepieterman.net/projects/meeetfrontpage/"><Button>
         See my project <ArrowRightOutline class="w-6 ms-2 text-white" />
        </Button></a>
    </Card>
</div>