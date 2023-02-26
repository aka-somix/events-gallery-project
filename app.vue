<script lang="ts" setup>

useHead({
  title: 'Events Gallery',
  titleTemplate: '%s - Events Gallery',
  meta: [
    { name: 'viewport', content: 'width=device-width, initial-scale=1' },
    {
      content: 'Events Gallery',
    },
  ],
  link: [{ rel: 'icon', type: 'image/x-icon', href: '/favicon.ico' }],
})
</script>

<template>
  <Html>
    <Body
      class="antialiased duration-300 transition-colors text-gray-800 dark:text-gray-200 bg-white dark:bg-gray-900"
    >
      <NuxtLayout>
        <NuxtLoadingIndicator :height="5" :duration="3000" :throttle="400" />
        <NuxtPage />
      </NuxtLayout>
    </Body>
  </Html>
</template>
