<script setup>
import CommunityUpdCard from './CommunityUpdCard.vue'
</script>

<template>
  <section class="community-section">
    <h2 class="heading-secondary u-text-center u-mb-s">Caring is the new marketing</h2>
    <p class="com-description u-text-center u-mb-m">
      The Nexcent blog is the best place to read about the latest membership insights, trends and
      more. See who's joining the community, read about how our community are increasing their
      membership income and lot's more.
    </p>
    <div class="community-cards">
      <CommunityUpdCard
        imgPath="/img/comImg1.png"
        heading="Creating Streamlined Safeguarding Processes with OneRen"
        btnText="Read more"
      />
      <CommunityUpdCard
        imgPath="/img/comImg2.png"
        heading="What are your safeguarding responsibilities and how can you manage them?"
        btnText="Read more"
      />
      <CommunityUpdCard
        imgPath="/img/comImg3.png"
        heading="Revamping the Membership Model with Triathlon Australia"
        btnText="Read more"
      />
    </div>
  </section>
</template>

<style scoped>
.community-section {
  display: flex;
  flex-direction: column;
  margin-top: 48px;
  margin-bottom: 80px;
  height: 506px;
}
.community-cards {
  display: flex;
  justify-content: space-between;
  padding: 0 144px;
}
.com-description {
  width: 628px;
  align-self: center;
  font-weight: 400;
  line-height: 24px;
  font-size: 16px;
  color: var(--Grey);
}
</style>
