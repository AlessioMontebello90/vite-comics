<script>
export default {};
</script>

<template>
  <footer>
    <section class="footer-up">
      <div class="options">
        <div class="option">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
          <p>DIGITAL COMICS</p>
        </div>
        <div class="option">
          <img src="../assets/img/buy-comics-merchandise.png" alt="" />
          <p>MERCHANDISE</p>
        </div>
        <div class="option">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
          <p>SUBSCRIPTION</p>
        </div>
        <div class="option">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
          <p>COMIC SHOP LOCATOR</p>
        </div>
        <div class="option">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
          <p>DC POWER VISA</p>
        </div>
      </div>
    </section>
    <section class="footer-mid">
      <div class="contacts"></div>
    </section>
    <section class="footer-bot">
      <div class="socials"></div>
    </section>
  </footer>
</template>

<style lang="scss" scoped>
@use "./../assets/styles/partials/variables.scss" as *;
.footer-up {
  background-color: blue;
  .options {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 8rem;
    max-width: 1200px;
    margin: auto;
    .option {
      display: flex;
      align-items: center;
      padding-inline: 1.5rem;
    }
    img {
      width: 2.2rem;
    }
    p {
      color: white;
      padding-inline: 0.7rem;
      white-space: nowrap;
      font-size: 0.7rem;
    }
    .footer-mid {
      background-image: url("../assets/img/footer-bg.jpg");
      height: 16rem;
    }
    .footer-bot {
      height: 5rem;
      background-color: gray;
      margin-bottom: 2rem;
    }
  }
}
</style>
