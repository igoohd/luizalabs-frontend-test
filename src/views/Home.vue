<template>
  <div class="home-page">
    <PageHeader />
    <h1 class="title">Home</h1>
    <ProductList />
  </div>
</template>

<script>
import PageHeader from "@/components/PageHeader";
import ProductList from "@/components/ProductList";

export default {
  name: "Home",

  components: {
    PageHeader,
    ProductList,
  },
};
</script>

<style lang="scss" scoped>
.home-page {
  > .title {
    font-weight: bold;
    font-size: 1.2rem;
    margin-left: 2rem;
    margin-top: 2rem;
    text-align: left;
  }
}
</style>
