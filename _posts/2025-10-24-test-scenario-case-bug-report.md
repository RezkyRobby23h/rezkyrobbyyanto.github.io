---
title: "Kelompok 4: Test Scenario, Case & Bug Report"
date: 2025-10-24 09:00:00 +0800
categories: [Artikel, STQA]
tags: [test scenario, test case, bug report, severity, priority]
image: /assets/img/kelompok4.png
---

## Overview
Test scenario, test case, dan bug report adalah tiga elemen penting dalam pengujian perangkat lunak yang saling melengkapi untuk memastikan aplikasi berjalan sesuai harapan.

## Test Scenario
Gambaran umum **apa** yang diuji untuk memastikan fungsi aplikasi sesuai kebutuhan.
* Menjawab pertanyaan: "Apa yang harus diuji?"
* Contoh: "Periksa fungsi penyimpanan history BMI."

### Template Test Scenario
* **ID Scenario:** Nomor unik skenario (misal: TS003)
* **Deskripsi:** Ringkasan skenario (misal: Periksa fungsi penyimpanan history BMI)
* **Modul/Fitur:** Modul atau fitur yang diuji (misal: History BMI)

## Test Case
Langkah detail pengujian, termasuk input, proses, dan hasil yang diharapkan.
* Menjawab pertanyaan: "Bagaimana melakukan pengujian?"
* Contoh: "Verifikasi penyimpanan hasil BMI terbaru ke dalam history."

### Template Test Case
* **ID Test Case:** Nomor unik
* **Deskripsi:** Ringkasan pengujian
* **Precondition:** Kondisi awal
* **Test Steps:** Langkah-langkah detail
* **Test Data:** Data yang digunakan
* **Expected Result:** Hasil yang diharapkan
* **Actual Result:** Hasil aktual
* **Status:** Lulus/Gagal (Pass/Fail)

## Bug Report
Laporan formal kesalahan/masalah pada sistem. Berisi detail masalah, cara mereproduksi, dan hasil aktual.

### Bug Severity vs. Bug Priority
* **Severity (Tingkat Keparahan):** Ukuran dampak bug pada fungsi software.
    * **Critical:** Kegagalan total sistem.
    * **Major (High):** Fungsionalitas utama tidak bekerja.
    * **Minor (Medium):** Tidak memengaruhi fungsionalitas utama, tapi mengganggu.
    * **Low:** Bug kosmetik atau tidak mengakibatkan kerusakan.
* **Priority (Tingkat Prioritas):** Ukuran urgensi perbaikan bug.
    * **P1 (Urgent/Critical):** Harus segera diperbaiki.
    * **P2 (High):** Penting, harus diperbaiki secepatnya.
    * **P3 (Medium):** Bisa diperbaiki di rilis berikutnya.
    * **P4 (Low):** Bisa diperbaiki kapan saja.

