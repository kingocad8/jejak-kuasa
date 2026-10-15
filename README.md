# Jejak Kuasa — Web Artikel

Situs statis artikel lengkap Jejak Kuasa. Versi ringkas tiap artikel tayang sebagai carousel di Instagram & TikTok **@jejakkuasa**.

## Struktur
```
web/
├── index.html                  → beranda + daftar artikel
├── style.css                   → tema perkamen
├── artikel/
│   └── embargo-minyak-1973.html
└── arsip/                      → foto arsip (diisi setelah verifikasi lisensi)
```

## Cara deploy ke Vercel (gratis, tanpa kartu)

1. **Buat repo GitHub baru**: nama `jejak-kuasa`, public. (github.com/new)
2. **Upload isi folder `web/`** ke repo — drag & drop lewat web GitHub, atau via browser.
3. **Vercel**: vercel.com → Add New Project → Import repo `jejak-kuasa` → Deploy.
4. Jadi: `https://jejak-kuasa.vercel.app` 🎉
5. Tiap artikel baru: tambah file di `artikel/`, tambah card di `index.html`, push → Vercel auto-deploy.

## Alur kerja per topik
1. Riset 1x (sumber terverifikasi) → tulis artikel lengkap di `artikel/`
2. Distilasi jadi carousel 10–15 slide untuk IG/TikTok (di `../sampel-*/`)
3. Foto arsip: hanya public domain, catat di `../arsip/SUMBER-FOTO.md`, copy ke `arsip/` untuk web
