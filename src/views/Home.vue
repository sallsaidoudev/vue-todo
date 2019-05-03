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

    <v-btn fab depressed color="pink white--text">
      <v-icon>email</v-icon>
    </v-btn>

    <v-btn flat color="pink">click me</v-btn>

    <v-btn class="hidden-md-and-down">click me >= md</v-btn>  <!-- hidden-md-and-down affiche le btn si on est sur
     un ecran >= medium !-->

    <v-btn class="hidden-md-and-up">click me <= md</v-btn>  <!-- hidden-md-and-down affiche le btn si on est sur
     un ecran <= medium !-->
    <v-btn class="hidden-sm-only">click me sm</v-btn>  <!-- hidden-sm-only affiche le btn si on est sur
     un ecran smallscreen !-->

  </div>
</template>

<script>
  export default {

  }
</script>
