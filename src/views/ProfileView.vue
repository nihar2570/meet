<template>
    <NavbarPart />
    <ProfilePart />
</template>

<script>
import NavbarPart from '../components/Navbar.vue'
import ProfilePart from '../components/Profile.vue'

export default {
    name: 'App',
    components: {
        NavbarPart,
        ProfilePart
    }
}
</script>