<template>
    <nav class="navbar bg-primary" data-bs-theme="dark">
      <div class="container">
        <router-link to="/" class="navbar-brand" href="#">
          Meet
        </router-link>
        <router-link to="/profile" class="text-white h6">
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
