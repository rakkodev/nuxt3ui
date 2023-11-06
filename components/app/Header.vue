<script lang="ts" setup></script>

<template>
  <div class="w-full border-b bg-green-100 border-green-300 min-h-[50px]">
    <div class="flex justify-between container items-center">
      <!-- header left -->
      <div>
        <NuxtImg src="https://nuxt.com/assets/design-kit/icon-green.svg" width="50px" />
      </div>
      <!-- header right -->
      <div>
        <div class="flex gap-5">
          <nuxt-link class="link text-green-600" to="/">Home</nuxt-link>
          <nuxt-link class="link text-green-600" to="/">About</nuxt-link>
          <nuxt-link class="link text-green-600" to="/">Contact</nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
