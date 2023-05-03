<script setup>
import SayHello from '@/components/SayHello.vue';
import { useMyStore } from '../stores/myStore';

const myStore = useMyStore();
</script>

<template>
  <div class="column items-center q-mt-md">
    <span class="text-h4">Home</span><br /><span>{{ myStore.message }}</span>
    <SayHello name="Robert"></SayHello>
  </div>

</template>
