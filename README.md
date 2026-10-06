# gate io komisyon indirimi: VIP seviyesi, GT ile ödeme ve emir tipi seçimiyle spot ücretini %0,10'un altına indirme rehberi

Gate'te işlem ücreti tek bir sayı değil. Hesabına bakıldığında üç ayrı şey aynı anda belirliyor: VIP seviyen, ücreti hangi varlıkla ödediğin ve emrin maker mı taker mı sayıldığı. "Komisyon indirimi" arayan çoğu kişi aslında bu üçünün nasıl bir araya geldiğini bilmiyor, çünkü tanıtım sayfaları genelde sadece manşet oranı yazıp geçiyor.

Kısa cevap: yeni açılmış bir hesapta spot işlem ücreti maker ve taker için de yüzde 0,10. GT ile ödeme seçeneğini açarsan bu oran yüzde 0,09'a düşüyor. Vadeli tarafta USDT marjinli sözleşmelerde VIP 0 seviyesinde maker yüzde 0,02, taker yüzde 0,05. Bunun altına inmek için ya hacim/GT/varlık eşiklerinden birini geçmen ya da ürün seçimini değiştirmen gerekiyor — ve ürün seçimi çoğu kişinin fark etmediği kısım.

## Gate'in ücret yapısını üç kalem belirliyor

Kafa karışıklığının kaynağı, Gate'in ücret tablosunu ürün bazında ayrı ayrı yayınlaması. Aynı hesapta spotta yüzde 0,10 ödeyen biri, USDC/USDT paritesinde sıfır ödüyor, vadeli tarafta bambaşka bir orana geçiyor.

- **VIP seviyesi**: 30 günlük işlem hacmi, 14 günlük ortalama GT varlığı ya da hesap varlık değeri üç ayrı kapı. Hangisi sana daha iyi sonuç veriyorsa seviye ona göre belirleniyor.
- **Ücreti neyle ödediğin**: GT bakiyenle ödeme yaptığında oran düşüyor. Bu indirim VIP 10'a kadar sürüyor, sonrasında iki sütun aynı sayıya dönüşüyor.
- **Emir tipi ve ürün**: Maker (emir defterine likidite ekleyen limit emri) ile taker (karşıdan alan piyasa emri) oranları düşük seviyelerde aynı, yüksek seviyelerde ayrışıyor. Ayrıca hangi sözleşmede işlem yaptığın da oranı değiştiriyor.

## VIP 0 seviyesinde gerçekte ne ödüyorsun?

| Ürün | Maker | Taker |
| --- | --- | --- |
| Spot (VIP 0, GT olmadan) | %0,10 | %0,10 |
| Spot (GT ile ödeme) | %0,09 | %0,09 |
| USDT marjinli sürekli vadeli (VIP 0) | %0,02 | %0,05 |
| USDC/USDT paritesi | %0 | %0 |
| Alpha işlemleri | — | %0,8 (tüm seviyelerde sabit) |
| Kripto yatırma | ücretsiz | — |
| Kripto çekme | ağa göre değişir | — |

Vade tarafında ücret, yatırdığın teminata göre değil pozisyonun nominal büyüklüğüne göre hesaplanıyor. 60.000 dolarlık bir pozisyonu piyasa emriyle açarsan VIP 0 taker oranıyla 30 dolar, limit emriyle girip maker olarak eşleşirsen 12 dolar ödüyorsun. Aynı işlem, iki farklı maliyet.

> Gate 9 Nisan 2026'da spot ve vadeli ücret yapısını güncelledi; VIP 10 ve üzerindeki seviyelerde maker oranı sıfırdan küçük pozitif değerlere çekildi, vadeli taker oranları da sözleşme gruplarına ayrıldı. Instagram'da ya da eski blog yazılarında gördüğün tablolar bu yüzden yanlış olabilir.

## VIP seviyesi: üç kapıdan hangisi açıksa

