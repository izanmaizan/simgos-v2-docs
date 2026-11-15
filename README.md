# SimGos v2

Pemasangan SimGos dalam bentuk terkontainer: satu perintah untuk menyiapkan layanan beserta data awal.

## Kegunaan

- Memasang SimGos secara konsisten di lingkungan baru.
- Menyediakan data awal setelah pemasangan.
- Mempermudah pemulihan layanan.

## Tech stack

| Lapis | Teknologi |
|---|---|
| Infrastruktur | Docker, Docker Compose |
| Otomasi | Skrip pemasangan shell |
| Data | Seed data awal |

## Alur singkat

1. Citra dibangun dari Dockerfile.
2. Skrip pemasangan menyiapkan layanan.
3. Seed data dimuat untuk pemakaian pertama.

## Ringkasan

| | |
|---|---|
| Mulai dikembangkan | September 2026 |
| Status | Aktif dipakai internal |

> Kode sumber tidak dipublikasikan. Repo ini hanya menjelaskan kegunaan, stack, dan alur kerja. Tidak ada data pengguna, data pasien, atau kredensial di sini.
