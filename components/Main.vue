<template>

<div class="main h-screen flex flex-col justify-center pl-20">
    <div class="absolute w-5/12 flex flex-col gap-4">
        <h2 class="text-5xl font-[lato-medium]">Efficient and Affordable Cleaning service in Nigeria</h2>
        <p class="text-xl font-[lato]">We are the no 1 trusted cleaning service nationwide. We deliver and satisfy our customers with 100%  professionalism.</p>

        <button class="px-6 py-2 w-max font-[gotham-bold] bg-[#008B16] text-white">Book now</button>
    </div>
</div>
    
</template>

<style scoped>
.main {
    width:100%;
    height: 100vh;
    background-color: #E8FFE7;
    background-image:url('@/assets/images/backgroundright.svg'),url('@/assets/images/backgroundleft.svg');
    /* linear-gradient(to right,transparent,transparent); */
    background-repeat: no-repeat;
    background-position-x: right , 11vh;
    background-position-y:bottom , 10vh ;
    background-size: 60%, 200px;
}
</style>