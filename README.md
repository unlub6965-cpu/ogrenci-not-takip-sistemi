# Öğrenci Not Takip Sistemi

Bu proje KUZEM Python Eğitimi Final Projesi kapsamında geliştirilmiş bağımsız bir konsol uygulamasıdır.

## Özellikler
- **OOP Mimarisi:** `Ogrenci` ve `NotSistemi` sınıfları.
- **Kalıcı Veri:** Öğrenci ve not bilgileri `ogrenciler.json` dosyasına JSON formatında kaydedilir.
- **Hata Yönetimi:** Dosya okuma (`FileNotFoundError`, `JSONDecodeError`) ve not girişlerinde hatalı karakter (`ValueError`) yakalanır.
- **CRUD & Arama:** Öğrenci ekleme, listeleme, arama ve silme işlemleri.
- **Raporlama:** Sınıf ortalaması, geçen/kalan sayısı özeti.

## Çalıştırma
```bash
python main.py
