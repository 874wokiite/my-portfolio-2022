

<template>
  <div class="Headline">

    <video class="herocover fixed" autoplay loop muted playsinline src="https://firebasestorage.googleapis.com/v0/b/portfolio-5ca2a.appspot.com/o/homevideo2.mp4?alt=media&token=088a371f-4484-4937-b0a7-dea65a63c3b3"></video>
    <div class="h-screen w-screen fixed flex flex-col justify-center items-center  md:flex-row justify-between">
      <div class="mx-36 mt-36 flex flex-col justify-center md:mt-0">
        <div class="flex flex-col items-center">
          <img class="h-16 target md:h-48" src="../assets/icons/myicon.svg" alt="">
          <h2 class="text-white" >Kanon Fujita</h2>
          <h3 class="purple3">Experience designer</h3>
        </div>

        <div class="flex flex-col items-center  mt-6 lg:flex-row">
          <nuxt-link class="" to="/project"><button class="primary">See my project!</button></nuxt-link>
          <a href="mailto:kanon874fujita@gmail.com"><button class="email secondry m-3">E-mail</button></a>
        </div>

      </div>
      <div class="pl-20 pr-20 flex flex-col h-auto bg-transparent justify-center md:bg-gray-900 pr-36 h-screen ">
        <nuxt-link class="snip1217 " to="/profile"><h1>Profile</h1></nuxt-link>
        <nuxt-link class="snip1217 " to="/project"><h1>Project</h1></nuxt-link>
        <nuxt-link class="snip1217 " to="/archive"><h1>Archive</h1></nuxt-link>
      </div>

    </div>

 
    <h4 class="fixed left-6 bottom-3">©2022 Kanon Fujita</h4>
    
  </div>
</template>
<style scoped>
img:hover {
	opacity: 1 ;
}

</style>