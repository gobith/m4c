<section>
  <h2>Lorem ipsum dolor</h2>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum perferendis
    velit repudiandae quae! Dignissimos veniam vel voluptatibus adipisci
    distinctio eius dicta cum, impedit modi inventore sapiente sit harum ut iste
    ipsam repellendus ab expedita tempora. Dignissimos nisi perspiciatis
    necessitatibus voluptas eaque repellat culpa, neque placeat corporis, atque,
    debitis accusamus. Eveniet magni quis voluptas esse? Ipsam culpa ut eum quia
  </p>
  <div class="button-wrapper">
    <button>click me</button>
  </div>
</section>

<style>
  section {
    /* border-radius: 0.3rem; */
    padding: 1rem;
    background-color: var(--color-tertiary);
    display: grid;
    grid-template-rows: min-content auto min-content;
  }

  h2 {
    color: var(--color-primary);
    font-size: var(--font-size-h2);
    font-weight: 100;
    line-height: 1.3rem;
  }

  p {
    font-size: var(--font-size-paragraph);
    line-height: 1.5rem;
    font-weight: 100;
    color: var(--color-secondary);
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
    margin-left: auto;
  }

  button:hover {
    background-color: var(--color-primary);
  }

  .button-wrapper {
    display: flex;
  }
</style>
