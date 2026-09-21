# Arena Simülasyon Örnekleri

Arena ile hazırladığım üretim ve hizmet süreci simülasyonlarını bu repoda topladım. Sekiz farklı senaryoya ait model dosyaları ve simülasyon sonuç raporları bulunuyor.

## Modeller

| Klasör                       | Senaryo                       |
| ---------------------------- | ----------------------------- |
| `1-atolyeornegi`             | Presleme işlemi içeren atölye |
| `2-havaalani_guvenlik`       | Havaalanı güvenlik kontrolü   |
| `3-iki_surecli_atolye`       | Montaj ve boyama süreçleri    |
| `4-elektronik_parca_uretimi` | Elektronik parça üretimi      |
| `5-firin_ornegi`             | Ekmek ve simit üretimi        |
| `6-yemekhane_ornegi`         | Yemekhane hizmet süreçleri    |
| `7-acil_servis_y`            | Acil servis hasta akışı       |
| `8-fabrika_ornegi_y`         | Fabrika işlem akışı           |

## Sonuç raporları

Modellerin `.out` dosyalarında aşağıdaki ölçümler yer alıyor:

* Kuyrukta bekleme süreleri
* Ortalama kuyruk uzunlukları
* Kaynak kullanım oranları
* Sistemde geçirilen süreler
* Sisteme giren ve sistemden çıkan varlık sayıları

Örneğin havaalanı güvenliği modelinin kayıtlı 60 dakikalık çalıştırmasında 30 yolcu sistemden çıkmış, ortalama yolcu bekleme süresi yaklaşık 3,41 dakika ve güvenlik personeli kullanım oranı %90,09 olarak raporlanmıştır.

Bu değerler yalnızca ilgili simülasyon çalıştırmasına aittir; gerçek bir işletmenin ölçümleri değildir.

## Dosyaları inceleme

* Modeli incelemek için ilgili klasördeki `.doe` dosyasını uyumlu bir Arena sürümünde açın.
* Sonuçları okumak için aynı klasördeki `.out` dosyasını açın.
* Yemekhane klasöründe ayrıca senaryoya ait bir PDF bulunuyor.

Model klasörlerinde yardımcı dosyalar ve yedek model dosyaları da tutuluyor.

## Sonuçların kapsamı

Mevcut raporlar tek replikasyonluk çalıştırmalar içeriyor. Modellerin çalışma süreleri ve zaman birimleri farklı olduğundan sonuçlar doğrudan birbirleriyle karşılaştırılmamalıdır.

Bu repo simülasyon örneklerini içerir; doğrulanmış bir optimizasyon veya gerçek işletme performans iyileştirmesi iddiası taşımaz.
