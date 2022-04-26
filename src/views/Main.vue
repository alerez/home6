<template>
  <main class="page__main main">
    <div class="main__container">
      <div class="main__body">
        <div class="main__description description">
          <div class="description__body">
            <div class="description__title">Авторское <br> строительство <br> современных <br> домов
              <div class="description__button pcBtn">в спб и Ленинград- <br>
              ской области</div></div>
            <div class="description__button mobileBtn">в спб и Ленинград- <br>
              ской области</div>
          </div>
        </div>

        <div class="main__download download">
          <div class="download__body">
            <div class="download__text">{{ store.mainData.text }}</div>
            <a class="download__button" :href="store.mainData.link">{{ store.mainData.button }}</a>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script setup>
import { useStore } from '@/store/index';

const store = useStore();
</script>
