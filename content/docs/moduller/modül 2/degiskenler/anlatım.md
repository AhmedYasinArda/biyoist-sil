---
title: "Anlatım"
date: 2026-04-07
draft: false
math: true
categories: ["Biyoistatistik", "Tıp"]
tags: ["Erciyes Üniversitesi", "Değişkenler", "Ölçüm Skalaları"]
---


# Değişkenler ve Ölçüm Skalaları

> **Erciyes Üniversitesi · Tıp Fakültesi · Biyoistatistik**  
> Slayt 24–39 · Temel kavramlardan klinik uygulamaya

---


## 1. Temel Tanım (1. Sınıf Seviyesi)

**Değişken (Variable / Feature):** Birimden birime farklı değerler alabilen ve bu değerleri sayısal olarak ifade edilebilen özelliklerdir. Kısaca: ölçebildiğimiz, saydığımız ya da kategorize edebildiğimiz her şey bir değişkendir.

|Örnek|Açıklama|
|---|---|
|Boy (cm)|Her insanın boyu farklı → değişken|
|Kan grubu (A, B, AB, 0)|Kategorik farklılık → değişken|
|Vücut ısısı (°C)|Sürekli ölçüm → değişken|

### 1.1 Bağımlı / Bağımsız Değişken

$$y = 3x^2 + 2x + 1, \quad x > 0$$

- **Bağımlı (Outcome / Response) değişken:** Değeri başka değişkenlerce belirlenen; araştırmada ölçülen sonuç.
- **Bağımsız (Predictor / Explanatory) değişken:** Araştırmacının kontrol ettiği ya da etkisini incelediği değişken.

**Örnek-1 (Slayt 37):** Bebek doğum ağırlığını etkileyen faktörler

$$y = \text{bebek doğum ağırlığı (gr)}$$

$$x_1 = \text{gebelik haftası}, \quad x_2 = \text{annenin sigara içme durumu (1: içen, 0: içmeyen)}$$

Bebek doğum ağırlığı → **bağımlı**; gebelik haftası ve sigara durumu → **bağımsız**.

---

## 2. Değişken Türleri ve Sınıflandırma

```
Değişken
├── Nitel (Qualitative / Categorical)
│   ├── İsimsel (Nominal)
│   └── Sıralı (Ordinal)
└── Nicel (Quantitative / Numerical)
    ├── Kesikli (Discrete)
    └── Sürekli (Continuous)
```

### 2.1 Nitel Değişkenler (Categorical / Qualitative)

|Tür|Tanım|Klinik Örnek|
|---|---|---|
|**İsimsel (Nominal)**|Kategoriler arasında sıralama yok|Kan grubu (A/B/AB/0), cinsiyet, meslek|
|**Sıralı (Ordinal)**|Kategoriler sıralı; aralıklar eşit değil|Ağrı şiddeti (yok < hafif < orta < şiddetli), eğitim durumu|

### 2.2 Nicel Değişkenler (Quantitative / Numerical)

|Tür|Tanım|Klinik Örnek|
|---|---|---|
|**Kesikli (Discrete)**|Yalnızca tam sayı değer alır|Çocuk sayısı, diş sayısı, yatış günü|
|**Sürekli (Continuous)**|Tam sayı ve kesirli değer alır|Boy (cm), ağırlık (kg), sistolik KB (mmHg), IQ|

> **Değişken türü neden önemlidir?**  
> Bilimsel çalışmada doğru istatistiksel test, grafik ve tanımlayıcı istatistik seçimi için değişken tipinin doğru belirlenmesi **zorunludur**. Bu, istatistiksel hipotezlerin ($H_0$ ve $H_1$) ve kullanılacak testlerin belirlenmesindeki **en kritik ilk adımdır**.

---

## 3. Ölçüm Skaları (4 Temel Skala)

Hassasiyet hiyerarşisi (en zayıftan en güçlüye):

$$\text{Nominal} \rightarrow \text{Ordinal} \rightarrow \text{Interval} \rightarrow \text{Ratio}$$

|#|Skala|Sıralama|Eşit Aralık|Mutlak Sıfır|Klinik Örnek|
|---|---|:-:|:-:|:-:|---|
|1|**Nominal**|—|—|—|Kan grubu, cinsiyet|
|2|**Ordinal**|✓|—|—|VAS ağrı skoru, eğitim durumu|
|3|**Interval**|✓|✓|—|Vücut ısısı (°C), IQ, Richter ölçeği|
|4|**Ratio**|✓|✓|✓|Boy (cm), ağırlık (kg), sistolik KB, hasta sayısı|

### 3.1 Aralıklı Ölçek (Interval Scale)

Veriler gerçek olmayan bir başlangıç noktasına göre belirlenir. Sıfır değeri mutlak yokluğu ifade etmez; bu nedenle **oransallık kurulamaz.**

> 10°C, 5°C'nin iki katı sıcaklık **anlamına gelmez.**

Klinik örnekler:

- Vücut ısısı ölçümü (termometre)
- Kan pH'ı (normal aralık: 7.1–7.5)
- Richter ölçeği (logaritmik; sıfır noktası görecelidir)
- Tansiyon aralıklı ölçümü (küçük–büyük tansiyon arası)

### 3.2 Oransal Ölçek (Ratio Scale)

