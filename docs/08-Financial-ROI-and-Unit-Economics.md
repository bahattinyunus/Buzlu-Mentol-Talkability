# 📈 8. FINANCIAL ROI & UNIT ECONOMICS: Pazarlama Mühendisliği ve Büyüme Modeli

> **Finansal Fizibilite, Birim Ekonomisi ve Duyarlılık (Sensitivity) Analizi**  
> **Temel Odak:** Project-Minus5 kampanyasının her bir temas noktasının (AR Filtre, Cool-Down Pod, Perakende POSM) birim maliyetini, yeni kullanıcı kazanım maliyetini (CAC) ve perakende satış hacmi artışını (Incremental Sales Lift) mühendislik matematiğiyle modellemek.

---

## 8.1. Kampanya Bütçe Dağılımı ve Birim Maliyet Mimarisi

Kampanya bütçesi, **en yüksek organik konuşulabilirlik çarpanı (Viral K-Factor)** ve **en düşük yeni müşteri kazanım maliyeti (New-to-Brand CAC)** üretecek şekilde 4 ana havuza dağıtılmıştır:

| Faz / Yatırım Kalemi | Bütçe Payı | Kapsanan Operasyonel Kalemler | Temel Çıktı & Verimlilik Metriği |
| :--- | :---: | :--- | :--- |
| **Faz 2: Emergency Cool-Down Pods & 50.000 Akıllı QR Numune** | **%40** | 4 adet gezici IoT Ferahlama Kabini üretimi, kampüs/gym lojistiği, 50.000 adet 90 ml QR kodlu seyahat boyu ürün. | Doğrudan hedef kitle eline teslim edilen **%100 doğrulanmış tekil deneme (Verified Trial)**. |
| **Faz 1: Dijital, Termal AR Filtre & Influencer Tohumlama** | **%35** | TikTok/IG Termal Kamera AR filtresi geliştirme, 35+ kampüs/fitness/espor içerik üreticisi işbirliği, `#HararetiKes` medya desteği. | **5.000.000+ Erişim** ve **75.000+ Organik UGC** ile düşük CPM / yüksek akran onayı. |
| **Faz 3: Perakende "Soğutucu Dolap" POSM & Hızlı Ticaret** | **%20** | 250+ kilit mağazada "Soğutucu Dolap" end-cap POSM kurulumu, Getir/Trendyol Go sepet algoritması sponsorluğu. | Test mağazalarında **+%22 SKU bazlı satış hacmi artışı (Incremental Lift)**. |
| **Faz 4: Telemetri, QR/UTM Altyapısı ve A/B Test Analitiği** | **%5** | Gerçek zamanlı lokasyon bazlı QR yönlendirme motoru, tek kullanımlık kupon entegrasyonu ve canlı KPI panosu. | En yüksek dönüşüm veren kampüslere haftalık **dinamik rota ve stok optimizasyonu**. |

---

## 8.2. Uçtan Uca Dönüşüm Hunisi Matematiği (Conversion Math)

Project-Minus5, konuşulabilirliği (Talkability) satışa (Purchase) bağlarken üç paralel kanaldan **Yeni Kullanıcı (New-to-Brand)** üretir:

1. **Kanal A — Fiziksel Numune & QR Dönüşümü (Pod-to-Purchase):**
   $$\text{QR Tarama} = 50.000 \text{ Numune} \times \%28 \text{ Tarama Oranı} = 14.000 \text{ Tekil Genç}$$
   $$\text{Kuponlu İlk Satın Alma} = 14.000 \times \%35 \text{ Kupon Kullanımı} = 4.900 \text{ Doğrudan Tam Boy Satış}$$
   *(Ayrıca QR okutmayıp marketten doğrudan satın alan organik deneme etkisiyle toplam ~6.000+ yeni tam boy kullanıcı).*

2. **Kanal B — Dijital AR & UGC Sosyal Kanıt Dönüşümü (Viral-to-Purchase):**
   $$\text{Organik UGC} = 5.000.000 \text{ Erişim} \times \%1.5 \text{ UGC Üretim Oranı} = 75.000 \text{ Paylaşım}$$
   Akran paylaşımı (Word-of-Mouth), geleneksel reklama göre **3.2x daha yüksek deneme eğilimi** yaratarak hızlı ticaret ve e-ticaret kanallarına doğrudan trafik taşır.

3. **Kanal C — Perakende "Soğutucu Dolap" POSM Satış Çarpanı (Retail Uplift):**
   Mağaza koridor başında sergilenen *Soğutucu Dolap POSM* stantları, H&S Buzlu Mentol SKU'sunda baz satışlara kıyasla **+%22 net hacim artışı** sağlar.

---

## 8.3. Senaryo ve Duyarlılık Analizi (Sensitivity Analysis — 12 Hafta)

| Performans Göstergesi (KPI) | 📉 Muhafazakar Senaryo (Conservative) | 🎯 Baz Hedef Senaryo (Target Base) | 🚀 Viral Patlama Senaryosu (Bull Case) |
| :--- | :---: | :---: | :---: |
| **Toplam Dijital Erişim (Reach)** | 3.200.000 | **5.000.000+** | 9.500.000+ |
| **`#HararetiKes` AR Filtre & UGC Sayısı** | 42.000 | **75.000+** | 145.000+ |
| **Sosyal Medya Etkileşim Oranı (ER)** | %4.8 | **>%6.5** | %8.9 |
| **Dağıtılan Akıllı QR Numune (90 ml)** | 40.000 | **50.000** | 60.000 |
| **QR Kod Tarama Oranı (Scan Rate)** | %20 (8.000 tarama) | **%28 (14.000 tarama)** | %38 (22.800 tarama) |
| **Kabin Slow-Mo Video Paylaşım Oranı** | %32 | **>%45** | %60 |
| **Perakende POSM Satış Artışı (Uplift)** | +%14.5 | **+%22.4** | +%31.0 |
| **1 Yıllık Tekrar Satın Alma (LTV Çarpanı)** | 2.8 şişe / yıl | **3.6 şişe / yıl** | 4.2 şişe / yıl |

---

## 8.4. Yaşam Boyu Değer (Customer Lifetime Value - LTV) Etkisi

18–24 yaş aralığında kazanılan bir tüketicinin şampuan kategorisindeki stratejik değeri, diğer yaş gruplarından çok daha yüksektir:
* **Erken Marka Sadakati:** Üniversite yıllarında kepek ve saç derisi ferahlığı konusunda H&S Buzlu Mentol ile tanışıp memnun kalan bir genç, yılda ortalama **3.5 – 4 adet tam boy şişe** tüketir.
* **Kültürel Elçilik (Advocacy):** Öğrenci evinde, yurtta veya spor salonu çantasında görünen H&S Buzlu Mentol şişesi, oda arkadaşları arasında da ikincil deneme (*secondary trial*) yaratır.
