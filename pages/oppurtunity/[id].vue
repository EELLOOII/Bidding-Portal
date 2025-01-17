<template>
    <div>
        <p>Oppurtunity ID {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae explicabo exercitationem velit deserunt doloremque asperiores quibusdam cupiditate repellendus vero eveniet! Quae eos architecto animi delectus nulla quasi nemo ducimus optio accusamus omnis officiis commodi, cupiditate velit, fugit voluptatem vel sunt.</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
</script>

<style lang="scss" scoped>

</style>