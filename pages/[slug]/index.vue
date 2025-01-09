<script setup lang="ts">
   const { params: { slug } } = useRoute();
</script>

<template>
    <main>
        <div>
            <ContentDoc :path="`/${slug}`">

            </ContentDoc>
        </div>
    </main>
</template>