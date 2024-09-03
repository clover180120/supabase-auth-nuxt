<script setup>
const user = useSupabaseUser();
console.log(user);
</script>

<template>
  <div>index</div>
  <NuxtLink to="/sign-out">Sign Out</NuxtLink>
  or
  <NuxtLink to="/sign-in">Sign In</NuxtLink>
  or
  <NuxtLink to="/sign-up">Sign Up</NuxtLink>
</template>