<template>
  <div class="top-block">
    <div
      class="top-block__background bg-cover pb-[133px] bg-[url(../assets/img/background.png)]"
    >
      <header class="top-block__header max-w-[1920px] mx-[90px] flex items-center justify-between">
        <h3
          class="top-block__header-title text-[36px] font-normal leading-[46px] font-['Allison'] text-white"
        >
          Trip with Stas
        </h3>

        <ul class="top-block__header-menu flex gap-10">
          <MenuItem v-for="name in names" :key="name.id" :title="name.title" />
        </ul>

        <div class="top-block__header-burger flex flex-col gap-1">
          <div class="w-[30px] h-[2px] bg-white"></div>
          <div class="w-[30px] h-[2px] bg-white"></div>
          <div class="w-[30px] h-[2px] bg-white"></div>
        </div>
      </header>
      <Promotion />
    </div>
  </div>
</template>

<script>
import Promotion from './Promotion';
import MenuItem from './MenuItem';

export default {
  components: {
    Promotion,
    MenuItem,
  },
  data() {
    return {
      names: [
        { id: 1, title: 'Все туры' },
        { id: 2, title: 'Отзывы' },
        { id: 3, title: 'Контакты' },
      ],
    };
  },
};
</script>

<style></style>
