<script setup>
import Icon from './icons/icon.vue'
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
<div class="container-fluid position-relative nav-bar p-0">
        <div class="container-lg position-relative p-0 px-lg-3" style="z-index: 9;">
            <nav class="navbar navbar-expand-lg bg-light navbar-light shadow-lg py-3 py-lg-0 pl-3 pl-lg-5">
                <a href="" class="navbar-brand">
                    <Icon />
                    <h1 class="m-0 text-primary" style="display: inline; color: #000;"><span class="text-dark">MYA</span>TEC</h1>
                </a>
                <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-between px-3" id="navbarCollapse">
                    <div class="navbar-nav ml-auto py-0">
                        <a href="index.html" class="nav-item nav-link active">INICIO</a>
                        <a href="about.html" class="nav-item nav-link">ACERCA</a>
                        <a href="service.html" class="nav-item nav-link">SERVICIOS</a>
                        <a href="package.html" class="nav-item nav-link">PAQUETES</a>
                        <a href="contact.html" class="nav-item nav-link">CONTACTO</a>
                    </div>
                </div>
            </nav>
        </div>
    </div>
</template>

<style scoped>

</style>
