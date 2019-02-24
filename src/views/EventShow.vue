<template>
  <div>
    <h1>Showing Event #{{ id }}</h1>
    <router-link :to="{ name: 'event-show', params: {id: '1'} }">Show Event #1</router-link>|
  </div>
</template>
<script>
export default {
  props: ['id']
}
</script>