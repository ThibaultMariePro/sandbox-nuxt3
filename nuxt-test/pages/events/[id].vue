<!-- <script>
    console.log('ola')
    const route = useRoute();
    console.log(route.params)
</script> -->

<script>
    const nuxt = useNuxtApp();
    console.log(nuxt)
</script>

<template>
    <div>
        events id : {{ $route.params.id }}
    </div>
</template>

