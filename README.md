# **Zomato Veri Analizi Projesi**

## 📌**Proje Açıklaması** 

Bu proje, Zomato veri seti kullanılarak restoranların online sipariş kabul etme durumu, puan dağılımları, fiyat aralıkları gibi faktörlerin analiz edilmesini amaçlamaktadır. Veri analizi teknikleri ve görselleştirme yöntemleri ile restoranların müşteri davranışları üzerindeki etkileri incelenmiştir.

## 📊 **Veri Seti**

Zomato veri seti, restoranlarla ilgili çeşitli bilgileri içermektedir. Kullanılan sütunlar şunlardır:

* name : Restoranın adı

* online_order: Online sipariş kabul ediyor mu? (Yes/No)

* book_table: Masa rezervasyonu yapılıyor mu? (Yes/No)

* rate: Müşteri puanı (örn: 4.1/5)

* votes: Kullanıcı oy sayısı

* approx_cost(for two people): 2 kişi için ortalama maliyet

* listed_in(type): Restoranın hizmet türü

## 📦 **Kullanılan Kütüphaneler**

Bu projede aşağıdaki Python kütüphaneleri kullanılmıştır:

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
```

## 📈 **Yapılan Analizler**

* Veri setinin genel incelenmesi ve eksik verilerin temizlenmesi

* Restoran puanlarının dağılımı

* Online sipariş ve puan arasındaki ilişki

* İki kişilik yemek maliyetlerinin analiz edilmesi

* Restoran türlerine göre dağılım

* Görselleştirmeler ile trendlerin yorumlanması

## 🚀 **Nasıl Çalıştırılır?**

1. Gerekli kütüphaneleri yükleyin:
```python
pip install pandas seaborn matplotlib
```
2. Notebook'u çalıştırın ve adım adım analizleri takip edin.

## 📊 **Görseller ve Sonuçlar**

Proje kapsamında elde edilen bazı görseller:

* Halkın en çok tercih ettiği restoran türleri grafiği

* Restoran türleri ve aldıkları puan ilişkisi

* Restoranların çevrimiçi/çevrimdışı hizmet kıyaslaması

* Çiftler restoranlarda akşam yemeği için hangi fiyat aralığını tercih ettiğinin grafiği

* Online sipariş/mekanda sipariş ve puan arasındaki ilişki

* En çok tercih edilen restoran tipi

Bu analizler, restoranların hizmet kalitesini değerlendirmek ve müşteri tercihlerini anlamak için faydalı olabilir.

___



📌 Not: Bu proje, veri analizi ve görselleştirme teknikleri üzerine bir çalışmadır. Veriler farklı şehirler veya restoran kategorileri için değişiklik gösterebilir.

🚀 Katkıda bulunmak veya geliştirmeler yapmak isterseniz pull request gönderebilirsiniz!

