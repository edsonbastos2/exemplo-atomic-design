<template>
    <div class="service-container">
        <Services title="Front-end" description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsum magni, expedita quaerat tenetur nobis explicabo, quis praesentium itaque veritatis ad, nisi neque nihil numquam nam inventore sint officia atque earum animi ut fuga! Dolores perferendis dicta vitae quaerat ipsum, iure eveniet dolorum architecto. Qui placeat nesciunt mollitia blanditiis rem molestiae?"/>

        <Services title="Back-end" description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsum magni, expedita quaerat tenetur nobis explicabo, quis praesentium itaque veritatis ad, nisi neque nihil numquam nam inventore sint officia atque earum animi ut fuga! Dolores perferendis dicta vitae quaerat ipsum, iure eveniet dolorum architecto. Qui placeat nesciunt mollitia blanditiis rem molestiae?"/>

        <Services title="Manutenção" description="Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsum magni, expedita quaerat tenetur nobis explicabo, quis praesentium itaque veritatis ad, nisi neque nihil numquam nam inventore sint officia atque earum animi ut fuga! Dolores perferendis dicta vitae quaerat ipsum, iure eveniet dolorum architecto. Qui placeat nesciunt mollitia blanditiis rem molestiae?"/>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import {Services} from '@/components/molecules'

export default defineComponent({
    components:{
        Services
    }
})
</script>

<style lang="scss" scoped>
.service-container{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 5rem;
}
</style>