<script>
  export let value = '';
</script>

<div
  contenteditable="true"
  class="w-full h-full p-6 font-sans text-lg outline-none leading-relaxed whitespace-pre-wrap"
  bind:innerText={value}
></div>
