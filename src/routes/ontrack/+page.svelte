<script>
  import Nav from "$lib/components/Nav.svelte";
  import TopBar from "$lib/components/TopBar.svelte";
  import Footer from "$lib/components/Footer.svelte";
  import imgArtboard from "$lib/assets/artboard.svg";
  import imgMan from "$lib/assets/man.png";
  import imgWoman from "$lib/assets/woman.png";
  import imgComputer from "$lib/assets/computer.png";
  import imgComputer2 from "$lib/assets/computer2.png";
  import imgMap from "$lib/assets/united_states_map.png";
  import "../../app.css"
</script>

<div class="bg-[#FFC331]">
  <TopBar />
  <div class="mt-[5rem]">
    <div class="flex flex-col gap-3 h-fit ml-[7rem] lg:ml-[14rem] p-[1rem]">
      <div class="flex flex-row gap-10 lg:flex-row">
        <h2 class="text-4xl font-bold max-w-[37.5rem]">OnTrack</h2>
        <div class="flex flex-row gap-3 content-between">
          <a href="https://github.com/Schneider-Alex/OnTrack" class="relative inline-flex items-center justify-start px-6 py-3 overflow-hidden font-medium transition-all bg-gray-600 rounded-xl group">
            <span class="absolute top-0 right-0 inline-block w-4 h-4 transition-all duration-500 ease-in-out bg-gray-800 rounded group-hover:-mr-4 group-hover:-mt-4">
            <span class="absolute top-0 right-0 w-5 h-5 rotate-45 translate-x-1/2 -translate-y-1/2 bg-white"></span>
            </span>
            <span class="absolute bottom-0 left-0 w-full h-full transition-all duration-500 ease-in-out delay-200 -translate-x-full translate-y-full bg-gray-500 rounded-2xl group-hover:mb-12 group-hover:translate-x-0"></span>
            <span class="relative w-full text-left text-white transition-colors duration-200 ease-in-out group-hover:text-white">Github Repo</span>
          </a>
          <a href="https://github.com/Schneider-Alex/OnTrack" class="relative inline-flex items-center justify-start px-6 py-3 overflow-hidden font-medium transition-all bg-gray-600 rounded-xl group">
            <span class="absolute top-0 right-0 inline-block w-4 h-4 transition-all duration-500 ease-in-out bg-gray-800 rounded group-hover:-mr-4 group-hover:-mt-4">
            <span class="absolute top-0 right-0 w-5 h-5 rotate-45 translate-x-1/2 -translate-y-1/2 bg-white"></span>
            </span>
            <span class="absolute bottom-0 left-0 w-full h-full transition-all duration-500 ease-in-out delay-200 -translate-x-full translate-y-full bg-gray-500 rounded-2xl group-hover:mb-12 group-hover:translate-x-0"></span>
            <span class="relative w-full text-left text-white transition-colors duration-200 ease-in-out group-hover:text-white">Github Repo</span>
          </a>
        </div>
      </div>
      <div></div>
      <div class="flex flex-row gap-10 lg:flex-row justify-between text-3xl">
        <span>Python, Flask, MySQL, Workbench, Bootstrap, AWS EC2, and Nginx</span>
        <span>This is an application designed for highschool track coaches and their athletes. OnTrack acts as a social network where coaches can post 
          their athletes event time, and season highlights. Athletes can see their team mates times, comment and like them!</span>
      </div>
      <Footer />
    </div>
  </div>
</div>