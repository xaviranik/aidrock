<template>
  <div class="flex h-screen bg-gray-200 text-gray-600" id="app">
    <div
      class="flex overflow-hidden bg-white container my-12 m-auto rounded-lg p-8 shadow-md"
    >
      <div class="w-1/4 p-8">
        <Sidebar />
      </div>
      <div class="w-1/2 bg-gray-100 rounded-lg">
        <ChatWindow />
      </div>
      <div class="w-1/4 p-8">
        <ChatBlock />
      </div>
    </div>
  </div>
</template>

<script>
import Sidebar from "@/components/Sidebar";
import ChatBlock from "@/components/ChatBlock";
import ChatWindow from "@/components/ChatWindow";

export default {
  name: "App",
  components: {
    Sidebar,
    ChatBlock,
    ChatWindow,
  },
};
</script>

<style>
</style>
