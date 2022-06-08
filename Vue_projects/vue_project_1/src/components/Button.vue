<template>
  <button :class="$attrs.class">{{ text }}</button>,
</template>

<script>
export default {
  props: ['text'],
};
</script>

<style scoped>
button {
  @apply text-[28px] leading-[34px] w-[422px] h-[103px]  rounded-[38px];
}
</style>
