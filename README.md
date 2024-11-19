# RFM Müşteri Segmentasyonu ve KMeans Clustering

Bu proje, müşteri verilerini analiz ederek segmente etmek ve anlamlı içgörüler elde etmek için **RFM (Recency, Frequency, Monetary)** analizi ile **KMeans Clustering** yöntemini birleştirmektedir.

## Proje Amacı
Projenin temel amacı, müüteri davranışlarını daha iyi anlamak ve pazarlama stratejilerini iyileştirmek için müşterileri segmente etmektir. Bu sayede, farklı segmentlere özel stratejiler geliştirilebilir.

## Kullanılan Teknolojiler ve Araçlar
- **Python**: Veri analizi ve makine öğrenimi
  - Kütüphaneler: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Jupyter Notebook**: Kod yazımı ve analiz
- **GitHub**: Projenin versiyon kontrolü ve paylaşımı

## Projede Yapılanlar

### 1. Veri Hazırlığı
- Eksik ve aykırı değerler temizlendi.
- RFM analizi için gerekli metrikler hesaplandı:
  - **Recency (Son Alışveriş Tarihi)**
  - **Frequency (Alışveriş Sıklığı)**
  - **Monetary (Toplam Harcama)**

### 2. RFM Skorlarının Hesaplanması
- Her bir müşteri için **R**, **F** ve **M** skorları belirlendi.
- Skorlar birleştirilerek **RFM Segmentleri** oluşturuldu.

### 3. KMeans Clustering ile Segmentasyon
- Veri, kümeleme algoritmasına uygun hale getirildi.
- **KMeans** algoritması kullanılarak müşteriler belirli küme sayılarına ayrıldı.
- En uygun küme sayısı belirlemek için **Elbow Method** kullanıldı.

### 4. Veri Görselleştirme
- Segmentlerin dağılımı grafiklerle gösterildi.
- Küme merkezleri ve müşteri segmentleri çarpıcı şekilde görselleştirildi.

## Sonuçlar
Bu proje, müşteri davranışlarını analiz etmenin ve stratejik karar alma sürecini desteklemenin etkili bir yöntemini sunmaktadır. Elde edilen segmentler, şu alanlarda kullanılabilecektir:
- Hedefli pazarlama kampanyaları
- Müşteri sadakat programları
- Gelir artırma stratejileri

## Dosyalar
- **notebook.ipynb**: Projede kullanılan kodlar ve analizlerin bulunduğu Jupyter Notebook.
- **data.csv**: Anonimleştirilmiş müşteri verileri.

## Nasıl Çalıştırılır
1. Bu depoyu bilgisayarınıza kopyalayın:
   ```bash
   git clone https://github.com/ardaxkantik/rfm-kmeans
   ```
2. Gerekli Python kütüphanelerini yükleyin:
   ```bash
   pip install -r requirements.txt
   ```
3. Jupyter Notebook'u çalıştırın ve **notebook.ipynb** dosyasını açın.

## Katkı
Bu projeye katkı sağlamak isterseniz, bir **pull request** oluşturarak değişikliklerinizi paylaşabilirsiniz.
