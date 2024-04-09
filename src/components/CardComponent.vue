<template>
    

        <div class="row">
            <q-card class="my-card q-ma-md col-5" v-for="data in datas" :key="data.id">
                <img src="https://placehold.co/300x300">
                <q-card-section>
                    <div class="text-h6">{{ data.label }}</div>
                    <div class="text-subtitle2">{{ data.text }}</div>
                </q-card-section>
            </q-card>
        </div>
    
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'CardComponent',

  props: {
    datas: {
      type: Object,
      required: true,
    }
  },
  
});
</script>
