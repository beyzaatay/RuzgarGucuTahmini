# Türbülans Verileriyle Rüzgar Türbinlerinden Dinamik Güç Tahmini

Derin Öğrenme Yöntemleri ile Rüzgar Gücü Tahmini

## Proje Özeti
Bu proje, yenilenebilir enerji kaynaklarının verimli kullanımını artırmak amacıyla geliştirilmiştir. İstanbul'un yedi farklı bölgesinden toplanan meteorolojik veriler kullanılarak rüzgar gücü tahmin modelleri oluşturulmuştur. Yapay zeka ve derin öğrenme yöntemleri ile türbülans etkileri entegre edilerek dinamik ve sürdürülebilir bir tahmin sistemi tasarlanmıştır.

## Amaç ve Yöntem
- **Amaç**: Rüzgar gücü tahminlerini daha doğru ve sürdürülebilir bir şekilde yapmak.
- **Yöntemler**:
  - CNN ve LSTM modelleri kullanılarak hem zamansal hem mekânsal analizler gerçekleştirilmiştir.
  - Türbülans etkilerini hesaplamak için Eddy Diffusivity, Monin-Obukhov Uzunluğu, Türbülans Yoğunluğu ve Rüzgar Kayması ölçütleri kullanılmıştır.
  - Öznitelik seçimi ile modelin dinamikliği artırılmıştır.

## Model Performansı
- CNN modeli ile R² skoru **0.999** olarak elde edilmiştir.
- Modeller enerji verimliliği, işlem maliyeti ve doğruluk kriterlerine göre değerlendirilmiştir.

## Kullanılan Teknolojiler
- **Programlama Dili**: Python
- **Kütüphaneler**: TensorFlow, Keras, NumPy, Pandas
- **Platform**: Yüksek işlem kapasiteli bilgisayarlar


