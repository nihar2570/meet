<template>
    <nav class="navbar bg-primary" data-bs-theme="dark">
      <div class="container">
        <a class="navbar-brand" href="#">
          Meet
        </a>
        <span class="text-white h6">
            Profile
        </span>
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
