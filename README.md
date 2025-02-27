# Linux Backup Script 🐧

Bu Bash script'i, Linux sistemlerinizdeki kritik dosyaları otomatik olarak yedekler, sıkıştırır ve eski yedekleri temizler. Ubuntu 22.04 LTS üzerinde test edilmiştir.

## 🚀 Özellikler
- **Zaman Damgalı Yedekler:** `backup_2023-10-05_14-30-00.tar.gz` gibi tarih formatı.
- **Loglama:** Tüm işlemler `/var/log/backup_script.log` dosyasına kaydedilir.
- **Otomatik Temizlik:** Belirlediğiniz günden (örneğin 7 gün) eski yedekler silinir.
- **Hata Yönetimi:** Klasör bulunamazsa veya sıkıştırma başarısız olursa script durur.

## 📦 Kurulum
1. Depoyu klonlayın:
   ```bash
   git clone https://github.com/bluecomputer37/linux-backup-script.git
   cd linux-backup-script
