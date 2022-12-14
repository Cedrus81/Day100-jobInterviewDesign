<template>
    <hero />
    <features-list />
    <stay-productive />
    <review-list />
</template>

<script>
import hero from '../components/hero.vue';
import featuresList from '../components/features.list.vue'
import stayProductive from '../components/stay-productive.vue';
import reviewList from '../components/review.list.vue';
export default {
    components:{
        hero,
        featuresList,
        stayProductive,
        reviewList,
    }
}
</script>
