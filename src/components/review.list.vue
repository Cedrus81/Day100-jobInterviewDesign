<template>
    <section class="review-list flex wrap">
        <article class="review-preview" v-for="review in reviews">

        </article>
    </section>
</template>

<script>
export default{
    data(){
        return{
            reviews : [ {},2,3]
        }
    }
}
</script>