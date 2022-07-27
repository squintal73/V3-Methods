<template>

<h1>COUNTER : {{ counter }}</h1>
<button @click="decrement">Decrementar</button>
<button @click="increment">Incrementar</button>
</template>

<script>

export default {
      name:'Counter_',
      data:() => ({
            counter:0
      }),
      methods:{
        decrement: function(){
            this.counter--
        },
        increment: function(){
            this.counter++
        }
      }
}
</script>



