<template>
    <FiltersPart/>
    <div class="container">
        <div class="row p-2 row-cols-1 row-cols-md-4 g-4">
            <div class="col">
                <div class="card shadow-sm border-light-subtle text-center border-light">
                    <img src="../assets/2.webp" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Daniel Wheatley</h5>     
                        <h6 class="card-subtitle mb-2 text-body-secondary">27 Years</h6>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card shadow-sm border-light-subtle text-center border-light">
                    <img src="../assets/5.webp" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">John White</h5>     
                        <h6 class="card-subtitle mb-2 text-body-secondary">21 Years</h6>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card shadow-sm border-light-subtle text-center border-light">
                    <img src="../assets/6.webp" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">David McKay</h5>     
                        <h6 class="card-subtitle mb-2 text-body-secondary">29 Years</h6>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card shadow-sm border-light-subtle text-center border-light">
                    <img src="../assets/7.webp" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">William Delacruz</h5>     
                        <h6 class="card-subtitle mb-2 text-body-secondary">25 Years</h6>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card shadow-sm border-light-subtle text-center border-light">
                    <img src="../assets/8.webp" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Matthew Everhart</h5>     
                        <h6 class="card-subtitle mb-2 text-body-secondary">24 Years</h6>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card shadow-sm border-light-subtle text-center border-light">
                    <img src="../assets/9.webp" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Stephen Robinson</h5>     
                        <h6 class="card-subtitle mb-2 text-body-secondary">26 Years</h6>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card shadow-sm border-light-subtle text-center border-light">
                    <img src="../assets/10.webp" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Kory Grimes</h5>     
                        <h6 class="card-subtitle mb-2 text-body-secondary">27 Years</h6>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card shadow-sm border-light-subtle text-center border-light">
                    <img src="../assets/11.webp" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Craig Johnson</h5>     
                        <h6 class="card-subtitle mb-2 text-body-secondary">22 Years</h6>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import FiltersPart from './filters.vue'
export default {
    name: 'CollectionsPart',
    components: {
        FiltersPart,
    }
}
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
