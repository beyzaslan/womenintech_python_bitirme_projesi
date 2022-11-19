**customers_dataset.csv analizleri**
* Veri seti çekildi.
* Veri seti içerisindeki sütun isimleri yeniden isimlendirildi.
* Baştan ve sondan sıralama yapıldı.
* Boş değer olup olmadığına bakıldı ve olmadığı görüldü.
* Veri setindeki sütun tiplerine bakıldı.
* Veri seti betimsel olarak tanımlandı.
* Hangi şehirde kaç müşteri var bunun sıralaması yapıldı.
* nunique olan değerler listelendi.
* dublicate veri kontrolü yapıldı.
* Şehri Brazilia olanların bilgileri getirildi. 
* Veri seti hakkında özet bilgi edinildi.
* Müşterilerin posta koduna göre grafik çizdirildi. 
* Veri setindeki değerlerin tipine bakıldı. 
* Veri setindeki sütunlar listelendi.
* Veri setinin kaç hücre ve sütunda oluştuğu bilgisine bakıldı.
* Posta kodu > 5000 den büyük olan müşterilerin verileri çağırıldı.
* Şehri sadece Brazilia olan müşterilerin bilgileri getirildi. 
* Müşteriler posta kodlarına göre gruplandırıldı (groupby)
* Müşterilerin posta kodlarına göre histogram grafiği çizdirildi.
* Veri seti içerisinde kaç tane şehir var bunun analizi yapldı.
* Müşteriler şehirlerine göre gruplandırıldı. 
* Posta kodları ülkelere göre gruplandırıldı.

**geolocation_dataset.csv analizleri**
* Veri seti çekildi.
* Veri seti içerisindeki sütun isimleri yeniden isimlendirildi.
* Baştan ve sondan sıralama yapıldı.
* Boş değer olup olmadığına bakıldı (isnull).
* Veri setindeki sütun tiplerine bakıldı.
* nunique(eşsiz olmayan) değerler listelendi.
* Posta kodu = 99950 olanlar listelendi(filtreleme).
* Boş değer olmadığı görüldü ve bu yüzden herhangi bir işlem yapılmadı.
* Coğrafi posta kodları şehirlere göre gruplandırıldı(groupby).
* Dublicate veri kontrolü yapıldı ve tekrar eden veriler olduğu görüldü (dublicate kontrol).
* Kaç hücre ve sütun olduğuna bakıldı. 
* Veri seti sütunları listelendi.
* Posta koduna göre boxplot grafiği çizdirildi.

**order_items_dataset.csv analizleri**
* Veri seti çekildi.
* Veri seti baştan ve sondan listelendi.
* Veri seti sütunları yeniden isimlendirildi.
* Veri seti hakkında özet bilgi edinildi.
* Veri setindeki sütun tiplerine bakıldı.
* nunique olan değerler listelendi.
* En yüksek nakliye ücretine sahip ürünlerin sıralaması yapıldı. 
* Ürünler, siparişlere göre gruplandırıldı.
* Veri setinin betimsel tanımlaması yapıldı. 
* Hangi sipariş türünden kaç tane var buna bakıldı. 
* Boş değer kontrolü yapıldı ve olmadığı görüldü.
* Kaç hücre ve sütun olduğuna bakıldı. 
* Dublicate değer kontrolü yapıldı.

**order_payments_dataset.csv analizleri** 
* Veri seti çekildi.
* Veri seti baştan ve sondan listelendi. 
* Boş değer kontrolü yapıldı.
* Veri seti sütunları yeniden isimlemdirildi.
* Veri seti hakkında özet bilgi edinildi.
* Veri setindeki sütun tiplerine bakıldı.
* nunique olan değerler listelendi.
* Odenecek tutar sütunu için grafik çizdirildi ve aykırı değer tespiti yaptırıldı.
* Kredi kartı ile ödeme yapılan siparişlerin bilgileri getirildi. 
* Hangi ödeme tipi ile ne kadar ödeme yapılmış buna bakıldı.
* Ödeme türlerine göre barh plot grafiği çizdirildi. 
* Ödeme taksitlerine göre barh plot grafiği çizdirildi.
* Maksimum ödenecek tutarın ne olduğuna bakıldı.
* Kaç hücre ve sütun olduğuna bakıldı. 
* Ortalama sipariş tutarına bakıldı.
* Dublicate veri kontrolü yapıldı.
* Ödeme türüne göre gruplandırma yapıldı.

