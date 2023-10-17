<template>
    <!-- Slots -->
   <header> <slot name="header"><h1>Default value</h1></slot></header>
<main><slot name="main"><h1>Default value</h1></slot></main>
    <footer><slot name="footer"><h1>Default value</h1></slot></footer>
</template>

<script>
export default {
    name: 'Child-page',
    
}
</script>
<style>
h1{
    color: purple
}
</style>