<template>
  <div>
    <sidebar />
    <div class="relative md:ml-64 bg-blueGray-100">
      <div class="px-4 md:px-10 mx-auto w-full -m-24 max-h-screen">
        <router-view />
      </div>
    </div>
  </div>
</template>
<script>
import Sidebar from '@/components/Sidebar/Sidebar.vue'

export default {
  name: 'GCBMLayout',
  components: {
    Sidebar
  }
}
</script>
