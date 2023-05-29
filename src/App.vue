<template>
  <HelloWorld/>
  <NavbarPart/>
  <ProfilePart/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NavbarPart from './components/Navbar.vue'
import ProfilePart from './components/Profile.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    NavbarPart,
    ProfilePart
  }
}
</script>

