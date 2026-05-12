# 🔑 Hash Table: Linear & Quadratic Probing Analysis

Bu proje, bir **Hash Tablosu (Karma Tablo)** yapısı üzerinde veri depolama ve çakışma durumlarında kullanılan **Doğrusal Yoklama (Linear Probing)** ve **Karesel Yoklama (Quadratic Probing)** yöntemlerinin işleyişini incelemek amacıyla geliştirilmiş bir **C# konsol uygulamasıdır**.

---

## 🛠️ Teknik Özellikler
- 💻 **Dil:** C#  
- 🏗️ **Geliştirme Ortamı:** Visual Studio  
- 📊 **Veri Yapısı:** Hash Table (Open Addressing)  
- ⚙️ **Algoritmalar:** Linear Probing & Quadratic Probing  
- 🎯 **Hash Fonksiyonu:** Division Method (Bölme Yöntemi)  

---

## 📁 Proje Yapısı
```plaintext
Linear-QuadraticProbing-Hash-Tablosu-master/
├── Program.cs              # Ana uygulama mantığı ve HashTable sınıfı
├── App.config              # Uygulama yapılandırma dosyası
├── Ödev10.csproj           # Proje yapılandırma dosyası
├── Ödev10.sln              # Visual Studio çözüm dosyası
├── LICENSE                 # Lisans bilgileri
└── README.md               # Proje dökümantasyonu
```
---
## 🎯 Öne Çıkan İşlevler
- 🔄 **Çakışma Yönetimi**  
  - **Linear Probing:** Çakışma durumunda bir sonraki boş indeksi doğrusal olarak *(index + 1)* arar.  
  - **Quadratic Probing:** Çakışma durumunda kareli bir artışla *(index + i²)* yeni bir yer arayarak kümelenmeyi azaltır.  

- 🎲 **Rastgele Veri Üretimi**  
  1 ile 200 arasında rastgele anahtarlar üreterek tabloları dinamik olarak doldurur.  

- 📋 **Görselleştirme**  
  Her iki yöntemin sonuçlarını konsol ekranında indeks bazlı olarak listeler.  

---

## 💡 Kazanımlar
- 🧠 Hash Tablosu mantığının derinlemesine anlaşılması  
- 📉 Linear vs Quadratic Probing arasındaki performans ve kümelenme farklarının gözlemlenmesi  
- 🔢 Division Method ile indeks hesaplama ve modüler aritmetik kullanımı  

---
## 🚀 Kurulum ve Kullanım

1.  📥 Projeyi klonlayın:
    ```bash
    git clone https://github.com/kullaniciadi/Linear-QuadraticProbing-Hash-Tablosu.git
    ```
2.  📂 Visual Studio ile `Ödev10.sln` dosyasını açın.
3.  ▶️ Projeyi derleyin ve çalıştırın.
4.  🖥️ Konsol çıktısında her iki yöntemin hash tablosu üzerindeki dağılımını inceleyin.

## 📜 Lisans

Bu proje **MIT License** ile lisanslanmıştır. Detaylı bilgi için `LICENSE` dosyasını inceleyebilirsiniz.

## 👩‍💻 Geliştirici

Şilan Pehlivan



