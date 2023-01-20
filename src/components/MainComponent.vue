<template>
  <main>
    <HomeComponent />
    <ShowVoneComponent />
    <ShowVtwoComponent />
    <SubscriptionComponent />
    <ShoppingCartComponent />
    <CartComponent />
    <CreateComponent />
  </main>
</template>

<script>
import HomeComponent from "./pages/HomeComponent.vue";
import ShowVoneComponent from "./pages/ShowVoneComponent.vue";
import ShowVtwoComponent from "./pages/ShowVtwoComponent.vue";
import SubscriptionComponent from "./pages/SubscriptionComponent.vue";
import ShoppingCartComponent from "./pages/ShoppingCartComponent.vue";
import CartComponent from "./MainComponents/CheckoutComponent.vue";
import CreateComponent from "./pages/CreateComponent.vue";

export default {
  name: "MainComponent",
  components: {
    HomeComponent,
    ShowVoneComponent,
    ShowVtwoComponent,
    SubscriptionComponent,
    ShoppingCartComponent,
    CartComponent,
    CreateComponent,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
