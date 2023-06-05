<script setup>
</script>
<template>
      <div class="container-fluid p-0">
        <div id="header-carousel" class="carousel slide" data-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img class="w-100" src="../assets/img/carousel-1.jpg" alt="Image">
                    <div class="carousel-caption d-flex flex-column align-items-center justify-content-center">
                        <div class="p-3" style="max-width: 900px;">
                            <h4 class="text-white text-uppercase mb-md-3">WEBS DINAMICAS</h4>
                            <h1 class="display-3 text-white mb-md-4">CREAMOS WEB APPS A MEDIDA DE TU NEGOCIO</h1>
                            <a href="" class="btn btn-primary py-md-3 px-md-5 mt-2">Ver m&aacutes</a>
                        </div>
                    </div>
                </div>
                <div class="carousel-item">
                    <img class="w-100" src="../assets/img/carousel-2.jpg" alt="Image">
                    <div class="carousel-caption d-flex flex-column align-items-center justify-content-center">
                        <div class="p-3" style="max-width: 900px;">
                            <h4 class="text-white text-uppercase mb-md-3">WEB ESTATICAS</h4>
                            <h1 class="display-3 text-white mb-md-4">Dise&ntildeamos tu sitio web</h1>
                            <a href="" class="btn btn-primary py-md-3 px-md-5 mt-2">Ver m&aacutes</a>
                        </div>
                    </div>
                </div>
            </div>
            <a class="carousel-control-prev" href="#header-carousel" data-slide="prev" @click="prev">
                <div class="btn btn-dark" style="width: 45px; height: 45px;">
                    <span class="carousel-control-prev-icon mb-n2"></span>
                </div>
            </a>
            <a class="carousel-control-next" href="#header-carousel" data-slide="next">
                <div class="btn btn-dark" style="width: 45px; height: 45px;">
                    <span class="carousel-control-next-icon mb-n2"></span>
                </div>
            </a>
        </div>
    </div>
</template>

<style scoped>

</style>
