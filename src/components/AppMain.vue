<script>
export default {};
</script>

<template>
  <main>
    <div class="contents">
      <h1>il contenuto andrà qui</h1>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur,
        minima dolor aut quia amet ab ipsum rem modi hic repellendus recusandae
        nostrum quas eum! Adipisci ullam culpa repellat vel laborum. Architecto
        rem, illum labore minima, porro magnam ipsum pariatur eveniet similique
        error voluptatem quae excepturi velit maxime! Adipisci, inventore earum
        similique unde est rem vero animi quam ullam, blanditiis dolores!
        Corrupti consectetur accusamus in sequi nemo ab laboriosam explicabo.
        Autem, ut sint, dolore nam quod cum deleniti vitae, in et itaque velit
        voluptatibus consectetur modi temporibus laudantium eligendi pariatur
        molestias. Quas, sapiente obcaecati minus, nostrum corrupti optio magni,
        quibusdam rerum eos eum ratione voluptatibus? Aperiam ad eligendi, esse
        accusamus atque libero facilis ab praesentium illum perferendis
        veritatis blanditiis officia quos. Odit incidunt recusandae aspernatur
        debitis officiis labore soluta doloribus minus nesciunt tempora error
        aperiam dolorem exercitationem excepturi ullam placeat numquam, fuga
        nulla magni tempore quia pariatur! Hic unde commodi mollitia!
      </p>
    </div>
  </main>
</template>

<style lang="scss" scoped>
@use "./../assets/styles/partials/variables.scss" as *;
main {
  background-color: rgb(28, 28, 28);
  .contents {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex-shrink: 1;
    color: white;
    max-width: 1200px;
    margin: auto;
    h1 {
      color: red;
      &:hover {
        cursor: pointer;
        color: white;
      }
    }
  }
}
</style>
