# COVID-19 ve Grip Genomlarının Makine Öğrenmesi ile Sınıflandırılması

## Proje Özeti
Bu proje, COVID-19 ve Grip genom dizilerini kullanarak bir makine öğrenmesi modeli geliştirmeyi amaçlamaktadır. Model, nükleotit dizilerini sınıflandırarak hangi dizinin hangi virüse ait olduğunu belirlemektedir.

## Veri Kaynakları
- **Grip (Influenza A)**: [NCBI Virus Resource](https://www.ncbi.nlm.nih.gov/labs/virus/)
- **COVID-19 (SARS-CoV-2)**: [NCBI Virus Resource](https://www.ncbi.nlm.nih.gov/labs/virus/)

## Kullanılan Yöntemler
- Veri okuma ve temizleme
- Nükleotit dizilerini sayısal formata dönüştürme
- Random Forest sınıflandırıcı ile model eğitimi
- Model değerlendirmesi ve görselleştirmeler

## Çalıştırma Talimatları
1. Gerekli kütüphaneleri `requirements.txt` dosyasından yükleyin:
   ```bash
   pip install -r requirements.txt
