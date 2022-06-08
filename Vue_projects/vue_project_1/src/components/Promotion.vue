<template>
  <div class="promotion-block mt-[147px] ml-[120px]">
    <h1
      class="promotion-block__title text-[77px] text-white font-['Playfair+Display'] font-bold leading-[103px] mb-[37px]"
    >
      Открой для себя <br />
      новую Исландию
    </h1>
    <p class="promotion-block__slogan text-[24px] text-white leading-[29px] mb-[64px]">
      Авторские туры по уголкам мира от Станислава <br />
      Воробьёва
    </p>
    <div class="promotion-block__button-section flex gap-[57px]">
      <Button
        text="Оставить заявку"
        class="bg-gradient-to-r from-orange-800 via-orange-500 to-purple-900 text-white"
      />

      <div class="promotion-block__video flex gap-[20px]">
        <div
          class="promotion-block__video-button rounded-full w-[98px] h-[98px] border-2 border-white relative after:absolute after:left-[37px] after:top-[25px] after:content-[''] after:w-[23.1px] after:h-[36px] after:bg-[url(../assets/img/triangle.svg)]"
        ></div>
        <p class="promotion-block__video-text text-[20px] text-white leading-[24px] self-center">
          Посмотри видео-<br />отчет 2020-2021
        </p>
      </div>
    </div>
    <div>
      <div class="promotion-block__bottom flex">
        <div class="promotion-block__social mt-[96px]">
          <p class="promotion-block__social-text mb-[42px]">Подписывайтесь в соцсетях</p>
          <Socials />
        </div>

        <div class="promotion-block__cards mt-[53px] ml-[283px] flex gap-[30px]">
          <Card
            text="Водопады 
Исландии"
            :image="require('../assets/img/card1.png')"
          />
          <Card
            text="Неизведанные 
озёра"
            :image="require('../assets/img/card2.png')"
          />
          <Card
            text="Леса 
Скандинавии"
            :image="require('../assets/img/card3.png')"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Button from './Button';
import Card from './Card';
import Socials from './Socials';

export default {
  components: {
    Button,
    Card,
    Socials,
    
  },
};
</script>
