<template>
    <div class="flex h-screen w-full bg-white">
        <!--login-col-1-->
        <div class="flex flex-col w-full md:w-1/3 lg:w-1/4 border border-r-2 justify-center align-middle md:w-1/3 px-10 md:mx-auto text-center h-full">
            <div class="text-3xl font-bold py-2 text-orange-600">Log In</div>

            <!--inputs-->
            <div class="flex flex-col">
                <div class="py-2">
                    <input  class="w-full px-3 py-2 border-b-2 focus:outline-none focus:border-orange-600" 
                            type="email" 
                            placeholder="Email">
                </div>
                <div class="py-2">
                    <input  class="w-full px-3 py-2 border-b-2 focus:outline-none focus:border-orange-600" 
                            type="password" 
                            placeholder="Password">
                </div>
            </div> <!--end inputs-->

            <div class="text-right font-bold text-sm text-orange-600 py-2">
                <a href="#">FORGOT PASSWORD?</a>
            </div>

            <button class="bg-orange-600 w-full py-2 font-bold">LOGIN</button>
        </div><!--end: login-col-1-->

        <!--login-col-2 -->
        <div class="flex flex-col hidden md:block md:w-2/3 lg:w-3/4">
            <div class="flex w-full justify-center p-10">
                <input class="border border-orange-600 px-2 text-center" placeholder="Buscar...">
            </div>
            <div class="flex flex-wrap w-full text-center h-full">
                <div class="flex w-1/3">
                    <svg class="fill-current text-orange-600 w-40 mx-auto" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path d="M339 314.9L175.4 32h161.2l163.6 282.9H339zm-137.5 23.6L120.9 480h310.5L512 338.5H201.5zM154.1 67.4L0 338.5 80.6 480 237 208.8 154.1 67.4z"/></svg>
                </div>
                <div class="flex w-1/3">
                    <svg class="fill-current text-orange-600 w-32 mx-auto" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path d="M400 64h-48V12c0-6.6-5.4-12-12-12h-40c-6.6 0-12 5.4-12 12v52H160V12c0-6.6-5.4-12-12-12h-40c-6.6 0-12 5.4-12 12v52H48C21.5 64 0 85.5 0 112v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V112c0-26.5-21.5-48-48-48zm-6 400H54c-3.3 0-6-2.7-6-6V160h352v298c0 3.3-2.7 6-6 6z"/></svg>
                </div>
                <div class="flex w-1/3">
                    <svg class="fill-current text-orange-600 w-32 mx-auto" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path d="M256 8C119 8 8 119 8 256s111 248 248 248 248-111 248-248S393 8 256 8zm57.1 350.1L224.9 294c-3.1-2.3-4.9-5.9-4.9-9.7V116c0-6.6 5.4-12 12-12h48c6.6 0 12 5.4 12 12v137.7l63.5 46.2c5.4 3.9 6.5 11.4 2.6 16.8l-28.2 38.8c-3.9 5.3-11.4 6.5-16.8 2.6z"/></svg>
                </div>
                <div class="flex w-1/3">
                    <svg class="fill-current text-orange-600 w-32 mx-auto" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path d="M256 8C119 8 8 119 8 256s111 248 248 248 248-111 248-248S393 8 256 8zm57.1 350.1L224.9 294c-3.1-2.3-4.9-5.9-4.9-9.7V116c0-6.6 5.4-12 12-12h48c6.6 0 12 5.4 12 12v137.7l63.5 46.2c5.4 3.9 6.5 11.4 2.6 16.8l-28.2 38.8c-3.9 5.3-11.4 6.5-16.8 2.6z"/></svg>
                </div>
                <div class="flex w-1/3">
                    <svg class="fill-current text-orange-600 w-40 mx-auto" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path d="M339 314.9L175.4 32h161.2l163.6 282.9H339zm-137.5 23.6L120.9 480h310.5L512 338.5H201.5zM154.1 67.4L0 338.5 80.6 480 237 208.8 154.1 67.4z"/></svg>
                </div>
                <div class="flex w-1/3">
                    <svg class="fill-current text-orange-600 w-32 mx-auto" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path d="M400 64h-48V12c0-6.6-5.4-12-12-12h-40c-6.6 0-12 5.4-12 12v52H160V12c0-6.6-5.4-12-12-12h-40c-6.6 0-12 5.4-12 12v52H48C21.5 64 0 85.5 0 112v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V112c0-26.5-21.5-48-48-48zm-6 400H54c-3.3 0-6-2.7-6-6V160h352v298c0 3.3-2.7 6-6 6z"/></svg>
                </div>
            </div>
        </div><!--end: login-col-2-->
    </div>
</template>

<script>
export default {
    name:'LoginTwo',
    data(){
        return {
            
        }
    }
}
</script>

<style>

</style>