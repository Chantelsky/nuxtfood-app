<template>
    <nav>
        <ul>
            <li><nuxt-link exact to="/"><span class="iconify" data-inline="false" data-icon="fluent:food-20-filled" style="color: #fff; font-size: 40px"></span></nuxt-link></li>
            <li><nuxt-link exact to="/restaurants">Restaurants</nuxt-link></li>
        </ul>
        <nuxt-link to="/cart">Cart</nuxt-link>
    </nav>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
</style>
