<template>
  <section class="tour-block flex flex-row-reverse gap-[100px] ml-[266px]">
    <BigCard
    text="Это был самый
лучший отпуск в моей
жизни..."
    top-text="Отзыв
Яна Стасян"
    :image="require('../assets/img/feed.png')"
    />
    <div class="tour-block__info flex flex-col gap-[33px]" >
    <ViewAll
    title="Что пишут участники
наших путешествий"
    text="87% участников приходят по
рекомендации своих друзей, а
каждый 4-ый путешетсвует с
нами больше двух раз!" />
 <Button text="Читать отзывы" class="border-[3px] border-amber-600 text-amber-600" />
 </div>
  </section>
</template>


<script>
import Button from "./Button";
import BigCard from "./BigCard";
import ViewAll from "./ViewAll";
export default{
    components:{
        BigCard,
        Button,
        ViewAll
    }
}

</script>