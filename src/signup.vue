<script></script>
<template>
    <div class="bg-white max-w-[500px] px-10 py-4 justify-center text-black rounded-[16px]">
    <h1 class="font-inter text-center font-bold text-6xl">Sign Up</h1>
    <p class="text-sm  text-center mb-10 mt-2">Already have an account? <span class="text-decoration-line: underline text-gray-600">Login</span>
    </p>
        <div class="w-full flex gap-3 items-center justify-center">
            <div class="w-1/2 ">
                <p class="font-inter font-light">First Name</p>
                <input type="text" name="firstName" id="firstName" class="ring ring-black/30 p-2 w-full  rounded-sm">
            </div>
            <div class="w-1/2">
                <p class="font-inter font-light">Last Name</p>
                <input type="text" name="firstName" id="firstName" class="ring ring-black/30 p-2 w-full  rounded-sm">
            </div>
        </div>
        <div class="w-full mt-6">
            <p class="font-inter font-light">Email</p>
            <input type="text" class="w-full ring p-2 rounded-sm ring-black/30">
        </div>
        <div class="w-full mt-6">
            <p class="font-inter text-sm ">Username  <span class="font-light text-gray-600">(only letters, numbers and underscores)</span></p>
            <input type="text" class="w-full ring p-2 rounded-sm ring-black/30">
        </div>
        <div class="w-full mt-6">
            <p class="font-inter text-sm ">Password  <span class="font-light text-gray-600 ">(min. 8 char)</span></p>
            <input type="text" class="w-full ring p-2 rounded-sm ring-black/30">
        </div>
        <div class="w-full mt-6">
            <input type="submit" value="Join" class="bg-[#262626] w-full p-2 rounded-sm text-white">
        </div>
    </div>
</template>
