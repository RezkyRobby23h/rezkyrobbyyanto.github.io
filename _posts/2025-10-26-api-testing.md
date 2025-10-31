---
title: "Kelompok 6: API Testing"
date: 2025-10-26 09:00:00 +0800
categories: [Artikel, STQA]
tags: [api, postman, soapui, request, response]
image: /assets/img/kelompok6.png
---

## Apa Itu API Testing?
API Testing adalah proses pengujian yang dilakukan pada Application Programming Interface (API) untuk memastikan bahwa API berfungsi sesuai dengan spesifikasi, dapat menangani berbagai skenario, dan menghasilkan output yang benar.

## Keunggulan API Testing
* Memastikan API berfungsi sesuai spesifikasi.
* Meningkatkan keandalan sistem dengan mendeteksi bug sejak awal.
* Menjamin keamanan API dari akses tidak sah.
* Mengukur performa API di bawah beban.
* Mempercepat siklus pengembangan.
* Menjadi pondasi integrasi antar sistem.

## Tools API Testing

### Postman
* **Fitur Utama:** Kirim request HTTP (GET, POST, PUT, DELETE), kelola environment, testing otomatis, collection, dokumentasi API.
* **Mengapa Postman?** User-friendly, mendukung berbagai metode HTTP, manajemen koleksi, dukungan otentikasi.

### SoapUI
* **Fitur Utama:** Mendukung SOAP dan REST API, functional testing, security testing, load testing.
* **Kelebihan:** Sangat kuat untuk SOAP API (berbasis XML), mendukung data-driven testing, cocok untuk skenario kompleks.

## Anatomi Request & Response API

### Request API (Permintaan)
Permintaan yang dikirim dari klien ke server. Terdiri dari:
* **Method (HTTP Verb):** Aksi yang ingin dilakukan (GET, POST, PUT, DELETE).
* **URL (Endpoint):** Alamat dari resource yang ingin diakses.
* **Headers:** Informasi tambahan (misal: Tipe Konten, Token Otorisasi).
* **Body:** Data yang dikirim (digunakan pada POST, PUT).

### Response API (Balasan)
Balasan yang diberikan server setelah memproses request. Terdiri dari:
* **Status Code:** Kode numerik hasil eksekusi, misal 200 (OK), 404 (Not Found), 500 (Server Error).
* **Headers:** Informasi tambahan dari server.
* **Body:** Data yang diminta (biasanya dalam format JSON atau XML).