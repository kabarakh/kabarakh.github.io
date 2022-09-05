<script setup lang="ts">

const props = defineProps({
  mode: undefined | '50-50' | '75-25' | '66-33'
});
const classes = {
  left: {
    'col-6': props.mode === undefined || props.mode === '50-50',
    'col-9': props.mode === '75-25',
    'col-8': props.mode === '66-33',
  },
  right: {
    'col-6': props.mode === undefined || props.mode === '50-50',
    'col-3': props.mode === '75-25',
    'col-4': props.mode === '66-33',
  }
}
</script>
<template>
  <div class="row">
    <div :class="classes.left">
      <slot name="left"/>
    </div>
    <div :class="classes.right">
      <slot name="right"/>
    </div>
  </div>
</template>