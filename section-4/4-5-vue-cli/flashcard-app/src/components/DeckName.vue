<template>
    <h1>{{name}}</h1>
</template>

<script>
    export default {
        name: 'DeckName',
        props: ['name']
    };
</script>

<style scoped>
    /* 
    You don't need to use style but it's a great place for component specific css
    and it cannot make it really easy to update this component later because we'll
    have the mark up, logic, and relevant CSS, all in one place.
    */
    h1 {
        font-style: italic;
    }
</style>