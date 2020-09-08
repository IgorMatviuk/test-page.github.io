<template>
  <div class="content-hidden">
    <Header/>
    <Main/>
    <ProductBrand/>
    <HeadphonesOptions/>
    <ProductSale/>
    <Test/>
    <ProductSeasonalSale/>
    <Advantage/>
    <div class="reverse">
      <div>
        <Top/>
      </div>
      <div>
        <InfoChoice/>
        <Delivery/>
      </div>
    </div>
    <Consultation/>
    <Footer/>
  </div>
</template>

<script>

import Header from "@/components/Header"
import Main from "@/components/Main"
import ProductBrand from "@/components/ProductBrand"
import HeadphonesOptions from "@/components/HeadphonesOptions"
import ProductSale from "@/components/ProductSale"
import Test from "@/components/Test"
import ProductSeasonalSale from "@/components/ProductSeasonalSale"
import Advantage from "@/components/Advantage"
import Top from "@/components/Top"
import InfoChoice from "@/components/InfoChoice"
import Delivery from "@/components/Delivery"
import Consultation from "@/components/Consultation"
import Footer from "@/components/Footer"

export default {
  Main,
  Header,
  ProductBrand,
  HeadphonesOptions,
  ProductSale,
  Test,
  ProductSeasonalSale,
  Advantage,
  Top,
  InfoChoice,
  Delivery,
  Consultation,
  Footer
}
</script>

<style>
.content-hidden{
  overflow: hidden;
}
@media (max-width: 414px) {
  .reverse{
    display: flex;
    flex-direction: column-reverse;
  }
}
</style>
