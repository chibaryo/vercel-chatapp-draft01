<script>
  import TheHeader from '$lib/common/TheHeader.svelte'
  import TheFooter from '$lib/common/TheFooter.svelte'
  import InputArea from '$lib/common/InputArea.svelte'
</script>

<div class="w-full flex flex-col min-h-[100svh]">
  <TheHeader />

  <main class="flex-1 overflow-y-scroll">
    <slot />
  </main>

  <InputArea />
  <!--  <TheFooter /> -->
</div>