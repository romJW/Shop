<template>
<div class="relative">
            <img class="relative" :src="image" alt="card" />
            <p class=" whitespace-pre-wrap text-white absolute left-[10px] bottom-[10px] z-1">{{text}}</p>
            <span
              class="relative after:bottom-[20px] after:left-[290px] after:content-[''] after:w-[25px] after:h-[25px] after:absolute after:bg-[url(../assets/img/arrow3.svg)]"
            ></span>
           
          </div>
</template>

<script>
export default {
  props: ['text','image'],

 
};
</script>


<style>

</style>