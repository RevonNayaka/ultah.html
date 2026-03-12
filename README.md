# ultah.html 🎂

Web kejutan ulang tahun untuk pasangan — **sudah berjalan dan siap digunakan!** 🎉

---

## ✅ Cara Pakai

Cukup **buka file `index.html`** di browser (double-click saja). Tidak perlu server, tidak perlu install apapun.

Atau kalau mau deploy online, upload `index.html` ke:
- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://netlify.com/) (drag & drop folder)
- [Vercel](https://vercel.com/)

---

## 🧪 Cara Coba di Trebedit

**Trebedit** adalah editor HTML online — kamu bisa langsung paste kodenya tanpa install apapun.

### Langkah-langkah:

1. Buka **[trebedit.com](https://trebedit.com/)** di browser
2. Buka file **[`index.html`](./index.html)** di repository ini (klik file-nya di GitHub)
3. Klik tombol **Raw** (pojok kanan atas) untuk lihat kode mentah
4. Tekan **Ctrl + A** (pilih semua) lalu **Ctrl + C** (copy)
5. Di Trebedit, **hapus** semua kode yang ada lalu **Ctrl + V** (paste)
6. Klik **▶ Run** atau **Preview** — halaman akan langsung muncul!

> 💡 **Tips:** Kamu juga bisa klik **Raw** di bagian atas file [`index.html`](./index.html) di GitHub, lalu copy semua teksnya.

### ⚠️ Catatan Trebedit:
- **Animasi hujan** (❤️ 🌸) sudah berjalan otomatis ✅
- **Tombol "Buka Pesannya"** akan fade ke halaman 2 ✅
- **Tombol Putar Lagu** membutuhkan koneksi internet (YouTube) ✅
- Jika lagu tidak bunyi di Trebedit, coba buka file langsung di Chrome/Firefox

---

## ✏️ Cara Mengubah Nama, Foto & Pesan

**Ya, bisa! Semua yang perlu diubah sudah dikumpulkan di satu tempat.**

Buka `index.html`, cari bagian **`CONFIG`** di dalam `<script>` (ada di bagian bawah file):

```javascript
var CONFIG = {
  // Nama orang yang berulang tahun
  nama: 'Kamu',

  // URL foto di halaman 2
  fotoUrl: 'https://i.imgur.com/6VBx8MA.png',

  // Pesan singkat di halaman pertama
  pesanAwal: 'Hari ini adalah hari yang spesial,<br>karena hari ini kamu dilahirkan.',

  // Kalimat ucapan terima kasih
  pesanKartu: 'Terima kasih sudah menjadi seseorang yang begitu berarti.',

  // Pesan panjang di halaman kedua
  pesanRomantis: '...',

  // ID video YouTube
  youtubeId: 'MWfKVAep1ew',
};
```

Ubah nilai-nilainya sesuai kebutuhan, lalu **save** → **refresh** → halaman langsung berubah!

### 🔧 Panduan per bagian:

| Yang ingin diubah | Ubah nilai ini | Contoh |
|---|---|---|
| Nama penerima | `nama` | `'Sinta'` |
| Foto | `fotoUrl` | URL foto dari imgur |
| Pesan halaman 1 | `pesanAwal` | Teks sapaan |
| Ucapan terima kasih | `pesanKartu` | Teks singkat |
| Pesan panjang hal. 2 | `pesanRomantis` | Kata-kata romantis |
| Lagu YouTube | `youtubeId` | ID video YouTube |

### 🖼️ Cara Ganti Foto

1. Buka **[imgur.com](https://imgur.com/)** → klik **New Post** → upload foto kamu
2. Setelah upload, klik kanan gambar → **Copy Image Address**
3. Paste URL tersebut ke `CONFIG.fotoUrl` di `index.html`

### 🎵 Cara Ganti Lagu

1. Buka video YouTube yang kamu mau di browser
2. Salin ID-nya dari URL: `youtube.com/watch?v=`**`MWfKVAep1ew`** ← bagian ini
3. Paste ke `CONFIG.youtubeId`

---

## 🌐 Cara Hosting (Gratis)

Setelah kamu ubah `index.html`, upload ke salah satu platform berikut:

| Platform | Cara Upload | Gratis |
|---|---|---|
| **GitHub Pages** | Push ke branch `main`, aktifkan Pages di Settings | ✅ |
| **Netlify** | Drag & drop folder ke [netlify.com](https://netlify.com/) | ✅ |
| **Vercel** | Import repo di [vercel.com](https://vercel.com/) | ✅ |

> Setelah hosting, kalau mau ubah isi — cukup **edit `CONFIG` di `index.html`** lalu **push/upload ulang** filenya.

---

## 📄 Fitur

| Fitur | Keterangan |
|---|---|
| Halaman 1 | Kartu ucapan + tombol "Buka Pesannya" |
| Halaman 2 | Foto bulat + kata-kata romantis + tombol putar lagu |
| Animasi | Hujan ❤️ 🌸 💕 ✨ 🎂 🎉 jatuh dari atas |
| Transisi | Perpindahan halaman halus (fade) |
| Musik | Play/Pause lagu Selamat Ulang Tahun via YouTube |

---

## 💻 Kode Lengkap

Seluruh kode ada di file **[`index.html`](./index.html)** — satu file, tidak ada dependensi eksternal.