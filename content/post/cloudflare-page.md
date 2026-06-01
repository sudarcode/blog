---
title: "Postingan Pertama di Static Site Generator"
slug: pindah-ke-ssg
date: 2025-12-26T20:23:41+08:00
draft: false

tags:
    - Page
    - Cloudflare

image: "/img/dns/cloudflare.png"
description: "Migrasi dari Wordpress ke Cloudflare page, dari Blogger ke Cloudflare Page"
---

Pada Awal tahun 2026 akhirnya bisa migrasi blog ke Static Site Generator, awalnya blog ini masih menggunakan Blogger untuk Ngeblog. 

Sebelum ke Static Site Generator ini saya pernah juga memakai wordpress yang mana itu sangat memberatkan apalagi belum sewa hosting setiap bulan nya di tambah lagi ke amanan blog pun bisa membuat tidak tidur

Dengan menggunakan Static Site Generator ini tentu tidak perlu memikirkan keamanan dan juga biaya pertahun berapa karena itu gratis dan unlimitid, meski pengunjung banyak tantu tidak akan membuat website menjadi lemot atau bahkan down saat di akses. 

Ditambah lagi pindah ke Static Site Generator ini bukan tanpa alasa ada beberapa alasan yang membuat saya pindah kesini, apa aja alasan nya? 

## Alasan Pindah ke SSG

Keunggulan utamanya meliputi:
- Performa Ekstrem: Halaman web dimuat dengan sangat cepat karena server hanya perlu menyajikan file HTML yang sudah jadi.
- Ramah SEO: Mesin pencari seperti Google dapat membaca konten dengan mudah dan cepat karena kode HTML lengkap sudah tersedia sejak awal.
- Keamanan Tinggi: Tidak ada koneksi langsung ke database atau pemrosesan sisi server (server-side processing) saat pengunjung mengakses situs, sehingga meminimalkan celah serangan siber.
- Hemat Biaya & Skalabel: File statis yang di-cache sangat ringan, sehingga situs web mudah di-hosting (bahkan gratis di platform seperti GitHub Pages atau Vercel) dan tahan banting saat terjadi lonjakan trafik.

Sejak lama saya mengetahui mengenai ini akan tetapi karena masih menulis blog menggunakan Handphone jadi sangat sulit untuk memulai nya, di dalam Static Site Generator ini banyak pilihan Platfrom nya seperti Astro, Hugo, Next.js, Jeklly, Gatsby itu bisa kalian pilih sesuai kemampuan kalian yang mana karena mereka semua memiliki keunggulan masing - masing. 

## Menemukan Astro.js

Sebelum nya saya menggunakan Hugo untuk platfrom ngeblog dan akhir nya saya menemukan Astro Bluid ini, Menggunakan Hugo mungkin sekarang ini sedang populer karena hugo sendiri juga ringan dan pilihan template nya juga banyak. 

Karena blog yang saya buat ini adalah berbasis protofolio jadi Astro ini sangatlah cocok untuk platfrom ngeblog apalagi untuk dikembangkan tentu sangatlah gamapang, ada beberapa keunggulan yang di miliki oleh Astro ini sendiri apa aja itu :

### 1. Performa Sangat Cepat (Zero JavaScript by Default)
Secara default, Astro tidak mengirimkan JavaScript apa pun ke browser. Halaman sepenuhnya dirender di server menjadi HTML murni yang ringan. Hasilnya, skor Core Web Vitals dan waktu muat (loading) menjadi sangat optimal.

### 2. Arsitektur Astro Islands
Teknologi ini memungkinkan Anda untuk mengisolasi elemen interaktif (seperti tombol pencarian atau keranjang belanja) menjadi bagian terpisah atau "pulau". Komponen lain tetap berupa HTML statis, sehingga browser hanya memuat JavaScript untuk bagian yang membutuhkan interaksi saja.

### 3. Kompatibilitas Lintas Framework
Anda tidak perlu terpaku pada satu framework. Astro memungkinkan Anda untuk menggabungkan komponen dari React, Vue, Svelte, hingga SolidJS dalam satu proyek atau bahkan dalam satu halaman yang sama.

### 4. Ramah SEO (Search Engine Optimization)
Karena Astro menghasilkan halaman berupa HTML sejak dari awal (dari server), perayap (crawler) mesin pencari seperti Google dapat membaca konten dan struktur situs Anda dengan mudah dan cepat.

### 5. Dukungan Koleksi Konten (Content Collections)
Astro memiliki fitur bawaan yang sangat baik untuk mengelola konten berbasis teks (Markdown atau MDX). Ini menjadikannya pilihan sempurna untuk situs web berbasis konten seperti blog, dokumentasi, maupun portofolio.

## Hosting di Cloudflare
![cloudflare pages](./assets/pages.png.jpg)
Karena di Cloudflare ini sangatlah gampang di operasikan jadi saya untuk hosting blog saya di Cloudfare ini ditambah lagi fitur yang free. 

Ada alternatif lain apabila kalian kesulitan menggunakan cloudflare ini seperti :
- [Varcel](varcel.com) : Gampang dan juga gratis
- [Netlify](netlify.com) : Free dan banyak di pakai devoloper
- [Github Pages](github.com) : Free dan Banyak dipakai Devoloper


Kalian pilih mana untuk hosting blog kalian! Itu semua tergantung kalian sendiri mana favorit karena setiap orang punya pilihan masing - masing. 😁

Kalau saya pribadi ini menggunakan github untuk menyimpan file nya karena lebih mudah juga untuk di operasikan pula apalagi bahkan bisa di privasi agar code tidak di ambil orang. 

## Akhir Kata
Mungkin pengalaman diatas bisa bermanfaat untuk kalian semua apabila kalian menemukan bug atau error bisa langsung aja tulis di komentar di bawah ini ya. 
