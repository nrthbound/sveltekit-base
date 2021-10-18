<script>
  import src from './logo.svg'
  const navItems = [
    {id: 1, title: 'Dashboard', url: '/'},
    {id: 2, title: 'About', url: '/about'},
    {id: 3, title: 'Settings', url: '/settings'},
  ]
</script>

<nav class="bg-gray-100 py-4">
  <div class="max-w-5xl mx-auto flex items-center">
    <a class:active="{false}" href="/" class="h-8 w-8 mr-10">
      <img {src} alt="Sveltekit Boilerplate" />
    </a>
    {#each navItems as item}
      <a href={item.url} class="mr-8 text-gray-600">
        {item.title}
      </a>
    {/each}
  </div>
</nav>
