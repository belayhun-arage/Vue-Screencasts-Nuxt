<template>
    <div>
        <h1>Vidio Lists:</h1>
        <nuxt-child :vidios="vidios"/>
        <div v-for="vidio in vidios" :key="vidio.id">
            <h1>{{vidio.name}}</h1>
        </div>
    </div>
</template>

 <script scoped>
     export default{
         data(){
            return{
             vidios:[
                 {id:0,name:"Vidio One is realeased"},
                 {id:1,name:"Vidio One is realeased"},
                 {id:2,name:"Vidio One is realeased"},
                 {id:2,name:"Vidio One is realeased"}
             ]
             } 
            } 
     }
 </script>