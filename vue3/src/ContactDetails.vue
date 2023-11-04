<template>
    <div class="contact-details">
        <h1> Contact Details</h1>
        <p> <strong> Name:</strong>{{ name }}</p>
        <p> <strong> Website:</strong>{{ webAddress }} </p>
        <p> <strong> Address:</strong> {{ address }} </p>
    </div>
</template>

<script>

export default {
    props: {"name": {
        type: String, 
    }, "webAddress": {
        type: String,
        required: false,
        default: "ddd.com"
    }, "address": {
        type: String,
        required: true,
        defoult: "ddd.com"
    }},
    data() {
        return { 
        };
    },
}

</script>

<style>
.contact-details {
    border: 1px solid #ddd;
    padding: 20px;
    display: inline-block;
    margin: 30px;
}

.contact-details h1{
    color: blue; 
}


</style>