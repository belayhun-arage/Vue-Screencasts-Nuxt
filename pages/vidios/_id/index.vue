<template>
    <div>
        Vidio Details
        <h1>{{vidio.name}}</h1>
        <p>{{vidio.id}}</p>
    </div>
</template>
<script>
    export default{
        props:['vidio'],
    }
</script>