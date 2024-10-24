<template>
<div>
     <Nuvbar></Nuvbar>
</div>
    <div class="container mx-auto p-5">
        <h1 class="text-3xl font-bold mb-5">Contact Us</h1>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-10">
            <!-- Contact Form -->
            <div class="bg-white p-6 rounded-lg shadow">
                <h2 class="text-2xl font-semibold mb-4">Get in Touch</h2>
                <form>
                    <div class="mb-4">
                        <label class="block text-gray-700" for="name">Name</label>
                        <input type="text" id="name" class="mt-1 p-2 border border-gray-300 rounded w-full" placeholder="Your Name" required>
                    </div>
                    <div class="mb-4">
                        <label class="block text-gray-700" for="email">Email</label>
                        <input type="email" id="email" class="mt-1 p-2 border border-gray-300 rounded w-full" placeholder="Your Email" required>
                    </div>
                    <div class="mb-4">
                        <label class="block text-gray-700" for="message">Message</label>
                        <textarea id="message" class="mt-1 p-2 border border-gray-300 rounded w-full" rows="4" placeholder="Your Message" required></textarea>
                    </div>
                    <button type="submit" class="bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-600">Send Message</button>
                </form>
            </div>

            <!-- Map -->
            <div class="bg-white rounded-lg shadow">
                <h2 class="text-2xl font-semibold p-6">Our Location</h2>
                <div class="h-64">
                   <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d422.78866667168495!2d103.18755987880586!3d13.011035246918942!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e1!3m2!1sen!2skh!4v1729322283568!5m2!1sen!2skh" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">
import Nuvbar from '@/layout/Nuvbar.vue';
</script>

<style>
/* Optional: Add custom styles here if needed */
</style>
