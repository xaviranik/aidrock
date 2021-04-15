<template>
  <div class="h-full relative">
    <div
      class="absolute z-20 top-0 left-0 w-full rounded-lg bg-white bg-opacity-90 backdrop-filter backdrop-blur-sm border-2 border-gray-100 py-4 px-4"
    >
      <div class="flex items-center justify-between text-sm font-medium">
        <div class="flex items-center ml-2">
          <div class="font-semibold text-xl">Ticket #12542</div>
          <div
            class="inline text-xs px-2 py-1 ml-4 rounded-md text-white bg-green-500"
          >
            Open
          </div>
        </div>
        <div class="flex items-center text-sm">
          <div class="bg-green-100 text-green-600 px-4 py-2 rounded-lg shadow">
            Messages
          </div>
          <div class="rounded-lg ml-4 px-4 py-2">Participants</div>
        </div>
      </div>
    </div>
    <div class="h-full rounded-lg px-6 overflow-y-auto pt-24">
      <div>
        <div class="text-sm flex mt-2">
          <img class="h-10 rounded-full" src="https://i.pravatar.cc/150?u=23" />
          <div
            class="relative bg-white shadow-sm rounded-lg p-4 speech-bubble left ml-4"
          >
            <p class="font-medium">
              Marks Richard
              <span class="text-xs text-gray-300 ml-1 font-light"
                >2 minutes ago</span
              >
            </p>
            <blockquote class="text-sm mt-2">
              Hello there, would you please help with the new order status?
            </blockquote>
          </div>
        </div>
        <div class="text-sm flex mt-2">
          <img class="h-10 rounded-full" src="https://i.pravatar.cc/150?u=23" />
          <div
            class="relative bg-white shadow-sm rounded-lg p-4 speech-bubble left ml-4"
          >
            <p class="font-medium">
              Marks Richard
              <span class="text-xs text-gray-300 ml-1 font-light"
                >2 minutes ago</span
              >
            </p>
            <blockquote class="text-sm mt-2">
              I can't figure that out.
            </blockquote>
          </div>
        </div>
        <div class="text-sm flex justify-end mt-2">
          <div class="relative bg-white shadow-sm rounded-lg p-4 ml-4">
            <p class="font-medium">
              Jon Snow
              <span class="text-xs text-gray-300 ml-1 font-light"
                >2 minutes ago</span
              >
            </p>
            <blockquote class="text-sm mt-2">
              First of all, you have to turn on the new order status from your
              dashboard.
            </blockquote>
          </div>
        </div>
        <div class="text-sm flex justify-end mt-2">
          <div class="relative bg-white shadow-sm rounded-lg p-4 ml-4">
            <p class="font-medium">
              Jon Snow
              <span class="text-xs text-gray-300 ml-1 font-light"
                >1 minutes ago</span
              >
            </p>
            <blockquote class="text-sm mt-2">
              Then, you can use the new order status.
            </blockquote>
          </div>
        </div>
      </div>
    </div>
    <div
      class="absolute bottom-0 mr-4 left-0 w-full rounded-b-lg bg-white border-2 border-gray-100 py-4 px-4"
    >
      <div class="flex items-center justify-between text-sm text-gray-400">
        <input
          type="text"
          placeholder="Write your message..."
          class="placeholder-gray-400 focus:outline-none w-full text-gray-900"
        />
        <div class="flex items-center ml-4">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M10 18a8 8 0 100-16 8 8 0 000 16zM7 9a1 1 0 100-2 1 1 0 000 2zm7-1a1 1 0 11-2 0 1 1 0 012 0zm-.464 5.535a1 1 0 10-1.415-1.414 3 3 0 01-4.242 0 1 1 0 00-1.415 1.414 5 5 0 007.072 0z"
              clip-rule="evenodd"
            />
          </svg>
          <svg
            class="h-5 ml-4"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M15.172 7l-6.586 6.586a2 2 0 102.828 2.828l6.414-6.586a4 4 0 00-5.656-5.656l-6.415 6.585a6 6 0 108.486 8.486L20.5 13"
            ></path>
          </svg>

          <div
            class="ml-4 p-3 bg-green-500 rounded-full shadow-lg hover:shadow-xl text-white"
          >
            <svg
              class="h-5"
              fill="currentColor"
              stroke="currentColor"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M8.75 17.612v4.638a.751.751 0 001.354.444l2.713-3.692zM23.685.139a.75.75 0 00-.782-.054l-22.5 11.75a.752.752 0 00.104 1.375l6.255 2.138 13.321-11.39L9.775 16.377l10.483 3.583a.753.753 0 00.984-.599l2.75-18.5a.751.751 0 00-.307-.722z"
              />
            </svg>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.speech-bubble.left:after,
.speech-bubble.left:before {
  content: "";
  display: block;
  position: absolute;
}
.speech-bubble.left:after {
  top: 16px;
}
.speech-bubble.left:before {
  top: 14px;
}
.speech-bubble.left:after {
  border: 8px solid transparent;
  border-right: 8px solid #fdfdfe;
  left: -8px;
  border-left: none;
}
.speech-bubble.left:before {
  border: 10px solid transparent;
  border-right: 10px solid #e0e8ed;
  left: -10px;
  border-left: none;
}
</style>
