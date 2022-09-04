<script setup>
    const route = useRoute();
</script>

<template>
    <div>
        <h1>動態頁面 : {{ route.path }}</h1>
    </div>
</template>