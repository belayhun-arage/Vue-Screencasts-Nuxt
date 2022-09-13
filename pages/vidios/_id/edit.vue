<template>
    <div>
        <h2>Editing :  {{vidio.name}}</h2>
        <nuxt-link :to="`/vidios/${vidio.id}`">
            <button>Save&Back</button>
        </nuxt-link>
    </div>
</template>
<script>
    export default{
        props:['vidio']
    }
</script>