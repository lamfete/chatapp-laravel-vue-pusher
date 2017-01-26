<template lang="html">
    <div>
        <p>{{ message.message }}</p>
        <small>{{ message.user }}</small>
    </div>
</template>

<script>
    export default {
        // data() {
        //     return {
        //         message: "This is some message text",
        //         user: "John Doe"
        //     }
        // }
        props: ['message']
    }
</script>

<style lang="css">
.chat-message {
    padding: 1rem;
}

.chat-message > p {
    margin-bottom: .5rem;
}
</style>
