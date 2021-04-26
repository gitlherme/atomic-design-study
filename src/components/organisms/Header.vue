<template>
  <header class="header">
    <Logo />
    <NavBar />
    <Search />
  </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Logo } from '@/components/atoms'
import { NavBar, Search } from '@/components/molecules'

export default defineComponent({
  components: {
    Logo,
    NavBar,
    Search
  }
})
</script>

<style scoped lang="scss">
.header {
  width: 100%;
  display: grid;
  grid-template-columns: 160px repeat(2, auto);
  align-items: center;
  justify-content: space-between;
}
</style>
