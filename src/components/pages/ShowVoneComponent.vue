<template>
  <div class="home">
    <div class="container">
      <div class="row">
        <ShowBox />
        <h4 class="fw-bold py-2">Elenco formati disponibili</h4>
        <TableComponent />
        <BannerNewsComponent />
      </div>
    </div>

    <ClassicLeft />
    <ClassicRight />
  </div>
</template>

<script>
import ShowBox from "../MainComponents/ShowBox.vue";
import TableComponent from "../MainComponents/TableComponent.vue";
import BannerNewsComponent from "../MainComponents/BannerNewsComponent.vue";

export default {
  name: "UnOnda",
  components: {
    ShowBox,
    TableComponent,
    BannerNewsComponent,
  },
};
</script>

<style>

</style>
