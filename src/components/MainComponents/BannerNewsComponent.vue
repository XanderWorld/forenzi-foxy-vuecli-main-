<template>
  <section class="news-banner d-flex">
    <div class="new position-relative">
      <img
        class="img-fluid"
        src="../../../public/Links/side-view-of-smiling-curly-woman-pointing-away.jpg"
        alt=""
      />
      <div style="font-weight: bold;" class="new-text position-absolute">
        <h1>NOVITÀ!!</h1>
        <span>
          Scopri i nostri nuovi prodotti a catalogo e tutti in pronta consegna e
          spedizione gratuita.
        </span>
      </div>
    </div>
    <div class="new" style="">
      <div class="new-img">
        <img class="img-fluid" src="https://picsum.photos/200/314" alt="" />
      </div>
      <div class="new-text">
        <h4>Scatole con maniglie</h4>
        <span>Disponibili bianche e avana</span>
        <button class="yellow-button">SCOPRI IL PRODOTTO</button>
      </div>
    </div>
    <div class="new">
      <div class="new-img">
        <img class="img-fluid" src="https://picsum.photos/200/314" alt="" />
      </div>
      <div class="new-text">
        <h4>Scatole colorate</h4>
        <span>Varie forme e colori</span>
        <button class="yellow-button">SCOPRI IL PRODOTTO</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  components: {},
  data() {
    return {}
  },
  created() {},
}
</script>

<style lang="scss" scoped>
.news-banner {
  .new {
    display: flex;
    align-items: center;

    padding: 4rem 0px;

    font-size: .8rem;

    height: 300px;
    width: 33.33%;
    background-color: lightgrey;
    margin: 50px 2px;

    img {
      height: 300px;
    }
    .new-text {
      width: 50%;
      padding: 20px;
      h1,
      h4 {
        color: rgb(246, 134, 48);
        font-weight: bold;
      }
    }
  }
}
</style>
