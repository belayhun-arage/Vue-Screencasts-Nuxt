<template>
    <div>
        Vidio Details
        <h1>{{vidio.name}}</h1>
        <nuxt-link :to="`/vidios/${vidio.id}/edit`">
            <button>Edit</button>
        </nuxt-link>
    </div>
</template>
<script>
    export default{
        props:['vidio'],
    }
</script>