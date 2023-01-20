<template>
  <div>
    <template>
      <section class="text-banner text-center">
        <h1 class="display-4">
          FoxTop - L’Abbonamento Ideale per la tua Azienda
        </h1>
        <span class="text fs-3">
          FoxTop è l’abbonamento annuale che ti permette di risparmiare
        </span>

        <p class="text fw-bold fs-4">
          su tutti i tuoi ordini a soli €19 all’anno invece di €59
        </p>
      </section>
    </template>
    <SectionSquares />
    <ClassicLeft />
    <SectionDelivery />
    <SectionQA />
    <SectionFox />
  </div>
</template>

<script>
import SectionSquares from "../MainComponents/SectionSquares.vue";
import SectionDelivery from "../MainComponents/SectionDelivery.vue";
import SectionQA from "../MainComponents/SectionQA.vue";
import SectionFox from "../MainComponents/SectionFox.vue";
import ClassicLeft from "../MainComponents/ClassicLeft.vue";
export default {
  txtbanners: [
    {
      titleTwo: "FoxyBox - Scatole di tutti i tipi consegnate in tempi record",
      descriptionTwo:
        "Scegli tra le nostre linee di prodotti in pronta consegna oppure le scatole con misure personalizzate. Acquista ora in modo facile, veloce e sicuro!",
      descriptionBoldTwo: "",
    },
  ],
  name: "SubscriptionComponent",
  components: {
    SectionSquares,
    SectionDelivery,
    SectionQA,
    SectionFox,
    ClassicLeft,
  },
};
</script>

<style lang="scss" scoped></style>
