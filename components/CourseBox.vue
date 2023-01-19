<template>
    <!-- ::::::::::::|Featured Courses|:::::::::::: -->
    <section class="mt-20 lg:mt-[140px]">
        <h1 class="heading-tertiory text-center mb-10 md:mb-16">
            Featured Courses
        </h1>

        <!-- ::::::::::::card:::::::::::: -->
        <div class="max-w-[400px] sm:max-w-[700px] lg:max-w-7xl w-full sm:px-6 lg:px-8 mx-auto grid sm:grid-cols-2 lg:grid-cols-3 gap-5 lg:gap-10">
            <div class="bg-white rounded overflow-hidden shadow-card">
                <a href="/">
                    <img
                        srcset="https://laravel-courses.com/storage/courses/3af6d790-51f4-42cf-89db-26740e1bf353.png 2000w, https://laravel-courses.com/storage/courses/1168288b-5e18-4c67-a489-640a02a46198.png 1200w, https://laravel-courses.com/storage/courses/e8f6ef53-4023-4677-8af9-d28e27f87c4d.png 400w"
                        sizes="(max-width: 600px) 400px, (max-width: 1200px) 1200px, 2000px"
                        src="https://laravel-courses.com/storage/courses/1168288b-5e18-4c67-a489-640a02a46198.png"
                        alt="PEST Driven Laravel"
                        class="w-full h-auto object-contain"
                    />
                </a>
                <div class="px-6 pb-5">
                    <div class="mt-7 flex justify-between items-center gap-4 mb-4">
                        <a href="/" class="text-lg-primary w-full hover:underline"> Course name</a>
                    </div>

                    <div>
                        <div class="flex items-center mb-2">
                            <div class="flex items-center">
                                <img src="https://laravel-courses.com/storage/thumbnails/default/56/tp/g7t7058gcgwk00s48cwww.png?p=authors%2Fa489f89a-4866-4c10-961f-5fa6526d9709.png&amp;s=pd&amp;smartcrop=28x28" alt="Christoph Rumpel" class="w-7 h-7 object-contain flex shrink-0 rounded-full"/>
                            </div>
                            <h4 class="text-sm-primary w-full leading-5 ml-2">
                                Christoph Rumpel
                            </h4>
                        </div>

                        <div class="mt-3">
                            <div class="flex items-center gap-3">
                                <div class="flex items-center space-x-px">
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                </div>
                                <p class="text-sm-primary">0.0</p>
                            </div>
                            <div class="flex items-center gap-3 mt-6">
                                <p class="text-sm-primary bg-parrot-100 py-1.5 px-1.5 rounded-[3px] flex items-center gap-1.5 w-max">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" fill="none">
                                        <path fill="#464646" d="M7.493 0A7.08 7.08 0 0 0 .417 7.083a7.08 7.08 0 0 0 7.076 7.084 7.088 7.088 0 0 0 7.09-7.084A7.087 7.087 0 0 0 7.493 0ZM7.5 12.75a5.665 5.665 0 0 1-5.667-5.667A5.665 5.665 0 0 1 7.5 1.417a5.665 5.665 0 0 1 5.667 5.666A5.665 5.665 0 0 1 7.5 12.75Zm-.156-9.208h-.042a.508.508 0 0 0-.51.51v3.343c0 .248.127.482.347.61l2.94 1.763a.505.505 0 0 0 .763-.358.502.502 0 0 0-.247-.513l-2.74-1.63V4.053a.508.508 0 0 0-.51-.51Z"/>
                                    </svg>
                                    06 h 17 min
                                </p>
                                <p class="text-sm-primary bg-accent-100 py-1.5 px-1.5 rounded-[3px] flex items-center gap-1.5 w-max">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="15" height="13" fill="none">
                                        <path fill="#464646" d="M14.063 12.188h-3.75V0h3.75v12.188Zm-2.813-.938h1.875V.937H11.25V11.25Zm-1.875.938h-3.75V3.75h3.75v8.438Zm-2.813-.938h1.875V4.687H6.563v6.563Zm-1.875.938H.938V6.561h3.75v5.625Zm-2.812-.938H3.75V7.5H1.875v3.75Z"/>
                                    </svg>
                                    Beginner
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="bg-white rounded overflow-hidden shadow-card">
                <a href="/">
                    <img
                        srcset="https://laravel-courses.com/storage/courses/3af6d790-51f4-42cf-89db-26740e1bf353.png 2000w, https://laravel-courses.com/storage/courses/1168288b-5e18-4c67-a489-640a02a46198.png 1200w, https://laravel-courses.com/storage/courses/e8f6ef53-4023-4677-8af9-d28e27f87c4d.png 400w"
                        sizes="(max-width: 600px) 400px, (max-width: 1200px) 1200px, 2000px"
                        src="https://laravel-courses.com/storage/courses/1168288b-5e18-4c67-a489-640a02a46198.png"
                        alt="PEST Driven Laravel"
                        class="w-full h-auto object-contain"
                    />
                </a>
                <div class="px-6 pb-5">
                    <div class="mt-7 flex justify-between items-center gap-4 mb-4">
                        <a href="/" class="text-lg-primary w-full hover:underline">PEST Driven Laravel</a>
                    </div>

                    <div>
                        <div class="flex items-center mb-2">
                            <div class="flex items-center">
                                <img src="https://laravel-courses.com/storage/thumbnails/default/56/tp/g7t7058gcgwk00s48cwww.png?p=authors%2Fa489f89a-4866-4c10-961f-5fa6526d9709.png&amp;s=pd&amp;smartcrop=28x28" alt="Christoph Rumpel" class="w-7 h-7 object-contain flex shrink-0 rounded-full"/>
                            </div>
                            <h4 class="text-sm-primary w-full leading-5 ml-2">
                                Christoph Rumpel
                            </h4>
                        </div>

                        <div class="mt-3">
                            <div class="flex items-center gap-3">
                                <div class="flex items-center space-x-px">
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                </div>
                                <p class="text-sm-primary">0.0</p>
                            </div>
                            <div class="flex items-center gap-3 mt-6">
                                <p class="text-sm-primary bg-parrot-100 py-1.5 px-1.5 rounded-[3px] flex items-center gap-1.5 w-max">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" fill="none">
                                        <path fill="#464646" d="M7.493 0A7.08 7.08 0 0 0 .417 7.083a7.08 7.08 0 0 0 7.076 7.084 7.088 7.088 0 0 0 7.09-7.084A7.087 7.087 0 0 0 7.493 0ZM7.5 12.75a5.665 5.665 0 0 1-5.667-5.667A5.665 5.665 0 0 1 7.5 1.417a5.665 5.665 0 0 1 5.667 5.666A5.665 5.665 0 0 1 7.5 12.75Zm-.156-9.208h-.042a.508.508 0 0 0-.51.51v3.343c0 .248.127.482.347.61l2.94 1.763a.505.505 0 0 0 .763-.358.502.502 0 0 0-.247-.513l-2.74-1.63V4.053a.508.508 0 0 0-.51-.51Z"/>
                                    </svg>
                                    06 h 17 min
                                </p>
                                <p class="text-sm-primary bg-accent-100 py-1.5 px-1.5 rounded-[3px] flex items-center gap-1.5 w-max">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="15" height="13" fill="none">
                                        <path fill="#464646" d="M14.063 12.188h-3.75V0h3.75v12.188Zm-2.813-.938h1.875V.937H11.25V11.25Zm-1.875.938h-3.75V3.75h3.75v8.438Zm-2.813-.938h1.875V4.687H6.563v6.563Zm-1.875.938H.938V6.561h3.75v5.625Zm-2.812-.938H3.75V7.5H1.875v3.75Z"/>
                                    </svg>
                                    Beginner
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="bg-white rounded overflow-hidden shadow-card">
                <a href="/">
                    <img
                        srcset="https://laravel-courses.com/storage/courses/3af6d790-51f4-42cf-89db-26740e1bf353.png 2000w, https://laravel-courses.com/storage/courses/1168288b-5e18-4c67-a489-640a02a46198.png 1200w, https://laravel-courses.com/storage/courses/e8f6ef53-4023-4677-8af9-d28e27f87c4d.png 400w"
                        sizes="(max-width: 600px) 400px, (max-width: 1200px) 1200px, 2000px"
                        src="https://laravel-courses.com/storage/courses/1168288b-5e18-4c67-a489-640a02a46198.png"
                        alt="PEST Driven Laravel"
                        class="w-full h-auto object-contain"
                    />
                </a>
                <div class="px-6 pb-5">
                    <div class="mt-7 flex justify-between items-center gap-4 mb-4">
                        <a href="/" class="text-lg-primary w-full hover:underline">PEST Driven Laravel</a>
                    </div>

                    <div>
                        <div class="flex items-center mb-2">
                            <div class="flex items-center">
                                <img src="https://laravel-courses.com/storage/thumbnails/default/56/tp/g7t7058gcgwk00s48cwww.png?p=authors%2Fa489f89a-4866-4c10-961f-5fa6526d9709.png&amp;s=pd&amp;smartcrop=28x28" alt="Christoph Rumpel" class="w-7 h-7 object-contain flex shrink-0 rounded-full"/>
                            </div>
                            <h4 class="text-sm-primary w-full leading-5 ml-2">
                                Christoph Rumpel
                            </h4>
                        </div>

                        <div class="mt-3">
                            <div class="flex items-center gap-3">
                                <div class="flex items-center space-x-px">
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                </div>
                                <p class="text-sm-primary">0.0</p>
                            </div>
                            <div class="flex items-center gap-3 mt-6">
                                <p class="text-sm-primary bg-parrot-100 py-1.5 px-1.5 rounded-[3px] flex items-center gap-1.5 w-max">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" fill="none">
                                        <path fill="#464646" d="M7.493 0A7.08 7.08 0 0 0 .417 7.083a7.08 7.08 0 0 0 7.076 7.084 7.088 7.088 0 0 0 7.09-7.084A7.087 7.087 0 0 0 7.493 0ZM7.5 12.75a5.665 5.665 0 0 1-5.667-5.667A5.665 5.665 0 0 1 7.5 1.417a5.665 5.665 0 0 1 5.667 5.666A5.665 5.665 0 0 1 7.5 12.75Zm-.156-9.208h-.042a.508.508 0 0 0-.51.51v3.343c0 .248.127.482.347.61l2.94 1.763a.505.505 0 0 0 .763-.358.502.502 0 0 0-.247-.513l-2.74-1.63V4.053a.508.508 0 0 0-.51-.51Z"/>
                                    </svg>
                                    06 h 17 min
                                </p>
                                <p class="text-sm-primary bg-accent-100 py-1.5 px-1.5 rounded-[3px] flex items-center gap-1.5 w-max">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="15" height="13" fill="none">
                                        <path fill="#464646" d="M14.063 12.188h-3.75V0h3.75v12.188Zm-2.813-.938h1.875V.937H11.25V11.25Zm-1.875.938h-3.75V3.75h3.75v8.438Zm-2.813-.938h1.875V4.687H6.563v6.563Zm-1.875.938H.938V6.561h3.75v5.625Zm-2.812-.938H3.75V7.5H1.875v3.75Z"/>
                                    </svg>
                                    Beginner
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="bg-white rounded overflow-hidden shadow-card">
                <a href="/">
                    <img
                        srcset="https://laravel-courses.com/storage/courses/3af6d790-51f4-42cf-89db-26740e1bf353.png 2000w, https://laravel-courses.com/storage/courses/1168288b-5e18-4c67-a489-640a02a46198.png 1200w, https://laravel-courses.com/storage/courses/e8f6ef53-4023-4677-8af9-d28e27f87c4d.png 400w"
                        sizes="(max-width: 600px) 400px, (max-width: 1200px) 1200px, 2000px"
                        src="https://laravel-courses.com/storage/courses/1168288b-5e18-4c67-a489-640a02a46198.png"
                        alt="PEST Driven Laravel"
                        class="w-full h-auto object-contain"
                    />
                </a>
                <div class="px-6 pb-5">
                    <div class="mt-7 flex justify-between items-center gap-4 mb-4">
                        <a href="/" class="text-lg-primary w-full hover:underline">PEST Driven Laravel</a>
                    </div>

                    <div>
                        <div class="flex items-center mb-2">
                            <div class="flex items-center">
                                <img src="https://laravel-courses.com/storage/thumbnails/default/56/tp/g7t7058gcgwk00s48cwww.png?p=authors%2Fa489f89a-4866-4c10-961f-5fa6526d9709.png&amp;s=pd&amp;smartcrop=28x28" alt="Christoph Rumpel" class="w-7 h-7 object-contain flex shrink-0 rounded-full"/>
                            </div>
                            <h4 class="text-sm-primary w-full leading-5 ml-2">
                                Christoph Rumpel
                            </h4>
                        </div>

                        <div class="mt-3">
                            <div class="flex items-center gap-3">
                                <div class="flex items-center space-x-px">
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                </div>
                                <p class="text-sm-primary">0.0</p>
                            </div>
                            <div class="flex items-center gap-3 mt-6">
                                <p class="text-sm-primary bg-parrot-100 py-1.5 px-1.5 rounded-[3px] flex items-center gap-1.5 w-max">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" fill="none">
                                        <path fill="#464646" d="M7.493 0A7.08 7.08 0 0 0 .417 7.083a7.08 7.08 0 0 0 7.076 7.084 7.088 7.088 0 0 0 7.09-7.084A7.087 7.087 0 0 0 7.493 0ZM7.5 12.75a5.665 5.665 0 0 1-5.667-5.667A5.665 5.665 0 0 1 7.5 1.417a5.665 5.665 0 0 1 5.667 5.666A5.665 5.665 0 0 1 7.5 12.75Zm-.156-9.208h-.042a.508.508 0 0 0-.51.51v3.343c0 .248.127.482.347.61l2.94 1.763a.505.505 0 0 0 .763-.358.502.502 0 0 0-.247-.513l-2.74-1.63V4.053a.508.508 0 0 0-.51-.51Z"/>
                                    </svg>
                                    06 h 17 min
                                </p>
                                <p class="text-sm-primary bg-accent-100 py-1.5 px-1.5 rounded-[3px] flex items-center gap-1.5 w-max">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="15" height="13" fill="none">
                                        <path fill="#464646" d="M14.063 12.188h-3.75V0h3.75v12.188Zm-2.813-.938h1.875V.937H11.25V11.25Zm-1.875.938h-3.75V3.75h3.75v8.438Zm-2.813-.938h1.875V4.687H6.563v6.563Zm-1.875.938H.938V6.561h3.75v5.625Zm-2.812-.938H3.75V7.5H1.875v3.75Z"/>
                                    </svg>
                                    Beginner
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="bg-white rounded overflow-hidden shadow-card">
                <a href="/">
                    <img
                        srcset="https://laravel-courses.com/storage/courses/3af6d790-51f4-42cf-89db-26740e1bf353.png 2000w, https://laravel-courses.com/storage/courses/1168288b-5e18-4c67-a489-640a02a46198.png 1200w, https://laravel-courses.com/storage/courses/e8f6ef53-4023-4677-8af9-d28e27f87c4d.png 400w"
                        sizes="(max-width: 600px) 400px, (max-width: 1200px) 1200px, 2000px"
                        src="https://laravel-courses.com/storage/courses/1168288b-5e18-4c67-a489-640a02a46198.png"
                        alt="PEST Driven Laravel"
                        class="w-full h-auto object-contain"
                    />
                </a>
                <div class="px-6 pb-5">
                    <div class="mt-7 flex justify-between items-center gap-4 mb-4">
                        <a href="/" class="text-lg-primary w-full hover:underline">PEST Driven Laravel</a>
                    </div>

                    <div>
                        <div class="flex items-center mb-2">
                            <div class="flex items-center">
                                <img src="https://laravel-courses.com/storage/thumbnails/default/56/tp/g7t7058gcgwk00s48cwww.png?p=authors%2Fa489f89a-4866-4c10-961f-5fa6526d9709.png&amp;s=pd&amp;smartcrop=28x28" alt="Christoph Rumpel" class="w-7 h-7 object-contain flex shrink-0 rounded-full"/>
                            </div>
                            <h4 class="text-sm-primary w-full leading-5 ml-2">
                                Christoph Rumpel
                            </h4>
                        </div>

                        <div class="mt-3">
                            <div class="flex items-center gap-3">
                                <div class="flex items-center space-x-px">
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                </div>
                                <p class="text-sm-primary">0.0</p>
                            </div>
                            <div class="flex items-center gap-3 mt-6">
                                <p class="text-sm-primary bg-parrot-100 py-1.5 px-1.5 rounded-[3px] flex items-center gap-1.5 w-max">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" fill="none">
                                        <path fill="#464646" d="M7.493 0A7.08 7.08 0 0 0 .417 7.083a7.08 7.08 0 0 0 7.076 7.084 7.088 7.088 0 0 0 7.09-7.084A7.087 7.087 0 0 0 7.493 0ZM7.5 12.75a5.665 5.665 0 0 1-5.667-5.667A5.665 5.665 0 0 1 7.5 1.417a5.665 5.665 0 0 1 5.667 5.666A5.665 5.665 0 0 1 7.5 12.75Zm-.156-9.208h-.042a.508.508 0 0 0-.51.51v3.343c0 .248.127.482.347.61l2.94 1.763a.505.505 0 0 0 .763-.358.502.502 0 0 0-.247-.513l-2.74-1.63V4.053a.508.508 0 0 0-.51-.51Z"/>
                                    </svg>
                                    06 h 17 min
                                </p>
                                <p class="text-sm-primary bg-accent-100 py-1.5 px-1.5 rounded-[3px] flex items-center gap-1.5 w-max">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="15" height="13" fill="none">
                                        <path fill="#464646" d="M14.063 12.188h-3.75V0h3.75v12.188Zm-2.813-.938h1.875V.937H11.25V11.25Zm-1.875.938h-3.75V3.75h3.75v8.438Zm-2.813-.938h1.875V4.687H6.563v6.563Zm-1.875.938H.938V6.561h3.75v5.625Zm-2.812-.938H3.75V7.5H1.875v3.75Z"/>
                                    </svg>
                                    Beginner
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="bg-white rounded overflow-hidden shadow-card">
                <a href="/">
                    <img
                        srcset="https://laravel-courses.com/storage/courses/3af6d790-51f4-42cf-89db-26740e1bf353.png 2000w, https://laravel-courses.com/storage/courses/1168288b-5e18-4c67-a489-640a02a46198.png 1200w, https://laravel-courses.com/storage/courses/e8f6ef53-4023-4677-8af9-d28e27f87c4d.png 400w"
                        sizes="(max-width: 600px) 400px, (max-width: 1200px) 1200px, 2000px"
                        src="https://laravel-courses.com/storage/courses/1168288b-5e18-4c67-a489-640a02a46198.png"
                        alt="PEST Driven Laravel"
                        class="w-full h-auto object-contain"
                    />
                </a>
                <div class="px-6 pb-5">
                    <div class="mt-7 flex justify-between items-center gap-4 mb-4">
                        <a href="/" class="text-lg-primary w-full hover:underline">PEST Driven Laravel</a>
                    </div>

                    <div>
                        <div class="flex items-center mb-2">
                            <div class="flex items-center">
                                <img src="https://laravel-courses.com/storage/thumbnails/default/56/tp/g7t7058gcgwk00s48cwww.png?p=authors%2Fa489f89a-4866-4c10-961f-5fa6526d9709.png&amp;s=pd&amp;smartcrop=28x28" alt="Christoph Rumpel" class="w-7 h-7 object-contain flex shrink-0 rounded-full"/>
                            </div>
                            <h4 class="text-sm-primary w-full leading-5 ml-2">
                                Christoph Rumpel
                            </h4>
                        </div>

                        <div class="mt-3">
                            <div class="flex items-center gap-3">
                                <div class="flex items-center space-x-px">
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                    <svg class="w-4 h-4 text-gray-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                        <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z" clip-rule="evenodd" />
                                    </svg>
                                </div>
                                <p class="text-sm-primary">0.0</p>
                            </div>
                            <div class="flex items-center gap-3 mt-6">
                                <p class="text-sm-primary bg-parrot-100 py-1.5 px-1.5 rounded-[3px] flex items-center gap-1.5 w-max">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" fill="none">
                                        <path fill="#464646" d="M7.493 0A7.08 7.08 0 0 0 .417 7.083a7.08 7.08 0 0 0 7.076 7.084 7.088 7.088 0 0 0 7.09-7.084A7.087 7.087 0 0 0 7.493 0ZM7.5 12.75a5.665 5.665 0 0 1-5.667-5.667A5.665 5.665 0 0 1 7.5 1.417a5.665 5.665 0 0 1 5.667 5.666A5.665 5.665 0 0 1 7.5 12.75Zm-.156-9.208h-.042a.508.508 0 0 0-.51.51v3.343c0 .248.127.482.347.61l2.94 1.763a.505.505 0 0 0 .763-.358.502.502 0 0 0-.247-.513l-2.74-1.63V4.053a.508.508 0 0 0-.51-.51Z"/>
                                    </svg>
                                    06 h 17 min
                                </p>
                                <p class="text-sm-primary bg-accent-100 py-1.5 px-1.5 rounded-[3px] flex items-center gap-1.5 w-max">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="15" height="13" fill="none">
                                        <path fill="#464646" d="M14.063 12.188h-3.75V0h3.75v12.188Zm-2.813-.938h1.875V.937H11.25V11.25Zm-1.875.938h-3.75V3.75h3.75v8.438Zm-2.813-.938h1.875V4.687H6.563v6.563Zm-1.875.938H.938V6.561h3.75v5.625Zm-2.812-.938H3.75V7.5H1.875v3.75Z"/>
                                    </svg>
                                    Beginner
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="flex justify-center mt-12 mb-12">
        <a href="https://laravel-courses.com/courses">
                <button class="btn-primary max-w-[160px] w-full h-14 lg:w-32">
                    Browse all
                </button>
            </a>
        </div>
        {{ course }}
    </section>
</template>
<script>
export default {
    props: ['course'],
}
</script>