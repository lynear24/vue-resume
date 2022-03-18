<template>
    <div id="gallery" class="my-5">
        <div id="carousel-gallery" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-inner">

                <div class="carousel-item active">
                    <img src="../assets/gallery/1.png" alt="monty" class="d-block w-100">
                </div>

                <div class="carousel-item">
                    <img src="../assets/gallery/2.png" alt="foxy" class="d-block w-100">
                </div>

                <div class="carousel-item">
                    <img src="../assets/gallery/3.png" alt="layla" class="d-block w-100">
                </div>

                <button class="carousel-control-prev" type="button" data-bs-target="#carousel-gallery" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>

                <button class="carousel-control-next" type="button" data-bs-target="#carousel-gallery" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>

            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'gallery',
    data () {
        return {
            msg: 'This is the Gallery Page'
        }
    }
}
</script>