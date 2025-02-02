<script setup>
import FooterLinks from './FooterLinks.vue'
</script>

<template>
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
      <FooterLinks
        heading="Company"
        :links="['About us', 'Blog', 'Contact us', 'Pricing', 'Testimonials']"
      />
      <FooterLinks
        heading="Support"
        :links="['Help center', 'Terms of service', 'Legal', 'Privacy policy', 'Status']"
      />
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
