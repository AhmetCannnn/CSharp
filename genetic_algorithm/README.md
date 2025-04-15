# Genetik Algoritma Projesi

## Proje Açıklaması
Bu proje, iki değişkenli bir optimizasyon problemi çözmek için genetik algoritma kullanmaktadır. Windows Forms uygulaması olarak geliştirilmiştir.

## Hedef Fonksiyon
f(x, y) = (x + 2y - 7)² + (2x + y - 5)²

## Kısıtlar
- -10 ≤ x ≤ 10
- -10 ≤ y ≤ 10

## Kullanılan Teknolojiler
- C#
- Windows Forms
- .NET Framework

## Proje Yapısı
- `Birey.cs`: Birey sınıfı ve fitness hesaplama
- `Populasyon.cs`: Popülasyon yönetimi ve genetik operatörler
- `GenetikAlgoritma.cs`: Genetik algoritma mantığı
- `Form1.cs`: Kullanıcı arayüzü

## Kurulum
1. Visual Studio'yu yükleyin
2. Projeyi klonlayın
3. Solution'ı açın
4. Projeyi derleyin

## Kullanım
1. Popülasyon boyutunu girin
2. Çaprazlama, mutasyon ve seçkinlik oranlarını ayarlayın
3. "Başlangıç Popülasyonu" butonuna tıklayın
4. Doğal seçim, çaprazlama ve mutasyon işlemlerini sırayla uygulayın
5. En iyi bireyi görmek için "Genetik Algoritma" butonuna tıklayın

## Genetik Operatörler
- **Doğal Seçim**: Turnuva seçimi ile en iyi bireylerin seçilmesi
- **Çaprazlama**: İki bireyin genlerinin birleştirilmesi
- **Mutasyon**: Bireylerin genlerinin rastgele değiştirilmesi

## Lisans
Bu proje MIT lisansı altında lisanslanmıştır. 