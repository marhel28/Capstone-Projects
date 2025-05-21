<script>

</script>
<template>
    <div class=" w-screen h-screen flex items-center justify-center bg-[#e5e5e5] text-black">
        <div class="w-1/3 max-h-96 border border-black/15 rounded-2xl bg-white">
            <h1 class="text-center font-inter font-bold font mb-8 mt-[70px] text-9xl ">LOGIN</h1>
            <form>
                <div>
                    <input type="text" name="username" id="username" placeholder="Username" class="mx-auto font-inter font-bold  bg-[#D9D9D9] placeholder-black/80 outline-0 block p-2 rounded-full  text-center w-80 mb-4">
                </div>
                <div>
                    <input type="password" name="password" id="password" placeholder="Password" class="mx-auto font-inter font-bold  bg-[#D9D9D9] placeholder-black/80 outline-0 block p-2 rounded-full  text-center w-80 mb-4">
                </div>
                <input type="submit" class="w-32 bg-[#43D1ED] rounded-full mx-auto font-inter font-bold shadow block mt-8 mb-[87px] text-xl py-1 text-white" value="Login">
            </form>
        </div>
    </div>
</template>