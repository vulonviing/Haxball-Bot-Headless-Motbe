# 🏫 Mötbe 🎓 Kliması

## **Önsöz**

2019 yılında başlatmış olduğum Mötbe projesi Haxball adlı oyunda Real Soccer adı verilen gerçek futbol kurallarına uygun oyun sistemini seven kullanıcıları bir araya getirmeye yönelik bir işti. Mötbe Kliması adını verdiğim bu bot ise oyunun kurallarını en efektif bir şekilde oyuncuya yansıtmayı ve oyuncunun oyun deneyimini geliştirecek birçok fonksiyonu da sunmayı amaç edinmiş bir scripttir.

Mötbe adını verdiğim Real Soccer severlerden oluşan oluşum son derece başarılı oldu. **Günlük yaklaşık 100'ün ve aylık olarak yaklaşık 2000 oyuncunun oyun odalarımıza giriş yapmasının yanı sıra yaklaşık 2000 kişilik de dev bir Discord grubumuz oluştu.**

Zaman içerisinde başlatmış olduğum bu proje kendi sadık oyuncularını toparladı ve bu oyuncular yönetim kadrosu olarak Mötbe topluluğunun kemik kitlesi oldular. Benim de dahil olduğum yönetim kadromuz yaklaşık 8-10 kişilikti.

Oluşum, kuruluşundan yaklaşık 5-6 ay sonra yönetim kadrosunun ortak fikriyle sonlandırıldı. Sonlandırılma nedeni hem oyuna olan açlığımızın bitmesi, hem iş ve eğitim hayatımızın yoğun fikstüründe hızla büyüyen 2000 kişilik oyuncu grubunu idare etmemizin gittikçe zorlaşmasıydı.

Tamamen gönüllü olarak yürüttüğümüz bu projede her gün odalarımıza gelen yüzlerce oyuncuya ve Discord grubumuza katılan binlerce kişiye 2019 yaz aylarını mükemmel geçirmemi sağladıkları için hiç teşekkür etme fırsatım olmadı. **Topluluğa yaptıkları katkıdan ve oyun sistemimize verdikleri şanstan ötürü aradan geçen üç sene sonra bütün topluluğumuza teşekkürü bir borç bilirim.**

Topluluğun büyümesinde ve botun gelişmesinde emeği geçen Mafiaso, BeetLeguesse (Emirkaan Sait), GooSe (Egecan Eren), Barış Toper, Carillo (Hidayet), Slazka (Okan), Ric7 (Özgür), Sadık, Fitbolcu, Ceyhan, Leviosa (Umut) ve Hi'ye şükranlarımı sunuyorum.

Bunun yanı sıra adını saymayı unuttuğum ya da atladığım bütün kemik oyuncu topluluğumuza yeniden teşekkürler. Siz olmasaydınız iki bin satırlık bu botu sıfır kodlama bilgisi ile geliştirmeye ve oyun deneyimimizi mükemmele yaklaştırmaya hiç uğraşmazdım...

## **Bot Üzerine - Mötbe Kliması**

Topluluğumuzun bu denli hızlı büyümesindeki en büyük etken şüphesiz ki sunduğumuz oyun deneyiminin mükemmele yakın olmasıydı. Mükemmele yakın olan oyun deneyimini de hazırlamış olduğum bu bota ve oyun yönetimlerini ahlaklı bir şekilde yapan yönetim ekibimize borçluyum. 

**Şu anda görmüş olduğunuz bu bot 2019 yılı özelinde bütün Haxball oyuncu topluluğunda bulunan en efektif ve en verimli oyun scriptidir. Öyle ki bu scripte eklemiş olduğum bazı fonksiyonlar bugünün yeni nesil botlarında bile hâlâ mevcut değil.** İlgili dönemde sadece güvendiğim kişilere verdiğim ve sakladığım bu botu artık tamamen açıyorum.

Haxball, Haxe programlama dilini temel almış bir oyundur. Java temelli düzenlemelerle Headless üzerinden oyun içerisinde oda açmanız ve bu odaları yaptığınız script üzerinden farklı fonksiyonlarla yönetmeniz, farklı özellikler kazandırmanız mümkündür. 

**Lütfen botun kodlamasını dikkate alırken benim Java hakkında hiçbir fikrim olmadığını bilin. Ben bu botu yaptığımda tamamen kodda gerçekleştirmiş olduğumu deneme yanılma yöntemini ve GitHub, Stackoverflow gibi platformlar üzerinden bulmuş olduğum örnek kodlamaları kullandım.** Botu yaparken bir tutorial açıp izlemişliğim bile yoktur ki bugün de hâlâ Java'ya hakim değilim. 

Botun temeli Wazarr94'ün yazmış olduğu Headless Bot'a dayanmaktır. **Thanks a lot to Wazarr94 for sharing source of his Headless Bot.**

## **Fonksiyonlar**

