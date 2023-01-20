<template>
  <div class="home">
    <div class="container">
      <div class="row">
        <NavBoxesComponent />
        <JumboComponent />
        <BannerNewsComponent />
        <BannerTextComponent
          v-for="(element, index) in txtbanners"
          :key="index"
          :title="element.title"
          :description="element.description"
          :descriptionBold="element.descriptionBold" />
        <BoxesComponent />
        <HolidayComponent />
      </div>
    </div>

    <ClassicLeft />
    <ClassicRight />
  </div>
</template>

<script>
import NavBoxesComponent from "../MainComponents/NavBoxesComponent.vue";
import JumboComponent from "../MainComponents/JumboComponent.vue";
import BannerNewsComponent from "../MainComponents/BannerNewsComponent.vue";
import BannerTextComponent from "../MainComponents/BannerTextComponent.vue";
import BoxesComponent from "../MainComponents/BoxesComponent.vue";
import HolidayComponent from "../MainComponents/HolidayComponent.vue";
import ClassicLeft from "../MainComponents/ClassicLeft.vue";
import ClassicRight from "../MainComponents/ClassicRight.vue";

export default {
  name: "HomeComponent",
  components: {
    NavBoxesComponent,
    JumboComponent,
    BannerNewsComponent,
    BannerTextComponent,
    BoxesComponent,
    HolidayComponent,
    ClassicLeft,
    ClassicRight,
  },
  data() {
    return {
      txtbanners: [
        {
          title: "FoxyBox - Scatole di tutti i tipi consegnate in tempi record",
          description:
            "Scegli tra le nostre linee di prodotti in pronta consegna oppure le scatole con misure personalizzate. Acquista ora in modo facile, veloce e sicuro!",
          descriptionBold: "",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped></style>
