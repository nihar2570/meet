<template>
    <NavbarPart />
    <CollectionsPart />
</template>

<script>
import NavbarPart from '../components/Navbar.vue'
import CollectionsPart from '../components/collections.vue'

export default {
    name: 'App',
    components: {
        NavbarPart,
        CollectionsPart,
    }
}
</script>

