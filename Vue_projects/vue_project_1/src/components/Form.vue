<template>
  <div class="form-block  pt-[106px] bg-no-repeat  bg-[url(../assets/img/imgForm.png)]">
    <div class="ml-[971px] flex">
    <div class="form-block__text-section ">
      <h3 class="text-[40px] font-bold leading-[53px]">
        Оставьте заявку <br />
        на бесплатную <br />
        консультацию
      </h3>
      <p class="text-[24px] leading-[29px]">
        Мы свяжемся с Вами <br />
        в ближайшее время!
      </p>
    </div>

    <form>
      <div class="form-block__inputs ml-[58px] flex flex-col gap-[23px]">
        <formInput
        :name="text"
        placeholder="Ваше имя"
        />
        <formInput
        :name="number"
        placeholder="+7(_ _ _)_ _ _-_ _-__"
        />
        <Button 
        text="Оставить заявку"
        class="mt-[10px] bg-gradient-to-r from-orange-800 via-orange-500 to-purple-900 text-white"
        />
      </div>
      
    </form>
  </div>
  </div>
</template>


<script>
import formInput from "./formInput"
import Button from "./Button"
export default{
    components:{
        formInput,
        Button
        
    },
    props:['text','placeholder',"number"]
}
</script>