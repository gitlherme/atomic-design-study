<template>
  <nav class="nav-bar">
    <NavItem to="/services" text="Serviços"></NavItem>
    <NavItem to="/about" text="Sobre"></NavItem>
    <NavItem to="/cases" text="Cases"></NavItem>
    <NavItem to="/contact" text="Contato"></NavItem>
  </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { NavItem } from '@/components/atoms'

export default defineComponent({
  components: { NavItem }
})
</script>

<style scoped>
.nav-bar {
  width: max-content;
  display: grid;
  grid-auto-flow: column;
  grid-gap: 2.5rem;
}
</style>
