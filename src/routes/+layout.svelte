<script>
    import "../app.css";
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
</script>
<Navbar  >
    <NavBrand href="/">
      <span class="self-center whitespace-nowrap text-xl font-bold dark:text-white">Nathan.dev</span>
    </NavBrand>
    <NavHamburger  />
    <NavUl >
        <NavLi href="/">Home</NavLi>
        <NavLi href="/about">About</NavLi>
        <NavLi href="/projects">Projects</NavLi>
        <NavLi href="/resume">Resume</NavLi>
    </NavUl>
</Navbar>

<slot />