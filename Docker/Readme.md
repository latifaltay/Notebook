Docker Nedir? 

Docker, işletim sistemi kaynaklarını verimli bir şekilde paylaştırarak birbirinden bağımsız izole kapsayıcılar oluşturmamıza olanak sağlayan açık kaynak kodlu bir kapsayıcı platformudur. 

Docker uygulamalarımızı hızla derlememizi test etmemizi ve dağıtmamızı sağlayan bir yazılım platformudur. 

 Docker, yazılımları kitaplıklar, sistem araçları, kod ve çalışma zamanı dahil olmak üzere çalışmamız için gerekli her şeyi içeren kapsayıcı adı verilen standartlaştırılmış birimler halinde paketler ve bizim kullanımımıza sunar. 

 

Geleneksel sanallaştırma mimarisinden farkı 

Işletim sistemi seviyesinde kaynak paylaşımı sağlayarak tamamen birbirinden izole sistemler oluşturmamıza olanak sağlamasıdır  

Geleneksel sanallaştırma mimarisinde biz fiziksel donanımımız üzerine kurmuş olduğumuz tip 1 veya tip 2 hypervisor yazılımları sayesinde fiziksel donanımımızın üzerinde bulunan ram, cpu hafıza birimleri ve ağ kaynaklarını mantıksal hale getirerek birbirinden izole işletim sistemleri oluşturup çalışmalarının tamamını gerçekleştirebiliyoruz 

Docker'da ise fiziksel veya sanal fark etmeksizin daha küçük birimlerde kapsayıcılar oluşturarak işletim sistemi seviyesinde veya direkt olarak servisler özelinde kaynaklarımı daha hızlı bir şekilde oluşturabilir ve kullanabilirim. 

 

Kapsayıcı (Container) Nedir? 

Container'lar sanal makinalara benzer bir rol oynayan bir uygulama dağıtım teknolojisidir. 

Linux veya windows işletim sistemlerinde birbirinden izole olarak çalıştırılan proseslerin her birine verilen isimdir. 

Hypervisor'daki sanal makinelerin alternatifleri Docker'daki container diyebiliriz. 

 

Container'ların avantajları 

Basit sanallaştırma yapısı sayesinde daha küçük iş birimleriyle süreçlerimizi işletebiliriz. 

Tüm donanım kaynaklarını sanallaştırmak ve bağımsız bir işletim sistemi çalıştırmak yerine ana bilgisayar sisteminin çekirdeğini kullanıyor ve bu işletim sistemi içinde bölümler ayrılmış  işlemler olarak çalışıyor.  

Yani daha hızlı bir şekilde container'larımızı oluşturabiliyoruz 

İzole bir ortam sunuyor. 

Standart paketleme formatı ve çalışma zamanı gibi avantajları var. 

 

 s