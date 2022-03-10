<template>
  <div class="">
    <div class="bg-white rounded-lg w-8/12">
      <div class="flex justify-between px-8 py-4">
        <p cl>Swap</p>
        <button>
          <img src="@/assets/icons/settings.png" alt="" srcset="">
        </button>
      </div>
      <div class="flex justify-between px-8 py-4 bg-gray-100 h-24 mb-1">
        <p cl>Swap</p>
        <p>settings</p>
      </div>
      <div class="flex justify-between px-8 py-4 bg-gray-100 h-18">
        <p cl>Swap</p>
        <p>settings</p>
      </div>
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
