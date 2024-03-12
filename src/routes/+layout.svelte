<script>
  import "../app.css";
    import Header from "../componets/header.svelte";
    import Hero from "../componets/hero.svelte";
    import Timeline from "../componets/timeline.svelte";
    import Timeline2 from "../componets/Timeline2.svelte";
</script>

<slot />
<main class="flex flex-col">
    <Header />
    <Hero />
    <Timeline />
    <Timeline2/>
</main>


