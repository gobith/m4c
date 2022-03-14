<script lang="ts">
  import SectionPrimary from "./SectionPrimary.svelte";
  import SectionSecondary from "./SectionSecondary.svelte";
</script>

<div class="container">
  <SectionPrimary />
  <SectionSecondary />
  <SectionPrimary />
  <SectionSecondary />
  <SectionPrimary />
  <SectionSecondary />
  <SectionPrimary />
  <SectionSecondary />
  <SectionPrimary />
  <SectionSecondary />
  <SectionPrimary />
  <SectionSecondary />
  <SectionPrimary />
  <SectionSecondary />
  <SectionPrimary />
  <SectionSecondary />
  <SectionPrimary />
  <SectionSecondary />
</div>

<style>
  .container {
    margin-top: 1.2rem;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(20rem, 1fr));
    gap: 1.2rem;
    padding: 0 0.8rem;
  }

  @media screen and (min-width: 1200px) {
    .container {
      padding: 0;
    }
  }
</style>
