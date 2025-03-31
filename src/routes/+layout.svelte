<script lang="ts">
  import '../app.css';
  let { children } = $props();
</script>

<svelte:head>
  <title>使用样例</title>
</svelte:head>

{@render children()}
