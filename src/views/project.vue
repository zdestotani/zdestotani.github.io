<template>
    <div class="Project">
        <Navbar />
        <div class="container mt-5">
            <div class="row text-center">
                <div class="col mb-2">
                    <h2>Projects Saya</h2>
                </div>
            </div>
            <div class="row">
                <div class="col-md-4 mb-3">
                    <div class="card bg-dark text-white">
                        <img src="../assets/yt.png" class="card-img-top" alt="projects1">
                        <div class="card-body">
                            <h4><a class="card-title" href="https://www.youtube.com/watch?v=VE8M8DJOMCI">INSTALL NODE JS</a></h4>
                            <p class="card-text">tutorial menginstall vue js dan node js</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-3">
                    <div class="card bg-dark text-white">
                        <img src="../assets/j2.jpeg" class="card-img-top" alt="projects2">
                        <div class="card-body">
                            <h4><a class="card-title" href="https://www.youtube.com/watch?v=Dz262iJ5xGY">MEMBUAT HOMEPAGE</a></h4>
                            <p class="card-text">Membuat homepage dengan Menggunakan Vue js</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-3">
                    <div class="card bg-dark text-white">
                        <img src="../assets/j3.jpeg" class="card-img-top" alt="projects3">
                        <div class="card-body">
                            <h4><a class="card-title " href="https://www.youtube.com/watch?v=N-GnwBZU3IA">INSTALL JSON PLACEHOLDER</a></h4>
                            <p class="card-text">tutorial menginstall json placeholder</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <Footer />
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'

export default {
    name: 'ProjectView',
    components: {
        Navbar,
        Footer
    }
}
</script>

<style>
.Project{
    padding-top: 4rem;
}
.card-title{
    text-decoration: none;
}
</style>