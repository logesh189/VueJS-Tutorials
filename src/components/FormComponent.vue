<template>
  <div>
    <form>
      <div id="form-header">
        <slot name="form-header"></slot>
      </div>
      <div id="form-field">
        <slot name="form-fields"></slot>
      </div>
      <div id="form-links">
        <slot name="form-links"></slot>
      </div>
      <div id="form-actions">
        <slot name="form-actions"></slot>
      </div>
    </form>
  </div>
</template>

<script>
  export default {
    name: "FormComponent",
    data() {
      return {

      }
    },
  }
</script>
