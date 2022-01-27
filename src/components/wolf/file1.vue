<template>
  <div>
    <img
      :src="require('@/assets/icons/dummy.svg')"
      alt="dummy"
    >
    <img
      :src="require('@/assets/icons/dummy.svg')"
      alt="dummy"
    >
  </div>
</template>

<script>
import Dummy from '@/components/atoms/dummy';

export default {
  components: {
    Dummy,
  },
};
</script>
