<template>
    <nav class="nav-bar">
        <NavItem text="Serviços" to="/"/>
        <NavItem text="Sobre min" to="/about"/>
        <NavItem text="Cases" to="/cases"/>
        <NavItem text="Contatos" to="/contact"/>
    </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import {NavItem} from '@/components/atoms'

export default defineComponent({
    components:{
        NavItem
    }
})
</script>

<style lang="scss" scoped>
.nav-bar{
    width: max-content;
    display: grid;
    grid-auto-flow: column;
    grid-gap: 2rem;
}
</style>