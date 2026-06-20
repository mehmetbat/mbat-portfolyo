# Güncelleme Notları

## 2026-06-20

### Yeni Projeler (+4)
- **Aylin Kuru Saç Ekimi** (filtre: "Aylin Kuru")
- **UMKE-DER**
- **Afet Psikolojisi Platformu** (filtre: "Afet Psikolojisi")
- **Koçtaş Fabel** için gerçek kapak görseli eklendi (önceden ilk ekranı fallback olarak kullanıyordu)

> Toplam proje sayısı: **43**

### Görseller
- Yeni eklenen tüm görseller WebP'ye çevrildi (q85) — kapaklar ~3-5 KB, ekran görselleri ~456-481 KB
- Tüm referanslar (kart + JSON) WebP'ye işaret ediyor

### Arayüz / Layout
- **Toolbar yeniden düzenlendi:** arama çubuğu üstte tek satır, tam genişlik
- **Filtre butonları** altta; `flex-grow` ile her satır eşit dolacak şekilde dağıtıldı (büyük boşluk yok), iki yana dayalı
- Ana açıklama metni iki yana yaslı (justify) yapıldı
- Filtre satırı responsive: dar ekranda doğal kayar, ≤560px'de yatay kaydırmalı şeride döner

### Önceki Sürümden Beri (özet)
- Logo: "BAT" monogramı (Anton fontu, siyah badge) — batman logosu kaldırıldı
- Üst sağ: "Bizimle çalış" CTA + slogan
- Dijital danışmanlık bölümü: iki açıklayıcı kart + tek satır iletişim
- Tüm görseller WebP (toplam ~81 MB → ~12 MB)

### Yayın Notu
- Site statik; `index.html` + ilgili klasörler olduğu gibi host'a yüklenebilir
- Orijinal jpg/png kaynaklar repoda yok (lokal yedek); site WebP kullanıyor
