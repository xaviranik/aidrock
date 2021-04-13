<template>
  <div class="overflow-y-auto">
    <div class="border-b-2 border-gray-100 pb-8 mb-8">
      <div
        class="w-full inline-flex items-center justify-between text-gray-400"
      >
        <div class="flex items-center text-gray-600 text-base font-semibold">
          <div class="flex">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6"
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
            <div>Active Tickets</div>
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
      class="w-full inline-flex items-center justify-between bg-gray-100 px-4 py-4 rounded-lg"
    >
      <div class="flex items-center">
        <img
          class="h-12 rounded-full"
          src="https://i.pravatar.cc/150?u=67"
          alt="avatar"
        />
        <div class="ml-4">
          <h1 class="text-base font-semibold">Ticket #12542</h1>
          <h1 class="text-xs mt-2">May I know the...</h1>
        </div>
      </div>
      <div class="text-xs">08:19 PM</div>
    </div>
    <div v-for="chat in chatBlocks" :key="chat.id">
      <div
        class="w-full inline-flex items-center justify-between px-4 py-4 rounded-lg"
      >
        <div class="flex items-center">
          <img
            class="h-12 rounded-full"
            :src="getRandomAvatar()"
            alt="avatar"
          />
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
          avatar: this.getRandomAvatar(),
          content: "hello, i wish to know...",
          time: "11:48 PM",
        },
        {
          id: "#23423",
          avatar: this.getRandomAvatar(),
          content: "I really want to know...",
          time: "02:12 AM",
        },
        {
          id: "#12543",
          avatar: this.getRandomAvatar(),
          content: "hey there, could you...",
          time: "11:21 AM",
        },
        {
          id: "#86523",
          avatar: this.getRandomAvatar(),
          content: "The service is not...",
          time: "11:10 AM",
        },
        {
          id: "#36521",
          avatar: this.getRandomAvatar(),
          content: "Booking for a order is...",
          time: "10:45 AM",
        },
      ],
    };
  },
  methods: {
    getRandomAvatar() {
      let imgID = Math.floor(Math.random() * 100 + 1);
      return "https://i.pravatar.cc/150?u=" + imgID;
    },
  },
};
</script>

<style>
</style>