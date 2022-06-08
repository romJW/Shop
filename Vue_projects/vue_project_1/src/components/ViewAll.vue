<template>
  <div class="tour-block__info flex flex-col gap-[30px]">
    <h3
      class="whitespace-pre tour-block__title font-['Playfair+Display'] text-[40px] font-bold leading-[53px]"
    >
      {{ title }}
    </h3>
    <p class="whitespace-pre tour-block__text text-[24px] leading-[29px]">{{ text }}</p>
   
  </div>
</template>

<script>

export default {
    
  props: ['title', 'text'],
};
</script>
