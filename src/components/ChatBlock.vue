<template>
  <div class="overflow-y-auto">
    <div class="border-b-2 border-gray-100 pb-5 mb-8">
      <div
        class="w-full inline-flex items-center justify-between text-gray-400"
      >
        <div class="flex items-center text-gray-600 text-base font-semibold">
          <div class="flex items-center">
            <div class="bg-gray-100 p-2 rounded-lg">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-4 text-gray-300"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M14 5l7 7m0 0l-7 7m7-7H3"
                />
              </svg>
            </div>
            <div class="ml-3 text-lg">Active Tickets</div>
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
    </div>
    <div
      class="w-full inline-flex items-center justify-between bg-gray-100 shadow-md px-4 py-4 mb-1 rounded-lg cursor-pointer"
    >
      <div class="flex items-center">
        <div
          class="h-12 w-12 rounded-full bg-pink-400 flex items-center justify-center"
        >
          <div class="p-3 text-lg font-semibold text-white">
            {{ getRandomAvatarLetter().toUpperCase() }}
          </div>
        </div>
        <div class="ml-4">
          <h1 class="text-base font-semibold">Ticket #12542</h1>
          <h1 class="text-xs mt-2">May I know the...</h1>
        </div>
      </div>
      <div class="text-xs">08:19 PM</div>
    </div>
    <div v-for="chat in chatBlocks" :key="chat.id">
      <div
        class="w-full inline-flex items-center justify-between px-4 py-4 mb-1 rounded-lg cursor-pointer hover:shadow"
      >
        <div class="flex items-center">
          <div
            class="h-12 w-12 rounded-full bg-pink-300 flex items-center justify-center"
          >
            <div class="p-3 text-lg font-semibold text-white">
              {{ getRandomAvatarLetter().toUpperCase() }}
            </div>
          </div>
          <div class="ml-4">
            <h1 class="text-base font-semibold">Ticket {{ chat.id }}</h1>
            <h1 class="text-xs mt-2">{{ chat.content }}</h1>
          </div>
        </div>
        <div class="text-xs">{{ chat.time }}</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      chatBlocks: [
        {
          id: "#12543",
          avatar: this.getRandomAvatarLetter(),
          content: "hello, i wish to know...",
          time: "11:48 PM",
        },
        {
          id: "#23423",
          avatar: this.getRandomAvatarLetter(),
          content: "I really want to know...",
          time: "02:12 AM",
        },
        {
          id: "#18543",
          avatar: this.getRandomAvatarLetter(),
          content: "hey there, could you...",
          time: "11:21 AM",
        },
        {
          id: "#86523",
          avatar: this.getRandomAvatarLetter(),
          content: "The service is not...",
          time: "11:10 AM",
        },
        {
          id: "#36521",
          avatar: this.getRandomAvatarLetter(),
          content: "Booking for a order is...",
          time: "10:45 AM",
        },
      ],
    };
  },
  methods: {
    getRandomAvatarLetter() {
      let alphabet = "abcdefghijklmnopqrstuvwxyz";
      return alphabet[Math.floor(Math.random() * alphabet.length)];
    },
  },
};
</script>

<style>
</style>