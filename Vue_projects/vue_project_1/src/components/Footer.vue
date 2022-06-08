<template>
<footer class="footer  flex  bg-[url(../assets/img/footerBg.png)]" >
    <div class="footer__content ml-[113px] flex pt-[64px] pb-[88px]">
 <h3
          class="footer__title mr-[131px] text-black text-[36px] font-normal leading-[46px] font-['Allison'] text-white"
        >
          Trip with Stas
        </h3>
        <div class="footer__secure flex gap-[195px] mr-[520px]">
            <p class="footer__secure-info">Политика <br>конфиденциальности</p>
            <p class="footer__secure-info">Соглашение на обработку<br> персональных данных</p>
        </div>
        <Socials />
</div>
</footer>
</template>

<script>
import Socials from "./Socials"
export default {
    components:{
    Socials,
    Socials
}
}

</script>