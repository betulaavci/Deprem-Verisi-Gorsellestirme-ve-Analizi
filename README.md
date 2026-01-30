# Deprem-Verisi-Gorsellestirme-ve-Analizi

1. AMAÇ
Bu projenin amacı, deprem verilerini analiz ederek büyüklük, derinlik, zaman ve lokasyon gibi özelliklerin dağılımını incelemek ve çeşitli görselleştirmeler yoluyla bu verilerden anlamlı içgörüler çıkarmaktır. Böylece deprem eğilimlerini anlamak ve risk farkındalığını artırmak hedeflenmiştir.

2. PROBLEM TANIMI
Depremler, ciddi sonuçlara yol açabilen doğal afetlerdir. Ancak bu verilerin anlamlı şekilde analiz edilmesi, karar vericilere ve halka fayda sağlayabilir. Bu proje kapsamında, tarihsel deprem verilerindeki eksikliklerin giderilmesi, verinin temizlenmesi ve farklı boyutlarda (zaman, lokasyon, büyüklük, derinlik) analiz edilmesi amaçlanmıştır.

3. KULLANILAN YÖNTEMLER VE ARAÇLAR
Veri Kaynağı: “data.csv” adlı dosya
Kullanılan Diller: Python
Kütüphaneler: pandas, matplotlib, seaborn
Veri Ön İşleme: Tarih sütunu datetime formatına çevrildi.Eksik veriler tespit edildi ve Location sütunundaki eksikler temizlendi.
Yıl, Ay, Gün, Hafta Günü gibi türetilmiş sütunlar oluşturuldu.

Görselleştirme Adımları:
1.Deprem büyüklüğü dağılımı
2.Derinlik dağılımı
3.Günlük deprem sayısının zamana göre değişimi
4.En çok deprem görülen 10 lokasyon
5.Harita üzerinde deprem noktalarının dağılımı (scatter plot)

4. SONUÇLAR
Deprem büyüklüklerinin çoğunlukla belirli bir aralıkta yoğunlaştığı gözlemlendi.Depremler, genellikle sığ derinliklerde meydana gelmiş.Zaman içinde bazı günlerde daha fazla deprem meydana geldiği görüldü.Belirli lokasyonlarda deprem yoğunluğu oldukça fazlaydı.Harita üzerinde yapılan görselleştirme, depremlerin coğrafi dağılımı hakkında önemli ipuçları sundu.

6. GELECEK PLANLAMALARI
Veriye konum koordinatları (enlem, boylam) eklenerek interaktif haritalama yapılabilir.Zaman serisi analizleri ile deprem tahminleme üzerine modeller geliştirilebilir.
Makine öğrenmesi ile risk sınıflandırması yapılabilir.Bölgesel bazda daha detaylı analizler (örneğin fay hatlarına göre) gerçekleştirilebilir.
