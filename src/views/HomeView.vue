<script setup lang="ts"></script>

<template>
    <main
        class="h-full flex justify-center items-center container mx-auto px-4"
    >
        <div class="md:w-3/5">
            <h1 class="text-4xl font-bold">
                Hi I'm <span class="text-purple-500">Xavier</span>
            </h1>
            <p class="pt-4 font-mono">
                I'm an aspiring software engineer and I love to build things.
                I'm currently studying in SIT (Singapore Institute of
                Technology) and is currently approaching my final year.
            </p>

            <div class="grid grid-cols-2 gap-4 pt-4">
                <div class="border rounded-lg px-4 py-3">
                    <div
                        class="flex flex-col justify-center items-center h-full"
                    >
                        <h1 class="text-2xl font-bold">Projects</h1>
                        <p class="pt-2 text-center">
                            See the list of projects that I have done.
                        </p>
                    </div>
                </div>

                <div class="border rounded-lg px-4 py-3">
                    <div
                        class="flex flex-col justify-center items-center h-full"
                    >
                        <h1 class="text-2xl font-bold">Blog</h1>
                        <p class="pt-2 text-center">
                            Insights about things i learned everyday.
                        </p>
                    </div>
                </div>

                <div class="border rounded-lg px-4 py-3">
                    <div
                        class="flex flex-col justify-center items-center h-full"
                    >
                        <h1 class="text-2xl font-bold">Contact Me</h1>
                        <p class="pt-2 text-center">
                            Drop me a text
                            <a href="mailto:xavier.oyj1999@gmail.com">here</a>
                            if you have any potential collaboration to work on.
                        </p>
                    </div>
                </div>

                <div class="border rounded-lg px-4 py-3">
                    <div
                        class="flex flex-col justify-center items-center h-full"
                    >
                        <h1 class="text-2xl font-bold">About Me</h1>
                        <p class="pt-2 text-center">
                            View my resume and accolades that I have achieved.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>
