<script>
  import { onMount } from 'svelte';
  import { goto } from '$app/navigation';

  onMount(() => {
    goto('/parent/child')
  })
</script>

<span class="text-6xl font-bold text-blue-700 flex justify-center items-center h-screen">Parent</span>