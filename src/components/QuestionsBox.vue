<template>
    <div class="question-box-container">
  <b-jumbotron>
    <template v-slot:lead>
      {{ currentQuestion.questions }}
    </template>

    <hr class="my-4">

    <p>
     List of answers comes here
    </p>

    <b-button variant="primary" href="#">Submit</b-button>
    <b-button variant="success" href="#">Next</b-button>
  </b-jumbotron>
</div>
</template>

<script>
export default {
  props: {
    currentQuestion: Object
  }
}
</script>