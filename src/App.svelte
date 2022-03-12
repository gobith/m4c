<script lang="ts">
</script>

<h1>Soops</h1>
<div class="wrapper">
  <section>
    <h2>Lorem, ipsum dolor.</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum
      perferendis velit repudiandae quae! Dignissimos veniam vel voluptatibus
      adipisci distinctio eius dicta cum, impedit modi inventore sapiente sit
      harum ut iste ipsam repellendus ab expedita tempora. Dignissimos nisi
      perspiciatis necessitatibus voluptas eaque repellat culpa, neque placeat
      corporis, atque, debitis accusamus. Eveniet magni quis voluptas esse?
      Ipsam culpa ut eum quia repudiandae natus voluptatum explicabo iure at
      tempore maiores iste provident eaque ratione quis, neque, aperiam
      voluptates exercitationem dolor voluptatem optio laboriosam.
      Necessitatibus, incidunt. Natus inventore labore reiciendis hic, nostrum,
      reprehenderit blanditiis, nemo vitae perspiciatis corporis consectetur
      molestiae saepe nam voluptatum ab!
    </p>
    <button>click me</button>
  </section>

  <section class="section-complementary">
    <h2>Lorem, ipsum dolor.</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum
      perferendis velit repudiandae quae! Dignissimos veniam vel voluptatibus
      adipisci distinctio eius dicta cum, impedit modi inventore sapiente sit
      harum ut iste ipsam repellendus ab expedita tempora. Dignissimos nisi
      perspiciatis necessitatibus voluptas eaque repellat culpa, neque placeat
      corporis, atque, debitis accusamus. Eveniet magni quis voluptas esse?
      Ipsam culpa ut eum quia repudiandae natus voluptatum explicabo iure at
      tempore maiores iste provident eaque ratione quis, neque, aperiam
      voluptates exercitationem dolor voluptatem optio laboriosam.
      Necessitatibus, incidunt. Natus inventore labore reiciendis hic, nostrum,
      reprehenderit blanditiis, nemo vitae perspiciatis corporis consectetur
      molestiae saepe nam voluptatum ab!
    </p>
    <button>click me</button>
  </section>
  <section>
    <h2>Lorem, ipsum dolor.</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum
      perferendis velit repudiandae quae! Dignissimos veniam vel voluptatibus
      adipisci distinctio eius dicta cum, impedit modi inventore sapiente sit
      harum ut iste ipsam repellendus ab expedita tempora. Dignissimos nisi
      perspiciatis necessitatibus voluptas eaque repellat culpa, neque placeat
      corporis, atque, debitis accusamus. Eveniet magni quis voluptas esse?
      Ipsam culpa ut eum quia repudiandae natus voluptatum explicabo iure at
      tempore maiores iste provident eaque ratione quis, neque, aperiam
      voluptates exercitationem dolor voluptatem optio laboriosam.
      Necessitatibus, incidunt. Natus inventore labore reiciendis hic, nostrum,
      reprehenderit blanditiis, nemo vitae perspiciatis corporis consectetur
      molestiae saepe nam voluptatum ab!
    </p>
    <button>click me</button>
  </section>
</div>

<style>
  :global(*) {
    font-size: 16px;
  }

  :root {
    --color-primary: #05086b;
    --color-secondary: #93a5b5;
    --color-complementary: #b87a1c;
    --color-white: white;
    --color-black: black;

    /* font-family: Arial, helvetica, sans-serif; */
  }

  .wrapper {
    display: grid;
    /* grid-template-columns: auto auto auto; */
    grid-template-columns: repeat(auto-fill, minmax(20rem, 1fr));
    gap: 1.2rem;
    margin: 1rem;
  }

  .section-complementary {
    color: var(--color-white);
    background-color: var(--color-primary);
  }

  h1 {
    color: var(--color-primary);
    font-size: 4rem;
    text-align: center;
  }

  section {
    border: 1px solid var(--color-primary);
    border-radius: 0.3rem;
    padding: 1rem;
  }

  h2 {
    color: var(--color-primary);
    font-size: 1.4rem;
    text-align: center;
  }

  p {
    font-size: 1rem;
  }

  button {
    color: var(--color-white);
    background-color: var(--color-complementary);
    padding: 0.6rem 1rem;
    border: none;
    border-radius: 0.3rem;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    cursor: pointer;
    font-size: 1.2rem;
    transition: background-color 0.3s;
    float: right;
  }

  button:hover {
    background-color: var(--color-secondary);
  }
</style>
