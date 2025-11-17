---
layout: post
title: "Ödev" Meselesini Tekrar Düşünmek: Veriye Dayalı Bir Kılavuz"
description: "K-12 eğitiminde yüz yıllık ödev tartışmasını son 15 yıldaki araştırma verileriyle yeniden değerlendiren kapsamlı analiz. Ödevin etkinliği, yaş gruplarına göre farklılıklar, tasarım ilkeleri ve öğrenci refahına etkileri bilimsel verilerle inceleniyor. #Eğitim #Ödev #K12"
date: 2025-11-17
feature_image: images/i251117001.jpg
tags: [eğitim, ödev, k-12, pedagoji, öğrenme]
---

K-12 eğitim kurumlarında dijital araçlar yoğun şekilde kullanılıyor ve bu da birçok siber güvenlik riskini beraberinde getirmekte. Okulların yüksek hacimde kişisel / kurumsal veriye sahip olması, onları siber saldırganların gözünde "hedef açısından zengin, siber güvenlik açısından yetersiz" yapılara dönüştürüyor[[1]](https://www.cisa.gov/K12Cybersecurity). ABD'deki bir araştırmaya göre her okulda günde en az bir siber olay yaşanıyor[[2]](https://www.cisa.gov/K12Cybersecurity). Bu nedenle okulların siber güvenliğe yatırım yapması, yalnızca bilgisayar ağlarını değil bütün bir eğitim ekosistemini ve hatta toplumu korumak anlamına geliyor.

<!--more-->

Kamu ve özel sektör iş birlikleri bu alanda kritik öneme sahip. Örneğin CIS (Center for Internet Security) ve MS-ISAC'ın 2025 raporu, Temmuz 2023 – Aralık 2024 arasında 5 binden fazla K-12 kurumunu inceledi. Çalışma, okulların siber saldırıların birincil hedefleri olduğunu ortaya koydu[[3]](https://www.cisecurity.org/insights/white-papers/2025-k12-cybersecurity-report): İncelenen dönemde kurumların %82'si siber saldırı etkisi yaşarken, toplamda 14 bin güvenlik olayı kaydedildi ve bunların 9 bininden fazlası teyit edilmiş siber saldırı olarak raporlandı[[3]](https://www.cisecurity.org/insights/white-papers/2025-k12-cybersecurity-report). Başka bir deyişle, incelenen her 5 okuldan 4'ü doğrudan siber saldırıyla karşılaştı. CIS raporu ayrıca saldırganların giderek daha sofistike hale geldiğini ve zamanlamada ustalaştığını vurguluyor[[4]](https://www.cisecurity.org/insights/white-papers/2025-k12-cybersecurity-report). Lisa Plaggemier (National Cybersecurity Alliance) gibi uzmanlar da K-12 okullarının genellikle kaynakları kısıtlı, temel güvenlik önlemlerine odaklanamayacak durumda kurumlar olduklarına ve zayıflıklarından dolayı basit hedefler haline geldiklerine işaret ediyor[[5]](https://www.gse.harvard.edu/ideas/edcast/25/04/cybersecurity-greatest-threat-schools-arent-ready)[[6]](https://www.gse.harvard.edu/ideas/edcast/25/04/cybersecurity-greatest-threat-schools-arent-ready). Özetle, dijital çağa uyum sağlamak isteyen okullar, siber tehditlere karşı hazırlıklı olmazlarsa, gelecekte onları eğitim ve hizmet misyonunu sürdürmekte çok daha zorlanacakları günler bekliyor.

## I. Okulların Sağladığı Hizmetler ve Saldırıların Toplumsal Etkileri

K-12 eğitimi aslında toplumun ana yapı taşlarından biri. Bu bakımdan CIS raporu, okulların siber saldırılara maruz kaldığında sadece eğitim yönünden değil aşağıda örneklenen yaşamsal hizmetler yönünden de zarar görebildiğini vurguluyor[[7]](https://www.cisecurity.org/insights/white-papers/2025-k12-cybersecurity-report):

 - **Beslenme desteği:** Kahvaltı ve öğle yemeği programları aracılığıyla yetersiz beslenen çocuklara günlük öğün sağlanır.
 - **Çocuk bakım alanları:** Çalışan ebeveynlerin çocuklarını güvenle bırakabileceği sınıflar ve programlar oluşturulur.
 - **Ruh sağlığı ve danışmanlık:** Öğrencilere psikolojik destek ve rehberlik hizmetleri sunulur.
 - **Özel eğitim hizmetleri:** Özel gereksinimli öğrencilerin eğitim ve gelişim ihtiyaçları karşılanır.
 - **Topluluk merkezleri:** Okul binaları, spor ve kültürel etkinlikler için halkın buluşma noktası olur.

Bu hizmetlerden herhangi biri kesintiye uğradığında etkisi sadece okul saatleriyle sınırlı kalmaz; tüm nüfusa yansır. Özetle rapor "siber saldırılar bu hizmetleri kesintiye uğrattığında etkiler tüm topluma yayılır"[[8]](https://www.cisecurity.org/insights/white-papers/2025-k12-cybersecurity-report) tezini kesin bir dille savunuyor.

## II. Mevcut Durum: Kaynaklar, Algılar ve Risk Değerlendirmesi

En gelişmiş ülkelerde dahi ne yazık ki çoğu K-12 okulu siber güvenlik için yeterli kaynağı ayırmıyor. Örn. ABD merkezli CoSN (Consortium for School Networking) araştırması, siber güvenlik harcamalarının %61 oranında genel bütçelerden karşılandığını, özel bir fon tahsis edilmediğini ortaya koyuyor[[9]](https://www.cosn.org/wp-content/uploads/2025/05/EdTechLeadership_2025_F2.pdf). Aynı araştırmaya göre, okulların siber güvenlik bütçelerinin büyük çoğunluğu (%78) tehdit tespiti, olay izleme ve müdahale sistemlerine harcanıyor[[9]](https://www.cosn.org/wp-content/uploads/2025/05/EdTechLeadership_2025_F2.pdf). Buna rağmen birçok kurum (yaklaşık %44) güvenlik izleme işini dış hizmet sağlayıcılarına yaptırıyor[[9]](https://www.cosn.org/wp-content/uploads/2025/05/EdTechLeadership_2025_F2.pdf). Bu da muhtemelen gerekli uzmanlığı bünyede oluşturma maliyet ve zorluğundan kaynaklanıyor.

Bu harcamalar ve dış kaynak kullanımı, okul idarecilerini güvenlik algısında yanıltabiliyor. CoSN anketine katılanların çoğu, bölümlerinin listelenen tehditler karşısında yüksek risk altında olduğunu düşünmüyor. En büyük endişeleri ise oltalama (phishing) saldırıları: Katılımcıların %27'si bunları ağları için yüksek risk olarak değerlendiriyor[[10]](https://www.cosn.org/wp-content/uploads/2025/05/EdTechLeadership_2025_F2.pdf). Buna karşın, veri ihlali ve fidye yazılımı gibi diğer büyük risklerin (%13'er) daha az fark edilmesi, bir tür bilişsel önyargıya işaret edebilir. Birçok uzman, saldırganların özellikle çocuk verisini hedef aldığını hatırlatıyor; öğrenci bilgilerinin değeri ihmal edilmemeli[[10]](https://www.cosn.org/wp-content/uploads/2025/05/EdTechLeadership_2025_F2.pdf)[[1]](https://www.cisa.gov/K12Cybersecurity).

Türkiye ve diğer ülkelerdeki detaylı araştırmalar sınırlı olsa da genel durum benzer endişeler barındırıyor. K-12 eğitimin dijitalleşmesiyle okul ağları dünyanın her yerinde saldırganlar tarafından zayıf halka olarak görülüyor. Örneğin 2023'te yayınlanan bir küresel analizde, eğitim sektöründe bildirilen fidye yazılımı saldırılarının %36'sının K-12 okullarını hedef aldığı saptandı[[11]](https://www.knowbe4.com/hubfs/Global-Education-Report_US_EN.pdf). Ayrıca Verizon'un 2024 Veri İhlali Raporu'na göre dünyada meydana gelen siber olayların %17'si eğitim sektörüne yönelik, %14'ü teyit edilmiş veri sızıntısı olarak gerçekleşiyor; bu oranlar eğitimi küresel çapta en çok etkilenen beş endüstri arasında gösteriyor[[12]](https://www.knowbe4.com/hubfs/Global-Education-Report_US_EN.pdf). Check Point Research ise 2024 yılında eğitim sektörünün haftalık 3.574 ortalama siber saldırıya maruz kaldığını raporladı – bu, bir önceki yıla göre %75'lik devasa bir artış demek[[13]](https://www.knowbe4.com/hubfs/Global-Education-Report_US_EN.pdf). Microsoft da 2024'te eğitim sektörünün en çok saldırıya uğrayan üçüncü sektör olduğunu ve okullara yönelik günde 15 binden fazla karekodlu oltalama e-postasının engellendiğini bildirdi[[14]](https://www.knowbe4.com/hubfs/Global-Education-Report_US_EN.pdf). Bu küresel veriler gösteriyor ki okulların bilişim alanında daima güncel tehditlerle yüzleşmesi gerekiyor.

## III. Siber Güvenlikte İyileştirme ve Öneriler

K-12 eğitim kurumlarında siber güvenlik düzeyini yükseltmek çok boyutlu hamleler gerektiriyor. Aşağıdaki başlıklar okul idarecilerinin ve diğer tüm eğitim liderlerinin atabileceği bazı temel adımları özetlemekte:

 - **Bütçe ve uzmanlık:** Okullar siber güvenlik için özel bütçeler ayırabilir, gerekirse BT personeline ek eğitim ve sertifikasyon (ör. CISSP, CEH) olanağı tanıyabilir ve/veya iş birlikleri (ör. konsorsiyumlar, devlet destekli bilgi paylaşımı ve analiz merkezleri; İng. Information Sharing and Analysis Center; kıs. ISAC) aracılığıyla uzman desteği alabilir. Kaynak yaratmak zor olsa da "hedef bakımından riskli" konumda olan okulların güvenlik harcamalarına yatırım yapması artık bir gerekliliktir[[1]](https://www.cisa.gov/K12Cybersecurity)[[9]](https://www.cosn.org/wp-content/uploads/2025/05/EdTechLeadership_2025_F2.pdf).

 - **Temel güvenlik önlemleri:** Tüm okul ağlarında ve cihazlarda yazılım güncellemeleri, güçlü parolalar ve Çok Faktörlü Kimlik Doğrulama (İng. Multi-Factor Authentication; kıs. MFA) uygulanmalıdır. Aslında siber suçluların büyük kısmı "güncel olmayan sistemleri, zayıf şifreleri ve temel ihmal hatalarını" sömürdüğü için, bu basit önlemler dahi çok ciddi koruma sağlar[[5]](https://www.gse.harvard.edu/ideas/edcast/25/04/cybersecurity-greatest-threat-schools-arent-ready)[[6]](https://www.gse.harvard.edu/ideas/edcast/25/04/cybersecurity-greatest-threat-schools-arent-ready).

 - **Eğitim ve farkındalık:** Öğretmenler, idareciler, öğrenciler ve veliler düzenli olarak siber güvenlik eğitimi alabilir. Özellikle oltalama e-postalarını tanıma, şüpheli bağlantılara tıklamama ve verileri koruma konusunda farkındalık artırılmalıdır. Bu amaçla ulusal ve bölgesel düzeyde seminerler, tatbikatlar ve simülasyonlar düzenlenebilir. İnsan hatası, K-12 tehditlerinin en yaygın etmenlerinden biridir.

 - **Veri yedekleme ve olay müdahalesi:** Okullar kritik kişisel ve kurumsal verilerini düzenli olarak yedeklemeli; fidye yazılımı veya saldırı durumunda hızlı geri dönüş planları oluşturmalıdır. Okul yönetimleri, bir siber saldırı durumunda kriz iletişimini, derslerin geçici olarak çevrim dışına alınmasını ve sürekli öğrenim imkanlarını sağlayacak iş sürekliliği planlarını önceden hazırlamalıdır. Unutulmamalıdır ki "saldırı kaçınılmaz; önemli olan hazırlıklı olmak ve atlatmaktır"[[15]](https://www.gse.harvard.edu/ideas/edcast/25/04/cybersecurity-greatest-threat-schools-arent-ready).

 - **İş birlikleri ve mevcut kaynaklardan yararlanma:** Ulusal ve uluslararası kurumların sağladığı rehberlik, eğitim ve erken uyarı sistemleri kullanılmalıdır. Örn. CISA'in (Siber Güvenlik ve Altyapı Güvenliği Ajansı) "Protecting Our Future" ('Geleceğimizi Korumak') raporu, K-12 için somut eylem tavsiyeleri sunuyor[[16]](https://www.cisa.gov/K12Cybersecurity). CIS-MS-ISAC gibi platformlar, okul personelini eğiten ücretsiz araçlar ve tehdit istihbaratı paylaşım ağları sağlıyor. Okullar, yer yer benzer deneyimleri paylaşmak için bölgesel eğitim bilişim ağlarına (SLIIA, EDUCAUSE vb.) katılabiliyor.

Örneklenen bu adımlar, okulların ideal siber güvenlik seviyesine ulaşmasına yardımcı olabilir. Diğer yandan bilinç ve iş birliği olmadan teknoloji ne kadar güçlü olursa olsun zafiyetler devam eder. Yukarıda atıfta bulunulan CIS raporunun da vurguladığı üzere siber güvenlik sadece teknoloji meselesi değil, insanları ve toplumu koruma meselesi[[17]](https://www.cisecurity.org/insights/white-papers/2025-k12-cybersecurity-report). K-12 okulları bu bakış açısıyla hareket ederek hem sağlıklı eğitim ortamını hem de toplumsal dayanıklılığı güçlendirebilir.

## IV. Özetle...

K-12 eğitim kurumları, artan dijitalleşmenin getirdiği avantajları bir yandan kullanırken diğer yandan yeni siber risklerle karşı karşıya. Güncel veriler açıkça gösteriyor ki okullar saldırganların gözünde değerli hedefler[[3]](https://www.cisecurity.org/insights/white-papers/2025-k12-cybersecurity-report)[[11]](https://www.knowbe4.com/hubfs/Global-Education-Report_US_EN.pdf). Mevcut durumda ise bütçe ve kaynak eksikliği, güvenlik algısındaki yanlış değerlendirmeler ve eğitimsizlik gibi zorluklar okulları olası saldırılara karşı kırılganlaştırıyor[[9]](https://www.cosn.org/wp-content/uploads/2025/05/EdTechLeadership_2025_F2.pdf)[[10]](https://www.cosn.org/wp-content/uploads/2025/05/EdTechLeadership_2025_F2.pdf). Bu kırılganlığı gidermek, okul idarelerinin, öğretmenlerin ve politika yapıcıların öncelikli sorumluluğu. Yatırım ve eğitimle güçlendirilen bir siber güvenlik kültürü, okulların sadece teknik altyapısını değil; aynı zamanda öğrencilerin, ailelerin ve tüm toplumun güvenliğini de teminat altına alır. Unutulmamalı ki okullar risklerden korunduğu ölçüde toplum da güvende olacak[[17]](https://www.cisecurity.org/insights/white-papers/2025-k12-cybersecurity-report)[[8]](https://www.cisecurity.org/insights/white-papers/2025-k12-cybersecurity-report).

### Kaynaklar

[1] [2] [16] Cybersecurity for K-12 Education | CISA  
https://www.cisa.gov/K12Cybersecurity

[3] [4] [7] [8] [17] 2025 CIS MS-ISAC K-12 Cybersecurity Report: Where Education Meets Community Resilience  
https://www.cisecurity.org/insights/white-papers/2025-k12-cybersecurity-report

[5] [6] [15] Cybersecurity for Schools | Harvard Graduate School of Education  
https://www.gse.harvard.edu/ideas/edcast/25/04/cybersecurity-greatest-threat-schools-arent-ready

[9] [10] 2025 State of EdTech District Leadership  
https://www.cosn.org/wp-content/uploads/2025/05/EdTechLeadership_2025_F2.pdf

[11] [12] [13] [14] knowbe4.com  
https://www.knowbe4.com/hubfs/Global-Education-Report_US_EN.pdf
