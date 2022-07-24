<script>
  import "../app.css"
</script>

<svelte:head>
	<meta charSet="utf-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1" />
	<link rel="manifest" href="/site.webmanifest" />
	<link rel="apple-touch-icon" href="/favicon.png" />
	<meta name="theme-color" content="#fff" />
</svelte:head>

<div class="w-screen h-screen">
  <div class="max-w-screen-md m-auto py-12">
    <slot />
  </div>
</div>