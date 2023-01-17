<template>
    <!--::::::::::::::::: Header :::::::::::::::::::-->
    <div class="w-full  bg-gray-100  h-auto bg-no-repeat bg-cover">
        <header class="w-full h-full relative ">
            <nav x-data="{ open: false }" class=" bg-white border-b border-gray-100 shadow ">
                <!-- Primary Navigation Menu -->
                <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                    <div class="flex justify-between h-16">
                        <div class="flex">
                            <!-- Logo -->
                            <div class="shrink-0 flex items-center">
                                <a href="/">
                                    <img class="w-56 h-auto object-contain" src="https://laravel-courses.com/img/logo.png?1.0" alt="">
                                </a>
                            </div>

                            <!-- Navigation Links -->
                            <div class="hidden space-x-8 sm:-my-px sm:ml-10 sm:flex">
                                <NuxtLink to="courses"
                                    class="inline-flex items-center px-1 pt-1 border-b-2 border-transparent text-base font-medium leading-5 text-gray-500 hover:text-gray-700 hover:border-gray-300 focus:outline-none focus:text-gray-700 focus:border-gray-300 transition">
                                    Courses
                                </NuxtLink>

                                <NuxtLink to="/"
                                    class="inline-flex items-center px-1 pt-1 border-b-2 border-transparent text-base font-medium leading-5 text-gray-500 hover:text-gray-700 hover:border-gray-300 focus:outline-none focus:text-gray-700 focus:border-gray-300 transition">
                                    Books
                                </NuxtLink>
                            </div>
                        </div>

                        <div class="hidden sm:flex sm:items-center sm:ml-6">
                            <div class="flex items-center md:ml-4">
                                <a href="/" class="text-sm font-medium text-gray-500 hover:text-gray-900">Sign in</a>
                                <a href="/" class="ml-8 inline-flex items-center justify-center rounded border border-transparent bg-black px-4 py-2 text-sm font-medium text-white shadow-sm hover:bg-red-500">Sign up</a>
                            </div>
                        </div>

                        <!-- Hamburger -->
                        <div class="-mr-2 flex items-center sm:hidden">
                            <button class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:bg-gray-100 focus:text-gray-500 transition">
                                <svg class="h-6 w-6" stroke="currentColor" fill="none" viewBox="0 0 24 24">
                                    <path class="inline-flex" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                                    <path  class="hidden" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                                </svg>
                            </button>
                        </div>
                    </div>
                </div>
            </nav>

            <!-- ::::::::::::header content:::::::::::: -->
            <div class="sm:mt-20">
                <form action="/" method="GET">
                    <div class="w-full relative max-w-[740px] lg:max-w-[860px] mx-auto px-5 pb-10 lg:pb-[138px] pt-20 lg:pt-24">
                        <div class="w-full max-w-[400px] sm:max-w-full mx-auto flex flex-col items-center justify-center">
                            <h1 class="lg:max-w-[750px] text-center w-full mx-auto heading-primary mb-3">
                                The best Courses and Books on the <span class="text-orange-100">Laravel</span> ecosystem
                            </h1>

                            <p class="text-lg-secondary w-full text-center my-4 mb-10">
                                Find the right books and courses on the Laravel framework and related topics to suite your level of expertise.
                                Know how good a course is through your peers review and share your own too.
                            </p>

                            <!-- ::::::::::::search for header:::::::::::: -->
                            <div class="grid grid-cols-1 md:grid-cols-[1fr,200px] lg:flex items-center flex-col sm:flex-row gap-5 max-w-[400px] sm:max-w-[700px] md:mb-0 w-full">
                                <input type="search" name="keyword" placeholder="Enter keywords to search courses" class="md:max-w-[482px] lg:max-w-[582px] w-full bg-white h-12 border border-orange-100 rounded-lg px-3.5 outline-none" required />
                                <button type="submit" class="btn-primary w-full lg:w-[106px] h-12 shrink-0">
                                    Search
                                </button>
                            </div>
                        </div>
                    </div>
                </form>
            </div>

            <!-- ::::::::::::series logo:::::::::::: -->
            <div class="max-w-[440px] sm:max-w-[740px] lg:max-w-7xl w-full mx-auto mt-2 md:mt-0 px-4 sm:px-6 lg:px-8">
                <ul class="grid grid-cols-2 sm:grid-cols-3 lg:flex items-center flex-nowrap justify-center lg:justify-between md:gap-y-7 gap-3">
                    <li class="w-full lg:max-w-[165px]">
                        <a href="/" class="bg-white border mx-auto border-orange-100 box-shadow w-full h-12 md:h-16 rounded-lg flex items-center justify-center">
                            <img src="https://laravel-courses.com/storage/series/54e8baab-727e-4593-a78a-e0c22c569b61.png" alt="Laravel" class="w-20 md:w-auto h-auto object-contain" />
                        </a>
                    </li>
                    <li class="w-full lg:max-w-[165px]">
                        <a href="/" class="bg-white border mx-auto border-orange-100 box-shadow w-full h-12 md:h-16 rounded-lg flex items-center justify-center">
                            <img src="https://laravel-courses.com/storage/series/c9cb9b3c-4d8c-4df6-a7b7-54047ce907ad.png" alt="Laravel" class="w-20 md:w-auto h-auto object-contain" />
                        </a>
                    </li>
                    <li class="w-full lg:max-w-[165px]">
                        <a href="/" class="bg-white border mx-auto border-orange-100 box-shadow w-full h-12 md:h-16 rounded-lg flex items-center justify-center">
                            <img src="https://laravel-courses.com/storage/series/7d2e33b5-fcd0-4227-bce6-aa49b976bd7c.png" alt="Laravel" class="w-20 md:w-auto h-auto object-contain" />
                        </a>
                    </li>
                    <li class="w-full lg:max-w-[165px]">
                        <a href="/" class="bg-white border mx-auto border-orange-100 box-shadow w-full h-12 md:h-16 rounded-lg flex items-center justify-center">
                            <img src="https://laravel-courses.com/storage/series/e63d6d09-4af0-4a6d-9cee-2daf537afcc8.png" alt="Laravel" class="w-20 md:w-auto h-auto object-contain" />
                        </a>
                    </li>
                </ul>
            </div>
        </header>
    </div>

    <slot/>

    <!--::::::::::::::::: Footer :::::::::::::::::::-->
    <Footer />
</template>