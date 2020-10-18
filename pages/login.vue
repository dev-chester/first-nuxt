<template>
  <div class="flex bg-gray-500">
    <aside class="relative bg-sidebar h-screen w-64 hidden sm:block shadow-xl">
      <div class="p-6">
        <a
          href="index.html"
          class="text-white text-3xl font-semibold uppercase hover:text-gray-300"
          >Hello User</a
        >
        <button
          class="w-full bg-white cta-btn font-semibold py-2 mt-5 rounded-br-lg rounded-bl-lg rounded-tr-lg shadow-lg hover:shadow-xl hover:bg-gray-300 flex items-center justify-center"
        >
          <i class="fas fa-plus mr-3"></i> New Task
        </button>
      </div>
      <nav class="text-white text-base font-semibold pt-3">
        <a
          href="#"
          class="flex items-center active-nav-link text-white py-4 pl-6 nav-item"
        >
          <i class="fas fa-tachometer-alt mr-3"></i>
          Dashboard
        </a>
        <a
          href="#"
          class="flex items-center text-white opacity-75 hover:opacity-100 py-4 pl-6 nav-item"
        >
          <i class="fas fa-sticky-note mr-3"></i>
          Pomodoro
        </a>
        <a
          href="#"
          class="flex items-center text-white opacity-75 hover:opacity-100 py-4 pl-6 nav-item"
        >
          <i class="fas fa-table mr-3"></i>
          Kanban
        </a>
        <a
          href="#"
          class="flex items-center text-white opacity-75 hover:opacity-100 py-4 pl-6 nav-item"
        >
          <i class="fas fa-align-left mr-3"></i>
          Milestones
        </a>

        <a
          href="#"
          class="flex items-center text-white opacity-75 hover:opacity-100 py-4 pl-6 nav-item"
        >
          <i class="fas fa-calendar mr-3"></i>
          Calendar
        </a>
      </nav>
    </aside>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  },
  methods: {},
}
</script>

<style scoped></style>