1. v6 harita switch opsiyonu. (6'ya 6 oynanan 12 kişilik harita.)
2. v6 kanatlı harita switch opsiyonu. (Normal şartlarda 1-3-6-8-10-9 olan dizilimi 1-3-6-7-11-9 olarak kanatlı tipe dönüştürür.)
3. v7 harita switch opsiyonu. (7'ye 7 oynanan 14 kişilik harita.)
4. Özelleştirilmiş duyuru opsiyonu.
5. Bütün chati susturma ve yeniden açma opsiyonu.
6. Küfür filtresi.
7. Oda çökertme BUG'ını engelleme filtresi. (O günlerde bütün odaların çökmesini sağlayan baş belası bir BUG'dı. Günümüzde bu BUG hâlâ devam ediyor mu bilmiyorum.)
8. Fısıldama opsiyonu. (Oyuncuların birbirleriyle özel olarak konuşmasını sağlar.)
9. v6 ve v7 için özel hazırlanmış dizilim mapleri opsiyonları.
10. Kaptan opsiyonu. (Takım kaptanı seçimi ve kaptanın oyuncuları istediği gibi çekebilmesi.)
11. Gelişmiş dizilim sistemine sahip mapler.
12. Gelişmiş ivmeleme ve top hızı ayarlamalarına sahip mapler.
13. Şut, aut ve korner imkânı tanıyan yay sistemi. (Şu anki botlarda kod içerisinde oto verilen bir durum. 2019 yıllarında oyun kodlarına bu sistem entegre edilmediği için botumda mevcut değil.)
14. Aut ve korner atışlarına özel kurallar ekleyen mapler.
15. Kimlik doğrulama sistemi (Auth ve conn id'leri baz alan bu sistem mükemmele yakın çalışmaktadır. Bot içerisinde göreceğiniz auth ve conn'lar kişilerin ip ve tarayıcı keylerinin ortaya çıkmaması adına tarafımca değiştirildi.)
16. Oyuncuların auth ve conn id'lerini görme, loga yansıtma.
17. Aynı bilgisayar üzerinden birden fazla kullanıcı ile giriş olursa uyarı sistemi.
18. Kara liste sistemi. (Oyun içerisinde ciddi küfür ve hakaret edenler topluluğumuzdan bu yöntem ile tamamen banlanıyorlardı.)
19. Taç sistemi. (Günümüzde Haxball'ın sunduğu imkânların artması doğrultusunda daha modern ve verimli hale gelmiş durumdadır.)
20. Gol, taç, aut, korner ve benzeri duyuruların sistemleri.
21. Gol halinde forma ve top değişimi.
22. Eşitlik durumları adına hile dedektörlü penaltı sistemi.
23. Kilitlenmiş mapler. (Maplerin save edilmesi mümkün değildir. An itibariyle public olarak açtığım için bu özelliğin pek bir sürprizi kalmadı.)
24. Afk tespiti ve banlama sistemi.
25. Bot üzerinden ban sistemi.
26. Fikstür sistemi. (Turnuvalarda kimin kaç gol attığını gösteren gol krallığı sistemi.)
27. Dolu oda bildirimleri.
28. Oyuncu ve top boyutu değiştirme sistemi.
29. Admin ve süperadmin sistemi. (Odanın asıl yöneticileri süperadmin tagını alarak adminlik tagı alan yöneticilerin kendilerini atma ve sistemi ele geçirme şansını bloke ediyordu. Bir nevi gelişmiş bir güvenlik sistemi.)
30. Oda kilitleme ve açma sistemi.
31. Spam filtresi. (5 kademeli olarak saniyeleri ayarlanabiiyor.)
32. Mevki, aut ve taç kural hatırlatmaları.
33. Çeşitli fonksiyonlara (fısıldama, spam, susturma ve benzeri) tam kontrol. Fonksiyonları açabilme ve kapatabilme yetkisi.
34. Big, small ve benzeri haritalara switch opsiyonu.

Bütün bunların yanı sıra hatırlamadığım, kod içerisinde gömülü olarak bulabileceğiniz farklı fonksiyonlar da bulunabilir.

## **Komutlar**

**-solo :** Benim kullandığım süperadmin komutu. Oyunun en üst düzey admin komutudur. Diğer yöneticilerimizin de şahsi admin komutları bulunmaktadır, kodlara gömülü olarak onlarınkileri de bulabilirsiniz.<br />
**-diz :** v6 dizilim haritasını açar. <br />
**-dizkanat :** v6 kanatlı dizilim haritasını açar. <br />
**-real :** v6 mapini açar.<br />
**-realyay :** yaylı v6 mapini açar.<br />
**-realkanat :** kanatlı v6 mapini açar.<br />
**-pen :** penaltı mapini açar.<br />
**-classic, -big, -huge :** adı geçen varsayılan mapleri açar.<br />
**-realv7 :** v7 mapini açar.<br />
**-dizv7 :** v7 dizilim haritasını açar.<br />
**-slowmode2, -slowmode5, -slowmode10, -slowmode20, -slowmode0 :** verilen sayı kadar saniyelik slowmode açar. 0 komutu 0 saniyedir ve dolayısıyla slowmode'u kapatır.
**-susun :** chati susturur.<br />
**-konuşun :** susturmayı kaldırır.<br />
**-spam0, -spam1 :** 0 spam filtresini kapatır, 1 açar.<br />
**-whisper0, -whisper1 :** 0 fısıldama özelliğini kapatır, 1 açar.<br />
**-size0, -size1 :** 0 boyut özelliğini kapatır, 1 açar.<br />
**-kaptan0 :** kaptanları temizler.<br />
**-korner, -aut, -taç, -bigbrother, -v7, -kanat, -mevki:** adı geçen kurallara yönelik duyurular yapar.<br />
**-kilitle, -kilidiaç :** odayı kilitler ve açar.<br />
**-affet :** odadan banlanan herkesin banını kaldırır, fakat bu blackliste alınanlar için dahil değildir. blacklistin manuel olarak kaldırılması gerekir.<br />
**-komutlar :** komutları sıralar.<br />

Atlamış olduğum komut olma ihtimali mevcuttur. Daha fazlası için kodlara göz atabilirsiniz.

## Sonsöz

Scriptin bugünkü Haxball topluluğuna yararlı olmasını ve botlara yeni fonksiyonlar sunmasını diliyorum. Bütün Haxball topluluğu, var olun, **and many thanks to Basro for creating Haxball, Haxball community and beatiful stories for us.**
