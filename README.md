# robotics-trend-analysis
# Otonom Sistemler ve Robotik Yazılım Trend Analizi

## Proje Bilgileri
* **Öğrenci Adı Soyadı:** Kerim Demirbaş
* **Numara:** 361526070
* **Ders:** Araştırma ve Yöntem Teknikleri

## Proje Konusu
Otonom sistemler ve robotik yazılımlarında kullanılan açık kaynaklı teknolojilerin GitHub API verileri üzerinden zaman içerisindeki değişim ve popülerlik trendlerinin incelenmesi.

## Kullanılacak Yöntem ve Araçlar
* Python
* GitHub REST API
* Keşifsel Veri Analizi (EDA)
* Pandas, Matplotlib / Seaborn


## UML Diyagramları (Ödev 3)

### 1. Use Case Diagram
![Use Case Diagram](docs/use_case_diagram.png)
* **Açıklama:** Sistemin aktörleri (Araştırmacı ve GitHub API) ile veri çekme, ön işleme, Keşifsel Veri Analizi (EDA) ve trend raporlama kullanım durumları arasındaki etkileşimi temsil eder.

### 2. Activity Diagram
![Activity Diagram](docs/activity_diagram.png)
* **Açıklama:** API isteklerinin atılması, HTTP yanıt kontrolleri, veri temizleme karar noktaları ve analitik grafik üretim süreçlerinin adım adım iş akışını gösterir.

### 3. Class Diagram
![Class Diagram](docs/class_diagram.png)
* **Açıklama:** Veri toplama (`GitHubDataFetcher`), veri modeli (`Repository`), temizleme (`DataPreprocessor`), istatistiksel analiz (`TrendAnalyzer`) ve görselleştirme (`Visualizer`) sınıflarının Nesne Yönelimli Programlama (OOP) yapısını temsil eder.
