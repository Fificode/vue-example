<template>

    <div>
        <h1 ref="user">User componenet</h1>
    </div>
</template>

<script>
export default {
    name: 'Users-page',
    beforeUnmount(){
        console.warn('before unmount', this.$refs['user']);
    },
    unmounted(){
        console.warn('mounted', this.$refs['user']);
    }
}
</script>