# RGB Kontrol Web Sunucusu

Bu proje, ESP32 mikrodenetleyici kullanarak bir RGB LED'in renklerini bir web tarayıcı üzerinden kontrol etmek için basit bir örnektir.

## Bağlantılar
- Kırmızı LED Pin: GPIO 23
- Yeşil LED Pin: GPIO 22
- Mavi LED Pin: GPIO 21

## Kurulum
1. Arduino IDE'yi açın.
2. Gerekli kütüphaneleri yükleyin (WiFi, WebServer).
3. WiFi bağlantı bilgilerinizi `ssid` ve `password` değişkenlerine ekleyin.
4. Kodu ESP32 kartınıza yükleyin.

## Kullanım
1. ESP32'yi güç kaynağına bağlayın ve WiFi ağına bağlanmasını bekleyin.
2. ESP32'nin IP adresini seri monitörden kontrol edin.
3. Tarayıcınızı açın ve ESP32'nin IP adresini ziyaret edin (örneğin, `http://192.168.1.100`).
4. Renk paleti üzerinden RGB LED'in renklerini kontrol edin.

## Notlar
- Renkleri kontrol etmek için web tarayıcısı üzerinden paleti kullanın.
- Konsol çıktısı üzerinden RGB değerlerini takip edin.
