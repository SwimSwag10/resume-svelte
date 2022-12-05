<script>
  import {page} from "$app/stores";
  import logo from "$lib/assets/logo_horizontal.png";
</script>

<div class="flex p-1">
  <img src={logo} alt class="m-1 w-[256px]" draggable="false">
  <nav class="flex basis-full justify-between text-lg select-none">
    <ul class="flex ml-[100px] gap-[50px] lg:gap-[100px] items-center">
      <li><a href="/" class={$page.url.pathname === "/" ? "font-bold" : ""} draggable="false">Platform</a></li>
      <li><a href="/plans" class={$page.url.pathname === "/plans" ? "font-bold" : ""} draggable="false">Plans</a></li>
      <li><a href="/" draggable="false">Support</a></li>
    </ul>
    <ul class="flex mr-[20px] ml-[20px] gap-[50px] lg:gap-[100px] items-center">
      <li><a href="/login" draggable="false">Log In</a></li>
      <li><a href="/signup" draggable="false">Get Started</a></li>
    </ul>
  </nav>
</div>
