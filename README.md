# Weather-Card# Hava Durumu Kartı

Bu proje, **OpenWeatherMap API** kullanarak güncel hava durumu bilgisini çekip Tailwind CSS ile hazırlanmış kart tasarımında göstermektedir.

## Özellikler

* Konum adı (şehir)
* Tarih (gün, ay, hafta günü)
* Sıcaklık (°C) ve hava durumu ikonu
* Nem oranı (Humidity)
* Görüş mesafesi (Visibility)
* Hava basıncı (Air Pressure)
* Rüzgar hızı (Wind)

## Kullanılan Teknolojiler

* **HTML5**
* **Vanilla JavaScript (fetch API)**
* **Tailwind CSS**
* **OpenWeatherMap API**

## Kurulum ve Çalıştırma

1. Depoyu bilgisayarınıza klonlayın veya ZIP olarak indirin.
2. Projeyi bir editörde açın (VS Code önerilir).
3. `index.html` dosyasını bir tarayıcıda açın.
4. Hava durumu bilgisi otomatik olarak yüklenecektir.

## API Bilgisi

Proje, OpenWeatherMap API üzerinden veri almaktadır.

* API URL:

  ```
  https://api.openweathermap.org/data/2.5/weather?lat=40.9882728&lon=29.0343543&appid=YOUR_API_KEY&units=metric&lang=tr
  ```
* `lat` ve `lon`: Lokasyon koordinatları
* `appid`: OpenWeatherMap API key
* `units=metric`: °C biriminde sıcaklık bilgisi
* `lang=tr`: Türkçe dil desteği

## Ekran Görüntüsü

![Hava Durumu Kartı](./screenshot.png)

## Notlar

* Varsayılan olarak İstanbul (lat: 40.9882728, lon: 29.0343543) konumu için veri çekilmektedir.
* API anahtarınızı almak için: [OpenWeatherMap](https://openweathermap.org/) sitesine kayıt olun.
* Tasarım, Figma dosyasında belirtilen kart görünümüne uygun şekilde hazırlanmıştır.
