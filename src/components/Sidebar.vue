<template>
  <div>
    <div class="border-b-2 border-gray-100 pb-4">
      <h1 class="text-4xl font-medium text-pink-600">
        <span>Aid</span><span class="text-pink-600 font-normal">Rock</span>
      </h1>
    </div>
    <div class="mt-6">
      <div class="w-full inline-flex flex-col items-center">
        <img
          class="h-32 rounded-full"
          src="https://i.pravatar.cc/150?u=52"
          alt="avatar"
        />
        <h1 class="text-2xl font-semibold mt-3">Jon Snow</h1>
        <div
          class="items-center bg-green-100 text-green-500 rounded-lg cursor-pointer hover:shadow-sm flex px-3 py-1 mt-3"
        >
          <div class="text-sm">Online</div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-4 ml-1"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M19 9l-7 7-7-7"
            />
          </svg>
        </div>
      </div>
    </div>
    <div class="mt-6">
      <div>
        <div class="relative flex w-full">
          <span
            class="z-10 h-full absolute bg-transparent rounded text-base items-center justify-center pl-3 py-4"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-4 text-gray-400"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="1"
                d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
              />
            </svg>
          </span>
          <input
            type="text"
            placeholder="Search"
            class="px-3 py-3 relative bg-gray-100 rounded-lg placeholder-gray-300 focus:outline-none w-full pl-10"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Sidebar",
};
</script>

<style>
</style>