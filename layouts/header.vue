<template>
  <div class="header">
    <div class="container">
      <div class="header__left">
        <img src="/logo.svg" alt="Logo" class="header__logo" />
        <h1 class="header__title">Kabeng Toi</h1>
      </div>
      <div class="header__right">
        <a href="#" class="header__link">Pinjam Alat</a>
        <a href="#" class="header__link">Pinjam Ruang</a>
        <a href="#" class="header__link">SOP</a>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.header {
  background-color: #f5f5f5;
  padding: 20px 0;
  &__container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
  }
  &__left {
    display: flex;
    align-items: center;
  }
  &__logo {
    width: 50px;
    height: 50px;
    margin-right: 10px;
  }
  &__title {
    font-size: 24px;
    font-weight: bold;
    margin: 0;
  }
  &__right {
    display: flex;
    align-items: center;
    gap: 20px;
  }
  &__link {
    text-decoration: none;
    color: #333;
    font-weight: bold;
    transition: color 0.3s ease;
  }
  &__link:hover {
    color: #007bff;
  }
}
</style>