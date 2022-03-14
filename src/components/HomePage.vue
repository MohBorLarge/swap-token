<template>
  <div class="home-page bg-white rounded-2xl w-7/12 h-full pb-4" style=";">
    <div class="flex justify-between px-8 py-4">
      <p>Swap</p>
      <button>
        <img src="@/assets/icons/settings.png" alt="" srcset="">
      </button>
    </div>
    <div class="flex justify-between px-8 py-4 bg-gray-100 h-24 mb-1 rounded-xl mx-4 hover:border-blue-400 border-solid border">
      <input type="number" class="bg-gray-100" placeholder="0.0">
      <p>settings</p>
    </div>
    <div class="flex justify-between px-8 py-4 bg-gray-100 h-20 mb-2 rounded-xl mx-4 hover:border-blue-400 border-solid border">
      <input type="number" class="bg-gray-100" placeholder="0.0">
      <p>settings</p>
    </div>
    <div class="connect-wallet flex justify-between px-8 py-4 h-18 rounded-xl">
      <p>settings</p>
      <p>dwriiiiidsd</p>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String
  },
  data() {
    return {

    }
  }
}
</script>

<style scoped>

.home-page {
  max-width: 480px;
}
.connect-wallet {
  background-color: rgb(247, 247, 247)
}
</style>