# 1) C# Nedir?
- Microsoft tarafından .NET çatısı altında geliştirilen ve gelişen modern bir programlama dilidir.

- Açık kaynak ve ücretsizdir.

<img src="1.png" width="auto">

- C benzeri bir dildir.

- OOP'yi ve OOP'nin gelişimini destekler.

- OOP Neste Tabanlı Programlama felsefesidir/yaklaşımıdır. C# işte bu yaklaşımı benimsemiş bir dildir.

<img src="2.png" width="auto">

- Orta seviyeli bir dildir.

- Burada seviyeden kasıt dilin okunabilirlik etkisi. Yani bir dil yüksek seviyeli ise bir beşeri dile daha yakındır. Baktığınız zaman makale gibi okuyabilirsiniz. 

- Mesela VisualBasic'e baktığınız zaman yazılmış bir şiir gibi takır takır takır gider. Çok fazla bir sembolik değer/ifade yoktur.

- Bir makine diline baktığınızda bildiğiniz Çince gibidir. Yani hiç birşey anlaşılmıyor 0'lardan 1'lerden oluşuyor bir assembly'e baktığınız zaman ciddi manada bakınca hiç birşey anlayamacağınız bir mantık otutturamayacağınız bir dil. 

- Yani bir dil eğer ki beşeri seviye de algılanabilir seviyedeyse baktığınızda metinselse kodları bu dil yüksek seviyelidir. Ama bir dil okunabilirliği düşüyorsa sembollerle ifade ediliyorsa ve bir matematiğe/mantığa göre yorumlanabiliyorsa o dil düşük seviyelidir.

<img src="3.png" width="auto">

- C 'nin bir üst versiyonu C++'tır yani C+1 denilebilir çünkü ++ operatörü kodlamada değeri bir arttırır. C#'ta aslında C++'ın bir üst versiyonudur. Yani C++++ olarak tasarlanmış ve #(diyez) işareti olmuştur C#. 

<img src="4.png" width="auto">

- Java'dan etkilenmiştir. Java'yı etkilemektedir.

- Diller birbirlerini örnek alabilirler. Birbirlerinden belirli şeyleri kopyalayabilirler. Belirli şeyleri miras alabilirler ya da farklı bir vizyonda daha da farklı ürünler ortaya koyup daha düne kadar kendisinin modellediğinin modellenmesine sebeb olabilirler. Dillerin gelişimi bu şekildedir.

<img src="5.png" width="auto">

## C# İle Neler Geliştirilebilir
- Aklınıza ne geliyorsa geliştirebilirsiniz.

- Web Uygulamaları

- Mobil

- Web Service

- Service Mimarileri

- Console

- DLL

- Windows Form

- Oyun

- ERP, Muhasebe, Multi Media, İstatistik, Güvenlik vs. Yazılımları

- Uzaya füze göndersek bile C# ile gönderebiliriz. 

- Her yerde mükemmel bir destek verebilir demiyoruz. Örneğin veri madenciliği boşuna Python diye bir dil çıkmadı. Python veri madenciliğinde dah performanslı daha da hızlı hareket etmemizi sağlıyor. C#veri madenciliği yapamaz demiyoruz. C# veri madenciliği yapabilir.

- Siz her ne olursa olsun ihtiyacınıza göre doğru olanı kullanmanız sizin açınızdan son derece iyi olacaktır.

- Derlenen bir programlama dilidir.

<img src="6.png" width="auto">

***
# 2) .NET Framework ve .NET Core Nedir? Farkları Nelerdir?
- Biz Microsoft'un bize sunduğu teknolojileri kullanarak yazılımlarımızı geliştiriyoruz.

- .NET Dil/Mimari/Kütüphane gibi yapılanmaları sunan çatıdır.

- .NET Microsoft'un developerler için geliştirdiği teknolojileri sunuduğu bir çatı.

| .NET Framework | .NET Core| 
|----------------|----------|
|İlk Çıkan Sürümdür.|.NET Core daha sonradan çıkmıştır.|
|Windows Ekosistemine yönelik çözümler getirir.|Cross Platform'dur. Çeşitli işletim sistemleri uygulamaları destekler|
|Geliştirdiğiniz ürün sadece Windows'a göre çözümler getirir. Microsoft'a bağlıdır. |Developer'ların her yerde geliştirme yapabileceği/çalıştırabileceği/serve edebileceği  bir çekirdek oluşturdu.|
|Sadece Windows 'işletim sisteminde çalışabilirsiniz.|Tüm işletim sistemlerinde çalışma sergileyebilir.|
|Open Source değildir.|.Net Framework'teki Windows bağımlılığını ortadan kaldırarak daha evrensel uygulamalar geliştirmemizi sağlamaktadır.|
||Modülerdir. Open Source'tur.|


