# MOBİL UYGULAMA GELİŞTİRME - OnlineShopAppProject

Proje Online Alışveriş (E-ticaret) deneyimini geliştirmeyi hedefleyen bir uygulamadır. Proje, Firebase veritabanıyla entegre olarak geliştirilmiştir, böylece kullanıcılar alışveriş yaparken güvenli ve sorunsuz bir deneyim yaşayabilirler. Uygulama, modern bir arayüz tasarımıyla donatılmıştır ve kullanıcıların kolayca ürünleri keşfetme, detaylı inceleme yapma, sepete ekleme ve güncelleme gibi işlevler sunmaktadır.

# Projede Yapılan Temel Özellikler

## 1. Android Hamburger Menu
Uygulamamızda gezinmeyi kolaylaştırmak için bir Android Hamburger Menu entegre edilmiştir. Bu menü sayesinde kullanıcılar, uygulamanın farklı bölümlerine hızlıca erişim sağlayabilirler.

## 2. Android Toolbar ve Options Menu
Android Toolbar ve Options Menu ile uygulamanın üst kısmında kullanıcı dostu bir navigasyon sağlanmıştır. Toolbar, uygulamanın ana başlıklarını ve önemli işlevleri gösterirken, Options Menu ile ek ayar ve seçenekler sunulmuştur.

## 3. Servis Çağrısı
Uygulamamızda dış veri kaynaklarına erişmek için bir servis çağrısı entegre edilmiştir. Bu özellik, kullanıcıların uygulama içerisindeki verileri dinamik olarak güncellemelerini ve senkronize etmelerini sağlar.

## 4. Intent Uygulaması
Bir intent uygulaması ile kullanıcılar farklı aktiviteler arasında veri paylaşımı yapabilirler. Bu özellik, uygulama içindeki kullanıcı deneyimini artırarak daha etkileşimli hale getirir.

## 5. Uygulama İkonu
Uygulama ikonu, projeye özel olarak tasarlanmış ve değiştirilmiştir. Bu, uygulamanın görsel kimliğini belirler ve kullanıcıların uygulamayı kolayca tanımalarını sağlar.

## Firebase Entegrasyonu
Proje başlangıcında Firebase veritabanı proje içerisine entegre edilmiştir. Uygulamanın ürün verilerini saklamak için bir veritabanı sunmuştur. Veri şu bölümleri içerir:

- **Banner**: Ana sayfa veya belirli kategoriler için banner görüntülerinin URL'lerini içerir.
- **Category**: Ürün kategorilerinin listesini ve her bir kategorinin adını ve resim URL'sini içerir.
- **Items**: Satılan ürünlerin listesini, her ürünün açıklamasını, fiyatını, eski fiyatını, resim URL'sini, derecesini ve değerlendirme sayısını içerir.
- **Review**: Kullanıcı yorumlarının listesini, her yorumun açıklamasını, derecesini, kullanıcı adını ve kullanıcı resminin URL'sini içerir.

## Uygulama Arayüzleri
- **Gösterge Paneli**: Uygulamanın ana sayfası olan gösterge paneli, modern bir tasarımla oluşturulmuştur. Kullanıcıların kolayca gezinip ürünleri keşfetmelerini sağlayacak bir arayüz tasarlanmıştır. İndirim kampanyaları, resmi marka ve popüler ürünler gösterilmektedir. Backend işlevselliği eklenmiş ve Firebase veritabanından ürün verileri çekilmiştir.
  
- **Ürün Detay Sayfası**: Kullanıcıların ürünler hakkında daha fazla bilgi almasını sağlayacak şekilde düzenlenmiştir. Ürün puanı, açıklamaları, yorumları ve beden seçenekleri eklenmiştir. Kullanıcıların ürünleri sepetlerine eklemelerine olanak tanıyan işlemler entegre edilmiştir.
  
- **Sepet Sayfası**: Kullanıcıların alışveriş sepetlerini düzenlemelerini ve ödeme işlemlerini tamamlamalarını sağlar. Sepet sayfasının backend işlevselliği eklenmiştir, kullanıcıların sepetlerindeki ürünleri güncelleyebilmeleri ve tutar işlemlerini tamamlayabilmeleri için gerekli işlemler entegre edilmiştir.



