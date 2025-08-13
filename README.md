# Yüz Ağları (Face Mesh) Projesi

[🇬🇧 English](README_EN.md) | [🇹🇷 Türkçe](README.md)

Bu proje, MediaPipe kullanarak yüz ağları tespiti ve analizi yapan bir Python uygulamasıdır.

## 🚀 Özellikler

- **Gerçek Zamanlı Yüz Tespiti**: Video akışında yüz ağları tespiti
- **468 Yüz Noktası**: MediaPipe'ın gelişmiş yüz landmark sistemi
- **FPS Göstergesi**: Performans takibi için FPS sayacı
- **Video Desteği**: MP4, AVI ve diğer video formatları desteği

## 📋 Gereksinimler

```bash
pip install opencv-python
pip install mediapipe
```

## 🎯 Kullanım

1. Projeyi klonlayın:
```bash
git clone https://github.com/Semihkulekcioglu/yuz_aglari_face_mesh.git
cd yuz_aglari_face_mesh
```

2. Gerekli kütüphaneleri yükleyin:
```bash
pip install -r requirements.txt
```

3. Programı çalıştırın:
```bash
python "Yuz_aglari(Face_mesh).py"
```

## 📁 Proje Yapısı

```
Yüz Ağları/
├── Yuz_aglari(Face_mesh).py    # Ana program dosyası
├── video1.mp4                  # Test video dosyası
├── video2.mp4                  # Test video dosyası
├── video3.mp4                  # Test video dosyası
├── Results/                     # Sonuç görüntüleri
│   ├── Result_1.png
│   └── Result_2.png
├── README.md                   # Türkçe açıklama
├── README_EN.md               # İngilizce açıklama
├── requirements.txt            # Python bağımlılıkları
└── .gitignore                 # Git ignore dosyası
```

## 🔧 Özelleştirme

- **Video Kaynağı**: `cap = cv2.VideoCapture("video2.mp4")` satırındaki dosya adını değiştirin
- **Yüz Sayısı**: `max_num_faces = 1` parametresini değiştirerek birden fazla yüz tespit edebilirsiniz
- **Çizim Stili**: `drawSpec` parametrelerini değiştirerek görsel stil ayarlayabilirsiniz

## 📸 Ekran Görüntüleri

Program çalıştığında:
- Yüz ağları gerçek zamanlı olarak çizilir
- Her yüz noktasının koordinatları konsola yazdırılır
- FPS değeri ekranın sol üst köşesinde gösterilir

## 🤝 Katkıda Bulunma

1. Bu repository'yi fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/yeni-ozellik`)
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/yeni-ozellik`)
5. Pull Request oluşturun

## Screenshot 
<img width="640" height="640" alt="Result_2" src="https://github.com/user-attachments/assets/cd724d27-4eed-4563-8d96-5d73efcf85fa" />

## 📝 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

## 📞 İletişim

Sorularınız için issue açabilir veya pull request gönderebilirsiniz.

---

**Not**: Bu proje MediaPipe ve OpenCV kütüphanelerini kullanmaktadır. Daha fazla bilgi için [MediaPipe Dokümantasyonu](https://mediapipe.dev/) ve [OpenCV Dokümantasyonu](https://opencv.org/) sayfalarını ziyaret edin.
