<template>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
    <path :class="[secondary, 'fill-current']" d="M512 224v64a16 16 0 0 1-16 16H80a16 16 0 0 1-16-16v-64a16 16 0 0 1 16-16h416a16 16 0 0 1 16 16z" />
    <path :class="[primary, 'fill-current']" d="M432 32H16A16 16 0 0 0 0 48v64a16 16 0 0 0 16 16h416a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16zm0 352H16a16 16 0 0 0-16 16v64a16 16 0 0 0 16 16h416a16 16 0 0 0 16-16v-64a16 16 0 0 0-16-16z" />
  </svg>
</template>

<script>
import icon from '@/mixins/icon'
export default { mixins: [ icon ] }
</script>
