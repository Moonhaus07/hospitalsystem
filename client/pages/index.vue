<template>
    <div class="bg-cover bg-center h-screen" style="background-image: url(../assets/landingpage.jpg);">
    <div class="justify-center text-center">

        <div class=" flex items-center justify-center h-30 mb-32">
            <img src="../assets/logo.png" alt="">
        </div>
        <h1 class="mb-32 text-4xl font-bold leading-none tracking-tight text-gray-900 md:text-5xl lg:text-6xl">
            Find the right Doctor and book an Appointment </h1>
        <p class="mb-6 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 xl:px-48 dark:text-gray-600">Need to book an appointment? Book here!</p>
        <NuxtLink to="/login"
            class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 dark:focus:ring-blue-900">
            Get Started
            <svg class="w-5 h-5 ml-2 -mr-1" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd"
                    d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                    clip-rule="evenodd"></path>
            </svg>
        </NuxtLink>

    </div>
</div>
</template>