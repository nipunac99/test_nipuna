<template>
    <div class="container">
        <div class="d-flex align-items-center justify-content-center mt-5 mb-5">
            <h2 class="main-topic-content fw-bold">{{ text }}</h2>

        </div>
    </div>
</template>

<script setup>
defineProps({
    text: {
        type: String,
        required: true
    },
})
</script>

<style></style>