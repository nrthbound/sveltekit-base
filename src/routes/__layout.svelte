<script>
  import "../app.scss";
</script>
<nav class="bg-gray-100 py-4">
  <div class="max-w-5xl mx-auto flex items-center">
    <a href="/" class="h-8 w-8 mr-10">
      <img src="logo.svg" alt="Logo" />
    </a>
    <a href="/about" class="mr-8 text-gray-600">
      About
    </a>
    <a href="/settings" class="text-gray-600">
      Settings
    </a>
  </div>
</nav>

<slot />


<style lang="scss">

</style>
