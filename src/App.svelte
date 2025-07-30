<script>
  import Editor from './components/Editor.svelte';
  let scratchText = '';
</script>

<main class="min-h-screen bg-white text-black">
  <Editor bind:value={scratchText} />
</main>
