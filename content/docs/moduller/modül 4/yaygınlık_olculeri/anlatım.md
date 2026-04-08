---
title: "Anlatım"
date: 2026-04-07
draft: false
math: true
categories: ["Biyoistatistik", "Tıp"]
tags: ["Erciyes Üniversitesi", "Değişkenler", "Ölçüm Skalaları"]
---


# Yaygınlık Ölçüleri

#### Temel Tanım (1. Sınıf Seviyesi)

Merkezi yer ölçüleri (ortalama, medyan) bir veri setini tek başına tanımlamak için yeterli değildir. Örneğin, iki farklı hasta grubunun ortalama kalp hızı 80 bpm olabilir. Ancak ilk gruptaki hastaların nabzı 78 ile 82 arasında dar bir bantta seyrederken, ikinci gruptaki hastaların nabzı 40 ile 120 arasında dalgalanıyor olabilir. İşte verilerin birbirinden ne kadar farklılaştığını, yani merkezin etrafında nasıl yayıldığını gösteren değerlere **yaygınlık (değişkenlik) ölçüleri** denir.

---

#### Mekanizma ve Sınıflandırma

Verinin homojen veya heterojen yapısını değerlendirmek için dört temel ölçüt kullanılır:

- **Dağılım Aralığı (Range):** Veri setindeki en büyük değer ile en küçük değer arasındaki farktır. Hesaplaması çok basittir ancak tek bir aşırı değer bile sonucu tamamen bozabilir (örneğin tek bir hastanın çok yüksek çıkması).
    
    - Formülü: $X_{max}-X_{min}$
        
- **Çeyrekler Arası Uzaklık (IQR - Interquartile Range):** Veri setini 4 eşit parçaya bölen çeyrekliklerden, 1. ve 3. çeyreklik arasındaki mesafeyi ölçer. Aşırı değerlerden (outliers) etkilenmeyen, **dirençli (robust)** bir ölçüdür. Genellikle medyan ile birlikte raporlanır.
    
    - Formülü: $IQR=Q_{3/4}-Q_{1/4}$
        
- **Varyans ve Standart Sapma:** İstatistikte en çok kullanılan yaygınlık ölçüleridir. Tüm gözlemler formüle dahil edildiği için aritmetik ortalama ile birlikte sunulurlar. Standart sapma ($s$), varyansın ($s^{2}$) kareköküdür. Standart sapma 0'a ne kadar yakınsa veri o kadar homojen, ne kadar büyükse o kadar heterojendir.
    
    - Örneklem Standart Sapma Formülü: $s=\sqrt{\frac{\sum_{i=1}^{n}(X_{i}-\overline{X})^{2}}{n-1}}$
        
- **Değişim Katsayısı (CV - Coefficient of Variation):** Gözlem sayıları ve ölçüm birimleri farklı olan değişkenlerin yayılımlarını karşılaştırmak için kullanılır. Birimi yoktur, yüzde (%) ile ifade edilir.
    
    - Formülü: $DK\%=\frac{s}{\overline{x}}\times 100$
        
    - **Yorumu:** $CV < \%10$ ise veri homojen, $\%10 \le CV < \%20$ ise orta/kabul edilebilir, $CV \ge \%20$ ise heterojendir.
        

---

#### Klinik Uygulama (Stajyer/İntern Seviyesi)

- **Laboratuvar Referans Aralıkları (Standart Sapma):** Hastanedeki tüm laboratuvar tetkiklerinin (örn. Hemoglobin: 12-16 g/dL) "normal" referans aralıkları, sağlıklı popülasyonun ortalamasından **$\pm 2$ Standart Sapma** alınarak belirlenir. Bu, sağlıklı insanların yaklaşık %95'ini kapsar. Kalan %5 ise tamamen sağlıklı olmasına rağmen "anormal" laboratuvar sonucuna sahip olabilir.
    
- **Aykırı Değer/Outlier Tespiti (IQR):** Kutu grafikleri (Box-plot) kullanılarak klinik çalışmalarda ekstrem vakalar (örn. dev doz antibiyotik gereken sıra dışı hastalar) tespit edilir. Bir hastanın değeri alt sınır olan $Q_{1/4}-1.5\times IQR$'dan küçükse veya üst sınır olan $Q_{3/4}+1.5\times IQR$'dan büyükse, o hasta klinik olarak "aykırı/ekstrem" kabul edilir.
    
- **Tıbbi Cihaz Kalibrasyonu (Değişim Katsayısı):** Yoğun bakımda kullanılan iki farklı kan gazı cihazının hangisinin daha güvenilir olduğunu belirlemek için CV'ye bakılır. CV'si %10'dan küçük olan cihaz daha tutarlı ve homojen (güvenilir) ölçüm yapıyor demektir.
    

---

#### Yüksek Verimli (High-Yield) Notlar

Komite ve TUS/USMLE sınavlarında yaygınlık ölçüleriyle ilgili gelen klasik tuzaklar şunlardır:

- **Tuzak 1:** Çeyrekler arası uzaklık (IQR) aşırı uç değerlere karşı _dirençliyken_, dağılım aralığı (Range) ve standart sapma aşırı uçlardan etkilenir. Eğer soruda "aşırı uçlardan etkilenmeyen yaygınlık ölçüsü" soruluyorsa cevap IQR'dır.
    
- **Tuzak 2 (68-95-99 Kuralı):** Normal dağılan bir popülasyonda gözlemlerin;
    
    - Yaklaşık **%68.26'sı** $\mu \pm 1\sigma$ (Ortalama $\pm$ 1 Standart Sapma) arasındadır.
        
    - Yaklaşık **%95.44'ü** $\mu \pm 2\sigma$ arasındadır.
        
    - Yaklaşık **%99.70'i** $\mu \pm 3\sigma$ arasındadır.
        
- **Tuzak 3 (Standart Sapma vs. Standart Hata):** Sınavlarda en sık karıştırılan kavramdır. Standart sapma örneklemdeki bireylerin yayılımını ölçer. Standart hata (SE) ise örneklem ortalamasının, tüm popülasyonun (evrenin) gerçek ortalamasını ne kadar iyi tahmin ettiğini gösterir. Örneklem büyüklüğü ($n$) arttıkça standart hata **küçülür**.
    