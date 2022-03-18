<template>
    <div class="flex bg-green-900 lg:px-52 w-full lg:justify-center lg:items-center lg:h-screen">
        <div class="bg-green-700 shadow-lg text-white lg:rounded-md">
            <div class="grid lg:grid-cols-2 grid-cols-1">
                <!-- <div>
                    <img src="../assets/images/sailorwhite.png" alt="sailor's logo">
                </div> -->
                <div>
                    <div class="lg:col-span-1 py-12 lg:px-10">
                    <h1 class="text-3xl font-bold lg:text-left text-center">Get <span class="text-green-200">insights</span> will help your business grow.</h1>

                    <h6 class="text-sm text-left text-lg lg:mr-7 pt-6 lg:text-left text-center">
                        Discover the benefits of data analytics and make better decisions regarding revenue, customers experience, and overall efficiency.
                    </h6>

                    <div class="lg:mt-12 mt-7 w-full">
                        <div class="grid lg:grid-cols-3 items-center justify-center w-full relative">
                            <div class="lg:col-span-1 leading-6">
                                <div class="flex flex-col lg:py-0 py-5">
                                    <span class="py-1 font-bold lg:text-2xl text-6xl lg:text-left lg:text-left text-center">10k+ </span>
                                    <span class="uppercase font-thin lg:text-left text-center text-sm">companies</span>
                                </div>
                            </div>

                            <div class="col-span-1">
                                <div class="flex flex-col lg:py-0 py-5">
                                    <span class="py-1 font-bold lg:text-2xl text-6xl lg:text-left text-center">314</span>
                                    <span class="uppercase font-thin lg:text-left text-center text-sm">templates</span>
                                </div>
                            </div>

                            <div class="col-span-1">
                                 <div class="flex flex-col lg:py-0 py-5">
                                    <span class="py-1 font-bold lg:text-2xl text-6xl lg:text-left text-center">12M+</span>
                                    <span class="uppercase font-thin lg:text-left text-center text-sm">queries</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                </div>

                <!-- image section -->
                <div class="lg:col-span-1 gradient-overlay lg:rounded-r-md overflow-hidden">
                    <div class="lg:rounded-r-md">
                        <img src="../assets/images/people.jpg" alt="people discussing image" class="lg:rounded-r-md h-96 relative w-full object-cover">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,200;0,300;0,400;0,600;0,700;0,800;0,900;1,200;1,300;1,400;1,600;1,700;1,800;1,900&display=swap');

    * {
        font-family: 'Nunito', sans-serif;
    }

    .gradient-overlay {
        position: relative;
    }

    .gradient-overlay::after {
        content: '';
        position: absolute;
        top:0;
        left:0;
        width: 100%;
        height: 100%;
        background-image: linear-gradient(to bottom, #047857, #047857);
        opacity: 0.6;
    } 

    img {
        filter: grayscale(1)
    }

</style>

<script>
export default {
    name: 'AboutUs',
}
</script>