# 🛠️ Arıza Takip / Teknik Destek Paneli

Bu proje, teknik destek süreçlerini ve arıza kayıtlarını takip etmek amacıyla geliştirilmiş bir React Native (Expo Router) mobil uygulamasıdır. Laboratuvar çalışmalarının aşamalı olarak geliştirilmesiyle son haline getirilmiştir.

## 📌 Geliştirme Süreci ve İlk Hal Durumu

### 1. Aşama (İlk Sürüm)
- **Başlangıç:** Projenin temel iskeleti ve temel sayfa yapısı kuruldu.
- **Temel Özellikler:** Arıza kayıtlarının statik verilerle listelenmesi ve basit bir arayüz tasarımı hedeflendi.
- **Git ve Versiyon Kontrolü:** Proje ilk olarak yerel depoda başlatıldı ve GitHub üzerinde (`ariza-takip` / `TeknikDestekPaneli`) versiyonlandı.

### 2. Son Aşama (Gelişmiş Sürüm)
- **Dinamik Yönlendirme:** Expo Router ile `[id].jsx` yapısı entegre edilerek her arızanın detay sayfasına dinamik geçiş sağlandı.
- **Hata Yönetimi (Error Handling):** Geçersiz veya sistemde bulunmayan arıza ID'leri için kullanıcı dostu bir hata ekranı ve geri dönüş butonları eklendi.
- **Arayüz İyileştirmeleri:** Kart bileşenleri, rozetler ve modern bir renk paletiyle kullanıcı deneyimi zenginleştirildi.

## 🚀 Öne Çıkan Özellikler
- **Arıza Listeleme:** Bildirilen arızaların ve durumlarının düzenli listelenmesi.
- **Detay Sayfası:** `[id].jsx` ile her kaydın detayına erişim.
- **Kapsamlı Hata Yönetimi:** Bulunamayan kayıtlar için uyarı ekranları.

## 🛠️ Kullanılan Teknolojiler
- React Native
- Expo Router
- JavaScript (ES6+)
- Git & GitHub