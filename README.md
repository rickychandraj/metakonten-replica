# Sepri Search

Folder ini berisi **Sepri Search**, halaman pencarian pribadi bergaya Perplexity dengan nama dan logo "Sepri".

## Isi folder

| File | Keterangan |
|---|---|
| `google-search.html` | Halaman utama Sepri Search. Cukup dibuka di browser, tidak perlu instalasi atau server. |
| `README.md` | File ini, penjelasan tentang isi folder. |

## Fitur

- **Tampilan bergaya Perplexity**: sidebar kiri (Beranda, Jelajahi, Ruang, Pustaka), judul "Apa yang ingin Anda ketahui?", dan kotak tanya besar
- **Tiga mode** di kotak tanya, lalu tekan Enter atau tombol panah:
  - **Cari**: hasil pencarian Google
  - **Tanya AI**: membuka Claude (claude.ai) dengan pertanyaan Anda
  - **Beruntung**: langsung membuka hasil teratas
- **Saran pertanyaan** di bawah kotak, klik untuk mengisi otomatis
- **Utas baru** (atau Ctrl/Cmd + I) untuk mengosongkan kotak
- **Logo Google Workspace** di bagian "Aplikasi" (Gmail, Drive, Docs, Sheets, Slides, Forms, Calendar, Meet, Chat, Keep, Sites, Contacts, Tasks, Gemini): klik untuk membuka aplikasinya
- **Pencarian suara** lewat ikon mikrofon, dalam Bahasa Indonesia (Chrome/Safari)
- **Pencarian gambar** lewat ikon klip (membuka Google Lens)
- **Mode gelap** selalu aktif
- **Responsif**: tetap rapi di layar HP

## Cara kerja

Sepri Search hanya mengurus **tampilan depan**. Saat Anda mencari, kata kuncinya dikirim ke `google.com/search` dan hasilnya dibuka di tab baru. Jadi hasil pencariannya tetap berasal dari Google.

## Cara membuka

Klik dua kali `google-search.html`, atau jalankan perintah ini di Terminal:

```bash
open google-search.html
```

## Catatan

Halaman ini memakai gaya tampilan Perplexity dan logo aplikasi Google. Gunakan untuk keperluan pribadi saja, dan jangan dipublikasikan seolah-olah layanan resmi Google.
