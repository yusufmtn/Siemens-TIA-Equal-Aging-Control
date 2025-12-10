# Siemens-TIA-Equal-Aging-Control
# 🚀 TIA Portal SCL - Equal Aging Motor Control (Eş Yaşlandırma)

Bu proje, endüstriyel pompa ve fan grupları için Siemens TIA Portal V17 kullanılarak geliştirilmiş gelişmiş bir **Eş Yaşlandırma (Equal Aging)** algoritmasıdır.

## 🎯 Projenin Amacı
Birden fazla motorun çalışma saatlerini birbirine eşitleyerek bakım ömürlerini uzatmak ve sistemin duruşunu engellemektir.

## 🛠️ Özellikler
- **Sıralı Çalışma (Sequential Start):** Motorlar şebekeye yüklenmemesi için 3 saniye (ayarlanabilir) gecikmeyle devreye girer.
- **Zorunlu Rotasyon (Forced Rotation):** Ayarlanan süre (Örn: 10 saat) dolduğunda, en çok çalışan motor otomatik durdurulur ve en az çalışan devreye alınır.
- **Kapasite Kontrolü:** İstenen motor sayısı, eldeki sağlam motor sayısını geçerse sistem otomatik limit koyar ve uyarı verir.
- **SCL Algoritması:** Tüm mantık `FOR` döngüleri ve `Array` yapıları kullanılarak SCL dilinde yazılmıştır.


## 💻 Kullanılan Teknolojiler
- **Yazılım:** Siemens TIA Portal V15 / PLCSIM
- **PLC:** S7-1200 / 1214C DC/DC/DC
- **Dil:** SCL (Structured Control Language)

## 📥 Kurulum
Proje dosyasını (`.zap17`) indirip TIA Portal üzerinden "Retrieve" seçeneği ile açabilirsiniz.
