<template>
  <div>
      <BlockProductSeasonalItem
        v-for="(item, index) in content.items"
        :key="index"
        :content="item"
      />
  </div>
</template>

<script>

import BlockProductSeasonalItem from "@/components/blocks/BlockProductSeasonalItem"

export default {
    components: {
        BlockProductSeasonalItem
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