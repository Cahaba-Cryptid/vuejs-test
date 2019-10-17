<template>
  <div class="question-box-container">
    <b-jumbotron>

      <template v-slot:lead>
        Questions go here.
      </template>

      <hr class="my-4" />

      <p>
        Answer list goes here.
      </p>

      <b-button variant="primary" href="#">Submit!</b-button>
      <b-button variant="success" href="#">Next</b-button>
    </b-jumbotron>
  </div>
</template>