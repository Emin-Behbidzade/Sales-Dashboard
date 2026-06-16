# Sales Dashboard

Excel-də hazırladığım satış analitika layihəsidir. 121,000+ sətirlik satış dataseti üzərində Pivot Table və chart-larla interaktiv dashboard qurdum.

---

## Dataset

121,317 sətir, 15 sütun. 2011–2014-cü illər ərzində 19,119 müştərinin 266 fərqli məhsul üzrə sifarişləri.

Sütunlar: Order ID, Order Year, Order Month, Order Total, Customer ID, Account Number, Ad/Soyad, Product ID, Product Name, Category, Subcategory, Quantity, Unit Price, Line Total.

---

## Nə etdim

**1. Dataya baxdım**
121,000+ sətirlik dataset idi. Sütunları, dəyər növlərini anladım. Kateqoriya strukturunu — 4 əsas kateqoriya (Bikes, Components, Clothing, Accessories) — ilk baxışdan gördüm.

**2. Pivot cədvəllər qurdum**
- İllər üzrə satış trendi (2011–2014)
- TOP 10 müştəri — ümumi alış məbləğinə görə
- İllər üzrə məhsul satış trendi
- Kateqoriya üzrə ümumi satış bölgüsü
- TOP 10 ən çox satılan məhsullar
- İllər üzrə satış bölgüsü

**3. Dashboard yaratdım**
Bütün pivot qrafikləri bir vərəqdə topladım. Slicer-larla illər üzrə filtrasiya əlavə etdim.

---

## Əsas Rəqəmlər

| Göstərici | Dəyər |
|---|---|
| Cəmi gəlir | $109,846,381 |
| Sifariş sayı | 121,317 |
| Unikal müştəri | 19,119 |
| Unikal məhsul | 266 |
| Əhatə etdiyi illər | 2011–2014 |

---

## Nə Gördüm

**Bikes kateqoriyası hər şeyi üstələyir.** Ümumi gəlirin 86%-i ($94.6M) yalnız Bikes kateqoriyasından gəlir. Components 10.7%, Clothing 1.9%, Accessories isə cəmi 1.2% təşkil edir. Bu o deməkdir ki, şirkətin gəliri praktiki olaraq bir kateqoriyadan asılıdır — bu həm güc, həm risk deməkdir.

**Ən çox satılan məhsullar Mountain-200 seriyasıdır.** İlk 5 yerdən hamısı Mountain-200-ün müxtəlif ölçüləridir (Black/Silver, 38/42/46). Ən yüksəki Mountain-200 Black 38 — $4.4M ilə.

**TOP müştərilər arasında fərq kiçikdir.** Roger Harui ($877K) ilə 5-ci yerdəki Ryan Calafato ($799K) arasında cəmi $78K fərq var. Bu, müştəri bazasının nisbətən balanslaşdığını göstərir — bir neçə super VIP yoxdur.

---

## Nə Əskikdir

- Aylıq satış trendini daha dərin analiz etmədim — mövsümilik ola bilər
- Məhsul rentabelliyi hesablamadım (Unit Price × Quantity məlumatı var amma mənfəət marjası yoxdur)
- Müştəri seqmentasiyası — coğrafi və ya davranış əsaslı bölgü edə bilmirdim, çünki ünvan sütunu datasete daxil deyildi
- Python ilə eyni analizləri yenidən etmək istəyirəm

---

## Alətlər

Microsoft Excel — Pivot Table, Charts, Slicers, Dashboard
