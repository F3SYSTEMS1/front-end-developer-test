<template>
  <div class="hello" style="width: 500px; margin: 0 auto;">
    <h1>Fu3e Front End Developer Challenge</h1>
    <p>
      This is a standard VueJS template. For this challenge, we would like you to do the following:
    </p>
    <ol>
      <li style="text-align: left;">Use the Faker API <a href="https://fakerapi.it/en" target="_blank">here</a> to retrieve books.</li>
      <li style="text-align: left;">Use the data from the API to present the information about the books in a user friendly way.</li>
    </ol>
    <p>Here are some things to think about:</p>
    <ul>
      <li style="text-align: left;">General User Experience</li>
      <li style="text-align: left;">Appropriate Design</li>
      <li style="text-align: left;">Pagination and filtering</li>
      <li style="text-align: left;">Semantics</li>
      <li style="text-align: left;">Tests</li>
    </ul>
  </div>
</template>
<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
<style scoped>
h3 {
  margin: 40px 0 0;
}
a {
  color: #42b983;
}
</style>
