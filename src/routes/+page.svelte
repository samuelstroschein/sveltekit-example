<script lang="ts">
  import { setLanguageTag } from "@inlang/paraglide-js/example";
  import * as m from "@inlang/paraglide-js/example/messages";
</script>

<h1>{m.hello()}</h1>
<!-- <p>{@html m.docs()}</p> -->

<button on:click={() => setLanguageTag("de")}>change the language to DE</button>
<button on:click={() => setLanguageTag("en")}>change the language to EN</button>
