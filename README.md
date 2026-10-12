# REBA Ergonomik Risk Analizi Programı

REBA (**Rapid Entire Body Assessment** - Hızlı Tüm Vücut Değerlendirmesi) metodolojisine dayalı, çalışma ortamlarındaki fiziksel ve ergonomik risk faktörlerini hesaplayan taşınabilir (**portable**) Windows masaüstü uygulamasıdır.

---

## Proje Hakkında

İş sağlığı ve güvenliği (İSG) ile endüstri mühendisliği alanlarında yaygın olarak kullanılan REBA analizi; çalışanların duruş, hareket, kuvvet ve kavrama koşullarını analiz ederek kas-iskelet sistemi rahatsızlıkları (MSD) riskini derecelendirir.

Bu yazılım; kullanıcı dostu bir arayüz ile görsel destekli duruş seçimlerini alır ve uluslararası REBA matris tablolarını (Tablo A, B ve C) kullanarak anlık olarak risk puanını ve gerekli aksiyon seviyesini hesaplar.

---

## Özellikler

- **A Grubu Duruş Analizi:** Boyun, Gövde ve Bacak pozisyonları + Yük/Kuvvet skoru.
- **B Grubu Duruş Analizi:** Üst Kol, Alt Kol ve Bilek pozisyonları + Kavrama (Kapma) kalitesi skoru.
- **Otomatik Matris Hesaplama:** Tablo A, B ve C matris eşleşmelerinin anlık hesaplanması.
- **Aktivite Skoru:** Tekrarlayan hareketler ve statik duruş faktörlerinin dahil edilmesi.
- **Risk Seviyesi & Eylem Planı:**
  - **1:** İhmal edilebilir risk
  - **2 - 3:** Düşük risk (Değişiklik gerekebilir)
  - **4 - 7:** Orta risk (İnceleme ve değişiklik gerekli)
  - **8 - 10:** Yüksek risk (Kısa süre içinde değişiklik gerekli)
  - **11+:** Çok yüksek risk (Derhal değişiklik gerekli)
- **Kurulumsuz (Portable):** Herhangi bir kurulum gerektirmez, doğrudan çift tıklayarak çalışır.

---

## Çalıştırma ve Kullanım

1. Repodaki veya son sürümdeki dosyaları indirin:
   - `RebaAnaliz.exe`
   - `RebaAnaliz.exe.config`
2. `RebaAnaliz.exe` dosyasına çift tıklayarak uygulamayı başlatın.
3. Çalışanın vücut açılarını ve duruş kriterlerini ilgili alanlardan seçin.
4. **Hesapla** butonuna basarak nihai REBA skorunu ve risk derecesini görüntüleyin.

---

## Sistem Gereksinimleri

- **İşletim Sistemi:** Windows 7 / 8 / 10 / 11
- **Platform:** .NET Framework 4.7.2 veya üzeri
- **Donanım:** Minimum 512 MB RAM, 10 MB boş disk alanı

---

## Lisans

Bu proje eğitim ve ergonomik risk analiz süreçlerini kolaylaştırmak amacıyla geliştirilmiştir.
