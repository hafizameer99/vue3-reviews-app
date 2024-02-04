<template>
  <div class="home">
    <div class="container">
      <!-- Reviews Form -->
      <ReviewsForm />
      <!-- Reviews Stats -->
      <ReviewsStats />
      <!-- Reviews List -->
      <ReviewList />
    </div>
  </div>
</template>
<script setup>
  import ReviewsForm from '../components/ReviewsForm.vue'; 
  import ReviewsStats from '../components/ReviewStats.vue';
  import ReviewList from '../components/ReviewsList.vue';
</script>