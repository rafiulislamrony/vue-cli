<template>
    <h1> Contact Details</h1>
    <p> <strong> Name:</strong>{{ name }}</p> 
    <p> <strong> Website:</strong>{{ web }} </p> 
    <p> <strong> Address:</strong> {{ address }} </p> 
</template>

<script>

export default {
    data(){
        return{
            name: "Rafiul Islam",
            web: "www.rafiul.com",
            address: "Dhaka, Bangladesh"
        };
    },
}
 
</script>