# Hisse Senedi LSTM ile Fiyat Tahmini Projesi

Bu proje, LSTM (Uzun Kısa Süreli Bellek Ağı) kullanarak hisse senedi fiyatlarını tahmin etmek için bir model oluşturmayı amaçlamaktadır. Ayrıca modelin tahminlerini değerlendirmek ve fiyat düşüşü tahminlerini anlamlandırmak için çeşitli teknik indikatörler de kullanılacaktır.

## Adımlar

1. **Veri Setinin Yüklenmesi ve Eksik Veri Kontrolü**: `yfinance` kütüphanesi kullanılarak hisse senedi verileri yüklenecek ve eksik veriler kontrol edilecek.

2. **Verilerin Ölçeklendirilmesi**: Veriler, LSTM modeline beslenmeden önce ölçeklendirilecek.

3. **Veri Setinin Model İçin Hazırlanması**: Giriş ve çıkış verileri belirlenecek ve veriler eğitim, doğrulama ve test kümelerine ayrılacak.

4. **Çok Katmanlı LSTM Modelinin Oluşturulması**: Keras ve TensorFlow kullanılarak LSTM modeli oluşturulacak.

5. **Modelin Eğitimi ve Geçerlilik İzlemesi**: Oluşturulan model eğitilecek ve eğitim sırasında doğruluk ve kayıp izlenecek.

6. **Model Performansının Değerlendirilmesi**: Modelin performansı eğitim ve doğrulama setleri üzerinde değerlendirilecek.

7. **Gerçek ve Tahmin Edilen Fiyatların Görselleştirilmesi**: Gerçek ve tahmin edilen fiyatlar görselleştirilecek.

8. **Gelecekteki Fiyat Tahminleri**: Eğitilmiş model kullanılarak gelecekteki fiyatlar tahmin edilecek.

9. **Teknik İndikatörlerin Kullanılması ve Analizi**: RSI, Bollinger Bantları, Ichimoku İndikatörü gibi teknik indikatörler hesaplanacak ve modelin fiyat düşüşü tahminindeki rolü analiz edilecek.

Geliştiren : HÜSEYİN EROL
Kişisel websitem : https://huseyineroll.com/
Github : https://github.com/HuseyinErol24