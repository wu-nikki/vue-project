<template lang="pug">
TopImageVue
#middle
  #left
    LeftMenuVue
    LeftUpdateVue
  #right
    RightMarquee
    #page
      router-view
FooterText
</template>

<script setup>
import TopImageVue from '@/components/TopImage.vue'
import LeftMenuVue from '@/components/LeftMenu.vue'
import LeftUpdateVue from '@/components/LeftUpdate.vue'
import RightMarquee from '@/components/RightMarquee.vue'
import FooterText from '@/components/FooterText.vue'
</script>
<!-- router-view  -->
