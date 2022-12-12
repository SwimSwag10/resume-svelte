<script>
  // make dynamic date to be added to footer
  let date = new Date().getFullYear();
  import github from "$lib/assets/icons/github.svg"
  import twitter from "$lib/assets/icons/twitter.svg"
  import youtube from "$lib/assets/icons/youtube.svg"
  import linkedin from "$lib/assets/icons/linkedin.svg"
  import instagram from "$lib/assets/icons/instagram.svg"
</script>

<footer class="relative bg-gray-200 pt-8 pb-6">
  <div
    class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20 h-20"
    style="transform: translateZ(0);"
  >
    <svg
      class="absolute bottom-0 overflow-hidden"
      xmlns="http://www.w3.org/2000/svg"
      preserveAspectRatio="none"
      version="1.1"
      viewBox="0 0 2560 100"
      x="0"
      y="0"
    >
      <polygon
        class="text-gray-200 fill-current"
        points="2560 0 2560 100 0 100"
      ></polygon>
    </svg>
  </div>
  <div class="container mx-auto px-4">
    <div class="flex flex-wrap text-center lg:text-left">
      <div class="w-full lg:w-6/12 px-4">
        <h4 class="text-3xl font-semibold">Let's keep in touch!</h4>
        <h5 class="text-lg mt-0 mb-2 text-gray-600">
          Find us on any of these platforms, we respond in 1-2 business days.
        </h5>
        <div class="mt-6 lg:mb-0 mb-6">
          <button
            class="bg-white text-gray-400 shadow-lg font-normal h-10 w-10 items-center justify-center align-center rounded-full outline-none focus:outline-none mr-2"
            type="button"
          >
            <img alt="..." class="max-w-full p-2" src="{twitter}"/>
          </button>
          <button
            class="bg-white text-gray-600 shadow-lg font-normal h-10 w-10 items-center justify-center align-center rounded-full outline-none focus:outline-none mr-2"
            type="button"
          >
            <img alt="..." class="max-w-full p-2" src="{instagram}"/>
          </button>
          <button
            class="bg-white text-pink-400 shadow-lg font-normal h-10 w-10 items-center justify-center align-center rounded-full outline-none focus:outline-none mr-2"
            type="button"
          >
          <img alt="..." class="max-w-full p-2" src="{youtube}"/>
          </button>
          <button
            class="bg-white text-gray-800 shadow-lg font-normal h-10 w-10 items-center justify-center align-center rounded-full outline-none focus:outline-none mr-2"
            type="button"
          >
            <img alt="..." class="max-w-full p-2" src="{linkedin}"/>
          </button>
        </div>
      </div>
      <div class="w-full lg:w-6/12 px-4">
        <div class="flex flex-wrap items-top mb-6">
          <div class="w-full lg:w-4/12 px-4 ml-auto">
            <span
              class="block uppercase text-gray-500 text-sm font-semibold mb-2"
            >
              Useful Links
            </span>
            <ul class="list-unstyled">
              <li>
                <a
                  class="text-gray-600 hover:text-gray-800 font-semibold block pb-2 text-sm"
                  href="/projects"
                >
                  Pojects
                </a>
              </li>
              <li>
                <a
                  class="text-gray-600 hover:text-gray-800 font-semibold block pb-2 text-sm"
                  href="https://github.com/SwimSwag10"
                >
                  Github
                </a>
              </li>
              <li>
                <a
                  class="text-gray-600 hover:text-gray-800 font-semibold block pb-2 text-sm"
                  href="https://thecommed.com/"
                >
                  Commed
                </a>
              </li>
            </ul>
          </div>
          <div class="w-full lg:w-4/12 px-4">
            <span
              class="block uppercase text-gray-500 text-sm font-semibold mb-2"
            >
              Other Resources
            </span>
            <ul class="list-unstyled">
              <li>
                <a
                  class="text-gray-600 hover:text-gray-800 font-semibold block pb-2 text-sm"
                  href="https://docs.google.com/document/d/1OJq3-G2zFVzoNlnV9DdeC9T0f9EmdMtY7YVctum4tKA/edit?usp=sharing"
                >
                  Resume
                </a>
              </li>
              <li>
                <a
                  class="text-gray-600 hover:text-gray-800 font-semibold block pb-2 text-sm"
                  href="https://creative-tim.com/terms?ref=ns-footer"
                >
                  Terms & Conditions
                </a>
              </li>
              <li>
                <a
                  class="text-gray-600 hover:text-gray-800 font-semibold block pb-2 text-sm"
                  href="https://creative-tim.com/contact-us?ref=ns-footer"
                >
                  Contact Us
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <hr class="my-6 border-gray-300" />
    <div class="flex flex-wrap items-center md:justify-between justify-center">
      <div class="w-full md:w-4/12 px-4 mx-auto text-center">
        <div class="text-sm text-gray-500 font-semibold py-1">
          Copyright © {date} by
          <a
            href="https://www.creative-tim.com?ref=ns-footer"
            class="text-gray-500 hover:text-gray-800"
          >
            Justin Fleagle
          </a>
          .
        </div>
      </div>
    </div>
  </div>
</footer>
