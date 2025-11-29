<script setup lang="ts">
import FeatureCard from './FeatureCard.vue';

</script>

<template>
  <section id="feature">
    <div class="feature__info">
      <h2 class="feature__title">Everything you need to stay organized</h2>
      <span class="feature__description">Tolate provides all the essential features to manage your day-to-day, without
        the clutter.</span>
    </div>
    <div class="feature__grid">
      <FeatureCard icon="/feature-1.svg" title="Effortlessly Add Tasks"
        description="Quickly capture your thoughts and to-dos the moment they strike." />
      <FeatureCard icon="/feature-2.svg" title="Organize with Categories"
        description="Group your tasks into projects and categories to keep your list tidy." />
      <FeatureCard icon="/feature-3.svg" title="Never Miss a Deadline"
        description="Set due dates and reminders to ensure nothing falls through the cracks." />
      <FeatureCard icon="/feature-4.svg" title="Focus with Dark Mode"
        description="Switch to a sleek, eye-friendly theme for late-night work sessions." />
    </div>
  </section>
</template>

<style scoped>
#feature {
  display: flex;
  flex-direction: column;
  gap: 40px;
  padding: 40px 16px;
}

.feature__info {
  display: flex;
  flex-direction: column;
  gap: 16px;
  align-items: center;
  justify-content: center;
}

.feature__title {
  font-weight: 700;
  font-size: 30px;
  line-height: 37.5px;
  letter-spacing: -0.75px;
  color: #333;
  text-align: center;
}

.feature__description {
  max-width: 672px;
  text-align: center;
  color: rgba(51, 51, 51, 0.8);
  font-size: 16px;
  line-height: 26px;
}

.feature__grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 24px;
}
</style>