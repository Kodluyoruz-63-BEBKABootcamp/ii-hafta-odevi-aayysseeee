# II. Hafta Ödevleri

 - Yeni bir Gitthub repository oluştururken, repomuza ekleyebileceğimiz lisanslar nelerdir, bu lisanslar arasındaki farklar nelerdir?
 - Merge - Squash-Rebase arasındaki farklar nelerdir?
 - Github Learning Lab'de First Day ve First Week kısımlarını bitiriniz.
 - Agile-Scrum-Kanban kavramlarını araştırınız
 - Derste yaptığımız .Net Console uygulamasının .NetCore versiyonunu yazmayı deneyiniz.
 - Github Flow'un alternatifleri nelerdir? Artılarını ve eksilerini karşılaştırınız.
 - Gang of Four(GOF) araştırınız.
 - Interface ve Abstract sınıflar arasındaki farklar nelerdir?

### MIT Lisansı
Ticari kullanımlara, dağıtılmasına, düzenlenmesine ve özel kullanıma izin verir. Yetki ve sorumluluk yükler. (Kaynak)[https://choosealicense.com/licenses/mit/]

### Apache Lisansı 2.0
Ticari kullanımlara, dağıtılmasına, düzenlenmesine, patent kullanımına ve  özel kullanıma izin verir. Yetki ve sorumluluk yükler, marka kullanımını engeller(kaynak)[https://choosealicense.com/licenses/apache-2.0/]

### GnuGenel Kamu Lisansı v.3.0
Ticari kullanımlara, dağıtılmasına, düzenlenmesine ve özel kullanıma izin verir. Kaynak açık bir şekilde paylaşıma devam edilir. Yetki ve sorumluluk yükler.(Kaynak)[https://choosealicense.com/licenses/gpl-3.0/]

Kullanıma göre farklı lisanslar bulunmaktadır. İhtiyaca göre (link)[https://choosealicense.com/]den bakılabilir.
Diğer (lisanslara)[https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/licensing-a-repository#where-does-the-license-live-on-my-repository] da bakılabilir. Yine detaylı okumalar için (linke)[https://www.yusufaytas.com/acik-kaynak-lisanslari/] bakılabilir.

### Merge - Squash - Rebase
Merge yaptığmızda is yeni bir “ Merge commit” yaratıp iki branchinde tüm history(yapılmış tüm değişiklikleri) sini içerecektir. Master , branch te yapılan tüm değişiklikleri alacak ve entegre edecektir ancak branch in history sinde hiçbir değişiklik olmayacaktır.Master a bir branch i rebase ettiğinizde , branch deki commitlerinizi tek tek alıp master ın sonuna ekleyecektir. Sonuç olarak rebase sonucunda tek bir history oluşturur çünkü tamamlanan işi bir branch ten diğerine aktarır. Bu süreçte istenmeyen history ortadan kalkar.(Kaynak)[https://medium.com/@halilibrahim_4325/git-merge-ve-rebasein-fark%C4%B1-nedir-1c6c81086fa9]

Detaylı bilgi için bakılacak kaynaklar (1)[https://qastack.info.tr/programming/2427238/in-git-what-is-the-difference-between-merge-squash-and-rebase] , (2)[https://rietta.com/blog/github-merge-types/], (3)[https://stackoverflow.com/questions/435646/combine-the-first-two-commits-of-a-git-repository], (4)[https://medium.com/@halilibrahim_4325/git-merge-ve-rebasein-fark%C4%B1-nedir-1c6c81086fa9]

### Agile - Scrum - Kanban
Agile (Çevik) TDK’da rastladığımız tanım “Kolaylık ve çabuklukla davranan, tetik, atik-çevik davranış” şeklindedir. Agile Proje Yönetimi kabaca, “Yapılmak istenen projeyi, küçük ve çalışan parçaları bir araya getirerek tamamlama işlemidir.” diyebiliriz. (Kaynak)[https://medium.com/atdijital/agile-%C3%A7evik-proje-y%C3%B6netimi-nedir-f07eaf0b172c]
2001 yılında çevik yazılım geliştiriciler, ortak bir paydada birleşmek
amacıyla "Çevik Yazılım Geliştirme Manifestosu"nu yayımlamışlardır. Bu manifestoda
yer alan esaslar şunlardır (Agilealliance, 2019a): Çevik yazılım geliştirme, çeşitli iteratif
ve artırımsal yazılım geliştirme yöntembilimlerini kapsayan bir terimdir. Çevik yazılım
geliştirmede; bireyler ve aralarındaki etkileşim, süreç ve kullanılan araçlardan daha
önemlidir. Yazılımın çalışması ayrıntılı bir şekilde dokümantasyon yapmaktan daha
önemlidir. Müşterinin yapacağı katkılar sözleşme ve anlaşmalardan daha önemlidir.
Değişikliklere cevap verebilmek düz bir planı izlemekten daha önemlidir. Çevik manifestoda on iki prensip üzerinde durulmaktadır (Agilealliance, 2019b): 1-
Müşteri için önem arz eden yazılımın en erken ve sürekli teslimini sağlayarak müşteri
memnuniyetini elde etmek ilk önceliktir. 2- Gecikmeler olsa dahi değişikliklere açık
olmak. Çevik süreç bu değişikliklerle müşterinin avantajlı şekilde rekabet etmesini
sağlar. 3- Kısa zamanda (2-6 hafta arası) çalışan yazılımı teslim etmek. 4- İş adamları ve
yazılım geliştiriciler günlük olarak proje için bir araya gelmelidirler. 5- Projeleri bireyleri
motive ederek uygulamak, onlara uygun ortamı sağlayarak ihtiyaçlarını karşılayıp işi
bitireceklerine güvenmek önemlidir. 6- Takım içerisinde bilgi aktarımının en etkili ve
kısa yolunun yüz yüze görüşmeler olduğunu bilmek önemlidir. 7- İşleyen yazılım,
sürecin ilk göstergesidir. 8- Çevik süreç kararlı gelişim sunar. Sponsorlar, geliştiriciler
ve kullanıcılar sürekli uyum içindedirler. 9- Teknik açıdan mükemmelliğe ve iyi tasarıma
sürekli dikkat edilmesi çevikliği artırır. 10- Basitlik önemlidir. 11- En iyi mimariler,
gereksinimler ve tasarımlar kendini organize edebilen takımlardan çıkar. 12- Takım,
çalışmasının daha verimli nasıl olabileceğini inceler ve buna göre davranışlarını iyileştirir. 
Scrum: Projede izlenmesi gereken adımları basit ama önemli birkaç kuralla belirterek
esnek yönetim sunmaktadır (Acm, 2016a). Gereksinimler ve uygulamalardan ziyade bir
dizi proje yönetim değerlerini ve çalışmalarını benimsemektedir ve bunlar diğer
yöntembilimlerle birleştirilebilir ya da tamamlayıcı olarak kullanılabilir. Taahhüt, odak,
açıklık, saygı ve cesaret olmak üzere beş değer üzerine kuruludur: (Larman, 2003: 174;
Ranniko, 2011: 24). En önemli çıktı sürecin şeffaf hale getirilerek süreç içerisinde
aksayan noktaların açığa vurulmasıdır. Böylece aksaklıkları çözümleyerek sürekli
iyileştirme yönünde proje ekibini motive eder (Acm, 2016a).SCRUM aksayan noktaları belirleme  ile “Süreç Değerlendirme Sınıfı”na
girmektedirler.(Kaynak)[]http://www.dergipark.org.tr/tr/download/article-file/835864

 Scrum; Agile proje yönetim metodolojilerinden biridir. Kompleks yazılım süreçlerinin yönetilmesi için kullanılır. Bunu yaparken bütünü parçalayan; tekrara dayalı bir yöntem izler. Düzenli geri bildirim ve planlamalarla hedefe ulaşmayı sağlar. Bu anlamda ihtiyaca yönelik ve esnek bir yapısı vardır. Müşteri ihtiyacına göre şekillendiği için müşterinin geri bildirimine göre yapılanmayı sağlar. İletişim ve takım çalışması çok önemlidir. 3 temel prensip üzerine kurulmuştur;
Şeffaflık; Projenin ilerleyişi, sorunlar,gelişmeler herkes tarafından görülebilir olmalıdır.
Denetleme; Projenin ilerleyişi düzenli olarak kontrol edilir.
Uyarlama; Proje, yapılabilecek değişikliklere uyum sağlayabilmelidir.(Kaynak)[https://medium.com/@secilcor/scrum-nedi%CC%87r-6a4326951dd8]

Scrum da 3 çeşit hikaye olur.

1.       Kullanıcı Hikayesi : Kullanıcı için değer yaratan fonksiyonları tanımlar, planlama kalemleridir, sprint kapsamasında yer alır.

2.       Teknik Hikaye : Geliştirme Takımı tarafından yazılır. Fonksiyonel olmayan projeye ilişkin gereksinimlerdir.

3.       Hata (Defect) üründe ki bir hata yada bulguyu tanımlar, çözüm önerisi sunulabilir. Ürün iş listesinden hatanın referansının tutulması önemlidir. (Kaynak)[http://www.mehmetagile.com/2019/10/14/agile-genel-kavramlar/]
Kanban: 1940 sonrasında Toyota mühendisi Taiichi Ohno tarafından geliştirildi. Süpermarket raflarda tükenen malların stoklanması gözlemleyerek, bunları kendi tedarik sistemine uyarladı. Ana amaç fazlalık üretmekten kaçma ve kaynaklarını olabildiğince verimli kullanmak üzerinedir. Bunun için birincil öncelik üretim bandında ilerleyen kaynakları görselleştirebilmektir. Bu sayede herkes süreç hakkında bilgi sahibi olup fazlalığı ve azlığı gerçek zamanlı yönetebilmesine olanak sağlar.
Scrum: Geliştiricilerin kendi planlarını yapabildikleri, güncelleyebildikleri, sistem işeyişini retrospective değerlendirebildikleri, sistem işleyişinden Scrum Master sorumlu olduğu, müşterinin isteklerini ürüne doğru ve öncelikli aktarılmasından Product Manager sorumlu olduğu, müşterinin istekleri doğrultunda önceliklendirilmiş ürün odaklı çevik geliştirme yöntemidir. 
Kanban:
* Odaklanma - Çok görevliliği azaltma
* İsrafı/boşa geçen zamanı azaltma
* Müşterinin ihtiyaçlarını en öncelikli değerlendirme
Scrum:
*Sprint hedefleri doğrultusunda ekibin ortak mutabakatı
*Doğru olduğunu düşündüğün işleri yapma (cesaret)
*Sprint işlere odaklanama
*Karşılaştığın zorluklara karşı açık sözlü olma
*Herkesin elinden geldiğinin en iyisini yaptığına güven (saygı)
(Kaynak)[https://odayibasi.medium.com/kanban-vs-scrum-vs-xp-extreme-programming-dc08d11b2fa] (1)[https://www.edrawsoft.com/kanban-vs-scrum.html?gclid=Cj0KCQiAhZT9BRDmARIsAN2E-J3mtBz4NDT6rEa6ip18WcCqM6p8xRR1rx-BmZ2UHK1bcCP3E1K-XE0aAm4vEALw_wcB]


### GitHub Flow  alternatifi ve özellikleri
 Git Workflow bize basit bir şekilde Git kullanarak etkili bir şekilde nasıl takım halinde kod geliştirebileceğimizi tanımlıyor. (Kaynak)[https://cangelis.com/takim-halinde-kod-gelistirmek-git-workflow/#comment-5156]
[ Kaynak)[http://fehmicansaglam.net/git-flow-bir-gelistirme-surecinin-anatomisi]


### Gang of Four(GOF)
23 Gang of Four (GoF) kalıpları genellikle diğer tüm modellerin temeli olarak kabul edilir. Üç grupta kategorize edilirler: Yaratıcı, Yapısal ve Davranışsal (tam bir liste için aşağıya bakın). Bu referans, 23 GoF modelinin her biri için kaynak kodu sağlar.(Kaynak)[https://www.dofactory.com/net/design-patterns]
Şu (linke)[https://springframework.guru/gang-of-four-design-patterns/] bakılabilir. 
Gang of Four topluluğu tarafından yayınlanan tasarım desenleri ,Nesne Yönelimli Programlama da karşılaşılmış tasarım sorunlarına üretilmiş optimum  çözümler olarak tanımlanabilir. Tasarım desenleri bizlere daha yönetilebilir ve okunabilir kod yazmak konusunda avantajlar sağlar. Bunun yanında performans ve geliştirilebilirlik konusunda da katkıları vardır.  Tasarım desenleri genel olarak 3 başlık altında toplanır.Bunlar;

Creational Patterns-Kurucu Desenler: Nesnelerin oluşturulması ile ilgili patternlerdir. Structural Patterns – Yapısal Desenler: Nesnelerin birbiri ile olan ilişkisini konu alır.Behavioral Patterns – Davranışsal Desenler : Sınıfların bir görevi yerine getirirken nasıl davranacağı ile ilgili desenlerdir. (Kaynak)[http://enesaysan.com/software/c-tasarim-desenleri-design-patterns/]
Tasarım kalıpları, yazılım tasarımında sürekli karşılaşılan genel sorunlara esnek, yeniden kullanılabilir, başarılı çözümler getiren hazır kalıplardır.Daha net bir ifadeyle Tasarım kalıpları, nesne yönelimli programlamada, programlama dili gözetmeksizin; sınıf ve nesneler arasındaki ilişkilerin en iyi şekilde nasıl olmaları gerektiğini açıklayan yöntemlerdir. Yaklaşık 25 yıl önce Gang of Four (GoF) olarak bilinen Erich Gamma, Richard Helm, Ralph Johnson and John Vlissides, Design Patterns — Elements of Reusable Object-Oriented Software adında kitap yayınladılar ve ilk kez yazılım alanında tasarım kalıpları kavramını ortaya attılar. (Kaynak)[https://deryacakmak.medium.com/tasar%C4%B1m-kal%C4%B1plar%C4%B1-nelerdir-cd216ba47921]
Tasarım desenleri(Design Patterns), bizlere yazılım dünyasındaki problemler için kalıcı ve tekrar edici çözümler sunar, gerçek dünyada bir çok karşılığını bulacağımız bu desenler, objeler arasındaki ilişkiyi ve bunların nasıl yönetileceği ile ilgili konuları tanımlar.

Tasarım desenleri(Design Patterns)  ilk defa Gang of Four (GoF- Dörtlü Çete) olarak bilinen, Eric Gamma, Richard Helm, Ralph Johnson ve John Vlissides tarafından yazılan “Design Patterns: Elements of Reusable Object-Oriented Software” kitabıyla Yazılım Mühendisliği literatüründe yerini aldı. Elbette, Gamma’nın ve diğer bazı yazılım mühendislerinin konu üzerinde 80’li yılların sonundan beri çalıştığını biliyoruz ancak GoF Design Patterns kitabı yayınlandığında tüm yazılım geliştiricilerin dikkatini bu konuya ve kavrama çekti. Bugün tasarım desenleri çok yaygın olarak tanımlanmakta ve kullanılmaktadır. Farklı problem türleri için zamanla tekrar eden çözümlerin “keşfedilmesi”yle çeşitli desenler ortaya çıkmıştır. Kısacası, desenler aslında yıllardır kullanılan çözümlerdir ve birisinin fikri yada tasarımı değildir.(Kaynak)[https://tasarimdesenleri.wordpress.com/]

### Interface - Abstract
Class içerisinde metotlar, değişkenler hatta yine sınıf tanımlarının yapılabildiği Object Oriented Programlama dilinin temelini oluşturan bir yapıdır. Aşağıdaki örnekte bir Users adında bir sınıfımız ve içerisinde getter ve setter tanımlı olan iki public değişkenimiz var.Class yapısı hakkında kısa bir açıklama yaptıktan sonra şimdi Interface(Arayüz) yapısına gelelim, Interface’de Class yapısına benzer bir yapıdadır, en kritik farklarından birisi içerisine metodun sadece tanımı eklenir burası biraz kafa karıştırıcı olabilir ama örnek ile anlaşılacağını düşünüyorum. (Kaynak)[https://www.akinabdullahoglu.com/Abstract-Class-ve-Interface-Nedir/]
1) Abstract
Yazdığımız sınıflar arasında inheritance(kalıtım) uygularken kullanırız. Alt sınıflar abstractsınıfı inherit alırlar. Abstract class içindeki implement edilmiş tüm method’lar diğer class’da da geçerlidir.

Abstract classdan implement ettiğimiz bir class içerisinde, sadece abstract class içerisinde abstract olarak tanımlanmış method, property gibi vb.lerini implement etmek mecburidir. Diğer method’lar zaten tanımlıdır ve implement edilmesi mecburi değildir. lerdir?
17 ŞUBAT 2019
EMİNEAKMAKC
Bu ikili, nesne yönelimli programlamada (OOP) sınıfları soyutlamaya yarayan yöntemlerden ikisidir. Bu ikisinin ortak oldukları ve farklı oldukları yönler vardır.

1) Abstract
Yazdığımız sınıflar arasında inheritance(kalıtım) uygularken kullanırız. Alt sınıflar abstractsınıfı inherit alırlar. Abstract class içindeki implement edilmiş tüm method’lar diğer class’da da geçerlidir.

Abstract classdan implement ettiğimiz bir class içerisinde, sadece abstract class içerisinde abstract olarak tanımlanmış method, property gibi vb.lerini implement etmek mecburidir. Diğer method’lar zaten tanımlıdır ve implement edilmesi mecburi değildir.

Abstract sınıflar genelde is-a ilişkilerinde kullanılır.
Örnek vermek gerekirse;

+Ferrari is-a Araba

Ferrari bir arabadır ve arabanın sahip olduğu tüm özelliklere sahiptir.

abstract class Araba
{
public string Marka { get; set; }
public int VitesSayisi { get; set; }
// Kısacası arabaların sahip oldukları tüm ortak özellikler
public abstract void MaximumHiz();
// Override edilecek methodumuz çünkü her arabanın kendine özgü bir maximum hız bilgisi vardır
}
/// /// Ferrari’yi Araba sınıfımızdan inherit alıyoruz. ///
class Ferrari : Araba
{
/// /// Maximum hız bilgimizi override ediyoruz ve Araba abstract sınıfımızın sahip olduğu tüm özelliklere sahip oluyor. ///
public override void MaximumHiz()
{
Console.WriteLine(“Ferrari’nin maximum hızı: 300”);
}
}
Örneğimizden de anlaşılacağı gibi araba örneğimizden yola çıkarak “Araba” isminde bir abstract sınıf oluşturuyoruz ve “Ferrari” bu sınıfdan inherit alarak Arabaların sahip olmuş oldukları tüm ortak özelliklere sahip olmuş oluyor.

Abstract sınıfın genel özelliklerini sıralayacak olursak;

Kod içerisinde “new” anahtar sözcüğü ile oluşturulamazlar.
Bir sınıf sadece bir abstract sınıfı inherit alabilir.
Inherit alıcak sınıflar arasında genelde “is-a” ilişkisi vardır.
Abstract sınıfda method ve değişkenler tanımlanabilir.
2) Interface
Interface sınıfında sadece method tanımları bulunur. İçlerine kod parçacığı yazılmaz. İçerisinde tanımlanan method tanımları bu interface’i implemente edecek diğer sınıflar tarafından implement edilmesi zorunludur. Interface sınıfının genel özelliklerini sıralayacak olursak;

Kod içerisinde “new” anahtar sözcüğü ile oluşturulamazlar.
Bir sınıf birden fazla interface implemente edebilir.
Implemente edicek sınıflar arasında genelde “can-do” ilişkisi vardır.
Interface içerisine sadece boş method’lar tanımlanabilir. (Kaynak)[https://eminecakmakci.wordpress.com/2019/02/17/interface-ve-abstract-class-arasindaki-farklar-nelerdir/]






