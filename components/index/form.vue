<template>
    <div>
        <form class="mt-8 text-black">
            <input type="text" placeholder="Your name" class="w-full lg:p-4 p-3 mb-8 lg:text-lg rounded-lg border-blue-800 border-4 shadow-lg outline-none" required>
            <select id="countries" class="w-full lg:p-4 p-3 mb-8 lg:text-lg font-semibold rounded-lg border-blue-800 border-4 shadow-lg outline-none" required>
                <option selected disabled>Choose services</option>
                <option value="FE">Front-End Development</option>
                <option value="FS">Full Stack Development</option>
            </select>
            <textarea placeholder="Message...." rows="10" class="w-full rounded-lg mb-8 lg:p-4 p-3 lg:text-lg border-blue-800 border-4 shadow-lg outline-none" required></textarea>
            <button type="submit" class="ms-auto block md:w-1/5 w-1/3 text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg md:text-xl text-lg md:py-3 py-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">Send</button>
        </form>
    </div>
</template>