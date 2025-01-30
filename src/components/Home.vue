<script setup></script>

<template>
  <section class="hero-section">
    <div class="info-block">
      <h1 class="heading u-mb-m">
        Lessons and insights <span class="green-empasis">from 8 years</span>
      </h1>
      <p class="text">Where to grow your business as a photographer: site or social media?</p>
      <button class="register-btn">Register</button>
    </div>
    <img src="/img/Illustration.png" alt="" class="illustration" />
  </section>
  <section class="clients-section">
    <h2 class="heading-secondary">Our Clients</h2>
    <p class="text u-mb-m">We have been working with some Fortune 500+ clients</p>
    <div class="clints-logos">
      <img src="/img/logos/Logo.png" alt="" class="cl-logo" />
      <img src="/img/logos/Logo-1.png" alt="" class="cl-logo" />
      <img src="/img/logos/Logo-2.png" alt="" class="cl-logo" />
      <img src="/img/logos/Logo-3.png" alt="" class="cl-logo" />
      <img src="/img/logos/Logo-4.png" alt="" class="cl-logo" />
      <img src="/img/logos/Logo-5.png" alt="" class="cl-logo" />
      <img src="/img/logos/Logo-6.png" alt="" class="cl-logo" />
    </div>
  </section>
  <section class="community-section">
    <h2 class="heading-secondary u-text-center">
      Manage your entire community <br />
      in a single system
    </h2>
    <p class="text">Who is Nextcent suitable for?</p>
    <div class="for-who-group u-mt-m">
      <div class="community-card u-shadow-s">
        <img src="/img/com-icon.png" alt="" class="card-icon u-mb-m" />
        <h3 class="heading-tertiary u-mb-s u-text-center">Membership Organisations</h3>
        <p class="card-text u-text-center">
          Our membership management software provides full automation of membership renewals and
          payments
        </p>
      </div>
      <div class="community-card u-shadow-s">
        <img src="/img/com-icon2.png" alt="" class="card-icon u-mb-m" />
        <h3 class="heading-tertiary u-mb-s u-text-center">National Associations</h3>
        <p class="card-text u-text-center">
          Our membership management software provides full automation of membership renewals and
          payments
        </p>
      </div>
      <div class="community-card u-shadow-s">
        <img src="/img/com-icon3.png" alt="" class="card-icon u-mb-m" />
        <h3 class="heading-tertiary u-mb-s u-text-center">
          Clubs And <br />
          Groups
        </h3>
        <p class="card-text u-text-center">
          Our membership management software provides full automation of membership renewals and
          payments
        </p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.hero-section {
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: var(--Silver);
  max-height: 100%;
  height: 599px;
  gap: 104px;
}
.info-block {
  max-width: 657px;
}
.heading {
  color: var(--D_Grey);
}
.green-empasis {
  color: var(--Primary);
}
.text {
  color: var(--Grey);
  line-height: 24px;
  font-size: 16px;
}
.register-btn {
  background-color: var(--Primary);
  color: var(--White);
  border: none;
  border-radius: 4px;
  padding: 14px 32px;
  margin-top: 32px;
  font-weight: 500;
  line-height: 24px;
  font-size: 16px;
}
.illustration {
  height: 407px;
  width: 391px;
}

.clients-section {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 100%;
  height: 190px;
  margin: 40px 0;
}
.heading-secondary {
  color: var(--D_Grey);
  margin-bottom: 8px;
}
.clints-logos {
  display: flex;
  max-width: 1152px;
  width: 1152px;
  height: 98px;
  gap: 40px;
  justify-content: space-around;
  align-items: center;
  margin-top: 16px;
}
.cl-logo {
  width: 48px;
  height: 48px;
}

.community-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100%;
  height: 416px;
}
.for-who-group {
  display: flex;
  width: 100%;
  padding: 0 144px;
  justify-content: space-around;
}
.heading-tertiary {
  color: var(--D_Grey);
}
.card-text {
  color: var(--Grey);
  font-size: 14px;
  line-height: 20px;
  font-weight: 400;
}
.community-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 299px;
  height: 260px;
  padding: 32px 24px;
  border-radius: 8px;
}
.card-icon {
  width: 65px;
  height: 56px;
}
</style>
