<script>
  import Nav from "$lib/components/Nav.svelte";
  import Button from "$lib/components/Button.svelte";
  import TopBar from "$lib/components/TopBar.svelte";
  import SideBar from "$lib/components/SideBar.svelte";
  import Footer from "$lib/components/Footer.svelte";
  import imgArtboard from "$lib/assets/artboard.svg";
  import imgMan from "$lib/assets/man.png";
  import imgWoman from "$lib/assets/woman.png";
  import imgComputer from "$lib/assets/computer.png";
  import imgComputer2 from "$lib/assets/computer2.png";
  import imgMap from "$lib/assets/united_states_map.png";
  import "../app.css"
</script>

<TopBar />
<div class="mt-[5rem]">
  <SideBar />
  <div class="flex flex-col gap-3 h-fit ml-[7rem] lg:ml-[14rem] p-[1rem]">
    <div class="flex flex-col gap-3 lg:flex-row justify-between">
      <h2 class="text-2xl font-bold">Dashboard</h2>
      <div class="flex gap-4">
        <button class="border border-black bg-white rounded-full w-[12.5rem] py-[2px] text-center">Add New Contact</button>
      </div>
    </div>
    <Footer />
  </div>
</div>