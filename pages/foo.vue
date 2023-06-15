<template>
  <div class="foo">
    <h1 @click="router.push('foo/aaa')">Foo</h1>
    <NuxtPage />
  </div>
</template>

<script setup lang="ts">
const router = useRouter();
</script>

<style scoped>
.foo {
  color: red;
  height: 200vh;
}
h1 {
  height: 100%;
  cursor: pointer;
}
</style>
