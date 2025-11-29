<script setup>
defineProps(['icon', 'title', 'description'])
</script>

<template>
  <div class="feature__card">
    <div class="feature__card-icon">
      <img :src="icon" alt="Feature Image">
    </div>
    <div class="feature__card-info">
      <h3 class="feature__card-title">{{ title }}</h3>
      <p class="feature__card-description">{{ description }}</p>
    </div>
  </div>
</template>

<style scoped>
.feature__card {
  padding: 24px;
  display: flex;
  flex-direction: column;
  gap: 16px;
  border: 1px solid #E0E4E8;
  border-radius: 24px;
  background-color: #FFF;
}

.feature__card-icon {
  width: 48px;
  height: 48px;
  border-radius: 16px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #E6F9FF;
}

.feature__card-info {
  width: 100%;
  display: flex;
  flex-direction: column;
  gap: 4px;
}

.feature__card-title {
  font-weight: 600;
  font-size: 16px;
  line-height: 20px;
  color: #333;
}

.feature__card-description {
  font-size: 14px;
  line-height: 21px;
  color: rgba(51, 51, 51, 0.7);
}
</style>