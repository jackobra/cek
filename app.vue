<template>
  <div>
    <header>
      <h1>Selamat Datang di Restoran Kami</h1>
      <nav>
        <ul>
          <li><NuxtLink to="/">Beranda</NuxtLink></li>
          <li><NuxtLink to="/menu">Menu</NuxtLink></li>
          <li><NuxtLink to="/about">Tentang Kami</NuxtLink></li>
          <li><NuxtLink to="/contact">Kontak</NuxtLink></li>
        </ul>
      </nav>
    </header>

    <main>
      <section>
        <h2>Special Offer</h2>
        <p>Temukan penawaran spesial kami hari ini!</p>
        <img src="/special-offer.jpg" alt="Special Offer" />
      </section>
    </main>

    <footer>
      <p>&copy; 2024 Restoran Kami. Semua hak cipta dilindungi.</p>
    </footer>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Beranda - Restoran Kami',
    }
  }
}
</script>

<style scoped>
header {
  background: #333;
  color: #fff;
  padding: 10px;
}
nav ul {
  list-style: none;
  padding: 0;
}
nav ul li {
  display: inline;
  margin-right: 10px;
}
footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 10px;
}
</style>