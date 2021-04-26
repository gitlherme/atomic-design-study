<template>
  <div class="presentation">
    <SocialList />
    <img
      src="@/assets/images/presentation.svg"
      alt="Apresentação"
      class="presentation"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialList } from '@/components/molecules'

export default defineComponent({
  components: { SocialList }
})
</script>

<style scoped lang="scss">
.presentation {
  position: relative;
  display: grid;
  justify-content: center;
  .presentation {
    width: 80%;
    justify-self: center;
  }
  .social-list {
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%);
  }
}
</style>
