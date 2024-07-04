<template>
  <section class="projects">

    <div class="container mt-5">
    <div class="text-center mb-5">
      <h1 style="font-size: 2.5em;">My Projects</h1>
      <p style="font-size: 1.2em;">Here are some of the projects I have worked on.</p>
    </div>
    
    <div class="row">
      <!-- Project 1 -->
      <div class="col-md-4 mb-4">
        <div class="card h-100" style="border: 1px solid #ddd;">
          <img src="assets/img/project1.png" class="card-img-top" alt="Project 2" style="height: 200px; object-fit: cover;">
          <div class="card-body">
            <h5 class="card-title">PT Usbarja</h5>
            <p class="card-text">Saya menjadi bagian dari pembuatan website ini.</p>
          </div>
        </div>
      </div>

      <!-- Project 2 -->
      <div class="col-md-4 mb-4">
        <div class="card h-100" style="border: 1px solid #ddd;">
          <img src="assets/img/ui-ux.jpg" class="card-img-top" alt="Project 2" style="height: 200px; object-fit: cover;">
          <div class="card-body">
            <h5 class="card-title">UI/UX</h5>
            <p class="card-text">Membuat ui/ux.</p>
          </div>
        </div>
      </div>

      <!-- Project 3 -->
      <div class="col-md-4 mb-4">
        <div class="card h-100" style="border: 1px solid #ddd;">
          <img src="assets/img/not.png" class="card-img-top" alt="Project 2" style="height: 200px; object-fit: cover;">
          <div class="card-body">
            <h5 class="card-title">not found</h5>
            <p class="card-text">belum ada job.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectsSection'
}
</script>

<style scoped>
.projects {
  padding: 50px 0;
  background: #e9ecef;
}
</style>
