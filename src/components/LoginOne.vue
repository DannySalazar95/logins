<template>
  <div class="h-screen bg-red-500 text-white bg-local" style="background-image: url('/img/wallpaper.jpg')">
    <div class="absolute z-10 w-full h-full"> 
      <!--login-content-->
      <div class="flex flex-col justify-center align-middle md:w-1/3 lg:w-1/4 px-10 md:mx-auto text-center h-full">
        <div class="text-3xl font-bold py-2">Log In</div>

        <div class="text-xl pb-4">Let's get to work</div>

        <!--inputs-->
        <div class="flex flex-col">
          <div class="py-2">
            <input  class="w-full rounded-full px-3 py-2 bg-transparent border focus:outline-none focus:shadow-outline" 
                    type="email" 
                    placeholder="Email">
          </div>
          <div class="py-2">
            <input  class="w-full rounded-full px-3 py-2 bg-transparent border focus:outline-none focus:shadow-outline" 
                    type="password" 
                    placeholder="Password">
          </div>
        </div> <!--end inputs-->

        <div class="text-right font-bold text-sm py-2">
          <a href="#">FORGOT PASSWORD?</a>
        </div>

        <button class="rounded-full bg-indigo-700 w-full py-2 font-bold">LOGIN</button>

        <div class="py-3">
          <a href="#">Or create account using social media</a>
        </div>

        <button class="rounded-full bg-blue-700 py-2">Login with Facebook</button>
      </div><!--end login-content-->
    </div>
    <div class="absolute transparent-coat z-0 w-full h-full"></div>
  </div>
</template>

<script>
  export default {
    name:'LoginOne',
  }
</script>

<style>
  .transparent-coat{
    background: #2b2980bd
  }
</style>