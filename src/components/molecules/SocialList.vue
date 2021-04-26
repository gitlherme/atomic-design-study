<template>
  <ul class="social-list">
    <li>
      <SocialLink
        to="https://github.com/gitlherme"
        socialName="Github"
        icon="github.svg"
      />
    </li>
    <li>
      <SocialLink
        to="https://twitter.com/gitlherme"
        socialName="Twitter"
        icon="twitter.svg"
      />
    </li>
    <li>
      <SocialLink
        to="https://facebook.com/guih.dev"
        socialName="Facebook"
        icon="facebook.svg"
      />
    </li>
  </ul>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLink } from '@/components/atoms/'

export default defineComponent({
  components: { SocialLink }
})
</script>

<style scoped lang="scss">
.social-list {
  display: grid;
  grid-gap: 1rem;
  list-style: none;
}
</style>
