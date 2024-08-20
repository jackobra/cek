<template>
  <div class="dashboard">
    <aside class="sidebar">
      <h2>Dashboard</h2>
      <ul>
        <li><NuxtLink to="/dashboard">Home</NuxtLink></li>
        <li><NuxtLink to="/dashboard/profile">Profile</NuxtLink></li>
        <li><NuxtLink to="/dashboard/settings">Settings</NuxtLink></li>
      </ul>
    </aside>
    <main class="content">
      <Nuxt />
    </main>
  </div>
</template>

<style scoped>
.dashboard {
  display: flex;
}

.sidebar {
  width: 200px;
  background: #f4f4f4;
  padding: 1rem;
}

.sidebar h2 {
  margin-top: 0;
}

.sidebar ul {
  list-style: none;
  padding: 0;
}

.sidebar ul li {
  margin: 0.5rem 0;
}

.sidebar ul li a {
  text-decoration: none;
  color: #333;
}

.content {
  flex: 1;
  padding: 1rem;
}
</style>