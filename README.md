# Tailwind CSS Cookie Modal

Tailwind CSS documentation: [https://tailwindcss.com/docs](https://tailwindcss.com/docs)

Background image: [Pexels](https://www.pexels.com/hu-hu/foto/tenger-termeszet-eg-strand-994605/)

![Screenshot](./images/screenshot.jpg)

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Tailwind CSS - Cookie Modal</title>
        <!-- Google Fonts -->
        <link rel="preconnect" href="https://fonts.googleapis.com" />
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet" />
        <!-- Tailwind CSS -->
        <link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet" />
        <style>
        /* Demo style */
        body {
            font-family: "Poppins", sans-serif;
            background-image: url("./images/pexels-fabian-wiktor-994605.jpg");
            background-size: cover;
            background-repeat: no-repeat;
            min-height: 100vh;
        }
        </style>
    </head>
    <body>
        <div
        class="
            bg-black bg-opacity-75
            w-full
            h-full
            p-5
            fixed
            inset-0
            z-50
            md:flex md:items-center md:justify-center
            overflow-y-auto
            select-none
        "
        >
        <div class="bg-white text-black p-5 md:p-10 rounded-md shadow-lg w-full md:max-w-xl">
            <h3 class="text-2xl md:text-4xl font-bold mb-4">Cookie settings</h3>
            <p class="text-sm mb-4">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sequi facilis rerum iste laboriosam explicabo libero
            magni corrupti atque hic!
            </p>

            <div>
            <div class="block py-3 border-t border-b border-gray-100">
                <label class="flex items-center">
                <input type="checkbox" checked disabled class="w-5 h-5" />
                <span class="text-sm ml-3">Necessary</span>
                </label>
            </div>

            <div class="block py-3 border-t border-gray-100">
                <label class="flex items-center">
                <input type="checkbox" checked name="statistic" id="statistic" class="w-5 h-5" />
                <span class="text-sm ml-3">Statistics</span>
                </label>
            </div>

            <div class="block py-3 border-t border-b border-gray-100">
                <label class="flex items-center">
                <input type="checkbox" checked name="marketing" id="marketing" class="w-5 h-5" />
                <span class="text-sm ml-3">Marketing</span>
                </label>
            </div>
            </div>
            <div class="grid md:grid-cols-2 gap-2 md:gap-4 mt-5">
            <div>
                <button type="button" class="px-4 py-2 bg-blue-600 text-white rounded-md w-full">Apply</button>
            </div>
            <div>
                <button type="button" class="px-4 py-2 bg-gray-200 text-black rounded-md w-full">Settings</button>
            </div>
            </div>

            <div class="text-sm text-center mt-5">
            <a href="#nogo" class="hover:underline hover:text-blue-600">Learn more</a>
            </div>
        </div>
        </div>

    </body>
    </html>
