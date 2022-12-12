<script>
  import icon_python from "$lib/assets/icons/icon_python.svg"
  import icon_django from "$lib/assets/icons/icon_django.svg"
  import icon_nodejs from "$lib/assets/icons/icon_nodejs.svg"
  import icon_nginx from "$lib/assets/icons/icon_nginx.svg"
  import angle_double_right from "$lib/assets/icons/angle_double_right.svg"
  import compass from "$lib/assets/icons/compass.svg"
</script>

<div class="w-full md:w-4/12 px-12 md:px-4 ml-auto mr-auto mt-40">
  <div class="flex flex-row gap-10 align-content-around">
    <div
      class="text-gray-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white"
    >
      <img
        alt="..."
        class=""
        src="{compass}"
      />
    </div>
    <h3 class="text-3xl mb-2 font-semibold leading-normal">
      Projects
    </h3>
  </div>
  <p class="text-lg font-light leading-relaxed mt-4 mb-4 text-gray-600">
    This is a list of projects I have completed in the past and ones that
    are currently being worked on.
  </p>
  <p class="text-lg font-light leading-relaxed mt-4 mb-4 text-gray-600">
    A couple of them are open-source projects that I started in order to 
    help the industry of healthcare. Here is my
    <a
      href="https://github.com/SwimSwag10"
      class="text-red-400 hover:text-red-800"
      target="_blank"
    >
      Github
    </a>
  </p>
</div>

<div class="w-full md:w-6/12 mr-auto ml-auto">
  <div class="justify-center flex flex-wrap relative">
    <div class="my-5 w-full lg:w-6/12 px-4">
      <a
        href="https://www.creative-tim.com/learning-lab/tailwind/svelte/alerts/notus?ref=ns-index"
        target="_blank"
      >
        <div
          class="bg-red-600 shadow-lg rounded-lg text-center p-8"
        >
          <img
            alt="..."
            class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
            src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/svelte.jpg"
          />
          <p class="text-lg text-white mt-4 font-semibold">
            Svelte
          </p>
        </div>
      </a>
      <a
        href="https://www.creative-tim.com/learning-lab/tailwind/react/alerts/notus?ref=ns-index"
        target="_blank"
      >
        <div class="bg-sky-700 shadow-lg rounded-lg text-center p-8 mt-8">
          <img
            alt="..."
            class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
            src="{icon_python}"
          />
          <p class="text-lg text-white mt-4 font-semibold">
            Python
          </p>
        </div>
      </a>
      <a
        href="https://www.creative-tim.com/learning-lab/tailwind/nextjs/alerts/notus?ref=ns-index"
        target="_blank"
      >
        <div
          class="bg-emerald-900 shadow-lg rounded-lg text-center p-8 mt-8"
        >
          <img
            alt="..."
            class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
            src="{icon_django}"
          />
          <p class="text-lg text-white mt-4 font-semibold">
            DJango
          </p>
        </div>
      </a>
    </div>
    <div class="my-4 w-full lg:w-6/12 px-4 lg:mt-16">
      <a
        href="https://www.creative-tim.com/learning-lab/tailwind/js/alerts/notus?ref=ns-index"
        target="_blank"
      >
        <div class="bg-yellow-500 shadow-lg rounded-lg text-center p-8">
          <img
            alt="..."
            class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
            src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/js.png"
          />
          <p class="text-lg text-white mt-4 font-semibold">
            JavaScript
          </p>
        </div>
      </a>
      <a
        href="https://www.creative-tim.com/learning-lab/tailwind/angular/alerts/notus?ref=ns-index"
        target="_blank"
      >
        <div class="bg-gray-900 shadow-lg rounded-lg text-center p-8 mt-8">
          <img
            alt="..."
            class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
            src="{icon_nginx}"
          />
          <p class="text-lg text-white mt-4 font-semibold">
            Nginx
          </p>
        </div>
      </a>
      <a
        href="https://www.creative-tim.com/learning-lab/tailwind/vue/alerts/notus?ref=ns-index"
        target="_blank"
      >
        <div
          class="bg-lime-500 shadow-lg rounded-lg text-center p-8 mt-8"
        >
          <img
            alt="..."
            class="shadow-md rounded-full max-w-full w-16 mx-auto p-2 bg-white"
            src="{icon_nodejs}"
          />
          <p class="text-lg text-white mt-4 font-semibold">
            Node.js
          </p>
        </div>
      </a>
    </div>
  </div>
</div>