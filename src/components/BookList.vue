<template>
<div>
<h1>{{title}}</h1>
<ul>
<li>Harry Potter</li>
<li>Tom Sawyer</li>
<li>Lily James</li>
</ul>
</div>    
</template>
<script>
export default {
    name: "BookList",
    data() {
        return {
            title: "All Books"
        }
    }
}
</script>
<style scoped>
h1, h2 {
font-weight: normal;

}
</style>