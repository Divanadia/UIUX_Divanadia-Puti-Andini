# 3_Version Control and Branch Management (Git)

## 1. Introduction and Instalation

Versioning adalah untuk mengatur versi dari source code yang dibuat (perubahan pada code).
Tool yang digunakan ada beberapa berikut ini seperti git bash, github, and visual studio code.
Ada 3 version control system:
1. Single user : hanya bisa 1 user
2. Centralized : komputer sudah mulai terpusat (beberapa komputer sudah terhubung)
3. Distributed : lokal antara server bisa terhubung secara langsung.

## 2. Setting Up and Push

Git Config membolehkan user untuk mendapatkan dan mengatur variabel-variabel pengaturan semua aspek 
Config global user dapat dilakukan dengan konfigurasi email serta password. 
Pertama membuat repository baru. Clone dapat dilakukan antara server dengan folder lokal di komputer
pribadi. GIT push: digunakan dalam mengirimkan perubahan file yang dilakukan setelah 
di commit ke remote repository.

#### Alur kerja dasar Git:

1. mengubah berkas dalam working directory.
2. Menyiapkan berkasnya, menambah snapshot darinya ke staging area.
3. Melakukan commit, yang mengambil berkas-berkas yang ada pada staging area dan menyimpan 
snapshot tersebut secara tetap ke dalam direktori Git.

## Branch And Conflict

Sebuah branch (cabang) di Git secara sederhana hanyalah pointer yang dapat bergerak ke salah
satu commit. Nama default dari branch dalam Git adalah master . Ketika membuat commit 
di awal, diberikan sebuah branch master yang menunjuk ke commit terakhir yang dibuat.

Saat melakukan merge, bisa saja terjadi konflik. Misalnya saat mengubah sesuatu di 
branch, developer lain melakukan perubahan juga pada branch main/master.
