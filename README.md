# 📦 JMS STORE – Katalog Produk

Website katalog resmi **JMS STORE** dengan tampilan dark mode premium, mendukung produk otomatis dari `products.json`, popup detail, kategori, dan order WhatsApp otomatis.

Website ini dirancang agar mudah kamu kelola tanpa perlu mengedit HTML.  
Cukup ubah data di `products.json`, dan produk akan langsung muncul di website.

---

## 🌐 Live Demo (GitHub Pages)

Aktifkan GitHub Pages untuk menampilkan website:

```
https://username.github.io/nama-repo/
```

Ganti `username` dan `nama-repo` sesuai GitHub kamu.

---

## 📁 Struktur Project

```
📦 jms-store-catalog
│
├── index.html        ← Halaman utama katalog
├── products.json     ← Data produk (bisa diedit tanpa ubah HTML)
└── README.md
```

---

## 📝 Format Produk (products.json)

Semua produk dikelola melalui file:

```
products.json
```

Format data produk:

```json
{
  "name": "Nama Produk",
  "category": "Paket Data / VPN Premium SG / VPN Premium ID / VPS",
  "price": "Rp10.000",
  "desc": "Deskripsi singkat.",
  "detail": "Deskripsi lengkap produk.",
  "img": "https://link-gambar.jpg",
  "wa": "Pesan WhatsApp otomatis"
}
```

Kategori yang tersedia:

- Paket Data  
- VPN Premium SG  
- VPN Premium ID  
- VPS  

---

## 🖼 Cara Ganti Gambar Produk

Gunakan layanan upload gambar:

- https://ibb.co  
- https://postimages.org  
- https://catbox.moe  

Lalu masukkan **direct image link** ke `"img"` di products.json.

Contoh direct link valid:

```
https://i.ibb.co/xxxxx/namagambar.png
```

---

## 🔄 Menjalankan Secara Lokal

Jika kamu membuka `index.html` secara langsung dari HP seperti:

```
file:///storage/emulated/0/index.html
```

⚠ **Produk tidak akan tampil**, karena browser memblokir `fetch()` ke JSON.

Gunakan salah satu cara:

### ✔ 1. VSCode + Live Server  
- Install extension "Live Server"  
- Klik kanan `index.html` → **Open With Live Server**

### ✔ 2. Upload ke GitHub Pages (disarankan)  
- Upload `index.html` dan `products.json`  
- Settings → Pages → Branch: `main` / root  
- Save  

Website akan muncul dalam beberapa detik.

---

## 🚀 Cara Deploy ke GitHub Pages

1. Buat repo baru di GitHub  
2. Upload file berikut:  
   - `index.html`  
   - `products.json`  
   - `README.md`  
3. Masuk **Settings → Pages**  
4. Pada **Branch**, pilih:  
   - `main`  
   - `/ (root)`  
5. Klik **Save**

GitHub akan memberikan link seperti:

```
https://username.github.io/jms-store/
```

---

## 🛠 Fitur Website

- ✓ Dark mode premium  
- ✓ Produk dari `products.json`  
- ✓ Kategori lengkap (Paket Data, VPN SG, VPN ID, VPS)  
- ✓ Popup detail produk  
- ✓ Filter kategori  
- ✓ Search bar pintar  
- ✓ Logo bulat di header  
- ✓ Favicon icon  
- ✓ WhatsApp auto-order  
- ✓ Responsif 100% mobile friendly  
- ✓ Hover animasi premium  

---

## 🖥 Ganti Nomor WhatsApp

Cari bagian ini di `index.html`:

```html
https://wa.me/6281234567890?text=
```

Ganti nomor sesuai nomor admin.

---

## 📞 Kontak JMS STORE

Gunakan tombol Order WhatsApp di setiap produk.  
Atau gunakan link:

```
https://wa.me/6281234567890
```

---

## 🏁 Lisensi

Bebas digunakan untuk keperluan bisnis **JMS STORE**.

---

# ⭐ Terima kasih!

Butuh tambah fitur seperti:

- Dashboard admin  
- Halaman status server  
- API order otomatis  
- Auto-update produk dari database  
- Mode Light/Dark toggle  

Tinggal bilang — aku siap bantu 🚀💚
