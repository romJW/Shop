<template>
  <section class="tour-block flex gap-[100px] ml-[266px]">
    <BigCard
    text="Дикие леса
Скандинавии. "
    top-text="9-20
июня"
    :image="require('../assets/img/card4.png')"
    />
    <div class="tour-block__info flex flex-col gap-[33px]" >
    <ViewAll
    title="Посмотрите все
направления туров"
    text="Дикие леса с редкими видами
деревьев. А также первозданные
места природы." />
 <Button text="Смотреть все" class="border-[3px] border-amber-600 text-amber-600" />
 </div>
  </section>
</template>

<script>
import BigCard from './BigCard';
import Button from './Button';
import ViewAll from './ViewAll';
export default {
  components: { BigCard,
  Button,
  ViewAll },
};
</script>
