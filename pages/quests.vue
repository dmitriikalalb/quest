<template>
  <div class="container">
    <div class="container__title">
      <h1>Квесты</h1>
    </div>
    <div class="container__row">
      <div class="container__column" v-for="item in 3">
        <div class="item" >
          <img class="item__image" :src="`https://picsum.photos/600/60${item}`">
          <div class="item__menu" :class="(item === 1 ) ? 'item__menu_open' : ''">
            <div class="item__header">
              <h2 class="item__title">Title</h2>
              <div class="item__option-bar">
                <button class="item__option"></button>
                <button class="item__option"></button>
                <button class="item__option">↑</button>
              </div>
            </div>
            <p class="item__description">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
              dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex
              ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
              fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt
              mollit anim id est laborum
            </p>
          </div>
        </div>
      </div>
<!--      <div class="container__column">-->
<!--        <div class="item">-->
<!--          <div class="item__icon"></div>-->
<!--          <div class="item__menu item__menu_open">-->
<!--            <div class="item__header">-->
<!--              <h2 class="item__title">Title</h2>-->
<!--              <div class="item__option-bar">-->
<!--                <button class="item__option"></button>-->
<!--                <button class="item__option"></button>-->
<!--                <button class="item__option"></button>-->
<!--              </div>-->
<!--            </div>-->
<!--            <p class="item__description">-->
<!--              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et-->
<!--              dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex-->
<!--              ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu-->
<!--              fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt-->
<!--              mollit anim id est laborum-->
<!--            </p>-->
<!--          </div>-->
<!--        </div>-->
<!--      </div>-->
<!--      <div class="container__column">-->
<!--        <div class="item">-->
<!--          <div class="item__icon"></div>-->
<!--          <div class="item__menu"></div>-->
<!--        </div>-->
<!--      </div>-->
    </div>
  </div>
</template>

<script>
  export default {}
</script>

<style>

</style>
