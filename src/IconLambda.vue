<template>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
    <path :class="[secondary, 'fill-current']" d="M194.62 243.73l-95 221.72A24 24 0 0 1 77.54 480H25.31a24 24 0 0 1-22.06-33.45l132.88-310.06z" />
    <path :class="[primary, 'fill-current']" d="M448 408v48a24 24 0 0 1-24 24h-81.5a32 32 0 0 1-28.1-16.68L131.5 128H24a24 24 0 0 1-24-24V56a24 24 0 0 1 24-24h145.5a32 32 0 0 1 28.1 16.68L380.5 384H424a24 24 0 0 1 24 24z" />
  </svg>
</template>

<script>
import icon from '@/mixins/icon'
export default { mixins: [ icon ] }
</script>
