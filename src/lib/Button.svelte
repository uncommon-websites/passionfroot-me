<script lang="ts">
  export let type: 'primary' | 'secondary' | 'outline' | 'white' = 'primary';
  export let href: string | undefined = undefined;
  export let className = '';
</script>

{#if href}
  <a
    {href}
    class="inline-flex items-center justify-center px-6 py-3 rounded-full font-medium transition-transform active:scale-95 {className}
    {type === 'primary' ? 'bg-dark text-white hover:bg-gray-800' : ''}
    {type === 'secondary' ? 'bg-orange-brand text-white hover:bg-orange-600' : ''}
    {type === 'outline' ? 'border border-gray-300 bg-transparent hover:bg-gray-100' : ''}
    {type === 'white' ? 'bg-white text-dark hover:bg-gray-50' : ''}"
  >
    <slot />
  </a>
{:else}
  <button
    class="inline-flex items-center justify-center px-6 py-3 rounded-full font-medium transition-transform active:scale-95 {className}
    {type === 'primary' ? 'bg-dark text-white hover:bg-gray-800' : ''}
    {type === 'secondary' ? 'bg-orange-brand text-white hover:bg-orange-600' : ''}
    {type === 'outline' ? 'border border-gray-300 bg-transparent hover:bg-gray-100' : ''}
    {type === 'white' ? 'bg-white text-dark hover:bg-gray-50' : ''}"
  >
    <slot />
  </button>
{/if}