**order_reviews_dataset.csv analizleri**
* Veri seti çekildi.
* Veri seti baştan ve sondan listelendi.
* Veri seti sütunları yeniden isimlemdirildi.
* Veri seti hakkında özet bilgi edinildi.
* Veri setindeki sütun tiplerine bakıldı.
* nunique olan değerler listelendi.
* Boş değer kontrolü yapıldı ve boş değer olduğu görüldü.
* Kaç tane boşluk olduğuna bakıldı.
* Boş olan değerlerin silinmesi işlemi gerçekleştirildi (dropna).

**orders_dataset_csv analizleri**
* Veri seti çekildi.
* Veri seti baştan ve sondan listelendi. 
* Boş değer kontrolü yapıldı ve boş değer olduğu görüldü.
* Boş değerler silindi.
* Veri seti sütunları yeniden isimlendirildi.
* Veri seti hakkında özet bilgi edinildi.
* Kaç tane boşluk olduğuna bakıldı(isnull).
* Boş değerler dolduruldu (fillna). 
* Dublicate veri kontrolü

**product_category_name.csv analizleri**
* Veri seti çekildi.
* ürün isimleri değiştirildi.
* Analiz yapılacak bir veri olmadığı için analiz edilmedi.
* Başka bir veri seti ile merge edilerek kullanıldı.

**products_dataset.csv analizleri**
* Veri seti çekildi.
* Veri seti baştan ve sondan listelendi. 
* Boş değer kontrolü yapıldı ve boş değer olduğu görüldü.
* Boş değerler silindi.
* Veri seti sütunları yeniden isimlendirildi.
* Veri seti hakkında özet bilgi edinildi.
* Veri setindeki sütun tiplerine bakıldı.
* Veri seti betimlendi.
* nunique olan değerler listelendi.
* Kaç tane boşluk olduğuna bakıldı(isnull)
* Hangi ürün, hangi kategoride bunun analizi yapıldı.
* Dublicate veri kontrolü
* Ürünler kategorilerine göre gruplandırıldı.
* Ürün ağırlığı < 500 gr dan küçük olan ürünler çağırıldı.
* Ürün kategori ismi "bebes" olan ürünler çağırıldı.
* Ürünlerin ortalama genişliği bulundu.
* Ürünlerin ortalama uzunluğu bulundu.
* Ürün ağırlığına ait boxplot grafiği çizdirildi. Aykırı değer olduğu görüldü. 

**sellers_dataser.csv analizleri**
* Veri seti çekildi.
* Veri seti baştan ve sondan listelendi.
* Veri seti hakkında özet bilgi edinildi. 
* Hücre ve sütun sayısına  (shape).
* Boş değer kontrolü yapıldı ve boş değer olmadığı görüldü.
* Veri setindeki sütun tiplerine bakıldı.
* Veri seti betimlendi.
* nunique olan değerler listelendi.
* Dublicate değer kontrolü yapıldı ve dublicate değer olmadığı görüldü. 
* Ülkesi SP olan satıcıların verileri çekildi.
* Satıcılar şehirlere göre gruplandırıldı. 
* Satıcıların posta koduna ait histogram grafiği çizdirildi.
* Posta kodu > 10000 olan satıcıların verileri getirildi.


------------------------------------**Merge İşlemlerine Ait Analizler**--------------------------------------
* satici_siparis = order_items_dataset ile seller_dataset birleştirildi (Satıcı numarasına göre)
* siparis = order_payments_dataset ile orders_dataset birleşimi
* musteri_siparis= customers_dataset ile orders_dataset birleştirildi

* müşterilerin ülke bazında ne kadar sipariş verdiklerine bakıldı.
* Bir ürüne ödenecek toplam fiyat bulundu.
* Bir müşterinin toplam harcaması bulundu.
* Siparişlerin ülkelere göre durumu
* Sipariş durumuna göre teslim zamanı
* Sipariş numarasına göre tahmini teslim tarihi
