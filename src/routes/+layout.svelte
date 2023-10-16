<script lang="ts">
  import ParaglideJsSvelteKitProviderSSR from "../lib/ParaglideJsSvelteKitProviderSSR.svelte";
  import ParaglideJsSvelteKitProviderCSR from "../lib/ParaglideJsSvelteKitProviderCSR.svelte";
</script>

<!-- <ParaglideJsSvelteKitProviderSSR>
  <slot />
</ParaglideJsSvelteKitProviderSSR> -->

<ParaglideJsSvelteKitProviderCSR>
  <slot />
</ParaglideJsSvelteKitProviderCSR>
