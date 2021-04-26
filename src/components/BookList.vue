<template>
<div>
<h1>{{title}}</h1>
<ul class="list">
<li v-for="book in books" :key="book.title">{{book.title}}, {{book.author}}</li>
</ul>
</div>    
</template>
<script>
export default {
    name: "BookList",
    data() {
        return {
            title: "All Books",
            books: [
    {title: 'Self-Reliance', author: 'Ralph Waldo Emerson'},
    {title: 'American Gods', author: 'Neil Gaiman'},
    {title: 'Amusing Ourselves to Death', author: 'Neil Postman'},
]
        }
    }
}
</script>
<style scoped>
h1, h2 {
font-weight: normal;
}
.list {
list-style-type: none;
padding: 0;
}
.list li {
display: block;
margin: 0 10px;
}
</style>