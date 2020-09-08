<template>
  <div>
      <BlockProductTopItem
        v-for="(item, index) in content.items"
        :key="index"
        :content="item"
      />
  </div>
</template>

<script>

import BlockProductTopItem from "@/components/blocks/BlockProductTopItem"

export default {
    components: {
        BlockProductTopItem
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