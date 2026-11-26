# Dying Light 1 — Subtitle Indonesia
[BuildID 24076292 (7 Juli 2026)](https://steamdb.info/patchnotes/24076292/)

Mod terjemahan Bahasa Indonesia untuk **Dying Light** (Techland, 2015). Seluruh teks dalam game — dialog, subtitle cutscene, objective, tooltip, deskripsi item — dialihbahasakan tanpa mengubah gameplay sama sekali.

Cara kerjanya: mod ini menimpa `DataEn.pak` resmi untuk bahasa inggris menjadi bahasa indonesia.

## Isi Terjemahan

- **15.460 string** diterjemahkan, mencakup seluruh teks game.
- Dialog dan subtitle cinematic, radio chatter, dan obrolan NPC.
- Objective, nama quest, hint, dan teks tutorial.
- Deskripsi item, skill, achievement, tooltip, loading tip, dan pesan error.
- Nama orang, tempat, dan senjata tetap dalam bahasa Inggris agar mudah dicari di wiki.
- Label menu sistem (`New Game`, `Options`, `Quit`, dan sejenisnya) tetap Inggris.
- Token kontrol (`%KEY(...)`, `%s`, `%d`, `&[Ammo]&`) dipertahankan persis agar tidak ada teks yang rusak.

## Cara Pemasangan

### 1. Cari folder instalasi Dying Light

**Steam / GOG / Epic (Linux/Windows):**

```text
../Steam/steamapps/common/Dying Light/DW/
```

### 2. Cadangkan file asli

Ganti nama `DataEn.pak` yang asli menjadi `DataEn.pak.original` — jangan dihapus untuk backup.

Mod ini bekerja dengan **mengambil alih bahasa English**: `DataEn.pak` adalah file bahasa Inggris resmi, dan versi mod berisi terjemahan Bahasa Indonesia di dalamnya. Jadi teks English di game akan tampil sebagai Bahasa Indonesia. Karena itu cadangan di langkah ini wajib — tanpa file asli, tidak ada jalan kembali ke English.

### 3. Pasang mod

Salin `DataEn.pak` menimpa file bahasa Inggris resmi yang sudah dicadangkan tadi.

Struktur akhirnya terlihat seperti ini:

```text
Dying Light/
└── DW/
    ├── DataEn.pak            <- file mod (Indonesia, menggantikan bahasa English)
    └── DataEn.pak.original   <- cadangan file English asli
```

### 4. Jalankan game

Buka Dying Light. Teks akan otomatis tampil dalam Bahasa Indonesia.

Jika masih muncul bahasa Inggris, pastikan bahasa game diset ke **English** di menu Options — mod ini menggantikan file bahasa Inggris, bukan menambah bahasa baru.

---

## Cara Melepas Mod

Hapus `DataEn.pak`, lalu ganti nama `DataEn.pak.original` kembali menjadi `DataEn.pak`. Game akan kembali ke bahasa Inggris seperti semula, karena file English asli sudah dipulihkan.

---

## Catatan Kompatibilitas

- Mod ini hanya mengganti teks. Aman dipakai bersama mod lain selama mod tersebut tidak ikut mengganti `DataEn.pak`.
- Kalau kamu memakai lebih dari satu mod teks, hanya satu yang bisa aktif — keduanya menimpa file yang sama.
- Dying Light: The Following memakai file teks yang sama, jadi terjemahan ikut berlaku untuk DLC tersebut.
- Diuji pada **Dying Light BuildID 24076292 (7 Juli 2026)**, versi Steam. File `DataEn.pak` di dalam mod dibangun dari file resmi pada build tersebut.
- Versi game yang sangat tua (sebelum patch 2016) bisa memakai format `.pak` berbeda, dan file `DataEn.pak` dari build lain belum tentu kompatibel.

---

## Kredit

- Game: **Dying Light** © Techland. Semua aset dan teks asli milik Techland.
- Terjemahan: Edwan132.
- Proyek ini tidak berafiliasi dengan Techland dalam bentuk apa pun.

## Lisensi

Skrip dan terjemahan dirilis di bawah MIT. Teks game asli tetap milik Techland dan tidak termasuk dalam lisensi ini.
Tidak untuk diperjual belikan tanpa sepengetahuan pemilik source.
