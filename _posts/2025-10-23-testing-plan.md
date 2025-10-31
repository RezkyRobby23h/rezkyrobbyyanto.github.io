---
title: "Kelompok 3: Testing Plan"
date: 2025-10-23 09:00:00 +0800
categories: [Artikel, STQA]
tags: [testing plan, ieee 829, bmi, demo]
image: /assets/img/kelompok3.png
---

## Apa Itu Testing Plan?
Testing Plan (Rencana Pengujian) adalah dokumen panduan yang menjelaskan bagaimana proses pengujian perangkat lunak akan dilakukan. Ini berfungsi sebagai acuan resmi bagi tim penguji agar kegiatan pengujian lebih terarah.

Di dalamnya memuat ruang lingkup, strategi/metodologi, sumber daya (tim, alat, data uji), serta jadwal pelaksanaan.

## Tujuan Testing Plan
* Menyediakan gambaran yang jelas tentang apa saja yang akan diuji dan bagaimana cara mengujinya.
* Memastikan proses pengujian menemukan sebanyak mungkin kesalahan.
* Mengoptimalkan penggunaan waktu, biaya, dan tenaga.
* Memberikan dokumentasi yang bisa dijadikan referensi dan evaluasi.

## Komponen Testing Plan (Standar IEEE 829)
Standar IEEE 829-1988 mendefinisikan berbagai komponen yang harus ada dalam sebuah dokumen test plan:
1.  Test Plan Identifier
2.  References (Referensi)
3.  Introduction (Pendahuluan)
4.  Test Items (Apa yang diuji)
5.  Software Risk Issues (Risiko)
6.  Features to be Tested (Fitur yang diuji)
7.  Features not to be Tested (Fitur yang tidak diuji)
8.  Approach (Pendekatan/Strategi)
9.  Item Pass/Fail Criteria (Kriteria Lulus/Gagal)
10. Suspension & Resumption Criteria (Kriteria Berhenti/Lanjut)
11. Test Deliverables (Hasil/Dokumen)
12. Remaining Test Tasks (Sisa Tugas)
13. Environmental Needs (Kebutuhan Lingkungan)
14. Staffing and Training Needs (Kebutuhan Tim & Pelatihan)
15. Responsibilities (Tanggung Jawab)
16. Schedule (Jadwal)
17. Planning Risks and Contingencies (Risiko Perencanaan)
18. Approvals (Persetujuan)
19. Glossary (Daftar Istilah)

## Demo Contoh: Test Plan Aplikasi BMI
Berikut adalah contoh penerapan komponen Test Plan pada aplikasi BMI Calculator:
* **Introduction:** Memastikan akurasi perhitungan BMI dan konsistensi klasifikasi kesehatan.
* **Test Items:** Validasi berat (kg) dan tinggi (cm), mesin perhitungan BMI, sistem klasifikasi (Underweight/Normal/dll).
* **Features To Be Tested:** Input slider, historis data, perhitungan akurat, tampilan hasil.
* **Features Not To Be Tested:** Login, print/export, pilihan multi-bahasa.
* **Approach:** Pengujian dilakukan secara manual berdasarkan Test Case.
* **Pass/Fail Criteria:** Perhitungan 100% akurat, Target >95% test case lulus, tidak ada defek kritis.
* **Schedule:** Pengujian dimulai 2 minggu sebelum rilis (Minggu 1: Eksekusi, Minggu 2: Perbaikan & Retest).

