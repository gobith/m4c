<script lang="ts">
  import SectionPrimary from "./SectionPrimary.svelte";
  import SectionSecondary from "./SectionSecondary.svelte";
  import Header from "./Header.svelte";
</script>

<Header />

<!-- <div class="wrapper">
  <SectionPrimary />
  <SectionSecondary />
  <SectionPrimary />
  <SectionSecondary />
  <SectionPrimary />
  <SectionSecondary />
</div> -->
<style>
  .wrapper {
    display: grid;
    /* grid-template-columns: auto auto auto; */
    grid-template-columns: repeat(auto-fit, minmax(20rem, 1fr));
    gap: 1.2rem;
  }

  h1 {
    color: var(--color-primary);
    font-size: var(--font-size-h1);
    font-weight: 100;
    line-height: 4.5rem;
    text-align: center;
  }
</style>
