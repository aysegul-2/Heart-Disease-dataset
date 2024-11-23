## Kalp Hastalığı Tahmini Modeli

Bu repo, kalp hastalığı riskini belirlemek için makine öğrenimi yöntemleri kullanan bir proje sunmaktadır. Lojistik regresyon ve karar ağacı algoritmaları kullanılarak geliştirilen modeller, kalp hastalığı varlığına dair tahminler yapmaktadır.

----

## Veri seti

UCI Machine Learning Repository'den elde edilen kalp hastalığı veri seti kullanılmıştır. Bu veri seti, hastanın yaş, cinsiyet, kolesterol seviyesi gibi çeşitli özelliklerini içermektedir.

-  **age**
-  **sex**
-  **chest pain type (4 values)**
-  **resting blood pressure**
-  **serum cholestoral in mg/dl**
-  **fasting blood sugar > 120 mg/dl**
-  **resting electrocardiographic results (values 0,1,2)**
-  **maximum heart rate achieved**
-  **exercise induced angina**
-  **oldpeak = ST depression induced by exercise relative to rest**
-  **the slope of the peak exercise ST segment**
-  **number of major vessels (0-3) colored by flourosopy**
-  **thal: 0 = normal; 1 = fixed defect; 2 = reversable defect**

Veri seti şu kaynaktan alınmıştır. :**Kaggle**.



## Projenin Özellikleri

* **Amaç:** Kalp hastalığı riskini belirlemek için makine öğrenimi modelleri geliştirmek.
* **Veri Seti:** UCI Machine Learning Repository'den alınan kalp hastalığı veri seti kullanılmıştır.
* **Modeller:** Lojistik Regresyon ve Karar Ağacı
* **Değerlendirme:** Model performansı, doğruluk oranı, karmaşıklık matrisi gibi metriklerle değerlendirilmiştir.


  ## Kullanılan Kütüphaneler
* **NumPy:** N-boyutlu dizi işlemleri için kullanılır.
* **Pandas:** Veri analizini kolaylaştıran güçlü bir veri çerçevesi kütüphanesidir.
* **Scikit-learn:** Makine öğrenimi algoritmalarının uygulanması için kapsamlı bir kütüphanedir.
* **Matplotlib:** Verileri görselleştirmek için kullanılır.

## Nasıl Çalıştırılır
1. **Veri setini indir:** `heart.csv` dosyasını indir ve aynı klasöre yerleştir.
2. **Jupyter Notebook:** Tüm kodları buraya yapıştır.
3. **Kodları çalıştır:** Her bir hücreyi sırayla çalıştır.

## Sonuçlar
* **Lojistik Regresyon:** %0.79 doğruluk oranı elde edilmiştir.Karmaşıklık matrisi, modelin hangi durumlarda daha fazla hata yaptığına dair bilgi vermektedir.
* **Karar Ağacı:** % 0.99 doğruluk oranı elde edilmiştir.Karar ağacı görselleştirmesi, modelin karar verme sürecinin nasıl olduğunu göstermektedir.


## Görselleştirmeler
Bu proje aşağıdaki görselleştirmeleri oluşturur:
1. Karmaşıklık Matrisi: Modelin performansını değerlendirir.
2. Karar Ağaçları : Karar ağaçlarının anlaşılmasını kolaylaştırmak için kullanılan bir görselleştirme tekniğidir.



## Lisans
Bu proje MIT Lisansı altında alınmıştır.

## Katkıda Bulun
Proje geliştirmek için çekinmeden Pull Request gönderebilirsiniz.


