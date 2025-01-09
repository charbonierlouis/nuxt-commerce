<script setup lang="ts">
   const { params: { slug } } = useRoute();
</script>

<template>
    <main>
        <section>
            <ContentDoc :path="`/products/informations/${slug}`" />
        </section>
    </main>
</template>