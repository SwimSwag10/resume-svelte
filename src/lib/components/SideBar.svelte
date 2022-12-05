<script>
  import dashboardIcon from "$lib/assets/dashboard_icon.svg";
  import tasksIcon from "$lib/assets/tasks_icon.svg";
  import listingsIcon from "$lib/assets/listings_icon.svg";
  import transactionsIcon from "$lib/assets/transactions_icon.svg";
  import contactsIcon from "$lib/assets/contacts_icon.svg";
  import templatesIcon from "$lib/assets/templates.png";
</script>

<div class="h-screen fixed text-lg flex flex-col select-none border-r bg-white z-[1]">
  <a href="/" class="flex gap-2 px-[2.5rem] py-2 hover:bg-[#ececec] font-bold bg-[#ececec]" draggable="false">
    <img src={dashboardIcon} alt draggable="false">
    <span class="hidden lg:block">Dashboard</span>
  </a>
</div>
