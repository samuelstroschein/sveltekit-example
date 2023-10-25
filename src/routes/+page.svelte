<script lang="ts">
  import * as m from "@inlang/paraglide-js/sveltekit-example/messages";
  import { setLanguageTag, languageTag } from "@inlang/paraglide-js/sveltekit-example";
</script>

<p>{m.greeting({ name: "Samuel", count: 5 })}</p>
<p>{m.currentLanguageTag({ languageTag: languageTag() })}</p>
<button on:click={() => setLanguageTag("de")}>change language to "de"</button>
<button on:click={() => setLanguageTag("en")}>change language to "en"</button>
 