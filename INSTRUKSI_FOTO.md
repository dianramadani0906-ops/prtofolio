# 📸 Instruksi Mengganti Foto Profil

## Langkah-Langkah:

### 1. **Siapkan Foto Profil Anda**
   - Format yang disarankan: **JPG** atau **PNG**
   - Ukuran yang ideal: **500x500px atau lebih**
   - Pastikan foto **square (persegi)** agar terlihat sempurna di frame lingkaran
   - Ukuran file sebaiknya tidak lebih dari **500KB**

### 2. **Letakkan Foto di Folder `images/`**
   - Buka folder `images/` (sudah ada di dalam folder portfolio_dian)
   - Copy/Paste foto profil Anda ke folder tersebut
   - Pastikan nama file mudah diingat, contoh: `profile.jpg`, `dian.jpg`, atau `dian.png`

### 3. **Update Path Foto di HTML**
   - Buka file `index.html` dengan text editor
   - Cari baris dengan:
     ```html
     <img src="images/profile.jpg" alt="Dian Ramadani" class="profile-photo" onerror="this.style.display='none'">
     ```
   - Ganti `images/profile.jpg` dengan path foto Anda
   
   **Contoh jika nama foto adalah `dian.png`:**
   ```html
   <img src="images/dian.png" alt="Dian Ramadani" class="profile-photo" onerror="this.style.display='none'">
   ```

### 4. **Simpan dan Refresh Browser**
   - Simpan file `index.html`
   - Refresh browser (tekan F5 atau Ctrl+R)
   - Foto profil akan muncul dengan otomatis!

---

## 📌 Tips:

✅ Foto akan otomatis beradaptasi dengan frame lingkaran  
✅ Jika foto tidak ditemukan, akan menampilkan placeholder "DR"  
✅ Frame emas akan terus berputar, foto Anda tetap diam  
✅ Responsive di semua ukuran layar  

---

## ⚠️ Troubleshooting:

**Foto tidak muncul?**
- Cek apakah file foto ada di folder `images/`
- Cek spelling nama file (case-sensitive)
- Pastikan path di HTML sudah benar: `images/namafile.jpg`

**Foto terlihat terpotong?**
- Gunakan foto yang square (1:1 aspect ratio)
- Atau gunakan foto landscape/portrait dan crop menjadi square di Photoshop/online tool

---

Selamat! Foto profil Anda siap di-customize! 🎉
