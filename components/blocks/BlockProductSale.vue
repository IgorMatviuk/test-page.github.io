<template>
  <div>
      <BlockProductSaleItem
        v-for="(item, index) in content.items"
        :key="index"
        :content="item"
      />
  </div>
</template>

<script>

import BlockProductSaleItem from "@/components/blocks/BlockProductSaleItem"

export default {
    components:{
        BlockProductSaleItem
    },
    props: {
        content: {
          type: Object,
          required: true
        }
    }
}
</script>

<style>

</style>