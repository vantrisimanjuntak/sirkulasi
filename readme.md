# Testing Push Pull Live

Repo ini sebagai catatan untuk melakukan git push/pull dari Github (dari branch dev ke main) ke Server tujuan

## Stack yang digunakan

* Almalinux 8
* Apache
* Virtualmin

## Langkah-langkah

1. Merge branch dev ke main
2. Dari panel Virtualmin, cari menu Schedule Cron Job - Create a New Schedule Cron Job
3. Di kolom Command isikan command berikut: 
```
cd /(lokasi folder yang ingin di pull dari Github) && git pull
```
4. Di bagian When to Execute, isikan time yang ingin di setting di Cronjob-nya
5. Klik Save 

Lalu silahkan di cek apakah website Anda sudah sesuai dengan yang ada di repo Github Anda.