Gate'te seviye, üç ölçütün en iyisine göre belirleniyor ve düzenli olarak otomatik yeniden hesaplanıyor. Üç yolu aynı anda doldurman gerekmiyor.

1. **30 günlük işlem hacmi**: Burada püf noktası, hacmin ürünlere göre farklı ağırlıklandırılması. Spot ve hisse işlemleri yüzde 100 sayılıyor, USDT/BTC vadeli işlemleri yüzde 40, USD1 sözleşmeleri ve opsiyonlar yüzde 20, CFD işlemleri yüzde 10. Yani spotta 100.000 dolar hacim yapan biri ile vadeli tarafta 100.000 dolar hacim yapan biri aynı seviyeye çıkmıyor.
2. **14 günlük ortalama GT varlığı**: Günlük bakiyenin ortalaması alınıyor, tek seferlik alım yetmiyor. VIP 1 için 50 GT, VIP 5 için 2.000 GT, VIP 14 için 1.500.000 GT gibi eşikler var.
3. **Hesap varlık değeri**: VIP 1 için 2.000 dolar, VIP 5 için 40.000 dolar, VIP 10 için 2.000.000 dolar civarı.

Sadece 40.000 dolar civarı varlık tutup orta düzey hacimle işlem yapan biri VIP 5'e çıkabiliyor; yüksek frekanslı çalışan biri 1 milyon dolarlık 30 günlük hacimle aynı seviyeye ulaşabiliyor. Hangisinin sana daha ucuz olduğu, ne kadar sık işlem yaptığına bağlı.

### Tüm VIP seviyeleri ve spot oranları

