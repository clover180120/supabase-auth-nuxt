<script setup>
const supabase = useSupabaseClient();
const router = useRouter();

supabase.auth.signOut();
router.push('/');
</script>

<template>
  <div></div>
</template>