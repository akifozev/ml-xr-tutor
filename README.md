# 🧠 ML XR Tutor

**Neural Network'leri 3D Sanal Gerçeklikte Öğren**

Google'ın [Vibe Coding XR](https://research.google/blog/vibe-coding-xr-accelerating-ai-xr-prototyping-with-xr-blocks-and-gemini/) çalışmasından ilham alınarak oluşturulmuş, makine öğrenmesi algoritmalarını XR/VR ortamında 3D olarak görselleştiren interaktif eğitim aracı.

> 🔗 **Canlı Demo:** [silver-empanada-02cc3d.netlify.app](https://silver-empanada-02cc3d.netlify.app/)

---

## ✨ Özellikler

- **3D Neural Network Arka Plan** — Canlı nöron animasyonları, parçacık akışı ve sürekli forward propagation
- **6 Eğitim Modülü** — Her biri XR Blocks Gem'e hazır prompt ile
- **Interaktif Önizleme** — Her modülün Three.js ile 3D önizlemesi
- **XR-Ready Prompt'lar** — Kopyala-yapıştır ile Gemini Canvas'ta çalıştır

## 📚 Modüller

| Modül | Seviye | Açıklama |
|-------|--------|----------|
| 🧠 Nöron ve Katmanlar | Temel | Tek nöronun iç yapısı, ağırlıklar, bias, aktivasyon |
| ⚡ Forward Propagation | Orta | Veri akışı, matris çarpım, katman geçişleri |
| 🔄 Backpropagation | İleri | Hata geri yayılımı, zincir kuralı, gradyan hesaplama |
| 📉 Loss Landscape | İleri | 3D loss yüzeyi, SGD vs Momentum vs Adam |
| 🎯 Aktivasyon Fonksiyonları | Orta | ReLU, Sigmoid, Tanh, Leaky ReLU karşılaştırması |
| 🏗️ CNN Filtre Görselleştirme | İleri | Konvolüsyon, feature map, max pooling |

## 🚀 Nasıl Kullanılır

### Web Demo
Siteyi ziyaret edin: [Canlı Demo](https://silver-empanada-02cc3d.netlify.app/)

### XR Blocks ile
1. [gemini.google.com](https://gemini.google.com) → XR Blocks Gem'i aç → Pro Mode seç
2. Sitede bir modüle tıkla → "Kopyala" butonuna bas
3. Prompt'u Gemini Canvas'a yapıştır
4. Masaüstünde test et veya Android XR başlığa deploy et

### Lokal Çalıştırma
```bash
git clone https://github.com/akifozev/ml-xr-tutor.git
cd ml-xr-tutor
# Herhangi bir HTTP sunucu ile aç
npx serve .
# veya
python -m http.server 8080
```

## 🛠️ Teknolojiler

- **Three.js** — 3D görselleştirme ve animasyonlar
- **WebXR API** — VR/AR cihaz desteği
- **XR Blocks** — Google'ın açık kaynak WebXR framework'ü
- **Gemini** — AI destekli XR kod üretimi
- **Netlify** — Hosting

## 🎯 İlham

Google Research'ün Mart 2026'da yayınladığı [Vibe Coding XR](https://research.google/blog/vibe-coding-xr-accelerating-ai-xr-prototyping-with-xr-blocks-and-gemini/) çalışması, doğal dilde yazılan prompt'ları 60 saniyede interaktif WebXR uygulamalarına dönüştürüyor. Matematik öğreticisi örneğinden yola çıkarak aynı yaklaşımı makine öğrenmesi eğitimi için uyguladım.

## 📄 Lisans

MIT License

## 🔗 Bağlantılar

- [XR Blocks Framework](https://github.com/google/xrblocks)
- [XR Blocks Gem](https://xrblocks.github.io/gem/)
- [Google Research Blog](https://research.google/blog/vibe-coding-xr-accelerating-ai-xr-prototyping-with-xr-blocks-and-gemini/)
- [Vibe Coding XR Paper (arXiv)](https://arxiv.org/html/2603.24591v1)
