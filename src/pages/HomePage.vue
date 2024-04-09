<template>
  <q-page padding>
    <h1>
        My Quasar Project
    </h1>
    <!-- {{ datas }} -->

    <div class="row">
      <div class="col-6">
        <CardComponent :datas="datas">
        </CardComponent>
      </div>
      

      <div class="col-6">
        <FormComponent ></FormComponent>

        <ResultFormComponent></ResultFormComponent>
      </div>
    </div>
    
  </q-page>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue'
import CardComponent from 'components/CardComponent.vue'
import FormComponent from 'components/FormComponent.vue'
import ResultFormComponent from 'components/ResultFormComponent.vue'
import { techno } from '../components/data.json'

export default defineComponent({
  name: 'HomePage',

  components: {
    CardComponent,
    FormComponent,
    ResultFormComponent
  },
  
  setup () {
    const datas = ref(techno)

    return {datas}
    
  }
})
</script>