| Seviye | 30 günlük hacim eşiği | Spot maker/taker | GT ile ödeme |
| --- | --- | --- | --- |
| [VIP 0](https://bit.ly/GateVIP) | eşik yok | %0,10 / %0,10 | %0,09 / %0,09 |
| [VIP 1](https://bit.ly/GateVIP) | 60.000 $ | %0,099 / %0,099 | %0,089 / %0,089 |
| [VIP 2](https://bit.ly/GateVIP) | 120.000 $ | %0,098 / %0,098 | %0,088 / %0,088 |
| [VIP 3](https://bit.ly/GateVIP) | 240.000 $ | %0,097 / %0,097 | %0,087 / %0,087 |
| [VIP 4](https://bit.ly/GateVIP) | 500.000 $ | %0,095 / %0,096 | %0,086 / %0,086 |
| [VIP 5](https://bit.ly/GateVIP) | 1.000.000 $ | %0,09 / %0,095 | %0,081 / %0,085 |
| [VIP 6](https://bit.ly/GateVIP) | 3.000.000 $ | %0,085 / %0,09 | %0,076 / %0,081 |
| [VIP 7](https://bit.ly/GateVIP) | 8.000.000 $ | %0,08 / %0,085 | %0,07 / %0,076 |
| [VIP 8](https://bit.ly/GateVIP) | 20.000.000 $ | %0,075 / %0,08 | %0,06 / %0,072 |
| [VIP 9](https://bit.ly/GateVIP) | 50.000.000 $ | %0,07 / %0,075 | %0,05 / %0,068 |
| [VIP 10](https://bit.ly/GateVIP) | 100.000.000 $ | %0,04 / %0,058 | seviye oranıyla aynı |
| [VIP 11](https://bit.ly/GateVIP) | 120.000.000 $ | %0,03 / %0,045 | seviye oranıyla aynı |
| [VIP 12](https://bit.ly/GateVIP) | 240.000.000 $ | %0,02 / %0,037 | seviye oranıyla aynı |
| [VIP 13](https://bit.ly/GateVIP) | 440.000.000 $ | %0,01 / %0,03 | seviye oranıyla aynı |
| [VIP 14](https://bit.ly/GateVIP) | 800.000.000 $ | %0,008 / %0,023 | seviye oranıyla aynı |
| [VIP 15](https://bit.ly/GateVIP) | 1.600.000.000 $ | %0 / %0,02 | seviye oranıyla aynı |
| [VIP 16](https://bit.ly/GateVIP) | 3.000.000.000 $ | %0 / %0,0175 | seviye oranıyla aynı |

Tabloda göze çarpan üç şey var. İlki, VIP 0–VIP 3 arasında maker ve taker oranı birebir aynı: emri defterde bekletmenin bu seviyelerde tek kuruş avantajı yok. Ayrışma VIP 4'te başlıyor ve oran VIP 9'a kadar bir baz puanın altında kalıyor. İkincisi, VIP 10'dan sonra GT ile ödemenin getirisi sıfırlanıyor. Üçüncüsü, sıfır maker oranı ilk kez VIP 15'te geliyor — yani ücretsiz işlem reklamı yapan borsaların standart saydığı orana ulaşmak için 15 seviye yükselmen gerekiyor.

## GT ile ödeme: küçük ama gerçek bir indirim

GT bakiyesiyle ücret ödemek, hesap ayarlarından açılan bir anahtar. Açıkken Gate önce GT'den çekiyor, bakiye yetmezse otomatik olarak VIP oranına dönüyor.

Etkisi şu ölçekte: 10.000 USDT'lik bir spot işlemde standart oran yüzde 0,10 ise 10 USDT, GT ile yüzde 0,09 ise 9 USDT ödüyorsun. Alış ve satışı birlikte düşünürsen 20 USDT yerine 18 USDT. Tek işlemde fark küçük, ayda 1 milyon USDT'lik benzer hacim ürettiğinde teorik fark 100 USDT civarına çıkıyor. GT bakiyesi aynı zamanda VIP eşiğinde sayıldığı için iki tarafı birden besliyor.

İki sınırı baştan bilmekte fayda var: GT ile ödeme sadece spot ücretlerde geçerli, vadeli işlem ücretlerinde değil. Ve VIP 10'dan sonra iki sütun aynı sayıya dönüştüğü için token tutmanın oran avantajı kalmıyor — o noktadan sonra GT'nin faydası seviye hesabına girmesiyle sınırlı.

👉 [Hesabını açıp GT ile ödeme ayarını kontrol et](https://bit.ly/GateVIP)

## Emir tipini değiştirmek, VIP beklemekten hızlı sonuç veriyor

VIP seviyesi yükseltmek hacim ya da ciddi varlık gerektiriyor. Emir tipini değiştirmek ise bugün yapılabilecek bir şey ve yüksek seviyelerde fark ciddi boyuta çıkıyor. VIP 9'da spot maker yüzde 0,07, taker yüzde 0,075; 100.000 USDT'lik bir işlemde aradaki fark 5 USDT. Tek işlemde önemsiz görünüyor, ama limit emriyle çalışan bir stratejide ayda yüzlerce işlem demek.

Vadeli tarafta daha net bir örnek var: Gate, 13 Ağustos 2026'dan itibaren USD1 marjinli sürekli vadeli sözleşmelerde maker ücretini yüzde 0'a, taker ücretini temel oranın yüzde 25'ine indirdi ve kampanya ek bildirim yapılana kadar sürüyor. BTCUSD1'de VIP 0 için taker oranı böylece yüzde 0,05'ten yüzde 0,0375'e iniyor; 10.000 dolarlık bir pozisyonda 5 dolar yerine 3,75 dolar. Bu kampanya VIP 0–VIP 16 aralığının tamamını kapsıyor ve USD1 marjinli dokuz sözleşmede geçerli — BTC, ETH, SOL'un yanı sıra altın, gümüş ve bazı hisse bağlantılı kontratlar.

Burada dürüst olmak gerekirse: sıfır maker ücreti, işlem maliyeti sıfır demek değil. Spread, kayma, fonlama oranı ve likidite derinliği toplam maliyetin parçası olmaya devam ediyor. Fonlama oranı özellikle pozisyonu uzun tutanlarda işlem ücretini kolayca geçebiliyor.

## Sabit sıfır oranlı iki alan: stablecoin paritesi ve hisse tarafı

USDC/USDT paritesinde Gate maker ve taker ücretini sıfır uyguluyor. Tek şartı var: bu paritedeki hacim VIP seviyesi hesabına sayılmıyor, yani ücretsiz işlem yapayım derken seviye atlama hacmini büyütmüş olmuyorsun.

Hisse tarafında Gate Stocks, 1 Ağustos'tan itibaren uygun ABD hisse ve ETF'lerinde sıfır işlem ücreti uyguluyor; hesap açma, bakım ve minimum işlem ücreti de sıfır. Üçüncü taraf takas ve düzenleyici masraflar kullanıcıda kalıyor. Program sona erdiğinde kademeli yapıya dönüleceği ve VIP 0'da oranın yüzde 0,1 olduğu belirtiliyor.

Alpha işlemlerinde ise oran tüm seviyelerde yüzde 0,8 sabit — VIP yükseltmenin burada hiçbir etkisi yok.

## Davet kodu ve referans: neyi değiştirir, neyi değiştirmez

"Komisyon indirimi" arayanların sık düştüğü yanılgı burada başlıyor. Gate'in davet programı sayfalarında öne çıkan yüzde 40 oranı, **işlem ücretinden alınan pay** — ve bu pay davet edene gidiyor, davet edilen kişinin kendi işlem oranını düşürmüyor. Yani bir davet kodu girmek senin spot oranını yüzde 0,10'dan yüzde 0,08'e çekmiyor. Oranı belirleyen şey yukarıdaki VIP tablosu ve ücreti neyle ödediğin.

Yeni kayıt tarafında ise kampanyaya bağlı hoş geldin ödülleri var; Gate'in duyuru sayfalarında 10.000 dolara kadar hoş geldin ödülü ifadesi geçiyor, ancak bunlar koşullu ve kampanya bazlı. Ayrıca coğrafi kısıtlamalar gerçek: davet kampanyalarının bir bölümünde Türkiye, Belçika, Birleşik Krallık, Fransa, Almanya, Hollanda, Avusturya ve Güney Kore'deki kullanıcılar kapsam dışında bırakılıyor. Kayıt olmadan önce ilgili kampanya sayfasındaki koşulları okumak, sonradan "ödül gelmedi" durumuna düşmemek için gerekli.

👉 [Kayıt sayfasındaki güncel kampanya koşullarını gör](https://bit.ly/GateVIP)

## Yatırma ve çekme tarafı: işlem ücretinden ayrı bir kalem

Kripto yatırma Gate tarafında ücretsiz; P2P işlemleri de komisyonsuz. Çekme ücreti ise sabit değil, ağa ve yoğunluğa göre yaklaşık saatlik güncelleniyor. Küçük tutarları Ethereum ana ağından çekmek, ücretin transferin ciddi bir kısmına denk gelmesine yol açıyor. Tron veya ikinci katman ağları gibi daha ucuz seçenekler varsa kullanmak, birden fazla küçük çekimi tek işlemde birleştirmek pratikte en çok tasarruf sağlayan iki yöntem.

24 saatlik çekim limiti de VIP seviyesine bağlı: VIP 0'da 3.000.000 dolar, VIP 5'te 5.000.000, VIP 9'da 8.000.000, VIP 14'te 30.000.000, VIP 16'da 50.000.000 dolar. Yüksek hacimle çalışan biri için bu tavan, ücret oranından daha kritik bir kısıt olabiliyor.

## Türkiye'den işlem yaparken pratik notlar

Gate'te Türk lirası, desteklenen para birimleri arasında listeleniyor; arayüzde TRY kurlarını görebiliyorsun. Bölgeye özel bir arayüz de mevcut. Öte yandan para birimi ve banka kaynaklı ücretler yerel düzenlemelere ve ödeme sağlayıcısına bağlı olduğu için ücret tablosunun dışında kalıyor — bunları hesabındaki ödeme ekranında görmen gerekiyor.

Bir de şu var: giriş yapmadan gördüğün ücret tablosu ile hesabına giriş yaptıktan sonra gördüğün oranlar farklı olabilir. Sana gerçekte yansıyan sayı hesabındaki VIP sayfasında yazandır, dışarıdaki tablolar değil.

## Örnek maliyet hesabı

Somut bir senaryo: ayda 10 spot alım-satım yapan, her işlemde 5.000 USDT hacim üreten bir hesap. Aylık hacim 100.000 USDT.

- VIP 0, GT olmadan: 100.000 × %0,10 = 100 USDT
- VIP 0, GT ile: 100.000 × %0,09 = 90 USDT
- VIP 5, maker ağırlıklı çalışma: 100.000 × %0,09 = 90 USDT, plus GT ödemesiyle 81 USDT

Yani GT ayarını açmak ve emirlerini limit olarak girmek arasında kalan fark, aynı hacimde yüzde 10–19 arası bir tasarruf demek. Bunun için ekstra para yatırmak gerekmiyor; sadece iki ayarı değiştirmek yeterli.

## Sık yapılan dört hata

**GT ile ödemeyi açık bıraktığını sanmak.** Ayarlar sıfırlanabilir ya da bakiye yetmediğinde sistem otomatik olarak VIP oranına döner. Ayın ortasında kontrol etmekte fayda var.

**Emir defterini hiç kullanmamak.** VIP 0–VIP 3 arasında maker avantajı yok, o yüzden düşük hacimli kullanıcıda bu bir şey değiştirmiyor. Ama VIP 4 ve üzerinde oran farkı açılıyor, ayrıca USD1 marjinli sözleşmelerde maker ücreti şu anda sıfır. Alışkanlığı erkenden oturtmak sonradan para kazandırıyor.

**Vadeli işlem maliyetini sadece işlem ücretinden ibaret sanmak.** Fonlama oranı sekiz saatte bir ödeniyor veya tahsil ediliyor ve pozisyonu uzun tutan biri için işlem ücretini rahatça geçebiliyor.

**Eski blog tablolarına güvenmek.** Gate 9 Nisan 2026'da ücret yapısını değiştirdi; VIP 10 ve üzerindeki maker oranları ve vadeli taker gruplaması o tarihte güncellendi. Eski ekran görüntüleriyle hesap yapmak yanlış sonuç veriyor.

## Sonuç: hangi ayar kime yarıyor

Düşük hacimle işlem yapan biri için en hızlı kazanç GT ile ödeme ayarını açmak; yüzde 0,10 yerine yüzde 0,09 ödemek ve bunun için hiçbir şey yapmamak. Orta hacimli, sık işlem yapan biri için asıl fark limit emri kullanma alışkanlığında — çünkü VIP 4 sonrası maker/taker ayrışması ve USD1 sözleşmelerindeki sıfır maker kampanyası burada devreye giriyor. Yüksek hacimli ya da ciddi GT varlığı tutan biri içinse seviye sistemi çok daha agresif çalışıyor; VIP 9'dan itibaren oranlar tek haneli baz puanlara düşüyor.

Davet kodu bu denklemin parçası değil. Komisyon payı davet edene gidiyor; senin oranın VIP tablosu, GT ödemesi ve emir tipinle belirleniyor. Bu üçünü doğru kurmak, herhangi bir kod avlamaktan daha çok para bırakıyor.

👉 [Gate hesabını aç, VIP seviyeni ve güncel ücret oranlarını kendi hesabında gör](https://bit.ly/GateVIP)
