<template>
<div class="relative">
      <img class="relative" :src="image" alt="card" />
      <p class="text-[32px] whitespace-pre-wrap text-white absolute left-[40px] top-[10px] z-1">
        {{topText}}
      </p>
      <p class="text-[32px] whitespace-pre-wrap text-white absolute left-[40px] bottom-[50px] z-1">
        {{text}}
      </p>
      <span
        class="relative after:bottom-[50px] after:left-[750px] after:content-[''] after:w-[40px] after:h-[40px] after:absolute after:bg-[url(../assets/img/arrow3.svg)]"
      ></span>
    </div>
</template>

<script>
export default{
    props:['text','topText','image']
}

</script>