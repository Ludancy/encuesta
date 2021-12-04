<template>
  <div class="container">
    <h1>Question</h1>

    <!-- form -->
    <form class="row g-3">
      <div class="col-md-6">
        <label class="form-label">Name</label>
        <b-form-input v-model="name" placeholder="Enter your name"></b-form-input>
      </div>
      <div class="col-md-4">
        <label class="form-label">Select</label>
        <b-form-select v-model="selected" :options="options"></b-form-select>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: 'formQuestion',
  data(){
    return{
      name: '',
      selected: null,
      options: [1,2,3,4,5,6,7,8]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
