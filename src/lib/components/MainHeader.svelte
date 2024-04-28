<script lang="ts">
  import Logo from "$lib/components/svg/Logo.svelte";
  import LinkedIn from "$lib/components/svg/LinkedIn.svelte";
  import Github from "$lib/components/svg/Github.svelte";
  import IconLink from "$lib/components/IconLink.svelte";
  import DarkmodeButton from "$lib/components/DarkmodeButton.svelte";
</script>

<header
  class="fixed z-10 top-0 inset-x-0 border-b"
>
  <nav
    class="flex items-center justify-between max-w-5xl mx-auto
        px-4 h-24"
  >
    <a href="/">
      <Logo class="w-20 h-20 dark:fill-white " />
    </a>

    <div class="flex space-x-1 items-center">
      <IconLink
        href="https://www.linkedin.com/in/silviangulica/"
        target="_blank"
      >
        <LinkedIn class="w-7 h-8" />
      </IconLink>

      <IconLink href="https://github.com/silviangulica" target="_blank">
        <Github class="w-7 h-8 " />
      </IconLink>
      <DarkmodeButton />
    </div>
  </nav>
</header>
