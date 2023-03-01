<template>
  <div id="MapView">
    <KakaoMap />
  </div>
</template>

<script>
import KakaoMap from '@/components/KakaoMap.vue';
export default {
  name: 'MapView',
  components: {
    KakaoMap,
  },
};
</script>
