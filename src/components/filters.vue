<template>
    <div class="container p-4">
        <div class="row">
            <div class="col font-monospace">
                <div class="btn-toolbar" role="toolbar" aria-label="Toolbar with button groups">
                    <div class="btn-group m-1" role="group" aria-label="First group">
                        <button type="button" class="shadow-sm btn btn-outline-info">Filter 1</button>
                    </div>
                    <div class="btn-group m-1" role="group" aria-label="First group">
                        <button type="button" class="shadow-sm btn btn-outline-info">Filter 2</button>
                    </div>
                    <div class="btn-group m-1" role="group" aria-label="First group">
                        <button type="button" class="shadow-sm btn btn-outline-info">Filter 3</button>
                    </div>
                    <div class="btn-group m-1" role="group" aria-label="First group">
                        <button type="button" class="shadow-sm btn btn-outline-info">Filter 4</button>
                    </div>
                    <div class="btn-group m-1" role="group" aria-label="First group">
                        <button type="button" class="shadow-sm btn btn-outline-info">Filter 5</button>
                    </div>
                    <div class="btn-group m-1" role="group" aria-label="First group">
                        <button type="button" class="shadow-sm btn btn-outline-info">Filter 6</button>
                    </div>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-sm-12 col-md-8 d-flex justify-content-start font-monospace">
                <button type="button m-1" class="btn btn-outline-primary m-1 shadow-sm fw-bold">
                    Filter Item<span class="badge text-bg-light">X</span>
                </button>
                <button type="button m-1" class="btn btn-outline-primary m-1 shadow-sm fw-bold">
                    Filter Item<span class="badge text-bg-light">X</span>
                </button>
            </div>
            <div class="col-sm-12 col-md-4 d-flex justify-content-end">
                <button type="button m-1" class="disabled btn-outline-light btn text-dark me-2 font-monospace">Sort by:</button>
                <button type="button m-1" class="btn btn-light me-2 shadow-sm">+</button>
                <button type="button m-1" class="btn btn-light shadow-sm">-</button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'FiltersPart',
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>