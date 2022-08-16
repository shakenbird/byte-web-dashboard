<template>
  <div class="navbar bg-base-100 text-base-content">
    <div class="flex-none">
      <div class="dropdown">
        <label tabindex="0" class="btn btn-square btn-ghost">
      
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          class="inline-block w-5 h-5 stroke-current"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16"
          ></path>
        </svg>
        </label>
        <ul tabindex="0" class="dropdown-content menu p-2 shadow bg-neutral rounded-box w-42">
          <li><a href="/">Home</a></li>
          <li><a href="/dashboard">Dashboard</a></li>
          <li><a href="/commands">Commands</a></li>
          <li><a href="/udpates">Updates</a></li>
        </ul>
      </div>
    </div>
    <div class="flex-1">
      <a class="btn btn-ghost normal-case text-xl">Byte Dashboard</a>
    </div>
    <div class="flex-none">
      <label for="my-modal-2" class="btn btn-square btn-ghost">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          class="inline-block w-5 h-5 stroke-current"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M5 12h.01M12 12h.01M19 12h.01M6 12a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0zm7 0a1 1 0 11-2 0 1 1 0 012 0z"
          ></path>
        </svg>
      </label>
    </div>
  </div>
   <div class="alert shadow-lg absolute inset-x-0 bottom-10 container mx-auto px-4">
  <div>
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="stroke-info flex-shrink-0 w-6 h-6"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
    <span>This dashboard is currently in development. Some features may be unavailable.</span>
  </div>
</div>
  <h1 class="font-bold text-3xl container mx-auto relative inset-x-0 top-10">Byte Dashboard</h1>
  <div class="flex flex-col space-y-10 relative inset-x-0 top-20">
      <div class="card lg:card-side bg-neutral shadow-xl container mx-auto px-6">
  <div class="card-body">
    <h2 class="card-title">Dashboard</h2>
    <p>Control the bot's core features through our dashboard.</p>
    <div class="card-actions justify-end">
      <label for="my-modal" class="btn btn-primary">View</label>
    </div>
  </div>
</div>
  <div class="card lg:card-side bg-neutral shadow-xl container mx-auto px-6">
  <div class="card-body">
    <h2 class="card-title">Commands</h2>
    <p>View information about Byte/MegaByte commands & how to use them.</p>
    <div class="card-actions justify-end">
      <button class="btn btn-primary">View</button>
    </div>
  </div>
</div>
  <div class="card lg:card-side bg-neutral shadow-xl container mx-auto px-6">
  <div class="card-body">
    <h2 class="card-title">Recent Updates</h2>
    <p>Click the button below to check out the most recent Byte updates.</p>
    <div class="card-actions justify-end">
      <button class="btn btn-primary">View</button>
    </div>
  </div>
</div>
</div>
<input type="checkbox" id="my-modal" class="modal-toggle" />
<div class="modal">
  <div class="modal-box">
    <h3 class="font-bold text-lg">Dashboard Unavailable</h3>
    <p class="py-4">Our dashboard is currently in early development and is not available to the public.</p>
    <div class="modal-action">
      <label for="my-modal" class="btn">dismiss</label>
    </div>
  </div>
</div>
<input type="checkbox" id="my-modal-2" class="modal-toggle" />
<div class="modal">
  <div class="modal-box">
    <h3 class="font-bold text-lg">401 Error</h3>
    <p class="py-4">You're not authorized to view this page.</p>
    <div class="modal-action">
      <label for="my-modal-2" class="btn">Dismiss</label>
    </div>
  </div>
</div>
</template>
