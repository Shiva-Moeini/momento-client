<script setup lang="ts">
import Timeline from '@/views/pages/timeline/Timeline.vue'
import TimelineItems from '@/views/pages/timeline/Timeline-Items.vue'
import TimelinesList from '@/views/pages/timeline/Timelines-List.vue'



</script>

<template>
  <VRow>
    <VCol
      cols="12"
      md="8"
    >
    <Timeline />
    <Timeline-Items />
    <Timelines-List />
    </VCol>
  </VRow>
</template>
