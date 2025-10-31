---
title: "Kelompok 5: Pengantar Unit Testing"
date: 2025-10-25 09:00:00 +0800
categories: [Artikel, STQA]
tags: [unit testing, aaa, pytest, junit, jest]
image: /assets/img/kelompok5.png
---

## Apa Itu Unit Testing?
Unit testing adalah jenis pengujian perangkat lunak yang berfokus pada pengujian unit-unit terkecil dalam sebuah sistem, seperti function, method, dan class. Ini adalah pengujian paling awal yang dilakukan oleh developer.

Menurut piramida pengujian, Unit Test adalah yang tercepat dan termurah untuk dieksekusi.

## Kenapa Unit Testing Penting?
* Mendeteksi Bug Lebih Awal
* Mempermudah Perubahan dan Refactoring
* Memberikan Dokumentasi Kode yang Hidup
* Menghemat Waktu dan Biaya
* Meningkatkan Kualitas Kode
* Meningkatkan Kepercayaan Diri

## Framework Populer
* **JUNIT 5 (Java):** Framework de facto untuk Java dan bahasa berbasis JVM.
* **JEST (JavaScript):** Framework buatan Meta, bagus untuk React, Node.js, dll.
* **PYTEST (Python):** Sederhana dan kuat, digunakan untuk berbagai proyek Python.

## Pola Dasar Arrange, Act, Assert (AAA)
Pendekatan populer yang membagi tes menjadi tiga bagian:
1.  **Arrange (Menyiapkan):** Menyiapkan kondisi awal tes.
2.  **Act (Menjalankan):** Menjalankan fungsi atau metode yang akan diuji.
3.  **Assert (Memverifikasi):** Memverifikasi bahwa hasilnya sesuai ekspektasi.

## Contoh Kode (Pytest)
Berikut adalah contoh sederhana pengujian `ShoppingCart` menggunakan Pytest.

**Kode File `shopping_cart.py`:**
```python
from typing import List

class ShoppingCart:
    def __init__(self, max_size: int) -> None:
        self.items: List[str] = []
        self.max_size = max_size

    def add(self, item: str):
        if len(self.items) >= self.max_size:
            raise OverflowError("cannot add more items")
        self.items.append(item)

    def get_items(self) -> List[str]:
        return self.items