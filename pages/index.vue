<template>
    <Welcome/>
</template>

<script>
export default {
  components: {
    Welcome: () => import('@/components/Welcome')
  }
}
</script>