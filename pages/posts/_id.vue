<template>
  <div>
    <h1>Post Detail : {{ id }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      id: this.$route.params.id,
    }
  },
}
</script>
