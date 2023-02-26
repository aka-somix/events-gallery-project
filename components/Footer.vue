<script lang="ts" setup>
import { AppConfigInput } from '@nuxt/schema'
const app = useAppConfig() as AppConfigInput
</script>

<template>
  <footer class="border-t lg:border-gray-900/10 dark:border-gray-50/[0.2]">
    <section
      class="max-w-8xl mx-auto px-4 lg:px-8 flex-1 flex w-full space-x-20"
    >
      <div class="w-full py-4 text-center md:text-left flex justify-between">
        <div class="mb-1 text-xs">
          🎞️ Events Gallery
        </div>
        <div class="text-xs text-gray-600 dark:text-gray-400">
          Made with <span class="text-red-500">❤</span>
          by <a href="https://github.com/aka-somix">Somix</a>
        </div>
      </div>
    </section>
  </footer>
</template>
