<template>
  <div>
    <BlockProductOneClickItem
        v-for="(item, index) in content.items"
        :key="index"
        :content="item"
      />
  </div>
</template>

<script>

import BlockProductOneClickItem from "@/components/blocks/BlockProductOneClickItem"

export default {
    components: {
        BlockProductOneClickItem
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