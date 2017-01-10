<style src="./style.css"></style>
<template src="./template.html"></template>

<script>
    export default {
        props: {
            barHeight: {
                type: Number,
                default: 5
            },
            value: {
                type: [Number, String],
                required: true
            }
        }
    }
</script>