<script lang="ts">
  import Mef4Cap from "./MEF4CAP.svelte";
  import SectionPrimary from "./SectionPrimary.svelte";
  import SectionSecondary from "./SectionSecondary.svelte";
</script>

<Mef4Cap />
<!-- <h1>Soops</h1> -->
<div class="wrapper">
  <SectionPrimary />
  <SectionSecondary />
  <SectionPrimary />
  <SectionSecondary />
  <SectionPrimary />
  <SectionSecondary />
</div>

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
