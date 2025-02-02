<script setup>
import AchievementsSection from './achievements/AchievementsSection.vue'
import CommunityUpdSection from './communityUpds/CommunityUpdSection.vue';
import CustomersSection from './CustomersSection.vue'
import InfoBlock from './InfoBlock.vue'
</script>

<template>
  <InfoBlock
    imgPath="img/Frame35.png"
    heading="The unseen of spending three years at Pixelgrade"
    paragraph="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sit amet justo ipsum. Sed
      accumsan quam vitae est varius fringilla. Pellentesque placerat vestibulum lorem sed porta.
      Nullam mattis tristique iaculis. Nullam pulvinar sit amet risus pretium auctor. Etiam quis
      massa pulvinar, aliquam quam vitae, tempus sem. Donec elementum pulvinar odio."
    btnText="Learn more"
  />
  <AchievementsSection />
  <InfoBlock
    imgPath="img/pana.png"
    heading="How to design your site footer like we did"
    paragraph="Donec a eros justo. Fusce egestas tristique ultrices. Nam tempor, augue nec tincidunt molestie, massa nunc varius arcu, at scelerisque elit erat a magna. Donec quis erat at libero ultrices mollis. In hac habitasse platea dictumst. Vivamus vehicula leo dui, at porta nisi facilisis finibus. In euismod augue vitae nisi ultricies, non aliquet urna tincidunt. Integer in nisi eget nulla commodo faucibus efficitur quis massa. Praesent felis est, finibus et nisi ac, hendrerit venenatis libero. Donec consectetur faucibus ipsum id gravida."
    btnText="Learn more"
  />
  <CustomersSection />
  <CommunityUpdSection />
</template>
