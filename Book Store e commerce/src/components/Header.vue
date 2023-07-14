
<script>
    import { RouterLink } from 'vue-router';
    import Search from './SearchBar.vue';
    import Icon from './Icon.vue';

    export default {
        components: {
            Search,
            Icon,
        }
    }
</script>

<template>
    <div class="w-full bg-gray-300 h-[93px] flex justify-center items-center">
        <div class="w-[90%] text-[1.125em] h-auto flex items-center">
            <RouterLink to="/" class="mr-[34%]">Pickle</RouterLink>
            <RouterLink to="/shop">Shop</RouterLink>
            <RouterLink to="/about" class="mx-[2%]">About Us</RouterLink>
            <RouterLink to="/contact">Contact</RouterLink>
            <Search class="mx-[2%]"></Search>
            <RouterLink to="/signup">Sign Up</RouterLink>
            <span>&nbsp;|&nbsp;</span>
            <RouterLink to="/login">Log in</RouterLink>
            <Icon class="ml-[2.1%] mr-[1%]" labelUrl="https://cdn-icons-png.flaticon.com/512/1089/1089292.png" desc="EN"></Icon>
            <Icon labelUrl="https://cdn-icons-png.flaticon.com/512/263/263142.png" desc="Cart(0)"></Icon>
        </div>
    </div>
</template>