Gerçek bir sıfır noktası (mutlak yokluk) vardır. Ölçümler birbirinin katı olarak ifade edilebilir.

$$\text{80 kg} = 2 \times \text{40 kg} \quad \checkmark$$

$$\text{Gelir: 60.000 TL} = 2 \times \text{30.000 TL} \quad \checkmark$$

Klinik örnekler:

- Ağırlık (kg): 0 kg gerçek yokluğu ifade eder
- Boy (cm), sistolik kan basıncı (mmHg)
- Hasta sayısı (0 hasta mümkündür)

---

## 4. Klinik Uygulama (Stajyer / İntern Seviyesi)

### 4.1 Hangi durum, hangi skala?

|Klinik Senaryo|Skala|Açıklama|
|---|---|---|
|Vücut ısısı ölçümü (°C)|Interval|Sıfır derece "ısısız" değil; oransallık yok|
|Sistolik kan basıncı (mmHg)|Ratio|0 mmHg = nabız yok; mutlak sıfır|
|VAS ağrı skoru (0–10)|Ordinal|6, 3'ün "iki katı ağrısı" anlamına gelmez|
|Diyabet durumu (var/yok)|Nominal|İkili binary değişken|
|Kan grubu|Nominal|Kategoriler arasında sıra yok|
|Richter ölçeği|Interval|Logaritmik; mutlak sıfır yok|
|Hastanın yatış gün sayısı|Ratio (Discrete)|Kesikli + mutlak sıfır var|

### 4.2 Test seçimi rehberi

|Değişken türü|Karşılaştırma|Uygun Test|
|---|---|---|
|Nicel (sürekli) — 2 grup|Kadın vs. erkek geliri|Student t / Mann-Whitney U|
|Ordinal — 2 grup|İyi/orta/kötü kategoriler|Ki-kare|
|Nicel — zaman içi değişim|Mevsimsel eğilim|Çizgi grafik + tekrarlı ANOVA|

### 4.3 Grafik seçimi

|Değişken türü|Önerilen Grafik|
|---|---|
|Nominal (cinsiyet, kan grubu)|Pasta (pie) veya çubuk (bar)|
|Nicel, zaman serisi|Çizgi grafik|
|İki nicel değişken ilişkisi|Saçılım (scatter) grafiği|
|Sürekli değişken dağılımı|Histogram veya kutu (box) grafiği|

### 4.4 Örnek Çalışmalar

**Örnek-2 (Slayt 38) — Diyabet tahmini:**

$$y = \text{Diyabet durumu (1: Diyabet, 0: Sağlıklı)} \quad \text{[Nominal, Nitel]}$$

Bağımsız değişkenler ($x$):

- Yaş → Sürekli, Ratio
- Kan şekeri (mg/dL) → Sürekli, Ratio
- Fiziksel aktivite seviyesi (0/1/2) → Ordinal
- Ailede diyabet geçmişi (var/yok) → Nominal

---

**Örnek-3 (Slayt 39) — Akademik başarı tahmini:**

$$y = \text{GANO} \quad \text{[Sürekli, Nicel, Ratio]}$$

Bağımsız değişkenler ($x$):

- Çalışma saatleri → Sürekli
- Ders devamlılık oranı → Sürekli
- Sosyoekonomik durum (1: Yüksek, 0: Düşük) → Nominal
- Uyku süresi (saat) → Sürekli

---

## 5. Yüksek Verimli Notlar (TUS / USMLE / Komite Sınavı)

### ⚠ Tuzak 1 — Interval skalada sıfır yokluğu ifade etmez

> **Yanlış:** "10°C, 5°C'nin iki katı sıcaklığıdır."  
> **Doğru:** Interval skalada oransallık kurulamaz. Bu ayrım sadece **Ratio** skalada geçerlidir.

### ⚠ Tuzak 2 — VAS ordinaldir, aralıklı değildir

VAS (0–10) veya Likert ölçeği ordinal kabul edilir. "3'ten 6'ya çıkış = iki kat ağrı" çıkarımı yapılamaz.

### ⚠ Tuzak 3 — Değişken türü yanlışsa test de yanlış

|Hatalı Seçim|Doğrusu|
|---|---|
|Ordinal veri için t-testi|→ Mann-Whitney U veya ki-kare|
|Nominal veri için ortalama hesabı|→ Frekans ve yüzde|
|Kesikli veri için histogram|→ Çubuk grafik tercih edilir|

### 📌 Hızlı Özet — Skala Özellikleri

|Skala|Sıralama|Eşit Aralık|Mutlak Sıfır|Uygun Test|
|---|:-:|:-:|:-:|---|
|Nominal|—|—|—|Ki-kare, Fisher|
|Ordinal|✓|—|—|Mann-Whitney, Kruskal-Wallis|
|Interval|✓|✓|—|t-testi, ANOVA|
|Ratio|✓|✓|✓|t-testi, ANOVA|

### 📌 Bağımlı / Bağımsız Ayırımı

> **"Neyi açıklıyoruz?"** sorusunun cevabı → **bağımlı değişken**  
> **"Ne ile açıklıyoruz?"** sorusunun cevabı → **bağımsız değişken**

---

_Kaynak: Erciyes Üniversitesi Biyoistatistik Dersi, Slayt 24–39_