- İkisinde de farketmeksizin bütün platformlara uygun geliştirmeler yapabilmekteyiz.


<img src="7.png" width="auto">
<img src="8.png" width="auto">

***
# 3) Compiler Nedir?
- Yazdığınız kodu sürekli derleyip ardından çalıştırmanız gerekecek.

- Bir programlama dili derleyici bir üslupla çalışıyorsa yani derlenen bir dilse bu programlama dilinin önce derlenmesi ardından çalıştırılması ve sonuç alınması gerekmektedir. 

- Derleme süreci bizim için önemlidir.

- Diyelim ki siz Source(kaynak) dosyanızın içine C# kodlarınızı yazdınız. Bu kodların makina tarafından okunulabilir işlenilebilir hale getirilmesi gerekiyor. İşte biz bunun için bu kodu derlemeliyiz.

- Burada derlemekten kastımız yazdığımız kodun makinanın anlayacağı dile/koda çevrilmesi gerekiyor. 

- Örneğin C# kodlarının kabataslak Assembly'e çevrilmesi için bu kodun derlenmesi gerekiyor.

- C#'ı ben algılayabiliyorum derlendikten sonra C#'ın derlenmiş halini makine/bilgisayar algılayabiliyor.

- Dolayısıyla bu derleme neticesinde bilgisayarın anlayabileceği kod üretiliyor. Dolayısıyla biz C# ile Assembly yazmadan bilgisayarla haberleşmiş oluyoruz.

- Bilgisayar bilimlerinde ön işleme süreci, derleme süreci, çevirme ve bağlama süreçleri söz konusudur.

- Windows'ta Eğer ki bir yazılımı çalıştırmak istiyorsanız .exe uzantılı bir dosyasını açarak sağlarız. 

- .exe : Kullanıcın çalıştırabileceği yazılım uzantısıdır.

- Kullanıcının çalıştırabileceği yazılım uzantısını derleme sonucunda elde edersiniz.

- Yani senin yazmış olduğun C#'taki kodunu kullanıcının işletim sisteminde çalıştırılabilir hale getirmen için o kodu derlemen lazım.

- Derlemenin 2 adet çıktısı vardır. Bu çıktılardan bir tanesi .exe'dir diğeri .dll'dir.

<img src="9.png" width="auto">

***
# 4) Kodlar Nasıl Compile Edilir?
- Derleme süreci ileride kullanacağımız editörler tarafından kendiliğinden yapılacağı için buradaki sorumluluk bizim üstlenmemiz gereken bir sorumluluk değil. Haliyle burası çok önemli bir konu değil.

- Derleme esnasında esasında dosyanın uzantısı önemli değildir. İçerisindeki kodlar satır satır yorumlandığından dolayı dosyanın uzantısından ziyade içerisinde ki yazan kodlar önemlidir.

- Developer Command Prompt sayesinde elimizdeki dosyaları derleyebiliyoruz. Tabiki o dosyaların içerisinde .NET türevlerinden bir dil kullanılmış olması kaydıyla.

- Bir kodu inşa ediyorsunuz ve bu inşa ettiğiniz kod derlenmediği sürece kullanılabilir hale gelmemektedir. Onun için kodu bizim derleyip daha sonra çalıştırmamız gerekiyor. Dolayısıyla buradaki süreçten kodun geçmesi gerekiyor. Buradaki süreç manuel bir şekilde geçmeyecektir. Bunu kullanacağımız editörler ya da .NET CLI dediğimiz asistan sayesinde çok rahat bir şekilde gerçekleştirebiliriz.

<img src="10.png" width="auto">
<img src="11.png" width="auto">

***
# 5) Visual Studio Ortam Tanıtımı
- Biz kodlarımızı yazarken bilgisayar ortamında en nihayetinde not defterini kullanabiliriz. Kodumuzu orada yazıp çalıştırıp inşa edip manuel derlemelerle sonuçlarımızı alıp test edebiliriz. Bu işlem basit işlemler de bir yere kadar idare edecektir ama kompleks çalışmalarda gerçekten kurumsal yapılanmalarda artık ihtiyacımız biraz da kod maliyetini düşürecek bir asistana ihtiyacımız olacaktır.

- İşte böyle durumlarda geliştirilmiş kod yazmamızı yani bir developer sürecinde bizlere eşlik edebilecek belirli ortamlar kullanmamız gerekecektir. Bu ortamlardan en yaygın olanı Visual Studio'yu kullanacağız.

