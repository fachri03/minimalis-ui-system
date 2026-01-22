# minimalis-ui-system
UAS(desain_system)AuliyaFachriHidayat-1123102102

# 🎨 Minimalis UI System

Sebuah **Design System berbasis JavaScript (Vanilla JS)** dengan konsep **minimalis modern** dan **tema Dark Blue & Black**, dibuat untuk memenuhi **Tugas UAS Design System**.

Project ini berisi kumpulan **komponen UI reusable** yang sederhana, konsisten, dan mudah dikembangkan tanpa framework tambahan.

---

## 📌 Identitas Proyek

* **Nama Proyek** : Minimalis UI System
* **Mata Kuliah** : Design System
* **Jenis Tugas** : UAS
* **Teknologi** : Vanilla JavaScript + HTML + CSS (inline style)
* **Build Tool** : `tsup`

---

## ✨ Fitur Utama

* 🎯 Desain **minimalis & konsisten**
* 🌙 Tema warna **Dark Blue & Hitam**
* ♻️ Komponen **reusable**
* ⚡ Tanpa framework (React/Vue)
* 📦 Build siap distribusi (`dist/`)

---

## 🧩 Komponen UI

Project ini memiliki **5 komponen utama**:

1. **Button**
   Tombol utama dengan gaya modern dan hover effect.

2. **Input**
   Field input dengan border halus dan warna gelap.

3. **Card**
   Container konten dengan judul dan deskripsi.

4. **Alert**
   Notifikasi sukses dengan warna kontras.

5. **Badge**
   Label status berbentuk pill.

---

## 🎨 Tema Warna

| Elemen           | Warna     |
| ---------------- | --------- |
| Background utama | `#020617` |
| Biru utama       | `#2563eb` |
| Biru hover       | `#1d4ed8` |
| Teks utama       | `#f8fafc` |
| Teks sekunder    | `#cbd5f5` |
| Border           | `#1e293b` |

---

## 📂 Struktur Folder

```bash
minimalis-ui-system/
├── src/
│   ├── components/
│   │   ├── Button.js
│   │   ├── Input.js
│   │   ├── Card.js
│   │   ├── Alert.js
│   │   └── Badge.js
│   └── index.js
├── dist/
│   ├── index.js
│   └── index.cjs
├── demo.html
├── tsup.config.js
├── package.json
└── README.md
```

---

## 🚀 Cara Menjalankan Project

### 1️⃣ Install Dependencies

```bash
npm install
```

### 2️⃣ Build Project

```bash
npm run build
```

Output build akan tersedia di folder `dist/`.

---

## 👀 Cara Melihat Tampilan (Demo)

Buka file berikut langsung di browser:

```bash
demo.html
```

File ini menampilkan seluruh komponen UI dengan tema Dark Blue secara visual.

---

## 🧪 Contoh Penggunaan

```js
import { Button, Input, Card, Alert, Badge } from "./dist/index.js";

const container = document.createElement("div");
container.append(
  Button({ label: "Primary Button" }),
  Input({ placeholder: "Nama pengguna" }),
  Card({
    title: "Design System",
    content: "Tema biru hitam minimalis"
  }),
  Alert({ message: "Data berhasil disimpan" }),
  Badge({ label: "ACTIVE" })
);

document.body.append(container);
```

---

## 📚 Tujuan Pembelajaran

* Memahami konsep **Design System**
* Menerapkan **konsistensi visual**
* Membuat komponen UI reusable
* Menggunakan build tool modern (`tsup`)

---

## 📝 Catatan

* Project ini dibuat **tanpa framework** untuk fokus pada konsep dasar.
* Semua styling menggunakan JavaScript agar mudah dikembangkan.

---

## 🙌 Penutup

Terima kasih telah melihat project ini. Semoga project **Minimalis UI System** dapat menjadi contoh sederhana namun rapi dalam penerapan Design System.

✨ Dibuat dengan penuh semangat belajar ✨

