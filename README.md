
# Ürün İsmi : Meyve Kaşifi 

Yapay zekâ destekli, çocukların meyveleri eğlenerek öğrenmesini sağlayan YOLOv4 tabanlı eğitim oyunu.

---
# Takım İsmi (Grup 84)

**VisionX**

---

# Takım Rolleri

| Takım Üyesi | Rol | Sorumluluklar |
|-------------|------|---------------|
| **Gamze GÜL** | Scrum Master & Computer Vision Developer | Scrum sürecinin yönetimi, sprint planlarının takibi, veri setinin hazırlanması ve etiketlenmesi, YOLOv4 modelinin eğitilmesi, test edilmesi ve performansının iyileştirilmesi. |
| **Abdullah AKÇAY** | Product Owner & Application Developer | Ürün gereksinimlerinin belirlenmesi, Product Backlog'un oluşturulması ve önceliklendirilmesi, uygulamanın geliştirilmesi ve oyun mekaniklerinin tasarlanması. |
| **Gamze FERİZLİ** | Application Developer & Documentation Coordinator | Uygulama geliştirme sürecine destek verilmesi, proje dokümantasyonunun hazırlanması, sprint raporlarının oluşturulması, proje ilerleyişinin takip edilmesi ve takım içi bilgilendirmelerin yürütülmesi. |


---

# Ürün Açıklaması

Meyve Kaşifi, çocukların meyveleri eğlenerek öğrenmelerini amaçlayan yapay zekâ destekli bir eğitim oyunudur. Oyuncu kamera veya galeriden bir meyve görseli seçer. YOLOv4 modeli görseldeki meyveyi tespit ederek ekranda gösterir. Doğru tahmin edilen her meyve için oyuncu puan kazanır. Proje; görüntü işleme, yapay zekâ ve oyunlaştırma tekniklerini bir araya getirerek çocukların öğrenme sürecini daha eğlenceli ve etkileşimli hale getirmeyi amaçlamaktadır.

---

# Ürün Özellikleri

- YOLOv4 ile meyve tanıma
- Kamera veya galeriden görsel yükleme
- Yapay zekâ destekli nesne tespiti
- Doğru tahminlerde puan kazanma sistemi
- Çocuk dostu kullanıcı arayüzü
- Oyun sonunda skor ekranı
- Oyunu yeniden başlatabilme
- Mobil, web veya Python tabanlı kullanım desteği

---

# Hedef Kitle

- 4-10 yaş arası çocuklar
- Okul öncesi öğrencileri
- İlkokul öğrencileri
- Öğretmenler
- Veliler

---

# Product Backlog

https://miro.com/welcomeonboard/OWd4UDFxZjU2bmR5NHgrTXhGVzh4NjFnUHA3U3VsTno0dXEzb3Q2UlBEcS9CdDAyY0E5TkZNbW96WFI1UkhEUS9aYUNUZmhPRXlVMGJJTWVXLzVtZXZIcUNtRHNwR2JqeXRGRUpRVHJXNFBDdzBDQWE0SDZ6KzU1VUoxN3IvUlZBd044SHFHaVlWYWk0d3NxeHNmeG9BPT0hdjE=?share_link_id=369723976325

# Sprint 1

- **Backlog düzeni ve Story seçimleri:** Product Backlog, projenin geliştirme sürecindeki önceliklere göre oluşturulmuştur. İlk sprint kapsamında araştırma, planlama ve veri hazırlığı süreçlerine odaklanılmıştır. Story'ler daha küçük görevlere (task) ayrılarak Sprint Board üzerinde takip edilmektedir. Sprint boyunca görevler öncelik ve bağımlılıklarına göre planlanmıştır.

- **Daily Scrum:** Daily Scrum toplantılarının ekip üyelerinin uygunluk durumuna göre WhatsApp grubu üzerinden gerçekleştirilmesine karar verilmiştir. Günlük ilerleme durumu, yapılan çalışmalar ve karşılaşılan engeller grup üzerinden paylaşılmıştır.

- **Sprint board update:** Sprint Board ekran görüntüleri Readme içerisinde paylaşılmıştır. Sprint sonunda;
  - Tamamlanan görevler:
    - Literatür taraması ve benzer projelerin incelenmesi
    - Proje takviminin oluşturulması
  - Devam eden görevler:
    - Gerekli araçların (kütüphaneler, yazılımlar) belirlenmesi
    - Meyve resimlerinden oluşan veri setinin toplanması
<img width="1136" height="1374" alt="Meyve Kaşifi (1)" src="https://github.com/user-attachments/assets/11a41c98-2f71-4aa9-8b71-b86bb4d25f5c" />

- **Ürün Durumu:** Sprint 1 sonunda ürün fikri netleştirilmiş, proje planlaması tamamlanmış ve geliştirme süreci için gerekli hazırlıklar başlatılmıştır. Araştırma ve planlama çalışmaları tamamlanmış, veri seti hazırlama süreci başlatılmıştır. Ürünün temel geliştirme çalışmalarına bir sonraki sprintte devam edilecektir.

