<template>
    <div class="header md:mt-20 ">
        <header class="md:mx-40 mt-2 ">
            <div class="flex justify-between  font-bold">
                <div class="md:w-1/9 ">
                    <img src="~/static/images/rone.png" class="md:visible invisible" alt="">
                </div>
                <!-- First -->
                <div class="md:w-1/9 md:-mt-3 text-center">
                    <nav>
                        <nuxt-link to='/' >ABOUT </nuxt-link>
                    </nav>
                </div>

                <div class="md:w-1/9 md:-mt-2 ml-2 ">
                    <img src="~/static/images/tone.png" class="md:visible invisible" alt="">
                </div>
                <!-- Second -->
                <div class="md:w-1/9 md:-mt-3 ml-2 text-center">
                    <nav>
                        <nuxt-link to='/'>ARTICLE </nuxt-link>
                    </nav>
                </div>
                
                <div class="md:w-1/9 md:-mt-2">
                    <img src="~/static/images/tone.png" class="md:visible invisible" alt="">
                </div>

                <!-- Third -->

                <div class="md:w-1/9 md:-mt-3  ml-2  text-center">
                    <nav>
                        <nuxt-link to='/'>BOOKS </nuxt-link>
                    </nav>
                </div>
                
                <div class="md:w-1/9 md:-mt-2">
                    <img src="~/static/images/tone.png" class="md:visible invisible" alt="">
                </div>

                <!-- Fourth -->

                <div class="md:w-1/9 md:-mt-3 text-center  ml-2 ">
                    <nav>
                        <nuxt-link to='/'>CONTACT </nuxt-link>
                    </nav>
                </div>

                <div class="md:w-1/9">
                    <img src="~/static/images/rone.png" class="md:visible invisible" alt="">
                </div>
            </div>
        </header>
    </div>
</template>