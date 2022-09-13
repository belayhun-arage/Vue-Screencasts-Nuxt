<template>
    <nuxt-child :vidio="vidio"/>
</template>

<script>
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
        },
        computed:{
            vidio(){
                return this.vidios.find(v=>this.$route.params.id==v.id);
            }
        }
    }
</script>