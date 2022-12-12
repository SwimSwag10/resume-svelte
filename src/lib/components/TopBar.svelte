<script>
  // import {goto} from "$app/navigation";
  // import {user} from "$lib/stores.js";
  // import {clickOutside} from '$lib/utils/clickOutside.js'
  // import apiClient from "$lib/utils/apiClient.js";
  import logo from "$lib/assets/name_logo_2.png";
  import searchIcon from "$lib/assets/search_icon.svg";
  import notificationsIcon from "$lib/assets/notifications_icon.svg";
  import settingsIcon from "$lib/assets/settings_icon.svg";
</script>

<div class="fixed w-screen flex items-center h-[5rem] top-0 z-[1] bg-white border-b">
  <a href="/"><img src={logo} alt class="m-2 w-[14.875rem]" draggable="false"></a>
  <div class="flex px-5 justify-between basis-full text-lg items-center">
    <div> </div>
    <div class="flex gap-4 items-center select-none">
      <div>Help</div>
      <img src={searchIcon} alt draggable="false">
      <img src={notificationsIcon} alt draggable="false">
      <img src={settingsIcon} alt draggable="false">
    </div>
  </div>
</div>
