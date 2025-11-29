<template>
  <nav class="nav">
    <div class="nav__brand">
      <img src="/tolate.svg" alt="Tolate Logo" width="24" height="24" class="nav__logo">
      <span class="nav__title">Tolate</span>
    </div>
    <div class="nav__ctas">
      <button class="nav__login">Log In</button>
      <button class="nav__signup">Sign Up</button>
    </div>
  </nav>
</template>

<style scoped>
.nav {
  display: flex;
  padding: 16px 24px;
  align-items: center;
  justify-content: space-between;
}

.nav__brand {
  display: flex;
  align-items: center;
  gap: 12px;
}

.nav__title {
  font-weight: 700;
  font-size: 20px;
  line-height: 25px;
  color: #333333;
}

.nav__ctas {
  display: flex;
  align-items: center;
  gap: 8px;
}

.nav__login {
  height: 40px;
  padding-inline: 24px;
  border-radius: 9999px;
  color: #333333;
  border: none;
  font-size: 14px;
  font-weight: 600;
  line-height: 21px;
  text-align: center;
  cursor: pointer;
}

.nav__signup {
  height: 40px;
  padding-inline: 24px;
  border-radius: 9999px;
  color: #FFF;
  background-color: #00BCFF;
  border: none;
  font-size: 14px;
  font-weight: 600;
  line-height: 21px;
  text-align: center;
  cursor: pointer;
}
</style>
