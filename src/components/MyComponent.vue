<template>
<!-- type vbase and click on vbase-css 
    and then-->
    <div>
<!-- 2. -->
<!-- then delete the helloworld.vue -->
<!-- go back to app.vue and delete the ref to helloworld file -->
<!-- 5. you need to use the component -->
    <h1>Hello components!</h1>
    <p>Lorem ipsum dolor sit amet.</p>

    </div>
</template>

<script>
//1. in export ..name : add your file name
//3. import MyComponent in app.vue
//4. add componets: in app.vue
    export default {
        name : "MyComponent"
        //add the bottom code to app.vue to register it in export
        // components : {
        //     MyComponent
        // }
    }
</script>

<style scoped>
h1{
    color: navy;
}

p{
    color: rgb(14, 138, 14);
    background-color: rgba(0, 128, 0, 0.258);
}

</style>