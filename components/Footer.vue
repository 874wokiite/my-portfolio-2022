<template>
    <div>
        <div class="w-screen h-24"></div>
        <nav class="flex flex-col justify-between p-5 w-screen bg-white border-t-2 purple2 md:flex-row">
            <div class="mx-10">            
                <nuxt-link  to="/"><img src="../assets/icons/myicon.svg" class="h-8 mr-3"></nuxt-link>
                <nuxt-link class="" to="/"><h2 class="text-lg">Kanon Fujita</h2></nuxt-link>
                <h4>©2022 Kanon Fujita</h4>
            </div>
            <div class="mx-10">
                <p>E-mail: </p>
                <a class="email" href="mailto:kanon874fujita@gmail.com"><p>kanon874fujita@gmail.com</p></a>
                <div class="my-3 flex">
                    <a class="mr-3" href="https://www.instagram.com/kanonnot/"><img class="h-4" src="../assets/icons/instaicon.png" alt=""></a>
                    <a class="" href="https://twitter.com/fujita_kanon874"><img class="h-4" src="../assets/icons/twittericon.png" alt=""></a>
                </div>
            </div> 
        </nav>
    </div>

</template>