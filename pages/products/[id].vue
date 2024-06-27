<template>
    <div>
        This is your route param id, "{{ id }}"
    </div>
</template>

<script setup>
        const { id } = useRoute().params
</script>