# HSMBank Otomasyon Projesi Gereksinim Dokümanı
# Manisa Celal Bayar Üniversitesi / Yazılım Mühendisliği <br/>
# YZM-2105 Nesneye Yönelik Programlama Dersi (2017-2018)
# Dönem Projesi / Banka Yazılım Otomasyonu
Sizden Nesneye Yönelik Programlama tekniklerinden faydalanarak bir Banka Otomasyonu
gerçekleştirmeniz istenmektedir.<br/>
## 1. Yeni Müşteri Ekleme; <br/>
Banka işlemlerini yapacak müşterilerin sisteme eklenmesi işlemi
yapılacaktır. Aynı müşteri numarası başka müşteriler tarafından kullanılamayacaktır. Ayrıca
farklı ayrıcalıklara sahip olan 2 tip müşteri bulunmaktadır. Müşteriler; ticari müşteri, bireysel
müşteri olabilmektedir.
## 2. Hesap Açtırma; <br/>
Bir müşterinin birden fazla hesabı olabilir. <br/>
Her hesabı için ayrı ayrı hesap numarası verilmesi gerekir. Aynı hesap numarası birden
fazla müşteriye verilmemelidir. <br/>
## 3. Para Çekme; <br/>
Müşteri, para çekecekse ilgili bilgiler girilip çekilen tutar kadar bakiyesinden
bakiyesi yetmiyorsa ek hesabını kullanarak para çekme işlemi gerçekleşecektir. Günlük
maksimum para çekme limiti 750 tl dir. Daha fazla para çekilmek istendiği takdirde işlem
gerçekleşmeyecektir. <br/>
## 4. Para Yatırma;<br/>
Müşteri, para yatıracaksa ilgili bilgiler girilip yatırılan tutar kadar bakiyesi
artacaktır.
## 5. Hesaba Havale; <br/>
Müşteri, havale yapacaksa; havale yapacağı kişinin hesabının kayıtlı olması
gerekmektedir. Ardından havale tutarı kadar miktar kendi hesabının bakiyesinden eksilecek,
gönderdiği kişinin bakiyesi artacaktır. Ayrıca Ticari Müşterilerden havale ücreti kesilmez iken,
Bireysel Müşterilerden gönderilecek tutarın %2 oranında havale ücreti kesilmektedir.
## 6. Banka Gelir-Gider Raporu; <br/>
Bankanın gelir-giderleri(bankadan giden, gelen ve bankada
bulunan toplam para miktarı vb.) hesaplanıp görüntülenecektir. <br/> Raporlama için grid bileşeni
kullanmanız beklenmektedir.
## 7. Hesap Özeti; <br/>
Seçilen bir hesap için belirtilen tarih aralığında hesap özeti görüntülenecektir.
Çekilen, yatırılan, havale yapılmışsa kime yapıldığı ve miktarı, başka bir hesaptan havale para
geldiyse kimden geldiği ve miktarı gibi bilgiler ve bu işlemlerin tarihleri görüntülenmelidir.
8. Hesap Kapama; İstenilen hesap kapatılabilecektir. Kapama işlemi için hesap bakiyesi 0
olması gerekmektedir.
## Notlar:
a. Dosya veya veritabanı işlemleri gerçekleştirilmeyecek, uygulama bellekte
çalışacaktır (Array, List).<br/>
b. Mutlaka abstract sınıf ve çok biçimlilik özellikleri desteklenmelidir.<br/>
c. Uygulamanızın bir ana menüsü olmalıdır. Ana menüyü MDI Child form
mantığında gerçekleştirebilirsiniz.
