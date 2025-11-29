<template>
  <footer class="footer">
    <p class="footer__copyright">© 2025 @fahmirizalbudi. All rights reserved.</p>
    <ul class="footer__links">
      <li class="footer__link">About</li>
      <li class="footer__link">Contact</li>
      <li class="footer__link">Privacy</li>
    </ul>
  </footer>
</template>

<style scoped>
.footer {
  padding: 32px 24px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.footer__copyright {
  font-size: 14px;
  color: #333;
  line-height: 20px;
}

.footer__links {
  display: flex;
  list-style: none;
  align-items: center;
  gap: 24px;
}

.footer__link {
  font-size: 14px;
  color: #333;
  line-height: 20px;
  font-weight: 500;
}
</style>