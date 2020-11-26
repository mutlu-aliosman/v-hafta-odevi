# v-hafta-odevi



#### SQLite ve LocalDB kavramlarını karşılaştırınız.

| Dağıtım-Kurulum-Veri Dosyası ve Programlanabilirlik özellikleri | SQLite                                    | LocalDB                                                  |
:---------                                                        |---------                                  |------                                                           
|Kurulum Boyutu                                                   |10 MB indidirme,14 mb diskte genişletilmiş |32 mb indirme 160 mb diskte                               |
|ClickOnce Dağıtımı                                       |	:heavy_check_mark:                        |     	:heavy_check_mark:                                         |
|Uygulam ile özel yüklenmiş,yerleşik                      |	:heavy_check_mark:                        |	:heavy_multiplication_x:                                         |
|Yönetici olmayan kurulum seçeneği                        | :heavy_check_mark:                        | :heavy_multiplication_x:                                         |
|.Net ile çalışır.                                        | :heavy_check_mark:                        | :heavy_check_mark:                                               |
|Windows mobil veya windows telefon platformunda çalışması| :heavy_check_mark:                        | :heavy_multiplication_x:                                         |
|WinRT'de çalışır (Telefon / Mağaza Uygulamaları)         |  :heavy_check_mark:                       | :heavy_multiplication_x:                                         |
|Microsoft dışı platformlarda çalışır                     |:heavy_check_mark:                         |:heavy_multiplication_x:                                          |
|MSI ile merkezi olarak kurulur                           |:heavy_check_mark:                         | :heavy_check_mark:                                               |
|Uygulama ile süreç içinde çalışır                        |:heavy_check_mark:                         |:heavy_multiplication_x:  uygulama tarafından başlatılınca çalışır|
|64 bit desteği                                           |:heavy_check_mark:                         |:heavy_check_mark:                                                |
|Hizmet olarak çalışması                                  |:heavy_multiplication_x:                   |:heavy_multiplication_x:                                          |
|Dosya Formatı                                            | Tek dosya                                 | Birden çok dosya                                                 |
|Bir ağ paylaşımında veri dosyası depolama                |:heavy_multiplication_x:                   | :heavy_multiplication_x:                                         |
|Farklı dosya uzantıları için destek                      |:heavy_check_mark:                         |:heavy_multiplication_x:                                          |
|Veritabanı boyutu desteği                                |140 TB                                     |10 GB                                                             |
|XML Depolama                                             |:heavy_check_mark:                         |:heavy_check_mark: Local                                          |
|İkili (BLOB) depolama                                    |:heavy_check_mark:                         | :heavy_check_mark:                                               |
|Dosya akış desteği                                       |:heavy_multiplication_x:                   | :heavy_multiplication_x:                                         |
|Kodsuz,Dosya formatı                                     |:heavy_check_mark:                         | :heavy_multiplication_x:                                         |
|Transact-SQL - Yaygın Sorgu Özellikleri                  |:heavy_multiplication_x:                   |:heavy_check_mark:                                                |
|Procedural T-SQL – Select Case, If, özellikleri          |Sınırlı                                    |:heavy_check_mark:                                                |
|Uzaktan Veri Erişimi (RDA)                               |:heavy_multiplication_x:                   |:heavy_multiplication_x:                                          |
|ADO.NET Sync Framework                                   |:heavy_multiplication_x:                   |:heavy_check_mark:                                                |
|LINQ to SQL	                                            |:heavy_multiplication_x:                   |:heavy_check_mark:                                                |
|ADO.NET Entity Framework                                 |:heavy_check_mark:                         | :heavy_check_mark:                                               |
|Basit işlemler                                           |:heavy_check_mark:                         | :heavy_check_mark:                                               |
|Dağıtılmış işlemler                                      |:heavy_multiplication_x:                   |  :heavy_check_mark:                                              |
|Native XML, XQuery/XPath	                                |:heavy_multiplication_x:                   |:heavy_check_mark:                                                |
|Stored procedures, views, triggers	                      |Views and triggers	                        |:heavy_check_mark:                                                |
|Role-based security	                                    |:heavy_multiplication_x:                   |:heavy_check_mark:                                                |
|Eşzamanlı bağlantı sayısı                                |Sınırsız                                   |Sınırsız (ancak yalnızca yerel)                                   |


####  Lazy Loading kavramı hakkında temel bir araştırma yapınız.

   -  Oluşturulan yeni bir entity model için varsayılan olarak tanımlı data yükleme yönetimidir. Bu yöntemde veriler sorguya bağlı olarak çekilir ancak veri setinin içindeki tüm dataları yüklemek yerine verilerin çağrıldıkça otomatik yüklenmesi söz konusudur. Yani bir uygulamada birbirine bağli olarak tanımlanmış componentlerin tamamının bir seferde yüklenmesi yerine istemci tarafından çağırıldığında yüklenmesine olanak veren bir yapıdır. 

####  Eager Loading
  
   -  Eager loading Linq sorgusu çalıştırıldığında verilerin tamamını yükler ve hafızaya alır.


