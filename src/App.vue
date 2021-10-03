<template>
  <div id="app">
    <FormComponent>
      <div slot="form-header">
        <h2>
          Signup Form
        </h2>
        <p>
          Please fill out the form
        </p>
      </div>
      <div slot="form-fields">
        <input type="text" class="form-input" placeholder="First name" />
        <input type="text" class="form-input" placeholder="Last name" />
        <input type="text" class="form-input" placeholder="Mail Id" />
        <input type="Password" class="form-input" placeholder="Password" />
      </div>
      <div slot="form-actions">
        <button class="btn btn-success">
          SUBMIT
        </button>
      </div>
      <div slot="form-links">
        <ul>
          <li><a href="#">Sign in,  </a></li>
          <li><a href="#">Forgot Password</a></li>
        </ul>
      </div>
    </FormComponent>
  </div>
</template>

<script>
import FormComponent from "./components/FormComponent";

export default {
  name: "App",
  components: {
    FormComponent
  }
};
</script>

<style>
</style>
