<template>
  <section class="about">
    <div class="container" style="margin-top: 50px;">
        <div class="row justify-content-center">
            <!-- Card 1 -->
            <div class="col-md-5" style="margin-bottom: 20px;">
                <div class="card" style="box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2); transition: 0.3s;">
                    <img src="assets/img/decision-making.png" alt="Profile GitHub" class="card-img-top" style="width:100%">
                    <div class="card-body text-center">
                        <h4 class="card-title" style="margin-bottom: 15px;">Profile GitHub</h4>
                        <p class="card-text" style="margin-bottom: 15px;">ini adalah profile GhitHub saya.</p>
                        <a href="https://github.com/RafiGian" class="btn btn-dark" style="margin-bottom: 5px;">GitHub</a>
                    </div>
                </div>
            </div>

            <!-- Card 2 -->
            <div class="col-md-5" style="margin-bottom: 20px;">
                <div class="card" style="box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2); transition: 0.3s;">
                    <img src="assets/img/instagram.png" alt="Instagram" class="card-img-top" style="width:100%">
                    <div class="card-body text-center">
                        <h4 class="card-title" style="margin-bottom: 15px;">Instagram</h4>
                        <p class="card-text" style="margin-bottom: 15px;">Ini adalah link instagram saya.</p> 
                        <a href="https://www.instagram.com/rafi.gian/" class="btn btn-dark" style="margin-bottom: 5px;">Instagram</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutSection'
}
</script>

<style scoped>
.about {
  padding: 20px 0;
}
.title {
  font-size: 2.5em;
  margin-bottom: 0.5em;
}
.description {
  font-size: 1.2em;
}
</style>