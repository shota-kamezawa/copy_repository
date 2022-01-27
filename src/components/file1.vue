<template>
  <div>
    <img
      :src="require('@/app/assets/icons/dummy.svg')"
      alt="dummy"
    >
    <img
      :src="require('~/app/assets/icons/dummy.svg')"
      alt="dummy"
    >
  </div>
</template>

<script>
import Dummy from '@/app/components/atoms/dummy';

export default {
  components: {
    Dummy,
  },
};
</script>
