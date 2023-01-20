<template>
    <!-- ::::::::::::|Featured Courses|:::::::::::: -->
    <section class="mt-20 lg:mt-[140px]">
        <h1 class="heading-tertiory text-center mb-10 md:mb-16">
            Featured Courses
        </h1>

        <!-- ::::::::::::card:::::::::::: -->
        <div class="max-w-[400px] sm:max-w-[700px] lg:max-w-7xl w-full sm:px-6 lg:px-8 mx-auto grid sm:grid-cols-2 lg:grid-cols-3 gap-5 lg:gap-10">
            <!-- :::::::::::: Feature Courses :::::::::::: -->
            <CourseBox 
                v-for="course in courses"
                :key="course.id" 
                :course="course" 
            />
        </div>

        <div class="flex justify-center mt-12 mb-12">
            <a href="https://laravel-courses.com/courses">
                <button class="btn-primary max-w-[160px] w-full h-14 lg:w-32">
                    Browse all
                </button>
            </a>
        </div>
    </section>
    
    <!-- :::::::::::: Newslatter :::::::::::: -->
    <div class="w-full bg-update bg-no-repeat bg-cover lg:h-[400px] py-10 lg:py-0">
        <div class="max-w-[440px] sm:max-w-7xl px-4 sm:px-6 lg:px-8 w-full flex flex-col lg:flex-row justify-between items-center gap-5 mx-auto h-full">
            <div class="max-w-[579px] w-full">
                <h2 class="heading-secondary">
                    Don’t miss any updates
                </h2>
                <p class="mt-3.5 text-base-primary">
                        We will be covering course reviews, comparison between the best courses, and will be sharing exclusive discounts with you on a monthly basis.
                </p>

                <div class="mt-6 md:mt-12 w-full flex flex-col sm:flex-row items-center gap-5">
                    <input wire:model="email" type="email" placeholder="Your email address" class="md:max-w-[385px] w-full h-14 bg-white border border-orange-100 rounded-lg px-3.5 text-base-primary text-[#262626] placeholder:text-current outline-none" required />
                    <button class="bg-white w-full sm:w-[135px] shrink-0 h-14 rounded-lg flex justify-center items-center border border-orange-100 text-lg-primary font-medium text-orange-100 hover:bg-orange-100 hover:text-white transition-all duration-300">
                            Subscribe
                    </button>
                </div>


            </div>

            <div class="hidden md:flex justify-center">
                <img src="https://laravel-courses.com/img/letter.png" alt="letter" class="w-auto h-auto object-contain" />
            </div>
        </div>
    </div>
</template>


<script setup>
const courses = await $fetch(`${process.env.BASE_URL}/courses/`);
</script>