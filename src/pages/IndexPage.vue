<template>
  <q-page class="row items-center justify-evenly">
    <CardComponent></CardComponent>
  </q-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
// import { Todo, Meta } from 'components/models';
import CardComponent from 'components/CardComponent.vue';

export default defineComponent({
  name: 'IndexPage',

  components: {
    CardComponent
  },

  // setup () {
  //   // const todos = ref<Todo[]>([
  //   //   {
  //   //     id: 1,
  //   //     content: 'ct1'
  //   //   },
  //   //   {
  //   //     id: 2,
  //   //     content: 'ct2'
  //   //   },
  //   //   {
  //   //     id: 3,
  //   //     content: 'ct3'
  //   //   },
  //   //   {
  //   //     id: 4,
  //   //     content: 'ct4'
  //   //   },
  //   //   {
  //   //     id: 5,
  //   //     content: 'ct5'
  //   //   }
  //   // ]);

  //   // const meta = ref<Meta>({
  //   //   totalCount: 1200
  //   // });

  //   // return { todos, meta };
  // }
});
</script>
