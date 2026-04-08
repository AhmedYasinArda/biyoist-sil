---
title: "Quiz"
date: 2026-04-07
draft: false
math: true
weight: 4 
categories: ["Biyoistatistik", "Tıp"]
tags: ["Erciyes Üniversitesi", "Değişkenler", "Ölçüm Skalaları"]
---

# Quiz

{{< quiz >}}
[
    {
      "question": "Tüm gözlem değerlerini hesaplamaya katan ve bir veriyi temsil eden tipik merkezi yer ölçüsü aşağıdakilerden hangisidir?",
      "options": ["Medyan", "Mod", "Aritmetik Ortalama", "Geometrik Ortalama"],
      "correctIndex": 2,
      "explanation": "Aritmetik ortalama, bir veriyi temsil eden ve verideki bütün gözlem değerlerini hesaplamaya alan tipik bir değerdir."
    },
    {
      "question": "Bakteri üremesi, nüfus artışı veya faiz gibi geometrik dizi ile artan olayların ortalama artış hızlarını hesaplamada kullanılan ortalama türü hangisidir?",
      "options": ["Aritmetik Ortalama", "Geometrik Ortalama", "Harmonik Ortalama", "Kareli Ortalama"],
      "correctIndex": 1,
      "explanation": "Geometrik ortalama, eşit zaman aralığı ile değişen oranların ortalamalarının ve bakteri üremesi, nüfus artışı gibi olayların artış hızlarını hesaplamada kullanılır."
    },
    {
      "question": "Zaman serileri ve belirli fiyat tipleri için genellikle daha kullanışlı olan ve elemanların terslerinin ortalamasının tersi alınarak hesaplanan ölçü hangisidir?",
      "options": ["Geometrik Ortalama", "Kareli Ortalama", "Medyan", "Harmonik Ortalama"],
      "correctIndex": 3,
      "explanation": "Harmonik ortalama, elemanların terslerinin ortalamasının tersi alınarak hesaplanır ve belirli fiyat tipleri ile zaman serileri için kullanışlıdır."
    },
    {
      "question": "Verideki aşırı değerlerden (outliers) etkilenmeyen ve çarpık dağılımları iyi temsil eden merkezi yer ölçüsü aşağıdakilerden hangisidir?",
      "options": ["Aritmetik Ortalama", "Geometrik Ortalama", "Ortanca (Medyan)", "Tepe Değeri (Mod)"],
      "correctIndex": 2,
      "explanation": "Ortalama aşırı değerlerden etkilenirken, ortancada (medyan) böyle bir durum söz konusu değildir ve çarpık dağılımları iyi temsil eder."
    },
    {
      "question": "Bir veri setinde en çok tekrarlanan gözlem değerine ne ad verilir?",
      "options": ["Mod (Tepe Değeri)", "Medyan", "Persantil", "Aritmetik Ortalama"],
      "correctIndex": 0,
      "explanation": "Bir veride en çok tekrarlanan gözlem değerine Tepe Değeri (Mod) denir."
    },
    {
      "question": "Küçükten büyüğe sıralandırılmış verileri 100 eş parçaya bölerek yorum yapılmasını sağlayan istatistiklere ne ad verilir?",
      "options": ["Kartiller", "Persantiller", "Mod", "Varyans"],
      "correctIndex": 1,
      "explanation": "Persentiller, veri setindeki küçükten büyüğe sıralandırılmış verileri 100 eş parçaya bölerek yorum yapılmasını sağlayan istatistiklerdir."
    },
    {
      "question": "İkinci çeyreklik (Q2) aşağıdakilerden hangisine eşittir?",
      "options": ["Aritmetik Ortalama", "Ortanca (Medyan)", "Mod", "3. Çeyreklik"],
      "correctIndex": 1,
      "explanation": "Ortanca, 2. çeyreklik (Q2) ve 50. yüzdelik değerleri birbirine eşittir."
    },
    {
      "question": "Verideki en büyük değer ile en küçük değer arasındaki uzaklığa ne denir?",
      "options": ["Varyans", "Standart Sapma", "Dağılım Aralığı (Range)", "Çeyrekler Arası Uzaklık"],
      "correctIndex": 2,
      "explanation": "Dağılım aralığı, verideki en büyük değer ile en küçük değer arasındaki uzaklıktır."
    },
    {
      "question": "Çeyrekler arası uzaklık (IQR) hangi formülle hesaplanır?",
      "options": ["Q3 + Q1", "Q2 - Q1", "Maksimum - Minimum", "Q3 - Q1"],
      "correctIndex": 3,
      "explanation": "Çeyrekler arası uzaklık 1. ve 3. çeyrekler arası uzaklığı ifade eder ve IQR = Q3 - Q1 formülü ile hesaplanır."
    },
    {
      "question": "Kutu grafiğinde bir gözlem değerinin alt sınırdan aykırı değer (outlier) kabul edilebilmesi için koşul nedir?",
      "options": ["Değer < Q1 - 1.5 * IQR", "Değer > Q3 + 1.5 * IQR", "Değer < Q2 - 1.5 * IQR", "Değer > Q1 + 1.5 * IQR"],
      "correctIndex": 0,
      "explanation": "Bir gözlem değeri Q1 - 1.5 * IQR değerinden küçükse alt sınırda aykırı değer kabul edilir."
    },
    {
      "question": "Standart sapma ile varyans arasındaki matematiksel ilişki nedir?",
      "options": ["Standart sapma, varyansın karesidir.", "Standart sapma, varyansın kareköküdür.", "Varyans, standart sapmanın kareköküdür.", "Aralarında matematiksel bir ilişki yoktur."],
      "correctIndex": 1,
      "explanation": "Standart sapma varyansın kareköküdür."
    },
    {
      "question": "Normal dağılım eğrisinde (çan eğrisi), gözlemlerin yaklaşık %68.26'sı hangi aralıkta bulunur?",
      "options": ["Ortalama ± 1 Standart Sapma", "Ortalama ± 2 Standart Sapma", "Ortalama ± 3 Standart Sapma", "Ortalama ± 0.5 Standart Sapma"],
      "correctIndex": 0,
      "explanation": "Gözlemlerin yaklaşık %68.26'sı Ortalama eksi 1 ve artı 1 standart sapma aralığında bulunur."
    },
    {
      "question": "Normal dağılım eğrisinde gözlemlerin yaklaşık %95'i hangi aralıkta bulunur?",
      "options": ["Ortalama ± 1 Standart Sapma", "Ortalama ± 2 Standart Sapma", "Ortalama ± 3 Standart Sapma", "Ortalama ± 4 Standart Sapma"],
      "correctIndex": 1,
      "explanation": "Gözlemlerin yaklaşık %95.44'ü Ortalama ± 2 Standart Sapma aralığında bulunur."
    },
    {
      "question": "Gözlem sayıları ve ölçü birimleri farklı olan değişkenlerin ortalamaya göre yayılışlarını karşılaştırmak için kullanılan ölçü hangisidir?",
      "options": ["Varyans", "Standart Hata", "Çeyrekler Arası Uzaklık", "Değişim Katsayısı (CV)"],
      "correctIndex": 3,
      "explanation": "Değişim (varyasyon) katsayısı ölçü birimleri farklı değişkenlerin yayılışlarını karşılaştırmak için kullanılır ve yüzde (%) ile gösterilir."
    },
    {
      "question": "Bir değişkenin homojen dağıldığı varsayımı için değişim katsayısı (DK) hangi aralıkta olmalıdır?",
      "options": ["DK >= %20", "%10 <= DK < %20", "DK < %10", "DK = 0"],
      "correctIndex": 2,
      "explanation": "Değişim katsayısı %10'dan küçük (DK < %10) ise verinin homojen dağıldığı varsayılır."
    },
    {
      "question": "Sola çarpık (negatif çarpık) bir dağılımda, merkezi eğilim ölçülerinin sıralaması nasıldır?",
      "options": ["Ortalama < Ortanca < Mod", "Ortalama > Ortanca > Mod", "Ortalama = Ortanca = Mod", "Mod < Ortalama < Ortanca"],
      "correctIndex": 0,
      "explanation": "Sola çarpık (negatif) dağılımda sol kuyrukta aşırı gözlemler vardır, bu nedenle Ortalama < Ortanca < Mod sıralaması görülür."
    },
    {
      "question": "Dağılım sağa uzun kuyruklu ise bu dağılım için ne söylenebilir?",
      "options": ["Sola çarpık dağılımdır", "Simetrik dağılımdır", "Sağa çarpık (pozitif) dağılımdır", "Basık dağılımdır"],
      "correctIndex": 2,
      "explanation": "Dağılım sağa uzun kuyruklu ise pozitif çarpık veya sağa çarpık denir."
    },
    {
      "question": "Normal dağılım eğrisinin sivrilik veya yayvanlık derecesine ne ad verilir?",
      "options": ["Çarpıklık", "Basıklık (Kurtosis)", "Varyasyon", "Standart Sapma"],
      "correctIndex": 1,
      "explanation": "Normal dağılım eğrisinin sivrilik veya yayvanlık derecesi basıklık olarak adlandırılır."
    },
    {
      "question": "Standart normal dağılışın (z dağılışı) aritmetik ortalaması ve standart sapması kaçtır?",
      "options": ["Ortalama: 1, Sapma: 0", "Ortalama: 0, Sapma: 1", "Ortalama: 1, Sapma: 1", "Ortalama: 0, Sapma: 0"],
      "correctIndex": 1,
      "explanation": "Aritmetik ortalaması 0, standart sapması 1 olan teorik normal dağılışa standart normal dağılış (z dağılışı) adı verilir."
    },
    {
      "question": "Herhangi bir örnek dağılışı standart normal dağılışa dönüştürmek için kullanılan Z dönüşüm formülü nedir?",
      "options": ["z = (X - Standart Sapma) / Ortalama", "z = (Ortalama - X) / Standart Sapma", "z = (X - Ortalama) / Standart Sapma", "z = (Standart Sapma - Ortalama) / X"],
      "correctIndex": 2,
      "explanation": "Herhangi bir örnek dağılışı teorik normal dağılışla karşılaştırmak için z = (X - Ortalama) / Standart Sapma formülü ile z dönüşümü uygulanır."
    }
]
{{< /quiz >}}