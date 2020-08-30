<template>
    <div class=" ">
       <div class="md:mt-12 mx-2 mt-4">
           <h1 class='cssanimation leRotateSkateInRight sequence infinite uppercase text-center font-black md:text-6xl'>hello</h1>
           <h2 class="text-center  font-medium mt-8 md:text-4xl text-3xl">My name is <span class="font-bold">Tunji Oyewole</span></h2>
           <p class="text-center md:text-xl">A Dad, Author, Teacher and Preacher of the Word</p>
       </div>
    <!-- ABOUT -->
        <About/>
    <!-- BOOKs -->
        <Books/>
    <!-- Contacts -->
        <Contacts/>
    <!-- Footer -->
        <div class="footer mt-16 md:mx-40 mb-4">
            <hr class="border-gray-400 border-2">
            <div class="md:flex justify-between">
                <div class="">
                    <p class="text-xl"> &copy; {{name}} Tunjioyewole {{datei}}. All Rights Reserved. </p>
                </div>
                <div class="">
                    <p class="text-xl">Developed by <a href="https://iamdyt.tk">@iamdyt</a></p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

export default {
    data(){
        return{
            datei: new Date().getFullYear(),
        }
    },

    

    mounted(){
        sal()
        
    },
    
    
    
}
</script>