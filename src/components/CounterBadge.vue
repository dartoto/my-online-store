<template>
  <span v-if="count > 0" class="badge">
    {{ count }}
  </span>
</template>

<script>
export default {
  name: 'counter-badge',
  props: ['count'],
}
</script>

<style>
.badge {
  position: absolute;
  top: 1.0rem;
  right: 20.0rem;
  display: flex;
  justify-content: center;
  align-items: center;
  height:40px;
  width: 40px;
  border-radius: 20px;
  background-color: #42b983;
  color: #FFF;
  font-weight: bold;
  font-size: 12px;
}
</style>