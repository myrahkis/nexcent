<script setup>
import InfoBlock from './InfoBlock.vue'
</script>

<template>
  <InfoBlock
    imgPath="/img/Frame35.png"
    heading="The unseen of spending three years at Pixelgrade"
    paragraph="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sit amet justo ipsum. Sed
      accumsan quam vitae est varius fringilla. Pellentesque placerat vestibulum lorem sed porta.
      Nullam mattis tristique iaculis. Nullam pulvinar sit amet risus pretium auctor. Etiam quis
      massa pulvinar, aliquam quam vitae, tempus sem. Donec elementum pulvinar odio."
    btnText="Learn more"
  />
  <section class="achievements-section">
    <div class="text-block">
      <h2 class="heading-secondary u-mb-s">
        Helping a local
        <span class="green-empasis"
          ><br />
          business reinvent itself</span
        >
      </h2>
      <p class="paragraph-text">We reached here with our hard work and dedication</p>
    </div>
    <div class="stats-block">
      <div class="stat-group">
        <img src="/img/stats-icon.png" alt="" class="stat-img" />
        <div class="stats">
          <h3 class="heading-tertiary">2,245,341</h3>
          <p class="body2">Members</p>
        </div>
      </div>
      <div class="stat-group">
        <img src="/img/stats-icon2.png" alt="" class="stat-img" />
        <div class="stats">
          <h3 class="heading-tertiary">46,328</h3>
          <p class="body2">Clubs</p>
        </div>
      </div>
      <div class="stat-group">
        <img src="/img/stats-icon3.png" alt="" class="stat-img" />
        <div class="stats">
          <h3 class="heading-tertiary">828,867</h3>
          <p class="body2">Event Bookings</p>
        </div>
      </div>
      <div class="stat-group">
        <img src="/img/stats-icon4.png" alt="" class="stat-img" />
        <div class="stats">
          <h3 class="heading-tertiary">1,926,436</h3>
          <p class="body2">Payments</p>
        </div>
      </div>
    </div>
  </section>
  <InfoBlock
    imgPath="/img/pana.png"
    heading="How to design your site footer like we did"
    paragraph="Donec a eros justo. Fusce egestas tristique ultrices. Nam tempor, augue nec tincidunt molestie, massa nunc varius arcu, at scelerisque elit erat a magna. Donec quis erat at libero ultrices mollis. In hac habitasse platea dictumst. Vivamus vehicula leo dui, at porta nisi facilisis finibus. In euismod augue vitae nisi ultricies, non aliquet urna tincidunt. Integer in nisi eget nulla commodo faucibus efficitur quis massa. Praesent felis est, finibus et nisi ac, hendrerit venenatis libero. Donec consectetur faucibus ipsum id gravida."
    btnText="Learn more"
  />
  <section class="customers-section">
    <img src="/img/image9.png" alt="" class="customers-img" />
    <div class="customers-block">
      <div class="content">
        <p class="customers-text u-mb-m">
          Maecenas dignissim justo eget nulla rutrum molestie. Maecenas lobortis sem dui, vel rutrum
          risus tincidunt ullamcorper. Proin eu enim metus. Vivamus sed libero ornare, tristique
          quam in, gravida enim. Nullam ut molestie arcu, at hendrerit elit. Morbi laoreet elit at
          ligula molestie, nec molestie mi blandit. Suspendisse cursus tellus sed augue ultrices,
          quis tristique nulla sodales. Suspendisse eget lorem eu turpis vestibulum pretium.
          Suspendisse potenti. Quisque malesuada enim sapien, vitae placerat ante feugiat eget.
          Quisque vulputate odio neque, eget efficitur libero condimentum id. Curabitur id nibh id
          sem dignissim finibus ac sit amet magna.
        </p>
        <h4><span class="green-empasis">Tim Smith</span></h4>
        <p class="customers-association u-mt-s u-mb-l">British Dragon Boat Racing Association</p>
        <div class="customers-logos">
          <img src="/img/logos/Logo-1.png" alt="" />
          <img src="/img/logos/Logo-2.png" alt="" />
          <img src="/img/logos/Logo-3.png" alt="" />
          <img src="/img/logos/Logo-4.png" alt="" />
          <img src="/img/logos/Logo-5.png" alt="" />
          <img src="/img/logos/Logo-6.png" alt="" />
          <button class="customers-btn">Meet all customers</button>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.achievements-section {
  display: flex;
  align-items: center;
  justify-content: space-around;
  background-color: var(--Silver);
  height: 288px;
  padding: 0 144px;
}
.text-block {
  max-width: 540px;
}
.paragraph-text {
  line-height: 24px;
  font-size: 16px;
  color: #18191f;
}
.stats-block {
  display: grid;
  grid-template-columns: 1fr 1fr;
  row-gap: 40px;
  column-gap: 30px;
}
.stat-group {
  display: flex;
  gap: 16px;
}
.stat-img {
  width: 48px;
  height: 48px;
}
.body2 {
  line-height: 24px;
  font-size: 16px;
  font-weight: 400;
  color: var(--Grey);
}
.customers-section {
  display: flex;
  align-items: center;
  background-color: var(--Silver);
  height: 390px;
  gap: 78px;
  padding: 32px 144px;
  margin-top: 48px;
}
.customers-img {
  width: 326px;
  height: 326px;
}
.customers-text {
  color: var(--Grey);
  line-height: 24px;
  font-size: 16px;
  font-weight: 500;
}
.customers-association {
  color: var(--Grey);
  font-weight: 400;
  line-height: 24px;
  font-size: 16px;
}
.customers-logos {
  display: flex;
  gap: 41px;
}
.customers-btn {
  cursor: pointer;
  padding: 8px;
  border: none;
  background-color: transparent;
  color: var(--Primary);
  font-weight: 600;
  line-height: 28px;
  font-size: 20px;
}
.customers-btn::after {
  content: '→';
  margin-left: 8px;
}
</style>
