<template>
  <ul class="menu w-full" :class="{ 'menu-horizontal': horizontal }">
    <li>
      <RouterLink :to="{ name: 'privacy' }">Privacy Policy</RouterLink>
    </li>
    <li><a href="https://app.uconverter.mehmetuysal.dev">App</a></li>
  </ul>
</template>

<script lang="ts">
export default {
  props: {
    horizontal: {
      type: Boolean,
      default: false
    }
  }
}
</script>
