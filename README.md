<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AndhyDesigns</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body { font-family: 'Segoe UI', sans-serif; }
  </style>
</head>
<body class="bg-white text-gray-800">

  <!-- Hero Section -->
  <section class="text-center py-16 bg-gradient-to-r from-blue-500 to-indigo-600 text-white">
    <h1 class="text-5xl font-bold">Selamat Datang di AndhyDesigns</h1>
    <p class="mt-4 text-xl">Jasa Desain Grafis Profesional & Kreatif</p>
    <a href="#layanan" class="mt-6 inline-block bg-white text-blue-600 font-semibold px-6 py-2 rounded-full shadow hover:bg-gray-100 transition">Lihat Layanan</a>
  </section>

  <!-- Layanan Section -->
  <section id="layanan" class="grid grid-cols-1 md:grid-cols-3 gap-6 p-8">
    <div class="bg-white p-6 rounded-2xl shadow">
      <h2 class="text-2xl font-bold mb-2">Desain Logo</h2>
      <p>Logo unik dan berkarakter untuk brand Anda.</p>
    </div>
    <div class="bg-white p-6 rounded-2xl shadow">
      <h2 class="text-2xl font-bold mb-2">Feed Sosial Media</h2>
      <p>Visual konten menarik untuk IG, FB, dan lainnya.</p>
    </div>
    <div class="bg-white p-6 rounded-2xl shadow">
      <h2 class="text-2xl font-bold mb-2">Spanduk & Brosur</h2>
      <p>Desain cetak profesional promosi bisnis Anda.</p>
    </div>
  </section>

  <!-- Portofolio Section -->
  <section class="bg-gray-100 p-8">
    <h2 class="text-3xl font-bold text-center mb-6">Portofolio</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
      <img src="https://via.placeholder.com/300x200?text=Desain+1" class="rounded-xl shadow-md">
      <img src="https://via.placeholder.com/300x200?text=Desain+2" class="rounded-xl shadow-md">
      <img src="https://via.placeholder.com/300x200?text=Desain+3" class="rounded-xl shadow-md">
    </div>
  </section>

  <!-- Testimoni Section -->
  <section class="p-8 bg-white">
    <h2 class="text-3xl font-bold text-center mb-6">Apa Kata Klien?</h2>
    <div class="space-y-4 max-w-2xl mx-auto">
      <blockquote class="bg-blue-100 p-4 rounded-lg">"Desainnya keren banget! Cepat dan profesional!" – Rina, Jakarta</blockquote>
      <blockquote class="bg-blue-100 p-4 rounded-lg">"Selalu puas dengan hasil dari AndhyDesigns." – Dedi, Bandung</blockquote>
    </div>
  </section>

  <!-- Kontak Section -->
  <section class="p-8 bg-gray-50">
    <h2 class="text-3xl font-bold text-center mb-4">Hubungi Kami</h2>
    <form class="max-w-md mx-auto space-y-4">
      <input type="text" placeholder="Nama" class="w-full p-3 rounded border" required>
      <input type="email" placeholder="Email" class="w-full p-3 rounded border" required>
      <textarea placeholder="Pesan Anda" class="w-full p-3 rounded border" rows="4" required></textarea>
      <button type="submit" class="bg-blue-600 text-white px-6 py-2 rounded-full hover:bg-blue-700 transition">Kirim</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-indigo-700 text-white text-center p-6">
    <p>© 2025 AndhyDesigns. All rights reserved.</p>
    <p>Instagram: @andhydesign | WhatsApp: 085345449125</p>
  </footer>

  <!-- Floating WhatsApp Button -->
  <a href="https://wa.me/6285345449125" target="_blank" class="fixed bottom-4 right-4 bg-green-500 p-4 rounded-full shadow-lg hover:bg-green-600 transition">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp" class="w-6 h-6">
  </a>

</body>
</html>
