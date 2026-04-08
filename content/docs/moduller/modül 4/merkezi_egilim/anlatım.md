---
title: "Anlatım"
date: 2026-04-07
draft: false
math: true
categories: ["Biyoistatistik", "Tıp"]
tags: ["Erciyes Üniversitesi", "Değişkenler", "Ölçüm Skalaları"]
---


# Merkezi Eğilim (Yer Ölçüleri)

#### Temel Tanım (1. Sınıf Seviyesi)

Merkezi yer ölçüleri; elde bulunan karmaşık bir veri setinin merkezinde toplanma eğilimini gösteren ve tüm veriyi tek bir "tipik" değer ile tanıtan istatistiklerdir. Kısacası, "Bu veri grubunun genel durumunu tek bir sayıyla ifade etmem gerekseydi, bu sayı ne olurdu?" sorusunun cevabıdır.

---

#### Mekanizma ve Sınıflandırma

Yer ölçüleri, verinin türüne ve dağılımına göre farklı şekillerde hesaplanır ve kategorize edilir.

- **Aritmetik Ortalama (Mean):** Veri setindeki bütün gözlem değerlerinin toplanıp gözlem sayısına bölünmesiyle elde edilir. Tüm gözlemler hesaplamaya dahil edilir.
    
    - Örneklem aritmetik ortalaması şu şekilde ifade edilir: $\overline{x}=\frac{\sum_{i=1}^{n}x_{i}}{n}$
        
- **Ortanca (Medyan):** Veriler küçükten büyüğe sıralandığında, veri setini tam iki eşit parçaya bölen ortadaki gözlem değeridir. Formülasyondan ziyade sıralamadaki pozisyona dayanır.
    
- **Tepe Değeri (Mod):** Bir veri setinde frekansı en yüksek olan, yani en çok tekrarlanan gözlem değeridir. Bazı verilerde hiç mod bulunmayabilirken, bazıları birden fazla moda (çok modlu / multimodal) sahip olabilir.
    
- **Geometrik Ortalama:** Veri setindeki $n$ adet elemanın çarpımının, $n$. dereceden kökünün alınmasıyla elde edilir. Logaritmik değişimleri ifade etmek için idealdir.
    
    - Formülü: $G.O=\sqrt[n]{x_{1}x_{2}x_{3}........x_{n}}$
        
- **Harmonik Ortalama:** Veri setindeki elemanların çarpmaya göre terslerinin ortalamasının tersidir. Hız ve zaman serilerinde kullanılır.
    
    - Formülü: $H.O=\frac{n}{\sum_{i=1}^{n}\frac{1}{x_{i}}}$
        

---

#### Klinik Uygulama (Stajyer/İntern Seviyesi)

Bu kavramlar hastane ortamında laboratuvar sonuçlarını ve hasta istatistiklerini yorumlarken doğrudan karşınıza çıkar:

- **Ortanca (Medyan) Kullanımı:** Yoğun bakım yatış süreleri (ICU LOS) genellikle medyan ile ifade edilir. Çünkü hastaların çoğu **3-5 gün** yatarken, birkaç komplike hasta **aylarca** yatabilir. Bu aşırı uç değerler (outliers) aritmetik ortalamayı inanılmaz derecede yükseltir; ancak medyan bu durumdan etkilenmez ve gerçeğe en yakın yansımayı sunar.
    
- **Tepe Değeri (Mod) Kullanımı:** "COVID-19 hastalarında acile başvuru anında _en sık görülen_ semptom öksürüktür" dediğinizde aslında tepe değerini (mod) kullanmış olursunuz.
    
- **Geometrik Ortalama Kullanımı:** İntaniye (Enfeksiyon Hastalıkları) rotasyonunda kan kültürlerindeki bakteri üreme hızını (eksponansiyel büyüme) veya bir salgındaki nüfus artış hızını hesaplarken kullanılır.
    

---

#### Yüksek Verimli (High-Yield) Notlar

USMLE, TUS ve komite sınavlarında istatistik sorularının en büyük tuzakları her zaman **aşırı değerlerin (outliers)** etkileri üzerinden kurulur.

- **Tuzak 1:** Aritmetik ortalama, veri setindeki aşırı uç değerlerden her zaman etkilenir. Örneğin, poliklinikte bekleyen hastaların yaşları 20, 22, 24, 25 ve 95 ise, bu 95 yaşındaki tek hasta ortalamayı aniden yukarı çeker. Ancak **Ortanca (Medyan)** aşırı uçlardan _kesinlikle etkilenmez_.
    
- **Tuzak 2:** Eğer bir dağılım sağa veya sola "çarpık (skewed)" ise, merkezi eğilimi göstermek için aritmetik ortalama yerine her zaman **ortanca (medyan)** kullanılmalıdır.
    
- **Tuzak 3 (Dağılım Şekilleri):** * **Simetrik (Normal) Dağılım:** Ortalama $=$ Ortanca $=$ Mod.
    
    - **Sağa Çarpık (Pozitif) Dağılım:** Kuyruk sağdadır. Aşırı büyük değerler vardır. Sıralama: **Ortalama $>$ Ortanca $>$ Mod** şeklindedir.
        
    - **Sola Çarpık (Negatif) Dağılım:** Kuyruk soldadır. Aşırı küçük değerler vardır. Sıralama: **Ortalama $<$ Ortanca $<$ Mod** şeklindedir.
        