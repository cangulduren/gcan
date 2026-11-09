---
layout: book-review
title: Thinking Like An Engineer
author: Michael Davis
cover: assets/img/book_covers/Thinking-Like-an-Engineer.jpg
olid: OL43499941M # use Open Library ID to fetch cover (if no `cover` is provided)
isbn: 7539967447 # use ISBN to fetch cover (if no `olid` is provided, dashes are optional)
categories: classics crime historical-fiction mystery novels thriller
tags: top-100
buy_link: https://www.amazon.com/Godfather-Deluxe-Mario-Puzo/dp/0593542592
date: 2024-08-23
started: 2024-08-23
finished: 2024-09-07
released: 1969
stars: 5
goodreads_review: 6318556633
status: Finished
---

Prolog: "Görünmez Köprüler" (Invisible Bridges)
Kaynak: G. Madhavan, Applied Minds: How Engineers Think. Özgün anlatımlı ders notudur; çeviri değildir.
🎯 Çıktılar
Mühendisliğin "her yerde ama görünmez" (omnipresent but invisible) olmasını açıklayabilmek
Barkodun iki ayrı buluşun birleşiminden doğduğunu anlatabilmek
Kısıt (constraint) ve çözüm uzayı (solution space) kavramlarını tanımlayabilmek
Bir çözümün beklenmedik alanlara taşınmasını örneklerle tartışabilmek
🗺️ Akış
Aşama	İçerik	Ana fikir
1	Rosie Ruiz vakası (1980)	Büyük ölçekte denetim zordur
2	David Collins ve KarTrak (1959)	Uzaktan otomatik tanımlama
3	George Laurer ve UPC (1970'ler)	Katı kısıtlar altında tasarım
4	Barkodun doğuşu ve ana tez	Mühendislik görünmezdir ama belirleyicidir
5	Maratona dönüş: RFID	Çözümler uyarlanarak yeni alanlara taşınır
1. Sorun: Maratonda Hile
1980 Boston Maratonu'nda Rosie Ruiz kadınlar kategorisinde birinci olarak bitirdi. Yorgun görünmüyordu, antrenman bilgisi yoktu; kontrol noktalarında ve görüntülerde hiç fark edilmemişti. İnceleme, yarışın büyük kısmını koşmadığını gösterdi ve diskalifiye edildi. Yazar olayı bir mühendislik problemi olarak kurar: Binlerce katılımcılı bir yarışta hile otomatik ve güvenilir biçimde nasıl tespit edilir? Temelde bu bir doğrulama (verification) sorunudur.
💡 Güncel örnekler: Çevrim içi sınav gözetimi, spor uygulamalarında GPS kaydı, oyunlarda hile tespit sistemleri.
2. Birinci Buluş: Vagonları Uzaktan Okumak
1959'da ABD demiryollarında yaklaşık 1,6 milyon yük vagonu vardı ve her birinin günlük konumu bilinemiyordu. Sylvania'dan David Collins projeye boş zamanlarında çalıştı. Zorluklar şunlardı: kodlar farklı renk, boyut ve yerde yazılıydı; trenler farklı hızlarla gidiyordu; kar, sis ve kir okumayı bozuyordu; laboratuvar yetmiyor, saha testi gerekiyordu.
Çözümün unsurları:
Işık huzmesiyle okuyan optik tarayıcı (optical scanner)
Tasarım parametreleri: kod noktası boyutu (code spot size), tarama hızı (scan rate), alan derinliği (depth of field)
Bir meslektaşın önerisiyle kodun yan çevrilmesi (yatay çubuk yerine dikey düzen)
Sabit ışık yerine dönen aynalar; sonraki yıllarda lazer
Sistemin adı KarTrak; 1967'ye gelince demiryollarında yayıldı
💡 Güncel örnekler: HGS/OGS geçiş sistemleri, kargo takibi, plaka tanıma sistemleri.
3. İkinci Buluş: Market Rafındaki Kod
1970'lerde market sektörü envanter yönetiminde zorlanıyordu. IBM'den George Laurer, yöneticisinin önerdiği "hedef tahtası" kodunun yetersiz olduğunu görüp riski göze alarak yeni bir tasarım geliştirdi.
Tasarım kısıtları:
Kısıt	Anlamı
Küçük boyut	Yaklaşık bir buçuk inç kare
Her yönden okunabilirlik	Omnidirectionality
Yüksek doğruluk	Yaklaşık %99,995
Farklı ambalajlara uyum	Sabun, kutu, kahve ambalajı
Maliyeti artırmama	Üretim maliyeti sabit kalmalı
Siyah-beyaz çubuk düzeni ışığı soğurup yansıtarak sensörde elektrik sinyaline dönüştü. Prototip testlerinde beklentilerin çok üzerinde doğruluk elde edildi. Kod Evrensel Ürün Kodu (Universal Product Code, UPC) adıyla 1973'te standart oldu.
"Altın tavuk" sorunu: Etin fiyatında olası bir hata çok yüksek tutarla sonuçlanabilirdi. Laurer'in gözlemi: İnsanlar küçük insan hatasını bağışlar, makine hatasını bağışlamaz. Çözüm, koda bir kontrol hanesi (check digit) eklemekti.
💡 Güncel örnekler: IBAN ve kart numaralarındaki doğrulama hanesi, yapay zekâ hatalarına düşük tolerans, otonom araç kazalarının haber değeri.
4. Birleşme ve Ana Tez
Collins'in okuma teknolojisi ile Laurer'in kod standardı birleşerek barkodu oluşturdu ve modern tedarik zincirinin (supply chain) temelini attı.
Yazarın tezleri:
Mühendisler problemleri fırsata dönüştürür; disiplinli, açık fikirli ve gerçekçidir.
Hatalardan öğrenme süreci, ilk fikir kadar önemlidir.
Mühendisler insanlara yeni seçenekler sunan bir çözüm uzayı yaratır.
Paradoks: Mühendislik her yerdedir ama yalnızca bir şey ters gidince (uçak kazası, köprü çökmesi) konuşulur. Gökdelenin başarısı, taşıyıcı sisteminin fark edilmemesidir.
Mühendislik zihniyeti üzerine iki görüş:
Craig Barrett (eski Intel CEO'su): Ayırt edici olan, titiz ve sistematik problem çözmedir.
Jim Plummer (eski Stanford dekanı): Mühendisler entegratördür; uygulanabilirlik (feasibility), sürdürülebilirlik (viability) ve istenirlik (desirability) kesişiminde çalışır.
💡 Güncel örnekler: 6 Şubat 2023 depremlerinde yapı mühendisliğinin ancak felaket anında görünür olması, Temmuz 2024 CrowdStrike kesintisinde altyapı yazılımının çökünce fark edilmesi.
5. Maratona Dönüş: Uyarlama
Boston olayından sonra New York Road Runners, Collins'e barkodla koşucu takibini sordu. Collins başta fikri reddetti; denemeler, vagonda çalışanın insanda (ter, hareket, sallanan numara) doğrudan çalışmadığını gösterdi. Uyarlama: Koşucular bitiş çizgisinde sıraya girip okutuldu. Hileyi doğrudan çözmek ise yıllar sonra başka bir mühendis ve RFID (radio-frequency identification) ile mümkün oldu. Bugün giysi veya ayakkabıdaki çipler saniyenin kesirleriyle izleme sağlar. Collins bunu öngörmediği bir uç uygulama (outlier application) olarak niteler.
💡 Güncel örnekler: AirTag benzeri takip etiketleri, mağazalarda RFID stok sayımı, hastane hasta bileklikleri, QR kodlu ödeme.
📚 Sözlük
Türkçe	English	Kısa açıklama
Çözüm uzayı	Solution space	Mümkün çözümler kümesi
Kısıt	Constraint	Tasarımı sınırlayan koşul
Şartname	Specification	Ölçülebilir gereksinim
Kontrol hanesi	Check digit	Hata yakalayan doğrulama hanesi
Her yönden okunabilirlik	Omnidirectionality	Açıdan bağımsız okuma
Tedarik zinciri	Supply chain	Üretimden tüketiciye akış
Uygulanabilirlik / Sürdürülebilirlik / İstenirlik	Feasibility / Viability / Desirability	Mühendislik kesişim üçlüsü
RFID	Radio-frequency identification	Radyo dalgasıyla kimlik okuma
Uç uygulama	Outlier application	Öngörülmemiş kullanım
💬 Tartışma
Bir teknolojinin tasarlandığı amacın dışında kullanılması ne zaman yararlı, ne zaman riskli olur?
Laurer'in yöneticisinin talimatına karşı çıkması etik açıdan nasıl değerlendirilir?
"Makine hatası bağışlanmaz" gözlemi yapay zekâ tasarımını nasıl etkilemelidir?
Mühendislik neden yalnızca bozulunca görünür olur? Kendi çevrenizden örnek veriniz.
Bir ürünün uygulanabilir, sürdürülebilir ve istenir olması ne demektir?
✅ Kontrol Listesi
[ ] Rosie Ruiz vakasının mühendislik sorusunu anlatabiliyorum
[ ] KarTrak ve UPC'nin farklı kökenlerini ayırt edebiliyorum
[ ] Laurer'in en az üç tasarım kısıtını sayabiliyorum
[ ] "Her yerde ama görünmez" paradoksunu güncel örnekle açıklayabiliyorum
