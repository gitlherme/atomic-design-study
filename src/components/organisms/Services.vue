<template>
  <div class="services">
    <Service
      title="Front end"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore dignissimos voluptatum deleniti praesentium voluptatem laborum, tempora sapiente iste nulla dolore quaerat. Laudantium cupiditate asperiores vel? Obcaecati possimus laboriosam facere at."
    />
    <Service
      title="Back end"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore dignissimos voluptatum deleniti praesentium voluptatem laborum, tempora sapiente iste nulla dolore quaerat. Laudantium cupiditate asperiores vel? Obcaecati possimus laboriosam facere at."
    />
    <Service
      title="Manual"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore dignissimos voluptatum deleniti praesentium voluptatem laborum, tempora sapiente iste nulla dolore quaerat. Laudantium cupiditate asperiores vel? Obcaecati possimus laboriosam facere at."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'
export default defineComponent({
  components: { Service }
})
</script>

<style scoped lang="scss">
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
