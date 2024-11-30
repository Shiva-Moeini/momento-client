<script lang="ts" setup>
import VerticalNavSectionTitle from '@/@layouts/components/VerticalNavSectionTitle.vue'
import VerticalNavGroup from '@layouts/components/VerticalNavGroup.vue'
import VerticalNavLink from '@layouts/components/VerticalNavLink.vue'
</script>

<template>

  <VerticalNavLink
    :item="{
      title: 'Dashboard',
      icon: 'bx-home-smile',
      href: 'dashboard'
    }"
  >
  </VerticalNavLink>
  <VerticalNavLink
    :item="{
      title: 'Timeline',
      icon: 'bx-file',
      href: 'timeline'
    }"
  >
  </VerticalNavLink>

</template>
