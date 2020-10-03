<template>
  <q-page class="flex column flex-center">
         <q-icon name="school" size="150px" :style="{color: '#8A529A'}"/>
         <p>{{text}}</p>
        <q-input
          standout="bg-teal text-white" 
          v-model="text" 
          label="Digite um texto" 
          class="q-my-xl q-pa-lg"
          bg-color="purple-2"
          autogrow
         />
  </q-page>
</template>

<script>
export default {
  name: 'Jacode Cursos',
  data() {
    return {
      text: 'Aqui vai o seu texto',
    };
  },
};
</script>
