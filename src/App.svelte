<script>
  import Navbar from "./Navbar.svelte";
  import Title from "./Title.svelte";
  let fruits = ["apple", "orange", "lemon"];
</script>

<Navbar />

{#each fruits as fruit}
  <h1>fruit: {fruit}</h1>
{/each}

{#each fruits as fruit}
  <Title titleName={fruit} />
{/each}
