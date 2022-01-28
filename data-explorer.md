# Azure Synapse Analytics Data Explorer Nedir ?
Azure Synapse Data Explorer, log ve telemetri verilerinden öngörüleri açmak için müşterilere 
etkileşimli bir query deneyimi sağlar. Telemetri verilerini, IoT sensörlerinde, app logları,web 
logları, zaman serileri, güvenlik logları gibi birçok yerde görebiliriz. Bu verilerden alınan 
bilgiler ile tüketicilerin ve işletmelerin güvendiği bağlı cihazlarda ilerleme sağlanır.
Synapse Data Explorer bu telemetri verilerinden yararlanılmasını sağlamak için 
oluşturuldu.Mevcutta bulunan SQL ve Apache Spark runtime motorlarını tamamlamak için 
yeni data explorer telemetri verilerinde yaygın olarak bulunan serbest metin ve yarı 
yapılandırılmış verileri otomatik olarak endekslemek için güçlü indeksleme teknolojisini 
kullanan verimli log analitiği için optimize edilmiştir.
Büyük hacimli zaman serilerini alıp, datayı loglara kaydedecek ve bunu Power BI’da veri 
görselleştirmeleri oluşturulabilir. Böylelikle düzensizlikler verimli bir şekilde belirlenebilir 
ve daha güvenli bir sistem sağlanabilir.

![dataexplorer](https://www.google.com.tr/url?sa=i&url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Fazure%2Fsynapse-analytics%2Foverview-what-is&psig=AOvVaw2MU2a5noOgH65VNHJxiMu1&ust=1643458785804000&source=images&cd=vfe&ved=0CAgQjRxqFwoTCOClqpy31PUCFQAAAAAdAAAAABAD)

## Data Explorer ile neler yapılabilir?

- Veriler otomatik olarak sıkıştırılır, indekslenir, otomatik olarak optimize edilir ve yerel SSD'lerde önbelleğe alınır ve depolamada kalıcı olur. Hesaplama ve depolama birbirinden ayrılmıştır, bu da size herhangi bir kesinti olmadan otomatik olarak içeri/dışarı ölçeklendirme esnekliği sağlar.
- Verimli serbest metin araması, normal ifade ve izlemeler\metin verilerinde ayrıştırma için Synapse Data Explorer sınıfının en iyisi metin dizini oluşturma özelliğini kullanarak ham telemetri ve zaman serisi verilerini keşfetmek için yüksek düzeyde optimize edilmiş Sezgisel Kusto Query Dili (KQL).
- Diziler ve iç içe geçmiş yapı dahil olmak üzere yarı yapılandırılmış verileri sorgulamak için kapsamlı JSON ayrıştırma yetenekleri.
- Model scoring için in-engine Python ve R yürütme desteği ile birden çok zaman serisinin oluşturulması, işlenmesi ve analizi için yerel, gelişmiş zaman serisi desteği.


``` Bu özellikler, Azure Synapse Data Explorer’ı loglar, olaylar, zaman serileri gibi telemetri verilerini ve diğer salt eklemeli telemetri verilerini almak, depolamak, sorgulamak ve görselleştirmek için mükemmel bir araç haline getirir. ```
