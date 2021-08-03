<template>
  <div class="container">
    <h1 class="text-center">Ürün Ekleme Uygulaması</h1>
    <hr />
    <app-new-product></app-new-product>
    <br /><br />
    <app-new-progress></app-new-progress>
    <br /><br />
    <app-new-products></app-new-products>
  </div>
</template>

<script>
import NewProductVue from "./components/NewProduct.vue";
import NewProgres from "./components/Progress.vue";
import NewProducts from "./components/Products.vue";
export default {
  components: {
    appNewProduct: NewProductVue,
    appNewProgress: NewProgres,
    appNewProducts: NewProducts
  }
};
</script>

<style>
body {
  background-color: aliceblue;
  padding-top: 20px;
  padding-bottom: 20px;
}

.card {
  margin-right: 5px;
  margin-bottom: 5px;
}

.card:last-child {
  margin-right: 0px;
}

.col-md-2 {
  max-width: 15.666667% !important;
}

.product-container {
  margin-left: 15px;
}
</style>
