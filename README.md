# Python-Selenium
Kodlama - io Python Kampı

Paytest; Python dilinde yazılmış kullanılan en yaygın test aracıdır. Yazılım testinin yapılma gayesi, bir programdaki sorunları görebilmek ve o ölçüde yapılandırmaktır. Kullanımı kolay ve anlaşılır bir dile sahiptir. Yapılan testlerin yürütülmesi, sıralanması ve raporlanması konularında oldukça fonksiyoneldir. Paytest, standart Python unittest modülüne göre daha basit ve daha esnek bir kullanım sağlar. Bu gibi sebeplerden dolayı Paytest  sıklıkla kullanılan bir araçtır. 

Decaratör ise test fonksiyonlarının özelliklerini değiştirmek ve genişletmek için kullanılır. Bu da testleri daha okunaklı ve anlaşılır hale getirir.
  
@pytest.fixture : Test fonksiyonlarında kullanılacak olan ve tekrar eden işlemleri tanımlamak için kullanılır. (Veri tabanlarına bağlanmak gibi.) 

@pytest.mark.xfail : Testin geçmesi beklenmeyen ve hatalı sonuçlar vermesi beklenen durumlarda kullanılır. 

@pytest.mark.skip : Belirlenmiş bir test fonksiyonunun geçici olarak atlanılmasını sağlar. 

@pytest.mark.parametrize : Test fonksiyonlarının farklı parametrelerde çalıştırılmasını sağlar. 

@pytest.mark.timeout : Bir test fonksiyonunun belirli bir sürede tamamlanması gerektiğini belirtmek için kullanılır. 

@pytest.mark.filterwarnings : Test fonksiyonlarında gelebilecek bir mesajın beklenen olduğunun belirtilmesinde kullanılır. 

