<script>
    import Logo from './Logo.vue'

    export default {
        components: {
            Logo
        }
    }
    
</script>

<template>
    <div class="w-full h-[152px] bg-gray-300 flex justify-center items-center">
        <div class="w-[90%] text-[1.125em] h-auto flex flex-col justify-center">
            <span class="text-right w-full pr-[4%]">Sign Up for our newsletter</span>
            <div class="w-full flex items-center">
                <Logo class="w-[4%] h-[16.75px]" url="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Visa_Inc._logo.svg/2560px-Visa_Inc._logo.svg.png"></Logo>
                <Logo class="w-[4%] h-[30.6px] mx-[2%]" url="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b7/MasterCard_Logo.svg/2560px-MasterCard_Logo.svg.png"></Logo>
                <Logo class="w-[6%] h-[84px]" url="https://cdn-icons-png.flaticon.com/512/196/196566.png"></Logo>
                <span class="ml-[22%] mr-[11.9%]">FAQ</span>
                <span>Join Us</span>
                <Logo class="w-[2%] h-[21px] mx-[1%]" url="https://cdn-icons-png.flaticon.com/512/5968/5968764.png"></Logo>
                <Logo class="w-[2%] h-[21px]" url="https://cdn-icons-png.flaticon.com/512/2111/2111370.png"></Logo>
                <Logo class="w-[2%] h-[21px] mx-[1%]" url="https://cdn-icons-png.flaticon.com/512/174/174855.png"></Logo>
                <Logo class="w-[2%] h-[21px]" url="https://cdn-icons-png.flaticon.com/512/5968/5968823.png"></Logo>
                <input type="text" class="w-[11.9%] h-[43px] ml-[6%] text-center" placeholder="Enter your email">
                <button class="w-[11%] h-[43px] bg-black text-white text-center">Subscribe</button>
            </div>
            <div class="w-full flex items-center opacity-50">
                <Logo class="w-[2%] h-[21px]" url="https://cdn-icons-png.flaticon.com/512/74/74717.png"></Logo>
                <Logo class="w-[0.4%] h-[5px] mx-[1%]" url="https://cdn-icons-png.flaticon.com/512/2/2013.png"></Logo>
                <span class="font-bold">Wix - All rights reserved</span>
            </div>
        </div>
    </div>
</template>