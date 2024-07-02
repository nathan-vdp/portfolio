<script>
    import { Footer, FooterCopyright, FooterLinkGroup, FooterBrand, FooterLink } from 'flowbite-svelte';
  </script>

  <Footer>
    <div class="sm:flex sm:items-center sm:justify-between">
      <FooterBrand href="https://github.com/nathan-vdp" name="Nathan.dev" />
      <FooterLinkGroup ulClass="flex flex-wrap items-center mb-6 text-sm text-gray-500 sm:mb-0 dark:text-gray-400 pt-3 pl-3">
        <FooterLink href="https://github.com/nathan-vdp">GitHub</FooterLink>
        <FooterLink href="/">About</FooterLink>
        <FooterLink href="mailto:nathan.vandepieterman@student.rocva.nl">Contact</FooterLink>
      </FooterLinkGroup>
    </div>
    <hr class="my-6 border-gray-200 sm:mx-auto dark:border-gray-700 lg:my-8 pl-5" />
    <FooterCopyright href="/" by="Nathan" />
  </Footer>