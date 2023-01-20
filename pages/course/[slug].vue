<template>
    <div class="w-full bg-gray-100 h-auto bg-no-repeat bg-cover">
        <header></header>
        <main>
            <section class="py-4 sm:py-6">
                <div class="max-w-7xl px-4 sm:px-6 lg:px-8 mx-auto">
                    <nav class="flex">
                        <ol role="list" class="flex items-center space-x-0.5">
                            <li>
                                <div class="-m-1">
                                    <NuxtLink to="/" 
                                        class="p-1 ml-0.5 text-base font-medium text-gray-400 rounded-md focus:outline-none focus:ring-2 focus:text-gray-900 focus:ring-gray-900 hover:text-gray-700">
                                        Home
                                    </NuxtLink>
                                </div>
                            </li>

                            <li>
                                <div class="flex items-center">
                                    <svg class="flex-shrink-0 w-5 h-5 text-gray-300" xmlns="http://www.w3.org/2000/svg"
                                        fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                                        <path d="M5.555 17.776l8-16 .894.448-8 16-.894-.448z"/>
                                    </svg>
                                <div class="-m-1">
                                    <NuxtLink to="/courses" class="p-1 ml-0.5 text-base font-medium text-gray-400 rounded-md focus:outline-none focus:ring-2 focus:text-gray-900 focus:ring-gray-900 hover:text-gray-700">
                                        Courses
                                    </NuxtLink>
                                </div>
                                </div>
                            </li>

                            <li>
                                <div class="flex items-center">
                                    <svg class="flex-shrink-0 w-5 h-5 text-gray-300" xmlns="http://www.w3.org/2000/svg"
                                        fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                                        <path d="M5.555 17.776l8-16 .894.448-8 16-.894-.448z"/>
                                    </svg>
                                                                <div class="-m-1" href="https://laravel-courses.com/series/php">
                                        <a href="https://laravel-courses.com/series/php" class="p-1 ml-0.5 text-base font-medium text-gray-400 rounded-md focus:outline-none focus:ring-2 focus:text-gray-900 focus:ring-gray-900 hover:text-gray-700">
                                            PHP
                                        </a>
                                    </div>
                                </div>
                            </li>
                        </ol>
                    </nav>

                    <div class="grid grid-cols-1 mt-12 lg:grid-cols-5 xl:grid-cols-6 lg:mt-4">
                        <div class="mt-2 pb-8 border-b border-gray-100 lg:col-span-3 xl:col-span-4 lg:border-r lg:pr-10 lg:pb-0 lg:border-b-0">

                            <div class="rounded-sm shadow-sm bg-white pb-3">
                                <img
                                srcset="https://laravel-courses.com/storage/courses/09fac06d-eb12-4828-8003-25e0e1c3bdd5.png 2000w, https://laravel-courses.com/storage/courses/c9c5fd6f-1705-410d-bb4b-66cd64a9d5ed.png 1200w"
                                sizes="(max-width: 1200px) 1200px, 2000px"
                                src="https://laravel-courses.com/storage/courses/c9c5fd6f-1705-410d-bb4b-66cd64a9d5ed.png"
                                alt="PHP For Beginners"
                                />

                                <div class="p-6 px-8">
                                    <div class="flex">
                                        <h1 class="text-3xl font-bold text-gray-900">
                                            PHP For Beginners
                                        </h1>
                                    </div>


                                    <ul class="flex flex-wrap items-center gap-4 mt-5 text-gray-700">
                                        <li class="flex items-center gap-2">
                                            <svg class="w-6 h-6 text-gray-400 shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" d="M3.375 19.5h17.25m-17.25 0a1.125 1.125 0 01-1.125-1.125M3.375 19.5h1.5C5.496 19.5 6 18.996 6 18.375m-3.75 0V5.625m0 12.75v-1.5c0-.621.504-1.125 1.125-1.125m18.375 2.625V5.625m0 12.75c0 .621-.504 1.125-1.125 1.125m1.125-1.125v-1.5c0-.621-.504-1.125-1.125-1.125m0 3.75h-1.5A1.125 1.125 0 0118 18.375M20.625 4.5H3.375m17.25 0c.621 0 1.125.504 1.125 1.125M20.625 4.5h-1.5C18.504 4.5 18 5.004 18 5.625m3.75 0v1.5c0 .621-.504 1.125-1.125 1.125M3.375 4.5c-.621 0-1.125.504-1.125 1.125M3.375 4.5h1.5C5.496 4.5 6 5.004 6 5.625m-3.75 0v1.5c0 .621.504 1.125 1.125 1.125m0 0h1.5m-1.5 0c-.621 0-1.125.504-1.125 1.125v1.5c0 .621.504 1.125 1.125 1.125m1.5-3.75C5.496 8.25 6 7.746 6 7.125v-1.5M4.875 8.25C5.496 8.25 6 8.754 6 9.375v1.5m0-5.25v5.25m0-5.25C6 5.004 6.504 4.5 7.125 4.5h9.75c.621 0 1.125.504 1.125 1.125m1.125 2.625h1.5m-1.5 0A1.125 1.125 0 0118 7.125v-1.5m1.125 2.625c-.621 0-1.125.504-1.125 1.125v1.5m2.625-2.625c.621 0 1.125.504 1.125 1.125v1.5c0 .621-.504 1.125-1.125 1.125M18 5.625v5.25M7.125 12h9.75m-9.75 0A1.125 1.125 0 016 10.875M7.125 12C6.504 12 6 12.504 6 13.125m0-2.25C6 11.496 5.496 12 4.875 12M18 10.875c0 .621-.504 1.125-1.125 1.125M18 10.875c0 .621.504 1.125 1.125 1.125m-2.25 0c.621 0 1.125.504 1.125 1.125m-12 5.25v-5.25m0 5.25c0 .621.504 1.125 1.125 1.125h9.75c.621 0 1.125-.504 1.125-1.125m-12 0v-1.5c0-.621-.504-1.125-1.125-1.125M18 18.375v-5.25m0 5.25v-1.5c0-.621.504-1.125 1.125-1.125M18 13.125v1.5c0 .621.504 1.125 1.125 1.125M18 13.125c0-.621.504-1.125 1.125-1.125M6 13.125v1.5c0 .621-.504 1.125-1.125 1.125M6 13.125C6 12.504 5.496 12 4.875 12m-1.5 0h1.5m-1.5 0c-.621 0-1.125.504-1.125 1.125v1.5c0 .621.504 1.125 1.125 1.125M19.125 12h1.5m0 0c.621 0 1.125.504 1.125 1.125v1.5c0 .621-.504 1.125-1.125 1.125m-17.25 0h1.5m14.25 0h1.5" />
                                            </svg>
                                            <span>27 videos</span>
                                        </li>


                                        <li class="flex items-center gap-2">
                                            <svg class="w-6 h-6 text-gray-400 shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z"/>
                                            </svg>
                                            <span>04 h 05 min</span>
                                        </li>

                                        <li class="flex items-center gap-2">
                                            <svg class="w-6 h-6 text-gray-400 shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 013 19.875v-6.75zM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V8.625zM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V4.125z" />
                                            </svg>
                                            <span>Beginner</span>
                                        </li>

                                        <li class="flex items-center gap-2" title="Last Updated">
                                            <svg class="w-6 h-6 text-gray-400 shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                                <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 012.25-2.25h13.5A2.25 2.25 0 0121 7.5v11.25m-18 0A2.25 2.25 0 005.25 21h13.5A2.25 2.25 0 0021 18.75m-18 0v-7.5A2.25 2.25 0 015.25 9h13.5A2.25 2.25 0 0121 11.25v7.5m-9-6h.008v.008H12v-.008zM12 15h.008v.008H12V15zm0 2.25h.008v.008H12v-.008zM9.75 15h.008v.008H9.75V15zm0 2.25h.008v.008H9.75v-.008zM7.5 15h.008v.008H7.5V15zm0 2.25h.008v.008H7.5v-.008zm6.75-4.5h.008v.008h-.008v-.008zm0 2.25h.008v.008h-.008V15zm0 2.25h.008v.008h-.008v-.008zm2.25-4.5h.008v.008H16.5v-.008zm0 2.25h.008v.008H16.5V15z" />
                                            </svg>
                                            <time>2022</time>
                                        </li>

                                        <li class="flex items-center gap-2">
                                        <svg class="w-6 h-6 text-gray-400 shrink-0" xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v12m-3-2.818l.879.659c1.171.879 3.07.879 4.242 0 1.172-.879 1.172-2.303 0-3.182C13.536 12.219 12.768 12 12 12c-.725 0-1.45-.22-2.003-.659-1.106-.879-1.106-2.303 0-3.182s2.9-.879 4.006 0l.415.33M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/>
                                        </svg>
                                        <span>FREE</span>
                                        </li>
                                    </ul>

                                    <div class="flex items-center gap-3 mt-7">
                                        <button wire:id="fEhKezKS5mW7xS7oGzv3" wire:initial-data="{&quot;fingerprint&quot;:{&quot;id&quot;:&quot;fEhKezKS5mW7xS7oGzv3&quot;,&quot;name&quot;:&quot;recommend&quot;,&quot;locale&quot;:&quot;en&quot;,&quot;path&quot;:&quot;courses\/php-for-beginners&quot;,&quot;method&quot;:&quot;GET&quot;,&quot;v&quot;:&quot;acj&quot;},&quot;effects&quot;:{&quot;listeners&quot;:[]},&quot;serverMemo&quot;:{&quot;children&quot;:[],&quot;errors&quot;:[],&quot;htmlHash&quot;:&quot;5e9ab4a9&quot;,&quot;data&quot;:{&quot;course&quot;:[],&quot;count&quot;:1,&quot;recommended&quot;:false},&quot;dataMeta&quot;:{&quot;models&quot;:{&quot;course&quot;:{&quot;class&quot;:&quot;App\\Models\\Course&quot;,&quot;id&quot;:14,&quot;relations&quot;:[&quot;series&quot;],&quot;connection&quot;:&quot;mysql&quot;,&quot;collectionClass&quot;:null}}},&quot;checksum&quot;:&quot;fc6057a60ff449aa9e0e036d04321d95bb449364d3dc1e5a832e8e8af0d16f4f&quot;}}" @click.prevent="showLoginModal = true" type="button" class="inline-flex items-center px-3 py-1.5 text-sm font-medium text-center text-white rounded focus:outline-none focus:ring-blue-300 bg-slate-600 hover:bg-slate-500">
                                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5">
                                                <path d="M1 8.25a1.25 1.25 0 112.5 0v7.5a1.25 1.25 0 11-2.5 0v-7.5zM11 3V1.7c0-.268.14-.526.395-.607A2 2 0 0114 3c0 .995-.182 1.948-.514 2.826-.204.54.166 1.174.744 1.174h2.52c1.243 0 2.261 1.01 2.146 2.247a23.864 23.864 0 01-1.341 5.974C17.153 16.323 16.072 17 14.9 17h-3.192a3 3 0 01-1.341-.317l-2.734-1.366A3 3 0 006.292 15H5V8h.963c.685 0 1.258-.483 1.612-1.068a4.011 4.011 0 012.166-1.73c.432-.143.853-.386 1.011-.814.16-.432.248-.9.248-1.388z"/>
                                            </svg>
                                            <span class="inline-flex justify-center items-center ml-2 w-4 h-4 text-xs font-semibold rounded-full text-gray-500 bg-gray-200 }}">1</span>
                                        </button>


                                        <!-- Livewire Component wire-end:fEhKezKS5mW7xS7oGzv3 -->
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

                                        <a href="#reviews" x-data @click.prevent="document.getElementById('reviews').scrollIntoView({ behavior: 'smooth', block: 'start'})" class="text-sm text-gray-500">
                                        0 Reviews
                                        </a>
                                    </div>

                                </div>
                            </div>

                            <div x-data="{ expanded : false }" class="px-6 py-6 bg-white shadow-md rounded-sm mt-6">

                                <h2 class="mb-4 text-xl font-bold text-gray-900">
                                    Overview
                                </h2>

                                <div class="text-base space-y-6 font-normal text-gray-700" :class="!expanded && 'line-clamp-20'">
                                    <p>We all start somewhere. For programming, this series is that first step. I've designed it specifically for newcomers to, not just PHP, but programming in general. Here, you'll learn the fundamentals of PHP - all the way down to defining basic variables and arrays.</p>
                                    <p>Think of this series as a key stepping stone for your programming journey.</p>

                                </div>

                                <div class="mt-6 lg:mt-4">
                                    <button x-show="!expanded" @click="expanded = true" type="button" class="inline-flex items-center rounded border border-gray-300 bg-white px-2.5 py-1.5 text-xs font-medium text-gray-700 shadow-sm hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:ring-offset-2">
                                        Read More
                                        <svg class="-mr-1 ml-1 h-5 w-5 flex-shrink-0 text-gray-400 group-hover:text-gray-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                                            <path fill-rule="evenodd" d="M5.23 7.21a.75.75 0 011.06.02L10 11.168l3.71-3.938a.75.75 0 111.08 1.04l-4.25 4.5a.75.75 0 01-1.08 0l-4.25-4.5a.75.75 0 01.02-1.06z" clip-rule="evenodd"/>
                                        </svg>
                                    </button>
                                    <button x-show="expanded" @click="expanded = false" type="button" class="inline-flex items-center rounded border border-gray-300 bg-white px-2.5 py-1.5 text-xs font-medium text-gray-700 shadow-sm hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:ring-offset-2">
                                Read Less
                                        <svg class="-mr-1 ml-1 h-5 w-5 flex-shrink-0 text-gray-400 group-hover:text-gray-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                                            <path fill-rule="evenodd" d="M14.77 12.79a.75.75 0 01-1.06-.02L10 8.832 6.29 12.77a.75.75 0 11-1.08-1.04l4.25-4.5a.75.75 0 011.08 0l4.25 4.5a.75.75 0 01-.02 1.06z" clip-rule="evenodd" />
                                        </svg>
                                    </button>
                                </div>
                            </div>

                            <h2 class="mt-4 pt-4 mb-4 text-lg font-bold text-gray-900">
                            Episodes
                            </h2>

                            <div x-data="{ showMoreButton : true}" class="px-6 py-4 bg-white shadow-md rounded-sm">
                                <ul id="episode-list" class="mt-4 space-y-4 max-h-[600px] overflow-hidden">
                                    <h3>SECTION 1 The Fundamentals</h3>
                                    <li class="bg-white border border-gray-200 divide-y divide-gray-200 rounded">
                                        <div class="px-5 py-4">
                                            <div class="flex items-start justify-between">
                                                <div class="flex items-center">
                                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                                                stroke="currentColor" class="w-4 h-4">
                                                        <path stroke-linecap="round" stroke-linejoin="round"
                                                                    d="M13.5 10.5V6.75a4.5 4.5 0 119 0v3.75M3.75 21.75h10.5a2.25 2.25 0 002.25-2.25v-6.75a2.25 2.25 0 00-2.25-2.25H3.75a2.25 2.25 0 00-2.25 2.25v6.75a2.25 2.25 0 002.25 2.25z"/>
                                                    </svg>
                                                    <div class="ml-3">
                                                        <p class="text-sm font-semibold text-gray-900">How to Choose a Programming Language
                                                            <a target="_blank" href="https://laravel-courses.com/links/49">
                                                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4 inline-block ml-1">
                                                                    <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 6H5.25A2.25 2.25 0 003 8.25v10.5A2.25 2.25 0 005.25 21h10.5A2.25 2.25 0 0018 18.75V10.5m-10.5 6L21 3m0 0h-5.25M21 3v5.25"/>
                                                                </svg>
                                                            </a>
                                                        </p>
                                                    </div>
                                                </div>
                                                <p class="text-sm font-normal text-right text-gray-500">01:21</p>
                                            </div>
                                        </div>

                                        <div class="px-5 py-4">
                                            <div class="flex items-center justify-between">
                                                <p class="text-sm font-medium text-gray-500">How exactly do you choose a first programming to learn? Why PHP, and not Ruby? And what about JavaScript or Python? How can you possibly be expected to make an educated decision at this early stage of your learning?</p>
                                            </div>
                                        </div>
                                    </li>
                                    <li class="bg-white border border-gray-200 divide-y divide-gray-200 rounded">
                                        <div class="px-5 py-4">
                                            <div class="flex items-start justify-between">
                                                <div class="flex items-center">
                                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                                        stroke="currentColor" class="w-4 h-4">
                                                        <path stroke-linecap="round" stroke-linejoin="round"
                                                            d="M13.5 10.5V6.75a4.5 4.5 0 119 0v3.75M3.75 21.75h10.5a2.25 2.25 0 002.25-2.25v-6.75a2.25 2.25 0 00-2.25-2.25H3.75a2.25 2.25 0 00-2.25 2.25v6.75a2.25 2.25 0 002.25 2.25z"/>
                                                    </svg>
                                                    <div class="ml-3">
                                                        <p class="text-sm font-semibold text-gray-900">Tools of the Trade
                                                            <a target="_blank" href="https://laravel-courses.com/links/50">
                                                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4 inline-block ml-1">
                                                                    <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 6H5.25A2.25 2.25 0 003 8.25v10.5A2.25 2.25 0 005.25 21h10.5A2.25 2.25 0 0018 18.75V10.5m-10.5 6L21 3m0 0h-5.25M21 3v5.25"/>
                                                                </svg>
                                                            </a>
                                                        </p>
                                                    </div>
                                                </div>
                                                <p class="text-sm font-normal text-right text-gray-500">08:37</p>
                                            </div>
                                        </div>

                                        <div class="px-5 py-4">
                                            <div class="flex items-center justify-between">
                                                <p class="text-sm font-medium text-gray-500">Before we can dig in, we must first create the world, so to speak. To follow along with this series, you&#039;ll need to install a handful of essential tools. Let&#039;s go over them in this episode.</p>
                                            </div>
                                        </div>
                                    </li>
                                    <li class="bg-white border border-gray-200 divide-y divide-gray-200 rounded">
                                        <div class="px-5 py-4">
                                            <div class="flex items-start justify-between">
                                                <div class="flex items-center">
                                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" class="w-4 h-4">
                                                        <path stroke-linecap="round" stroke-linejoin="round"
                                                            d="M13.5 10.5V6.75a4.5 4.5 0 119 0v3.75M3.75 21.75h10.5a2.25 2.25 0 002.25-2.25v-6.75a2.25 2.25 0 00-2.25-2.25H3.75a2.25 2.25 0 00-2.25 2.25v6.75a2.25 2.25 0 002.25 2.25z"/>
                                                    </svg>
                                                    <div class="ml-3">
                                                        <p class="text-sm font-semibold text-gray-900">Your First PHP Tag
                                                            <a target="_blank" href="https://laravel-courses.com/links/51">
                                                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4 inline-block ml-1">
                                                                    <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 6H5.25A2.25 2.25 0 003 8.25v10.5A2.25 2.25 0 005.25 21h10.5A2.25 2.25 0 0018 18.75V10.5m-10.5 6L21 3m0 0h-5.25M21 3v5.25"/>
                                                                </svg>
                                                            </a>
                                                        </p>
                                                    </div>
                                                </div>
                                                <p class="text-sm font-normal text-right text-gray-500">08:09</p>
                                            </div>
                                        </div>

                                        <div class="px-5 py-4">
                                            <div class="flex items-center justify-between">
                                                <p class="text-sm font-medium text-gray-500">Our first order of business is to prepare some basic HTML, boot a PHP server, and view it in the browser.</p>
                                            </div>
                                        </div>
                                    </li>
                                    <li class="bg-white border border-gray-200 divide-y divide-gray-200 rounded">
                                        <div class="px-5 py-4">
                                            <div class="flex items-start justify-between">
                                                <div class="flex items-center">
                                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                                                        stroke="currentColor" class="w-4 h-4">
                                                        <path stroke-linecap="round" stroke-linejoin="round"
                                                            d="M13.5 10.5V6.75a4.5 4.5 0 119 0v3.75M3.75 21.75h10.5a2.25 2.25 0 002.25-2.25v-6.75a2.25 2.25 0 00-2.25-2.25H3.75a2.25 2.25 0 00-2.25 2.25v6.75a2.25 2.25 0 002.25 2.25z"/>
                                                    </svg>
                                                    <div class="ml-3">
                                                        <p class="text-sm font-semibold text-gray-900">Variables
                                                            <a target="_blank" href="https://laravel-courses.com/links/52">
                                                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4 inline-block ml-1">
                                                                    <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 6H5.25A2.25 2.25 0 003 8.25v10.5A2.25 2.25 0 005.25 21h10.5A2.25 2.25 0 0018 18.75V10.5m-10.5 6L21 3m0 0h-5.25M21 3v5.25"/>
                                                                </svg>
                                                            </a>
                                                        </p>
                                                    </div>
                                                </div>
                                                <p class="text-sm font-normal text-right text-gray-500">07:18</p>
                                            </div>
                                        </div>

                                        <div class="px-5 py-4">
                                            <div class="flex items-center justify-between">
                                                <p class="text-sm font-medium text-gray-500">Okay, let&#039;s move on and review basic concatenation and variables. The first time I learned about variables, my first thought was, &quot;But why?&quot;. Let&#039;s talk about it!</p>
                                            </div>
                                        </div>
                                    </li>

                                </ul>


                                <button x-show="showMoreButton" @click.prevent="showEpisodes" type="button"         class="inline-flex items-center rounded border border-gray-300 bg-white px-2.5 py-1.5 text-xs font-medium text-gray-700 shadow-sm hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:ring-offset-2 mt-4 mb-2">Show All Episodes
                                </button>
                            </div>

                            <h2 id="reviews" class="mt-4 pt-4 text-lg font-bold text-gray-900">Reviews</h2>

                            <p class="mt-2 bg-white rounded-sm shadow p-6">No review yet.</p>

                        </div>

                        <div class="pt-8 lg:col-span-2 lg:pl-10 lg:pt-0">
                            <div class="mt-2 mb-4 space-y-3">
                                <a href="https://laravel-courses.com/links/443" target="_blank" class="flex items-center justify-center w-full px-4 py-3 text-base font-bold text-center text-white transition-all duration-200 bg-red-500 border-2 border-transparent rounded focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-900 hover:bg-white hover:text-black hover:border-b-2 hover:border-red-500">
                                                                    Get the Course &nbsp;
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                                        <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 6H5.25A2.25 2.25 0 003 8.25v10.5A2.25 2.25 0 005.25 21h10.5A2.25 2.25 0 0018 18.75V10.5m-10.5 6L21 3m0 0h-5.25M21 3v5.25"/>
                                    </svg>
                                </a>
                            </div>

                            <div class="mt-2 mb-7 space-y-3">
                                <button @click.prevent="showLoginModal = true" class="flex items-center justify-center w-full px-4 py-3 text-base font-bold text-center text-white transition-all duration-200 hover:bg-white hover:text-black hover:border-b-2 hover:border-black bg-gray-900 border-2 border-transparent rounded focus:outline-none">
                                        Write a Review &nbsp;
                                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" class="w-4 h-4">
                                        <path stroke-linecap="round" stroke-linejoin="round" d="M16.862 4.487l1.687-1.688a1.875 1.875 0 112.652 2.652L10.582 16.07a4.5 4.5 0 01-1.897 1.13L6 18l.8-2.685a4.5 4.5 0 011.13-1.897l8.932-8.931zm0 0L19.5 7.125M18 14v4.75A2.25 2.25 0 0115.75 21H5.25A2.25 2.25 0 013 18.75V8.25A2.25 2.25 0 015.25 6H10"/>
                                    </svg>
                                </button>
                            </div>

                            <div class="overflow-hidden bg-white border border-gray-200 rounded-sm shadow-sm">
                                <div class="space-y-4 p-6">
                                    <h3 class="text-sm font-bold tracking-widest text-gray-900 uppercase">Author</h3>
                                    <hr class="mt-5 mb-5 border-gray-200"/>
                                    <div class="space-y-4 pb-2">
                                        <div class="aspect-w-3 aspect-h-2">
                                            <img class="object-cover w-48 m-auto shadow" src="https://laravel-courses.com/storage/thumbnails/default/3w/00/uc93dx6owgksg00wkg8kk.png?p=authors%2Fd60f2e38-05f7-4608-b129-2ab901941771.png&amp;s=pd&amp;widen=200" alt="Jeffrey Way Profile Picture">
                                        </div>
                                        <div class="space-y-1 text-lg font-medium leading-6 text-center">
                                            <h4 class="font-semibold">Jeffrey Way</h4>
                                        </div>

                                        <ul role="list" class="flex space-x-5 justify-center">
                                            <li>
                                                <a href="https://twitter.com/jeffrey_way"
                                                    class="text-gray-400 hover:text-gray-500" target="_blank">
                                                    <span class="sr-only">Twitter</span>
                                                    <svg class="h-6 w-6" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                                        <path d="M19.633 7.997c.013.175.013.349.013.523 0 5.325-4.053 11.461-11.46 11.461-2.282 0-4.402-.661-6.186-1.809.324.037.636.05.973.05a8.07 8.07 0 0 0 5.001-1.721 4.036 4.036 0 0 1-3.767-2.793c.249.037.499.062.761.062.361 0 .724-.05 1.061-.137a4.027 4.027 0 0 1-3.23-3.953v-.05c.537.299 1.16.486 1.82.511a4.022 4.022 0 0 1-1.796-3.354c0-.748.199-1.434.548-2.032a11.457 11.457 0 0 0 8.306 4.215c-.062-.3-.1-.611-.1-.923a4.026 4.026 0 0 1 4.028-4.028c1.16 0 2.207.486 2.943 1.272a7.957 7.957 0 0 0 2.556-.973 4.02 4.02 0 0 1-1.771 2.22 8.073 8.073 0 0 0 2.319-.624 8.645 8.645 0 0 1-2.019 2.083z"></path>
                                                    </svg>
                                                </a>
                                            </li>

                                            <li>
                                                <a href="https://github.com/JeffreyWay" class="text-gray-400 hover:text-gray-500"
                                                    target="_blank">
                                                    <span class="sr-only">GitHub</span>
                                                    <svg class="w-6 h-6" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                                        <path
                                                                fill-rule="evenodd"
                                                                clip-rule="evenodd"
                                                                d="M12.026 2c-5.509 0-9.974 4.465-9.974 9.974 0 4.406 2.857 8.145 6.821 9.465.499.09.679-.217.679-.481 0-.237-.008-.865-.011-1.696-2.775.602-3.361-1.338-3.361-1.338-.452-1.152-1.107-1.459-1.107-1.459-.905-.619.069-.605.069-.605 1.002.07 1.527 1.028 1.527 1.028.89 1.524 2.336 1.084 2.902.829.091-.645.351-1.085.635-1.334-2.214-.251-4.542-1.107-4.542-4.93 0-1.087.389-1.979 1.024-2.675-.101-.253-.446-1.268.099-2.64 0 0 .837-.269 2.742 1.021a9.582 9.582 0 0 1 2.496-.336 9.554 9.554 0 0 1 2.496.336c1.906-1.291 2.742-1.021 2.742-1.021.545 1.372.203 2.387.099 2.64.64.696 1.024 1.587 1.024 2.675 0 3.833-2.33 4.675-4.552 4.922.355.308.675.916.675 1.846 0 1.334-.012 2.41-.012 2.737 0 .267.178.577.687.479C19.146 20.115 22 16.379 22 11.974 22 6.465 17.535 2 12.026 2z"
                                                                >
                                                        </path>
                                                    </svg>
                                                </a>
                                            </li>

                                        </ul>

                                        <div class="text-sm px-7">
                                            <p class="text-gray-500">Hi, I'm Jeffrey. I'm the creator of Laracasts and spend most of my days building the site and thinking of new ways to teach confusing concepts. I live in Orlando, Florida</p>
                                        </div>

                                    </div>
                                </div>
                            </div>

                            <div class="overflow-hidden bg-white border border-gray-200 rounded-sm mt-6 shadow-sm">
                                <div class="px-4 py-5 sm:p-6">
                                    <h3 class="text-sm font-bold tracking-widest text-gray-900 uppercase">Topics</h3>
                                    <hr class="mt-5 border-gray-200"/>

                                    <div class="mt-8 flex flex-wrap gap-2.5">
                                        <a href="https://laravel-courses.com/topics/database" class="relative inline-flex items-center rounded-full border border-gray-300 px-3 py-1.5 hover:bg-gray-100">
                                            <div class="absolute flex flex-shrink-0 items-center justify-center">
                                                <span class="h-1.5 w-1.5 rounded-full bg-rose-500" aria-hidden="true"></span>
                                            </div>
                                            <div class="ml-3.5 text-sm font-medium text-gray-900">Database</div>
                                        </a>
                                        <a href="https://laravel-courses.com/topics/request" class="relative inline-flex items-center rounded-full border border-gray-300 px-3 py-1.5 hover:bg-gray-100">
                                            <div class="absolute flex flex-shrink-0 items-center justify-center">
                                                <span class="h-1.5 w-1.5 rounded-full bg-rose-500" aria-hidden="true"></span>
                                            </div>
                                            <div class="ml-3.5 text-sm font-medium text-gray-900">Request</div>
                                        </a>
                                                                                                                                                    <a href="https://laravel-courses.com/topics/validation" class="relative inline-flex items-center rounded-full border border-gray-300 px-3 py-1.5 hover:bg-gray-100">

                                            <div class="absolute flex flex-shrink-0 items-center justify-center">
                                                <span class="h-1.5 w-1.5 rounded-full bg-rose-500" aria-hidden="true"></span>
                                            </div>
                                            <div class="ml-3.5 text-sm font-medium text-gray-900">
                                                Validation
                                            </div>
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </main>
    </div>
</template>

<script setup>
    definePageMeta({
        layout: 'syle2'
    })
    const route = useRoute();
    const course = await $fetch(`${process.env.BASE_URL}/course/${route.params.slug}`);
</script>