- **Sprint Review:** Sprint boyunca literatür araştırması gerçekleştirilmiş, benzer projeler incelenmiş ve proje takvimi oluşturulmuştur. Sprint Board hazırlanmış, Product Backlog oluşturulmuş ve geliştirme sürecinde kullanılacak araçların belirlenmesi ile veri seti toplama çalışmalarına başlanmıştır. Sonraki sprintte veri setinin hazırlanması, geliştirme ortamının kurulması ve model geliştirme çalışmalarına başlanması planlanmaktadır.

Sprint Review katılımcıları:
- Gamze Gül
- Abdullah Akçay
- Gamze Ferizli

- **Sprint Retrospective:**
  - Proje planlaması ve görev dağılımı başarılı şekilde tamamlanmıştır.
  - Sprint Board üzerinden görev takibinin düzenli yapılmasına karar verilmiştir.
  - Veri hazırlama ve geliştirme süreçlerinin bir sonraki sprintte daha planlı ilerletilmesi hedeflenmiştir.
 


# Sprint 2

- **Backlog düzeni ve Story seçimleri:** Sprint 2 kapsamında proje planlama aşamasından geliştirme hazırlık aşamasına geçilmiştir. Bu sprintte model eğitimi için gerekli veri setinin oluşturulmasına öncelik verilmiştir. Story'ler veri toplama, veri işleme, veri seti düzenleme ve etiketleme görevlerine ayrılarak Sprint Board üzerinden takip edilmiştir.


- **Daily Scrum:** Daily Scrum toplantılarının ekip üyelerinin uygunluk durumuna göre WhatsApp grubu üzerinden gerçekleştirilmesine karar verilmiştir. Günlük ilerleme durumu, yapılan çalışmalar ve karşılaşılan engeller grup üzerinden paylaşılmıştır.


- **Sprint board update:** Sprint Board ekran görüntüleri Readme içerisinde paylaşılmıştır. Sprint sonunda;
  - Tamamlanan görevler:
    - Gerekli araçların (kütüphaneler, yazılımlar) belirlenmesi
    - Meyve resimlerinden oluşan veri setinin toplanması
  - Devam eden görevler:
    - Veri setinin etiketlenmesi
    - Veri setinin eğitim ve test olarak ayrılması
    - Geliştirme ortamının kurulması
    
<img width="1102" height="1416" alt="Meyve Kaşifi (1)" src="https://github.com/user-attachments/assets/3cacfcd1-1ad1-4358-8d38-147c7a4784e5" />


- **Ürün Durumu:** Sprint 2 sonunda model geliştirme süreci için gerekli veri seti büyük ölçüde hazırlanmıştır. Meyvelere ait videolar çekilmiş, bu videolar frame'lere ayrıştırılarak görüntüler elde edilmiştir. Oluşturulan veri seti eğitim (train) ve test olarak düzenlenmiştir. Veri setinin etiketlenme süreci devam etmekte olup, tamamlandıktan sonra YOLOv4 modelinin eğitimine başlanacaktır.


- **Sprint Review:** Sprint boyunca YOLOv4 modeli için kullanılacak veri setinin hazırlanmasına odaklanılmıştır. Meyvelere ait videolar çekilmiş, videolar frame'lere bölünerek görüntüler elde edilmiştir. Elde edilen görüntüler train ve test veri setleri olarak düzenlenmiş, etiketleme çalışmalarına başlanmıştır. Sonraki sprintte veri seti etiketleme işlemlerinin tamamlanması, YOLOv4 modelinin eğitilmesi ve ilk model performans sonuçlarının değerlendirilmesi planlanmaktadır.


Sprint Review katılımcıları:
- Gamze Gül
- Abdullah Akçay
- Gamze Ferizli


- **Sprint Retrospective:**
  - Veri toplama süreci planlandığı şekilde tamamlanmıştır.
  - Veri setinin düzenlenmesi ve train/test ayrımı başarıyla gerçekleştirilmiştir.
  - Etiketleme sürecinin ekip üyeleri arasında paylaştırılarak daha hızlı ilerletilmesine karar verilmiştir.
  - Bir sonraki sprintte veri seti etiketlemesinin tamamlanması ve YOLOv4 model eğitimine başlanması hedeflenmiştir.

    

### Veri Seti Etiketleme Çalışmaları

Sprint 2 kapsamında veri setinin etiketleme çalışmalarına başlanmıştır. Etiketleme işlemleri **MakeSense.ai** platformu üzerinden gerçekleştirilmekte olup, proje için belirlenen **4 farklı sınıf** doğrultusunda bounding box'lar oluşturulmaktadır.

#### Etiketleme Örneği 1

<img width="1920" height="1020" alt="Ekran görüntüsü 2026-07-19 222644" src="https://github.com/user-attachments/assets/101fad67-95f5-4fad-bebf-22392e79f62e" />

#### Etiketleme Örneği 2

<img width="1920" height="1020" alt="Ekran görüntüsü 2026-07-19 222651" src="https://github.com/user-attachments/assets/12d1aa6c-543a-47a7-9901-8af48af408e4" />




 
