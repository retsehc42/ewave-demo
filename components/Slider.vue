<template>
    <div>
        <carousel :paginationEnabled="false" :loop="true" :autoplayTimeout="2000"  :autoplay="true" :per-page="1"  :mouse-drag="true">
            <slide class="block">
                <div class="h-96 bg-red-400 flex justify-center items-center"> 
                    <span class="text-7xl text-white">1</span>
                </div>
            </slide> 
            <slide class=" hidden md:block">
                <div class="h-96 bg-blue-400 flex justify-center items-center"> 
                    <span class="text-7xl text-white">2</span>
                </div>
            </slide> 
            <slide class="hidden md:block">
                <div class="h-96 bg-yellow-400 flex justify-center items-center"> 
                    <span class="text-7xl text-white">3</span>
                </div>
            </slide> 
            <slide class="hidden lg:block">
                <div class="h-96 bg-green-400 flex justify-center items-center"> 
                    <span class="text-7xl text-white">4</span>
                </div>
            </slide> 
            <slide class="hidden lg:block">
                <div class="h-96 bg-purple-400 flex justify-center items-center"> 
                    <span class="text-7xl text-white">5</span>
                </div>
            </slide> 
        </carousel>
    </div>
</template>
 
