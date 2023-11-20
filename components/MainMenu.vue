<template>
    <div>
        <div class="fixed top-0 left-o right-0 ">
            <nav class="flex justify-between items-center p-5 w-screen gradient1">
                <div class="mx-2 flex md:mx-10">            
                    <nuxt-link  to="/"><img src="../assets/icons/myicon.svg" class="h-8 mr-3"></nuxt-link>
                    <nuxt-link class="" to="/"><h2 class="text-lg">Kanon Fujita</h2></nuxt-link>
                </div>
                <div class="hidden md:flex mx-10 ">
                    <nuxt-link class="snip1217 ml-10 text-gray-900" to="/"><p>Home</p></nuxt-link>
                    <nuxt-link class="snip1217 ml-10 text-gray-900" to="/profile"><p>Profile</p></nuxt-link>
                    <nuxt-link class="snip1217 ml-10 text-gray-900" to="/project"><p>Project</p></nuxt-link>
                    <nuxt-link class="snip1217 ml-10 text-gray-900" to="/archive"><p>Archive</p></nuxt-link>
                </div> 

                <div class="flex justify-between items-center md:hidden">
                    <button @click="isOpen = !isOpen" class="relative md:hidden h-5 w-6">
                    <span :class="isOpen ? 'transform rotate-45 top-2 w-7 transition duration-300' : 'top-0 w-6'" 
                            class="h-1 inline-block transition-all absolute right-0 bg-black"></span>
                    <span :class="isOpen ? 'hidden' : 'top-2 w-6'" 
                            class="h-1 inline-block transition-all absolute right-0 bg-black"></span>
                    <span :class="isOpen ? 'transform -rotate-45 top-2 w-7 transition duration-300' : 'top-4 w-6'" 
                            class="h-1 inline-block transition-all absolute right-0 bg-black"></span>
                    </button>
                </div>
            </nav>
            <div v-if="isOpen" class="w-screen bg-gray-100 h-64 md:hidden">
                <div class="px-6">
                    <nuxt-link class="m-3 text-gray-900" to="/"><p>Home</p></nuxt-link>
                    <nuxt-link class="m-3 text-gray-900" to="/profile"><p>Profile</p></nuxt-link>
                    <nuxt-link class="m-3 text-gray-900" to="/project"><p>Project</p></nuxt-link>
                    <nuxt-link class="m-3 text-gray-900" to="/archive"><p>Archive</p></nuxt-link>
                </div>
                    
            </div>

        </div>
        
        

        <div class="w-screen h-24"></div>

        
    </div>

</template>



<script>

export default {
  data() {
    return {
      isOpen: false
    }
  }
}
</script>
