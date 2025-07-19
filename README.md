# restore-old-photos-bay.
Platform AI restorasi foto lama dan ganti pakaian otomatis buatan Indonesia.
📄 File Lengkap: pages/index.js

// File: pages/index.js

import Head from "next/head";

export default function Home() {
  return (
    <>
      <Head>
        <title>Restore Old Photos.Bay</title>
        <meta name="description" content="Situs AI untuk memperbaiki foto lama, mengganti pakaian, dan membuat latar belakang AI" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
      </Head>

      <main style={{ padding: "2rem", fontFamily: "sans-serif", textAlign: "center" }}>
        <h1 style={{ fontSize: "2rem", marginBottom: "1rem" }}>
          Selamat Datang di Restore Old Photos.Bay
        </h1>

        <p style={{ marginBottom: "1rem" }}>
          Platform AI serbaguna untuk mengedit dan memperindah foto lama Anda!
        </p>

        <div style={{ textAlign: "left", maxWidth: "500px", margin: "0 auto" }}>
          <ul>
            <li>📸 <b>Restoration Siri:</b> Perbaiki blur, noise, dan warna pada foto lama.</li>
            <li>🖼️ <b>ArtRoom:</b> Ganti pakaian AI otomatis (jas, kebaya, seragam, batik, dll).</li>
            <li>🎨 <b>ArtPhotos:</b> Edit manual dan AI extender untuk detail tambahan.</li>
            <li>🌄 <b>AI Background:</b> Ganti latar belakang dengan suasana pemandangan, studio, dll.</li>
            <li>🔒 <b>Login & Premium:</b> Akses riwayat dan unduh hasil tanpa watermark.</li>
            <li>📤 <b>Unduh:</b> Hasil foto tersedia dalam format JPG/PNG hingga resolusi 8K.</li>
          </ul>
        </div>

        <p style={{ marginTop: "2rem" }}>
          Silakan mulai dari menu navigasi atau login untuk menggunakan semua fitur.
        </p>
      </main>
    </>
  );
}


---

📁 Tempat Menaruh File

Pastikan file ini disimpan di:

restore-old-photos-bay/
│
├── pages/
│   └── index.js   ✅ TARUH DI SINI
│
├── public/
├── styles/
└── ...

Jika belum ada folder pages/, kamu harus buat dulu, lalu tempatkan index.js di dalamnya.


---

🧠 Apa yang Dilakukan File Ini?

Menampilkan halaman depan (beranda) saat pengguna membuka situs kamu.

Memuat <title> dan deskripsi SEO-friendly.

Menjelaskan semua fitur utama proyek:

Restoration Siri

ArtRoom

ArtPhotos

Background AI

Premium

Unduh hasil
