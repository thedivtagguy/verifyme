<script context="module">
    export const load = async ({ url }) => ({ props: { url } });
</script>

<script>
  import "$styles/app.css";
  export const router = true;
  import PageTransition from "$components/helpers/PageTransition.svelte";
  export let url;
</script>

<main class="max-w-7xl mx-auto px-6" id="content">
  <PageTransition {url}>
    <slot />
  </PageTransition>
</main>
