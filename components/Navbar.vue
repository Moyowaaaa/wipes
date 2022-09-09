<script lang="ts">
      const click = () => {
            console.log("click")
        }
        

    

</script>
<template>
    <div class=" py-4 flex items-center justify-between lg:px-20 px-4 ">
        <h2 class="font-[lato-heavy] text-[#008B16]">WIPER.NG</h2>

        <div class="hidden lg:flex gap-4 items-center font-[lato-medium]">
            <p>Home</p>
                <p>FAQ</p>
                <p>About Us</p>
                <p class="text-[#008B16]">Login</p>
                <button class="px-6 py-2  font-[gotham-bold] bg-[#008B16] text-white rounded-sm">Book now</button>
        </div>

        <img src="~/assets/images/kebab.svg" class="lg:hidden pr-6" @click="click" />

        <!-- <div class="absolute  right-0 pr-4"   @click="toggle">
                <img src="~/assets/images/kebab.svg" :class="[open ? 'hidden' : 'flex']">

                <p class="text-white text-xl " :class="[open ? 'flex' : 'hidden']">X</p>

            </div> -->


    </div>
</template>

