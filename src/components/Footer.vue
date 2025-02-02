<script setup>
import Logo from '@/ui/Logo.vue'
</script>

<template>
  <section class="get-demo-section">
    <h1 class="heading u-text-center">
      Pellentesque suscipit <br />
      fringilla libero eu.
    </h1>
    <button class="demo-btn">Get a Demo</button>
  </section>
  <footer class="footer">
    <div class="company-info">
      <img src="/img/logo-white.png" alt="" />
      <div>
        <p class="u-mb-s">Copyright © 2020 Nexcent ltd.</p>
        <p>All rights reserved</p>
      </div>
      <div class="socials">
        <img src="/img/Social-Icons.png" alt="" />
        <img src="/img/Social-Icons-1.png" alt="" />
        <img src="/img/Social-Icons-2.png" alt="" />
        <img src="/img/Social-Icons-3.png" alt="" />
      </div>
    </div>
    <div class="links">
      <div class="company">
        <h4 class="links-heading">Company</h4>
        <ul class="links-list">
          <li>About us</li>
          <li>Blog</li>
          <li>Contact us</li>
          <li>Pricing</li>
          <li>Testimonials</li>
        </ul>
      </div>
      <div class="support">
        <h4 class="links-heading">Support</h4>
        <ul class="links-list">
          <li>Help center</li>
          <li>Terms of service</li>
          <li>Legal</li>
          <li>Privacy policy</li>
          <li>Status</li>
        </ul>
      </div>
      <div class="reach">
        <h4 class="links-heading">Stay up to date</h4>
        <div class="input-container">
          <input type="email" class="email-input" placeholder="Your email address" />
          <button class="send-btn">
            <img src="/img/send.png" alt="" />
          </button>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.get-demo-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 300px;
  background-color: var(--Silver);
  color: var(--Black);
  gap: 32px;
}
.heading {
  width: 887px;
}
.demo-btn {
  cursor: pointer;
  border: none;
  border-radius: 4px;
  background-color: var(--Primary);
  padding: 14px 32px;
  color: var(--White);
}
.demo-btn::after {
  content: '→';
  margin-left: 8px;
}

.footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 125px;
  padding: 64px 165px;
  height: 382px;
  background-color: var(--Black);
}
.company-info {
  display: flex;
  flex-direction: column;
  gap: 42px;
  color: var(--White);
}
.socials {
  display: flex;
  gap: 20px;
}
.links {
  display: grid;
  grid-template-columns: repeat(2, 160px) 255px;
  column-gap: 30px;
}
.links-list {
  display: flex;
  flex-direction: column;
  gap: 12px;
  margin-top: 24px;
  color: var(--White);
  list-style: none;

  li {
    cursor: pointer;
    font-weight: 400;
    line-height: 20px;
    font-size: 14px;
  }
}
.links-heading {
  color: var(--White);
}
.input-container {
  position: relative;
  margin-top: 24px;
}
.email-input {
  width: 100%;
  height: 40px;
  border: none;
  border-radius: 8px;
  padding: 16px;
  background-color: rgba(255, 255, 255, 0.2);
  color: #d9dbe1;
  font-size: 14px;
  line-height: 20px;
  font-weight: 400;
}
.send-btn {
  cursor: pointer;
  position: absolute;
  top: 11px;
  right: 12px;
  z-index: 1;
  background-color: transparent;
  border: none;

  img {
    width: 18px;
    height: 18px;
  }
}
</style>
