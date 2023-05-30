<template>
    <nav class="navbar bg-primary shadow-sm" data-bs-theme="dark">
      <div class="container">
        <router-link to="/" class="navbar-brand h6" href="#">
          Meet
        </router-link>
        <router-link to="/profile" class="navbar-brand text-white">
            Profile
        </router-link>
      </div>
    </nav>
</template>

<script>
export default {
    name: 'NavbarPart',
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
