<script lang="ts" setup>

const { data } = await useFetch('/api/hello')

</script>

<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>
