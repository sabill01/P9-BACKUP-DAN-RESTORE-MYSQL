# README - Backup & Restore Database Perikanan

## PERINTAH INTI

Backup:
mysqldump -u root perikanan > C:\backup\perikanan_backup.sql

Restore:
mysql -u root perikanan < C:\backup\perikanan_backup.sql

Verifikasi:
mysql -u root -e "USE perikanan; SHOW TABLES;"

---

## HASIL

Backup: Berhasil
Restore: Berhasil
Jumlah Tabel: 9 tabel

---

## LANGKAH CEPAT

1. cd C:\xampp\mysql\bin
2. mkdir C:\backup
3. mysqldump -u root perikanan > C:\backup\perikanan_backup.sql
4. mysql -u root perikanan < C:\backup\perikanan_backup.sql

---

## KESIMPULAN

Backup dan restore database perikanan berhasil 100%

---

