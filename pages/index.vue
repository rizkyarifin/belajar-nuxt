<template>

  <section class="container">
    <!-- <div>
      <logo />
      <h1 class="title">
        birmingham
      </h1>
      <h2 class="subtitle">
        Muslim Studio Landing Page
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green"
        >Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey"
        >GitHub</a>
      </div>
    </div> -->

    <div class="md:flex">
      <div class="md:flex-shrink-0">
        <img class="rounded-lg md:w-56" src="https://images.unsplash.com/photo-1556740738-b6a63e27c4df?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=448&q=80" alt="Woman paying for a purchase">
      </div>
      <div class="mt-4 md:mt-0 md:ml-6">
        <div class="uppercase tracking-wide text-sm text-indigo-600 font-bold">Marketing</div>
        <a href="#" class="block mt-1 text-lg leading-tight font-semibold text-gray-900 hover:underline">Finding customers for your new business</a>
        <p class="mt-2 text-gray-600">Getting a new business off the ground is a lot of hard work. Here are five ideas you can use to find your first customers.</p>
      </div>
      <button class="bg-blue-500 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded">
        Button
      </button>
    </div>
  </section>

</template>
<script>
export default {
  data () {
    return {
      menu: false,
      items: [
        {
          title: 'Home',
          href: '#home'
        },
        {
          title: 'About',
          href: '#about'
        },
        {
          title: 'Contact',
          href: '#contact'
        },
        {
          title: 'App',
          href: '#app'
        }
      ]
    }
  }
}
</script>
