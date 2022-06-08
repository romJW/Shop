<template>
<input
          class=" text-[28px] leading-[34px] font-[600] text-center text-[#97B4C7] border border-[#97B4C7] w-[387px] rounded-[38px] h-[103px]"
          :type="text"
          :placeholder="placeholder"
        />
</template>

<script>
export default {
    props:['text','placeholder']
}
</script>