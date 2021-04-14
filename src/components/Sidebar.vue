<template>
  <div>
    <div class="border-b-2 border-gray-100 pb-4">
      <h1 class="text-4xl font-bold text-pink-600">
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
    <div class="mt-6">
      <h1 class="text-lg font-semibold">Shared Files & Links</h1>
      <div class="grid grid-cols-2 gap-4 mt-4">
        <div
          class="bg-green-100 px-4 py-6 rounded-lg shadow-md text-green-500 font-semibold"
        >
          <div class="flex items-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-8"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M2 6a2 2 0 012-2h5l2 2h5a2 2 0 012 2v6a2 2 0 01-2 2H4a2 2 0 01-2-2V6z"
              />
            </svg>
            <div class="ml-3">
              <div class="text-xs">All Files</div>
              <div class="text-4xl">120</div>
            </div>
          </div>
        </div>
        <div
          class="bg-gray-100 px-4 py-6 rounded-lg text-gray-500 font-semibold"
        >
          <div class="flex items-center">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-8 text-gray-300"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M12.586 4.586a2 2 0 112.828 2.828l-3 3a2 2 0 01-2.828 0 1 1 0 00-1.414 1.414 4 4 0 005.656 0l3-3a4 4 0 00-5.656-5.656l-1.5 1.5a1 1 0 101.414 1.414l1.5-1.5zm-5 5a2 2 0 012.828 0 1 1 0 101.414-1.414 4 4 0 00-5.656 0l-3 3a4 4 0 105.656 5.656l1.5-1.5a1 1 0 10-1.414-1.414l-1.5 1.5a2 2 0 11-2.828-2.828l3-3z"
                clip-rule="evenodd"
              />
            </svg>
            <div class="ml-3">
              <div class="text-xs">All Links</div>
              <div class="text-4xl">75</div>
            </div>
          </div>
        </div>
      </div>

      <div
        class="mt-6 w-full inline-flex items-center justify-between text-gray-400"
      >
        <div class="flex items-center text-gray-600 text-base font-semibold">
          <div class="flex items-center">
            <div class="bg-green-100 p-2 rounded-lg">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-4 text-green-500"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M15 19l-7-7 7-7"
                />
              </svg>
            </div>
            <div class="mx-3 text-sm">All Files</div>
            <div class="bg-green-100 p-2 rounded-lg">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-4 text-green-500"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9 5l7 7-7 7"
                />
              </svg>
            </div>
          </div>
        </div>
        <div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-4 ml-2"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            />
          </svg>
        </div>
      </div>

      <div class="flex items-center justify-between mt-4">
        <div class="flex items-center">
          <div class="bg-yellow-100 px-4 py-3 rounded-lg">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 text-yellow-600"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M4 4a2 2 0 012-2h4.586A2 2 0 0112 2.586L15.414 6A2 2 0 0116 7.414V16a2 2 0 01-2 2H6a2 2 0 01-2-2V4z"
                clip-rule="evenodd"
              />
            </svg>
          </div>
          <div class="ml-4">
            <div class="text-sm font-semibold">Documents</div>
            <div class="mt-1 text-xs">126 files, 268 MB</div>
          </div>
        </div>
        <div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-4 text-gray-500"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9 5l7 7-7 7"
            />
          </svg>
        </div>
      </div>
      <div class="flex items-center justify-between mt-4">
        <div class="flex items-center">
          <div class="bg-blue-100 px-4 py-3 rounded-lg">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 text-blue-600"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M4 3a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V5a2 2 0 00-2-2H4zm12 12H4l4-8 3 6 2-4 3 6z"
                clip-rule="evenodd"
              />
            </svg>
          </div>
          <div class="ml-4">
            <div class="text-sm font-semibold">Images</div>
            <div class="mt-1 text-xs">2226 files, 868 MB</div>
          </div>
        </div>
        <div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-4 text-gray-500"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9 5l7 7-7 7"
            />
          </svg>
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