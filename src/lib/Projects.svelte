<script>
    import { Card, Button } from 'flowbite-svelte';
    import { ArrowRightOutline } from 'flowbite-svelte-icons';
    let Background = '$lib/assets/projectimg1.jpg';
    let Background2 = '$lib/assets/projectimg2.png';
    let vCard = false;
  </script>

<div class="flex flex-col sm:flex-row justify-center gap-4">
    <Card img={Background} reverse={vCard}>
      <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Pokedex </h5>
      <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 leading-tight">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
      <Button>
        See my project <ArrowRightOutline class="w-6 h-6 ms-2 text-white" />
      </Button>
    </Card>
    <Card img={Background2} reverse={vCard}>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Pokedex </h5>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 leading-tight">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
        <Button>
          See my project <ArrowRightOutline class="w-6 h-6 ms-2 text-white" />
        </Button>
    </Card>
</div>