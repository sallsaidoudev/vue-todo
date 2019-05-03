<template>
  <div class="home">
    <h1 class="display-2">homePage</h1>

    <v-btn class="pink white--text">click me</v-btn>

    <v-btn depressed color="pink">click me</v-btn>

    <v-btn depressed small color="pink white--text">
      <v-icon left>email</v-icon><span>Email me</span>
    </v-btn>

    <v-btn depressed large color="pink white--text">
      <v-icon left large>email</v-icon><span>Email me</span>
    </v-btn>

    <v-btn flat color="pink">click me</v-btn>

  </div>
</template>

<script>
  export default {

  }
</script>