- Visual Studio Microsoft tarafından geliştirilmiştir. .NET mimarilerinin hemen hemen hepsini en mükemmel şekilde kodlayabileceğimiz bir platformdur.

- [Buradan Visual Studio'ya erişim sağlayabilirsiniz](https://visualstudio.microsoft.com/tr/)

- Visual Studio dediğimiz editör Microsoft tarafından biz developerlar için geliştirilmiş harika muazzam bir editördür/ortamdır. 

- Aklınıza gelen bütün çalışmaları biz buradan yapabiliyoruz. Mimarilerinizi, kodunuzu, uygulamanızı, programınızı, tasarımınızı, herşeyinizi bunda yapabiliyorsunuz ve bunun üzerinden tek seferde derleme işlemini gerçekleştirebiliyorsunuz. 

- Derleme sürecini Visual Studio kendi sorumluluğunda/kendine dahili bir şekilde bu sorumluluğu üstlenmiştir. 

 - Yukarıdaki menülerden önemli olarak : 
    * Debug, 
    * Tools, 
    * Solution Explorer : Yazdığımız/çalıştırdığımız/ üzerinde çalıştığımız projeye dair tüm dosyalar buradaki pencere de listelenecektir. Tek elden yönetebiliyoruz.
    * Error List :Derleme sürecinde yaşanan alınan hataları görebilirsiniz.


<img src="12.png" width="auto">

***
# 6) Proje ve Solution Kavramları
- Uygulama oluştururken temelde 2 kavram vardır.

- Proje : İçerisinde amaca dair çözümler getirilen kodsal çalışmaların yapıldığı(yani operasyonların yürütüldüğü) bir bütündür. Gerekli algoritmalarını yazıyorsun/mimarilerini oluşturuyorsun/veritabanı işlemlerini yapıyorsun vs.

- Solution : İçerisinde bir veya birden fazla proje barındıran evrensel bir kümedir.

- Gerçek hayatta bir uygulama yazarken yazdığınız uygulama bir proje değil esasında bir çözümdür/solution'dır. Dolayısıyla bu solution yani yapacağınız uygulama birden fazla projenin bir araya gelmiş hali olabilir.

- Mesela bir banka uygulamasında ekibin bir kısmı Bakiye projesinde çalışırken bir kısmı bankamatik projesinde çalışıyor olabilir başka bir kısmı ERP projesi vardır orada çalışıyordur Her proje birbirinden farklı ama kendi aralarında bir entegrasyon var. İşte biz bunların her birini bir Solution altında toplayabiliyoruz.

<img src="13.png" width="auto">

# 7) Visual Studio İle Proje Oluşturma ve Derleme
1. İlk olarak hangi proje de çalışacağımızı seçeriz. Hangi platform'da çalıştığınız önemli değil.

2. Sonra açılan ekranda proje ismi ve Solution ismi belirlenir. Ve aynı zaman da yapılan Solution'ın/kaynak dosyalarının hangi lokasyon'da/nerede depolanması gerektiği belirtilir.
    * Diyelim ki bir banka uygulaması; Banka uygulamasında solution Banka olur Projeler de Bankamatik, Bakiye, ERP bunların hepsini Banka Solution'ı daha evrensel bir isim altında toplamış olursunuz. 
    * Bir Solution altında birden fazla aynı isimde proje bulunamaz.

- Hangi platform da çalıştığımız önemli olmaksızın her daim Solution Explorer penceresinde ilgili projenin dosyalarını görebilirsiniz.

- Bir solution'a birden fazla proje eklemek için solution oluşturulduktan sonra Solution üzerinde sağ click yaparak Add->New Project diyerek projeler ekleyebilirsiniz

- Proje derlemeyi ister Proje bazlı isterseniz de Solution bazlı yapabilirsiniz. Solution'da derleme yaparsanız altındaki bütün projeler derlenir. Eğer ki proje bazlı yaparsanız sadece o proje derlenir. 

- İlgili projeye sağ click yaptığınızda;
    * Build : Derlemeyi yapar.
    * Rebuild : Önceden derlenip çıktı alınan dosyaları siler yeniden üzerine derleme yapar.
    * Clean : Derlenmiş dosyaları siler.

- Proje üzerinde sağ click Open Folder in File Explorer dediğimizde projenin kaynak dosyalarına erişebiliriz.

- Hangi proje seçiliyse başlat düğmesine tıklayarak ilgili projenin derlenip arkada üretilen exe dosyası çalıştırılacaktır.

- Proje üzerinde sağ click Set As Startup Project dersek eğer ilgili/seçilen proje o Solution'da başlangıç projesi olacaktır.

<img src="14.png" width="auto">
<img src="15.png" width="auto">
<img src="16.png" width="auto">
<img src="17.png" width="auto">
<img src="18.png" width="auto">
<img src="19.png" width="auto">

***
# 8) Visual Studio Code Ortam Tanıtımı
- Visual Studio Code çok hızlıdır.

- Microsoft tarafından UI teknolojileri için geliştirilen bir editör olduğundan dolayı hızlı kod yazmamızı/geliştirmemizi sağlıyor.

- Backend'de geliştirebilirsiniz.

- dotnet CLI dediğimiz asistana Terminal(komut satırı) üzerinden çok rahat bir şekilde komutlar verebiliyoruz.

- debugging yapabiliyorsunuz.

- Build işlemini CLI dediğimiz kod üzerinden gerçekleştiririz.

<img src="20.png" width="auto">

***
# 9) Visual Studio Code İle Proje Oluşturma ve Derleme
- Visual Studio Code, Visual Studio gibi direkt efektif komponentler barındırmamaktadır. Bu yüzden hali hazırda proje oluşturacak bir menü taşımamaktadır.

- Proje oluşturmak için dotnet cli komutlarından yararlanırız. 

- Dotnet CLI bizim komut satırı arayüzümüz aynı zamanda asistanımız da diyebiliriz. Bu asistanın bir arayüzü yok. Bu asistana cmd'den/powershell'den/Console'dan yani bir komut satırından talimat vermemiz gerekiyor.

- Bu talimatı verebilmek için Visual Studio Code'dan Terminal penceresini açarız.

- Öncelikle dikkat edilmesi gereken şu; Talimatı verdiğiniz dizin çok önemlidir. Çünkü projeyi o dizine oluşturacaktır.

- İlgili dizini seçtikten sonra ilgili dizinde dotnet cli komutlarını çağırırız.

- dotnet => Dotnet CLI'i çağırır. Bundan sonrasında talimat verebiliriz.

- dotnet'te ne yapacağınızı bilmezseniz direkt enter tuşuna basabilirsiniz o sizi bilgilendirir.

- dotnet --info => Dotnet CLI ile ilgili bilgi verir.

- dotnet --help => Dotnet CLI ile yapacaklarınızı görebilirsiniz.

- dotnet new => dediğimiz zaman bir proje oluştur demiş oluyoruz.

- dotnet new projectType --name projectName => Şu formata uyduğunuz sürece ilgili type'da(Console/MVC/WebApi) ve --name parametresinden sonra verdiğiniz isimde bir proje oluşturulacaktır.

- dotnet build => bulunduğunuz dizindeki projeyi build edecektir.

- dotnet run => bu dizindeki projeyi hem derleyecek hem de run edecektir/çalıştıracaktır.

<img src="21.png" width="auto">
<img src="22.png" width="auto">
<img src="23.png" width="auto">
<img src="24.png" width="auto">

***
# 10) Dotnet CLI Nedir?
- Command Line Interface(Komut Satırı Arayüzü)

- .NET uygulamalarını geliştirirken bize eşlik eden bir komut satırı arayüzüdür.

- Programlama yaparken yazmış olduğumuz koda eşlik edecek bir asistanımızın olması lazım. Örneğin ben proje oluşturucaksam bu projeyi bir zahmet bu asistanın oluşturması gerekiyor. Benzer mantıkla kodumu yazdım en son güncellemem gerekiyor bu güncelleme işlemini manuel bir şekilde yapıp kendim sonucunu test ediyorsam bu büyük bir zamansal maliyet haliyle bunu yapacak başka bir asistana daha ihtiyacım oluyor. Bu işlemleri dotnet CLI ile de yapabiliriz.
 
- Herhangi dosyayı/projeyi oluştururken artık görsel bir grafik arayüz üzerinden işlem yapmıyorum. Çünkü iki satır kod ile ha deyince sana istediğin yapılanmayı oluşturabiliyor ve bu iki satır kopdu yazabileceğin yer herhangi bir görsellik gerektiren bir yer değil. o yüzden günümüzde CLI denilen yapılanmalar kullanıyoruz. Bu yazılımların arayüzü yoktur. Direkt konsoldan talimat alırlar.

- .NET uygulamaları geliştirmeyi, oluşturmayı, çalıştırmayı ve yayınlamayı sağlar.

- .NET SDK ile birlikte gelir.
    * SDK dediğimiz geliştirme kitimizdir. C# kodlarını yazmak çalıştırmak için SDK'ya ihtiyacımız var.

- Prototip => Dotnet [command]

<img src="25.png" width="auto">