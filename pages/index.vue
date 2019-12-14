<template>
  <section>
    <!-- Hero -->
    <Hero />
    <!-- What We Do -->
    <WhatWeDo />
    <!-- Statistics -->
    <Statistics />
    <!-- Offer -->
    <Offer />
    <!-- Reviews -->
    <Reviews />
  </section>
</template>

<script>
import Hero from '~/components/Hero.vue'
import WhatWeDo from '~/components/pages/index/WhatWeDo.vue'
import Statistics from '~/components/pages/index/Statistics.vue'
import Reviews from '~/components/pages/index/Reviews.vue'
import WeWorkWith from '~/components/pages/index/WeWorkWith.vue'
import Offer from '~/components/pages/index/Offer.vue'

export default {
  name: 'HomePage',

  components: {
    Hero,
    WhatWeDo,
    Statistics,
    Reviews,
    WeWorkWith,
    Offer
  }
}
</script>
