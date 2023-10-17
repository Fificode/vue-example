<template>
<div>
    <h1>Routing </h1>
    <!-- before Unmount and unmounted -->
    <!-- <button @click="show=false">Hide</button>
    <Users v-if="show"/> -->
    <!-- beforeUpdate and updated life cycle method -->
    <!-- <h2 ref="count">{{ counter }}</h2>
    <button @click="counter=counter+1">Update counter</button> -->
    <!-- Teleport component -->
    <!-- <teleport to="#footer">
      <h1>Hii</h1>
<Footer />
    </teleport> -->
    <!-- Slots -->
    <!-- <Child>
        <template v-slot:header>
       <h1>Heyy</h1>
    </template>
    <template v-slot:main>
       <h2>Don't go chasing waterfalls</h2>
    </template>
      <template v-slot:footer> <button>Buy now</button></template>
    </Child> -->
    
    
    <!-- Watchers -->
   <!-- <h2>{{ count }}</h2>
   <button @click="count=count+1">+</button>
   <button @click="count=count-1">-</button> -->
   <!-- Props -->
    <!-- <User item="some data" name="user-comp"/> -->
    </div>
</template>

<script>
// import User from './User.vue';
// import Child from './Child.vue';
// import Footer from './Footer.vue';
// import Users from './Users.vue';

export default {
    name: 'Home-page',
    components: {
        // Child,
        // User,
        // Footer,
        // Users,
    },
   data(){
        return{
            // show: true
        //   count: 0
        // counter: 0
        }
    }, 
    //beforeUpdated
    // beforeUpdate(){
    //   console.log('beforeUpdate',this.$refs['count'].textContent)
    // },
    //updated
//     updated(){
// console.log('updated', this.$refs['count'].textContent)
//     },
    // watch:{
    //     count(val, prev){
    //        if(val > 10 && val>prev){
    //         this.count=0
    //        }
    //     }
    // },
    computed: {


    },
    methods: {
       
    }
}
</script>
<style>

</style>