# 🍰 DessertRecycleView

Aplikasi Android sederhana yang dikembangkan untuk mempraktikkan implementasi **RecyclerView**, **Adapter**, dan **Card/Custom Layout** dalam pemrograman aplikasi bergerak menggunakan Kotlin.

---

## 📱 Fitur & Tampilan Aplikasi
- **Dynamic List**: Menampilkan daftar menu *dessert* secara efisien menggunakan komponen `RecyclerView`.
- **Custom Item Layout**: Setiap item dirancang menggunakan kustomisasi layout `itemdesert.xml` yang mencakup:
  - Wadah gambar berbentuk lingkaran (`FrameLayout` dengan `circle_background`).
  - Gambar ilustrasi menu *dessert*.
  - Teks deskripsi menu.
  - Variasi warna latar belakang berbasis kode HEX.

---

## 🛠️ Teknologi & Tools yang Digunakan
- **Bahasa Pemrograman**: Kotlin
- **Environment**: Android Studio
- **Komponen Utama**:
  - `RecyclerView` & `RecyclerView.Adapter`
  - `RecyclerView.ViewHolder`
  - Custom XML Drawable (`shape oval`)

---

## 📂 Struktur Package & File Utama
- **`MainActivity.kt`**: Activity utama tempat inisialisasi data dummy *dessert* dan pengaturan `LinearLayoutManager` serta pemasangan adapter ke `RecyclerView`.
- **`DessertAdapter.kt`**: Kelas penghubung (*adapter*) yang mengatur pemetaan data dari objek ke tampilan item baris di layar.
- **`Dessert.kt`**: Model data berupa *data class* (`description`, `imageRes`, `colorHex`).
- **`itemdesert.xml`**: Berkas layout XML untuk tata letak tiap elemen baris item di dalam daftar.

---

## 🚀 Cara Menjalankan Project
1. Clone repository ini ke komputer lokal kamu menggunakan perintah Git:
   ```bash
   git clone [https://github.com/uziekrimbawatibilqiss/DessertRecycleView.git](https://github.com/uziekrimbawatibilqiss/DessertRecycleView.git)
