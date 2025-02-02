<script setup>
import AchievementStat from './AchievementStat.vue';

</script>

<template>
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
      <AchievementStat imgPath="/img/stats-icon.png" stat="2,245,341" name="Members" />
      <AchievementStat imgPath="/img/stats-icon2.png" stat="46,328" name="Clubs" />
      <AchievementStat imgPath="/img/stats-icon3.png" stat="828,867" name="Event Bookings" />
      <AchievementStat imgPath="/img/stats-icon4.png" stat="1,926,436" name="Payments" />
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
</style>
