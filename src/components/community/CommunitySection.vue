<script setup>
import CommunityCard from './CommunityCard.vue'
</script>

<template>
  <section class="community-section">
    <h2 class="heading-secondary u-text-center u-mb-s">
      Manage your entire community <br />
      in a single system
    </h2>
    <p class="text">Who is Nextcent suitable for?</p>
    <div class="for-who-group u-mt-m">
      <CommunityCard
        imgPath="/img/com-icon.png"
        heading="Membership Organisations"
        text="Our membership management software provides full automation of membership renewals and
              payments"
      />
      <CommunityCard
        imgPath="/img/com-icon2.png"
        heading="National Associations"
        text="Our membership management software provides full automation of membership renewals and
          payments"
      />
      <CommunityCard
        imgPath="/img/com-icon3.png"
        heading="Clubs And <br /> Groups"
        text="Our membership management software provides full automation of membership renewals and
          payments"
      />
    </div>
  </section>
</template>

<style scoped>
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
</style>
