# Svelte Starter: Tailwind | Typescript | MDX

A tiny starter template for Svelte + SvelteKit with inbuilt support for Tailwind, Typescript, and MDX files.
Write Svelte code inside markdown files!

```svelte
<script>
  let count = 0;
  $: message = (count > 0) ? "Keep on going, get that counter up!": "Click the button on the right!"
</script>
<div class="flex my-8 justify-center">
  <button 
    class="bg-primary-300 px-3 py-2 rounded shadow hover:bg-primary-400 active:bg-primary-500" 
    on:click={() => { count += 1; }}
  >{message}</button>
  <p class="text-xl px-2 py-2 ml-8">{count}</p>
</div>
```
