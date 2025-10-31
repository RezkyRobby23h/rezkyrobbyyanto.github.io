---
title: "Kelompok 7: Pengantar Selenium WebDriver"
date: 2025-10-27 09:00:00 +0800
categories: [Artikel, STQA]
tags: [selenium, webdriver, automasi, python]
image: /assets/img/kelompok7.png
---

## Apa itu Selenium?
Selenium adalah framework open-source untuk automasi browser. Digunakan untuk menguji aplikasi web dengan berbagai bahasa pemrograman (Python, Java, C#, JS) dan mendukung banyak browser (Chrome, Firefox, Edge, Safari).

## Apa itu Selenium WebDriver?
WebDriver adalah komponen inti Selenium. Ia berfungsi sebagai penghubung antara kode kita dengan browser. WebDriver inilah yang bertugas mengontrol browser, seperti melakukan klik, input teks, navigasi, dan validasi.

## Kenapa Harus Selenium?
* Open-source dan gratis.
* Mendukung banyak bahasa (Python, Java, C#, JS).
* Multi-platform (Windows, macOS, Linux).
* Bisa diintegrasikan dengan framework testing seperti Pytest, JUnit, TestNG.
* Memiliki komunitas besar dan dokumentasi lengkap.

## Test Scenario & Case (Studi Kasus: SauceDemo)
Berikut adalah contoh skenario dan kasus uji untuk mengotomatisasi pengujian di web 'SauceDemo'.

### Test Scenario
* **TS-001:** Login berhasil di halaman SauceDemo
* **TS-002:** Login gagal dengan kredensial salah
* **TS-003:** Menambahkan produk ke keranjang

### Test Case
* **TC-001 (Login sukses):** Input 'standard_user' & 'secret_sauce' -> Klik Login -> Expected: Masuk ke halaman inventory.
* **TC-002 (Login gagal):** Input user salah -> Klik Login -> Expected: Muncul pesan error.
* **TC-003 (Tambah produk):** Login sukses -> Klik "Add to cart" -> Expected: Cart bertambah 1.
