# 📋 Panduan Perubahan Portfolio

## ✅ Perubahan yang Telah Dilakukan

### 1. **Foto Profil Bisa Diganti**
- Klik pada foto profil di section "About Me" untuk mengganti foto Anda
- Foto akan tersimpan otomatis di browser Anda (localStorage)
- Foto akan tetap ada meski halaman di-refresh
- **Cara:** Cukup klik pada gambar "DR" untuk membuka file picker

### 2. **Link Project Ditambahkan**
Semua project sekarang memiliki link yang bisa diklik:
- **Luxe Store** → `https://example.com/luxe-store`
- **DataPulse** → `https://example.com/datapulse`
- **NexusAI** → `https://example.com/nexusai`

**Edit link project Anda:**
Buka file `portfolio2.html` dan cari setiap `<a href="https://example.com/...">`, ganti dengan link project Anda yang sebenarnya.

### 3. **Contact Section Dipusatkan**
- Section kontak sekarang tampil di tengah halaman
- Contact details (email, lokasi, jam kerja) semuanya centered
- Social media buttons juga di-center

### 4. **Social Media Links Berfungsi**
Semua tombol social media sekarang langsung membuka ke platform:
- 🐙 **GitHub** → https://github.com
- 💼 **LinkedIn** → https://linkedin.com  
- 🐦 **Twitter** → https://twitter.com
- 📷 **Instagram** → https://instagram.com

---

## 🔧 Cara Mengkustomisasi

### Update Social Media Links
Edit di section `<!-- ══ CONTACT ══ -->`:

```html
<!-- Ganti URL berikut dengan username/profile Anda -->
<a href="https://github.com/USERNAME_ANDA" target="_blank" class="social-btn" title="GitHub">⚡</a>
<a href="https://linkedin.com/in/PROFILE_ANDA" target="_blank" class="social-btn" title="LinkedIn">💼</a>
<a href="https://twitter.com/USERNAME_ANDA" target="_blank" class="social-btn" title="Twitter">🐦</a>
<a href="https://instagram.com/USERNAME_ANDA" target="_blank" class="social-btn" title="Instagram">📷</a>
```

### Update Project Links
Cari setiap `<a href="https://example.com/...">View Details →</a>` dan ganti:

```html
<!-- Project 1: Luxe Store -->
<a href="https://LINK_PROYEK_ANDA_1" target="_blank" class="proj-link">View Details →</a>

<!-- Project 2: DataPulse -->
<a href="https://LINK_PROYEK_ANDA_2" target="_blank" class="proj-link">View Details →</a>

<!-- Project 3: NexusAI -->
<a href="https://LINK_PROYEK_ANDA_3" target="_blank" class="proj-link">View Details →</a>
```

### Update Contact Email
Cari:
```html
<div class="contact-detail"><div class="contact-detail-icon">✉</div><span>hello@yourname.dev</span></div>
```

Ganti dengan email Anda:
```html
<div class="contact-detail"><div class="contact-detail-icon">✉</div><span>email@anda.com</span></div>
```

### Update Nama di Footer
Cari:
```html
<p>© 2025 <strong>Your Name</strong> &nbsp;·&nbsp; Designed & developed with ✦ precision</p>
```

Ganti dengan nama Anda:
```html
<p>© 2025 <strong>Dian Ramadani</strong> &nbsp;·&nbsp; Designed & developed with ✦ precision</p>
```

---

## 📸 Fitur Foto Profil

### Cara Kerja:
1. Klik pada foto profil (area "DR" atau foto yang sudah ada)
2. Pilih foto dari komputer Anda
3. Foto akan langsung ditampilkan
4. Foto tersimpan otomatis (tidak akan hilang saat refresh)

### Notes:
- Format yang didukung: JPG, PNG, GIF, WebP
- Foto disimpan di browser menggunakan localStorage
- Jika ingin reset, buka Console (F12) dan jalankan: `localStorage.removeItem('profilePhoto')`

---

## 🎯 Fitur Lainnya

### Project Links:
- Setiap project card sekarang memiliki tombol "View Details →" yang berfungsi
- Tombol akan membuka link di tab baru (karena `target="_blank"`)

### Contact Section:
- Dipusatkan dengan `max-width: 600px` untuk tampilan optimal
- Responsive di semua ukuran layar
- Social buttons dengan hover effect

---

## ✨ Selesai!

Portfolio Anda sekarang sudah:
✅ Bisa ganti foto profil  
✅ Project punya link yang berfungsi  
✅ Contact section dipusatkan  
✅ Social media bisa diklik langsung  

**Jangan lupa update:**
- Social media links Anda
- Project links Anda  
- Email & informasi kontak Anda
- Nama di footer

Semoga sukses dengan portfolio Anda! 🚀
