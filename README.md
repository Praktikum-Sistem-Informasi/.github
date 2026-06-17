# 📘 Panduan Asisten Praktikum

Dokumen ini berisi panduan untuk asisten praktikum (asprak) dalam membuat dan mengelola repository praktikum di organization ini.

## 1. Membuat Repo Baru
1. Buka repository template (`[template-repository]`) di organization ini.
2. Klik tombol **"Use this template"** → **"Create a new repository"**.
3. Pilih organization ini sebagai pemilik repo.
4. Beri nama sesuai konvensi penamaan (lihat poin 2).
5. Pilih **Private** atau **Public** sesuai kebijakan koordinator.

## 2. Konvensi Penamaan Repo
```
{kode-matkul}-{angkatan}-{label-kelas}
```
- `kode-matkul`: singkatan mata kuliah, huruf kecil (contoh: `jarkom`, `sbd`)
- `angkatan`: tahun ajaran/masuk mahasiswa peserta (contoh: `2025`)
- `label-kelas`: identitas kelas/sesi (contoh: `a`, `b`, `a1`, `b1`)

Contoh lengkap: `algoritma-2026-a`

## 3. Struktur Folder di Dalam Repo
```
.
├── README.md                      # info kelas: matkul, angkatan, asprak, daftar pertemuan
├── pertemuan-01-topik/
│   ├── README.md                  # info pertemuan: tujuan, cara run, deadline
│   ├── soal/
│   ├── src/
│   └── docs/
├── pertemuan-02-topik/
│   └── ...
```
- Nama folder pertemuan: `pertemuan-{2 digit}-{topik-singkat}` (contoh: `pertemuan-01-pengenalan`).
- Update tabel "Daftar Pertemuan" di README root setiap kali menambah folder pertemuan baru.

## 4. Sebelum Sesi Praktikum
- [ ] Buat folder `pertemuan-XX-topik` baru dari hasil duplikasi struktur folder.
- [ ] Isi `README.md` pertemuan tersebut (tujuan, cara run, deadline).
- [ ] Masukkan soal ke folder `soal/`, materi pendukung ke `docs/`.
- [ ] Update tabel daftar pertemuan di README root.

## 5. Pertanyaan / Kendala
Hubungi Ketua Asisten Praktikum: 

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/6285156448913)
