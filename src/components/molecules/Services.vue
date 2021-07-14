<template>
    <div class="service">
        <h1 class="title">
            {{title}}
        </h1>
        <p class="descriptio">
            {{description}}
        </p>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    props:{
        title:{
            type: String,
            required: true
        },
        description:{
            type: String,
            required: true
        }
    }
})
</script>

<style lang="scss" scoped>
.service{
    .title {
    color: #935e92;
    font-weight: bold;
    margin-bottom: 0.8rem;
  }
  .description {
    color: #293947;
    line-height: 1.5;
  }
}
</style>