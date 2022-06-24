<template>
  <q-item
    clickable
    tag="a"
    target="_blank"
    :href="link"
  >
  </q-item>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'StatCard',
  props: {
    name: {
      type: String,
      required: true,
    },
    // image: {
    //   type: String,
    //   required: true,
    // },
    // content: {
    //   type: Array,
    //   required: true,
    // },
  },
});
</script>
