<template>
  <section id="hero">
    <div class="hero__info">
      <div class="hero__text">
        <h1 class="hero__title">Bring Calm to Your
          Chaos</h1>
        <p class="hero__description">Tolate is the simple, beautiful to-do list designed to help
          you focus on what truly matters.</p>
      </div>
      <button class="hero__cta">Get Started - It's Free</button>
    </div>
    <img src="/hero__illustration.png" width="456" height="342" alt="Illustration" class="hero__illustration">
  </section>
</template>

<style scoped>
#hero {
  padding: 40px 16px;
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 48px;
}

.hero__info {
  display: flex;
  justify-content: center;
  flex-direction: column;
  gap: 32px;
}

.hero__text {
  display: flex;
  flex-direction: column;
  gap: 16px;
}

.hero__title {
  font-size: 48px;
  color: #333;
  line-height: 48px;
  font-weight: 700;
  letter-spacing: -1.2px;
}

.hero__description {
  font-size: 16px;
  line-height: 26px;
  color: rgba(51, 51, 51, 0.8);
}

.hero__cta {
  width: 320px;
  height: 48px;
  padding-inline: 32px;
  border-radius: 9999px;
  color: #FFF;
  background-color: #00BCFF;
  border: none;
  font-size: 16px;
  font-weight: 600;
  line-height: 24px;
  letter-spacing: 0.4px;
  text-align: center;
  cursor: pointer;
}
</style>