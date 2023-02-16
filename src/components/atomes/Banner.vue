<template>
    <h1>{{ title }}</h1>
    <img src="" alt="">
</template>

<script>
    export default {
        name: 'Banner',
        props: {
            title: {
                type: String,
                default: ''
            },
            image: {
                type: String,
                default: ''
            }
        }
    }
</script>