<template>
    <div class="feedback-stats">
        <h4>{{store.reviewsCount ? store.reviewsCount : "No" }} Reviews</h4>
        <h4>Average Rating: {{ store.averageRating == 'NaN' ? 0 : store.averageRating }}</h4>
    </div>
</template>
<script setup>
import { useReviewsStore } from '../stores/reviews';

const store = useReviewsStore();


</script>
<style scoped>
</style>