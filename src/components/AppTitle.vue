<script>

export default {
  name: 'AppTitle',

  data(){
    return{

      title: 'La mia prima app con Vite!',
      subtitle: '...la prima di una lunga serie'

    }
  }

}

</script>

<template>

  <div class="container">

    <h1>{{title}}</h1>
    <h2>{{subtitle}}</h2>

  </div>

  
</template>


<style scoped>

h1{
  font-size: 4rem;
  color: white;
}

h2{
  font-size: 2.5rem;
  color: darkorange;
}

</style>