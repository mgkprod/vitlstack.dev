<template>
  <Head>
    <title>VITL Stack - The vital stack for your Laravel apps</title>
    <meta name="description" content="The VITL stack is made up of Vue.js, Inertia.js, Tailwind CSS and Laravel and is a great tech stack for building your Laravel apps." />
  </Head>

  <div class="min-h-screen px-6 py-10 mx-auto md:w-5/6 md:px-0">
    <h1 class="text-4xl font-bold text-center">
      The VITL stack is the vital stack for your Laravel apps
    </h1>
    <div class="mt-5 text-center">
      <p class="text-gray-800">Vue.js, Inertia.js, Tailwind and Laravel.</p>
    </div>

    <div class="mt-8 text-left">
      <div>
        <p class="text-xl font-semibold text-center text-gray-800">
          The stack for making full-stack applications with the power of modern tech.
        </p>
      </div>
      <div class="my-8 text-gray-900 rounded bg-vue-opacity vue-shadow">
        <a href="https://vuejs.org/" class="block p-4">
          <span class="font-bold">Vue.js</span> - Build all your pages with the popular and magical Vue.js.
        </a>
      </div>
      <div class="my-8 text-gray-900 rounded bg-inertia-opacity inertia-shadow">
        <a href="https://inertiajs.com/" class="block p-4">
          <span class="font-bold">Inertia.js</span> - Make the front-end an SPA without building an API with Inertia.js and create the modern monolith.
        </a>
      </div>
      <div class="my-8 text-gray-900 rounded bg-tailwind-opacity tailwind-shadow">
        <a href="https://tailwindcss.com" class="block p-4">
          <span class="font-bold">Tailwind CSS</span> - Style with the powerful and productive Tailwind, you won't believe how easy it is.
        </a>
      </div>
      <div class="my-8 text-gray-900 rounded bg-laravel-opacity laravel-shadow">
        <a href="https://laravel.com/" class="block p-4">
          <span class="font-bold">Laravel</span> - Handle the logic with mature and powerful Laravel, which handles most of the complex stuff for you and become an Artisan.
        </a>
      </div>
    </div>
    <div class="pt-8 text-center">
      <p class="text-gray-700">
        Built and maintained by
        <a href="https://mgk.dev" class="text-blue-500 underline">Simon Rubuano</a> |
        <a href="https://github.com/mgkprod/vitlstack.dev" class="text-blue-500 underline">Open source on GitHub</a>
      </p>
      <p class="text-sm text-gray-700">
        Original website by <a href="https://twitter.com/SamNewby_" class="text-blue-500 underline">Sam Newby</a>.
      </p>
    </div>
  </div>
</template>

<script>
import { Head } from '@inertiajs/vue3'

export default {
  components: {
    Head,
  },
}
</script>

<style scoped>
.bg-laravel-opacity {
    background-color: rgba(255, 45, 32, 0.35);
}
.bg-vue-opacity {
    background-color: rgba(66, 184, 131, 0.35);
}
.bg-tailwind-opacity {
    background-color: rgba(56, 178, 172, 0.35);
}
.bg-inertia-opacity {
    background-color: rgba(183, 148, 244, 0.35);
}
.vue-shadow {
    -webkit-box-shadow: 8px 8px 0px 0px rgba(66, 184, 131, 1);
    -moz-box-shadow: 8px 8px 0px 0px rgba(66, 184, 131, 1);
    box-shadow: 8px 8px 0px 0px rgba(66, 184, 131, 1);
}
.inertia-shadow {
    -webkit-box-shadow: 8px 8px 0px 0px rgba(183, 148, 244, 1);
    -moz-box-shadow: 8px 8px 0px 0px rgba(183, 148, 244, 1);
    box-shadow: 8px 8px 0px 0px rgba(183, 148, 244, 1);
}
.tailwind-shadow {
    -webkit-box-shadow: 8px 8px 0px 0px rgba(56, 178, 172, 1);
    -moz-box-shadow: 8px 8px 0px 0px rgba(56, 178, 172, 1);
    box-shadow: 8px 8px 0px 0px rgba(56, 178, 172, 1);
}
.laravel-shadow {
    -webkit-box-shadow: 8px 8px 0px 0px rgba(255, 45, 32, 1);
    -moz-box-shadow: 8px 8px 0px 0px rgba(255, 45, 32, 1);
    box-shadow: 8px 8px 0px 0px rgba(255, 45, 32, 1);
}
</style>
