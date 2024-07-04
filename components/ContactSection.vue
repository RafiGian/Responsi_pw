<template>
  <section class="contact">
    <form @submit.prevent="handleSubmit">
      <div class="container mt-5">
        <h2 class="text-center mb-4">Contact Me</h2>
        <div class="row justify-content-center">
          <div class="col-md-6">
            <div class="form-group">
              <label for="name" style="font-weight: bold;">Name</label>
              <input
                type="text"
                class="form-control"
                id="name"
                v-model="name"
                placeholder="Enter your name"
                style="border: 1px solid #ced4da; border-radius: 0.25rem; padding: 0.375rem 0.75rem;"
              />
            </div>
            <div class="form-group">
              <label for="email" style="font-weight: bold;">Email address</label>
              <input
                type="email"
                class="form-control"
                id="email"
                v-model="email"
                placeholder="Enter your email"
                style="border: 1px solid #ced4da; border-radius: 0.25rem; padding: 0.375rem 0.75rem;"
              />
            </div>
            <div class="form-group">
              <label for="message" style="font-weight: bold;">Message</label>
              <textarea
                class="form-control"
                id="message"
                v-model="message"
                rows="4"
                placeholder="Enter your message"
                style="border: 1px solid #ced4da; border-radius: 0.25rem; padding: 0.375rem 0.75rem;"
              ></textarea>
            </div>
            <button
              type="submit"
              class="btn btn-primary"
              style="background-color: #007bff; border-color: #007bff;"
            >
              Submit
            </button>
          </div>
        </div>
      </div>
    </form>
  </section>
</template>

<script>
export default {
  data() {
    return {
      name: '',
      email: '',
      message: '',
    };
  },
  methods: {
    handleSubmit() {
      // Handle the form submission
      console.log('Name:', this.name);
      console.log('Email:', this.email);
      console.log('Message:', this.message);
      // Reset the form
      this.name = '';
      this.email = '';
      this.message = '';
    },
  },
};
</script>