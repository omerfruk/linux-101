# Linux 101

* [Linux Nedir?](#linux-nedir)
* [Distro Nedir?](#distro-nedir)
* [Distrolar Arasındaki Farklar](#distrolar-arasındaki-farklar)
* [Bazı Distroların Dosya Yapıları](#bazı-distroların-dosya-yapıları)
* [Paket Yönetim Sistemi](#paket-yönetim-sistemi)
* [Bazı Distroların Paket Yöneticileri](#bazı-distroların-paket-yöneticileri)
* [Debian Nedir?](#debian-nedir)
* [CentOS Nedir?](#centos-nedir)
* [Red Hat Nedir?](#red-hat-nedir)
* [Shell Nedir?](#shell-nedir)
* [Terminal Nedir?](#terminal-nedir)
* [SSH Servisi](#ssh-servisi)
* [Komutlar](#komutlar)
  * [History](#history)
  * [Man](#man)
  * [Shutdown](#shutdown)
* [Dosya/Klasör İzinleri](#dosya--klasör-i̇zinleri)
  * [Yetkiler](#yetkiler)
  * [Erişim Yetkilerinin Değiştirilmesi](#erişim-yetkilerinin-değiştirilmesi)
  * [Suid Biti](#suid-biti)
  * [Umask Komutu](#umask-komutu)
  * [Chattr Komutu](#chattr-komutu)
* [Bir Dosyayı Okuma](#bir-dosyayı-okuma)
* [Dosya Monitoring](#dosya-monitoring)
* [Vim Editörü](#vim-editörü)
* [Aradığımız Dosyayı Bulma](#aradığımız-dosyayı-bulma)
* [Dosya/Klasör İşlemleri](#dosya-i̇şlemleri)
  * [Dosya Oluşturma](#dosya-oluşturma)
  * [Dosya Silme](#dosya-silme)
  * [Dosya Kopyalama](#dosya-kopyalama)
  * [Dosya Taşıma](#dosya-taşıma)
  * [Dosya İsim Değiştirme](#dosya-i̇sim-değiştirme)
* [Dosya İçinde Kelime Arama](#dosya-i̇çinde-kelime-arama)

------------

### Linux Nedir?

Unix’e fikirsel ve teknik anlamda atıfta bulunarak geliştirilmiş açık kaynak kodlu, özgür ve ücretsiz (destek hariç) bir işletim sistemi çekirdeğidir. Çekirdeğin kaynak kodları GNU (Genel Kamu Lisansı) çerçevesinde özgürce dağıtılabilir, değiştirilebilir ve kullanılabilir. Linux ismi ilk olarak Linus Torvalds tarafından yazılan ve 5 Ekim 1991 Linux 0.02 etiketiyle duyurusu yapılan, Linux çekirdeğinden gelmektedir. Linux’un Unix ile herhangi bir kod ortaklığı bulunmamaktadır yani Linux’un kodları sıfırdan başlanılarak yazılmıştır.

### Distro Nedir?

Linux'un dağıtımlarına verilen isimdir. Bunlardan en yaygın olarak bilinenleri;

- Debian
- Linux Mint
- Ubuntu
- OpenSUSE
- Fedora

### Distrolar Arasındaki Farklar

Dağıtımlar ihtiyaçlara göre geliştirilmişlerdir. Örneğin mint dağıtımı genelde görselliğe önem verir ve windowsdan gelen kullanıcılara cazip gelir. Ayrıca paket yönetim şekilleri ve dosya yapıları gibi farklılıklarda mevcuttur.

###  Bazı Distroların Dosya Yapıları

- [Linux Mint](https://community.linuxmint.com/tutorial/view/355 "Linux Mint")
- [Debian](https://www.debian.org/releases/buster/amd64/apcs02.en.html "Debian")
- [Ubuntu](https://help.ubuntu.com/community/LinuxFilesystemTreeOverview "Ubuntu")
- [Fedora](https://fedoraproject.org/wiki/Docs/Drafts/DirectoryStructure "Fedora")

### [Paket](https://tr.wikipedia.org/wiki/Paket_y%C3%B6netim_sistemi "Paket") Yönetim Sistemi

Paket yönetim sistemi ya da paket yöneticisi; yazılım paketlerinin ve kütüphanelerinin kurulum, güncelleme, konfigürasyon, kaldırılması işlemlerinin tutarlı ve stabil bir şekilde yürütülmesini sağlayan olan sistemlerdir. Tipik olarak paket ve kütüphanelerin hangi versiyonunun kurulduğunu ve birbirlerine olan bağımlılıklarını da hesaba katarlar. Modern paket yöneticilerinin birçoğu merkezi bir kaynaktan yazılım ve kütüphanelerin indirilip yüklenmesi işlevine sahiptirler.

Paket yönetim sistemleri, bir işletim sistemine kurulan yazılımların yönetimi için kullanılabildiği gibi yazılım geliştirme sırasında kullanılan yazılım kütüphanelerinin kurulması ve bağımlılık yönetimi (dependency management) için hazırlananları da mevcuttur.

### Bazı Distroların Paket Yöneticileri

- Linux Mint, Debian ve Ubuntu: [dpkg](https://tr.wikipedia.org/wiki/Dpkg "dpkg")
- OpenSUSE: ZYpp, YaST ve RPM
- Fedora: [RPM Paket Yöneticisi](https://tr.wikipedia.org/wiki/RPM_Paket_Y%C3%B6neticisi "RPM Paket Yöneticisi")

### Debian Nedir?

[Debian](https://wmaraci.com/nedir/debian "Debian") Linux, birçok Linux dağıtımının kaynak olarak kullandığı arayüzden ziyade daha çok komutların kullanıldığı ve orta seviyedeki her Linux kullanıcısının kullanabileceği bir Linux dağıtımıdır. 1993 yılından bu yana geçen süreç içerisinde sürekli olarak geliştiriliyor olması ve donanım konusunda kullanıcılara sunduğu geniş desteği sayesinde Debian Linux deneyiminin tam anlamıyla yaşanabileceği en iyi işletim sistemlerinden biridir.

### CentOS Nedir?

CentOS Red Hat firmasının dağıtımı olan Red Hat Enterprise Linux (RHEL) kaynak kodları üzerine kurulu ve bu dağıtım ile uyumlu bir linux dağıtımıdır. Bağımsız bir grup tarafından geliştirilen işletim sisteminin isminin açılımı The Community ENTerprise Operating System biçimindedir. Ocak 7, 2014 tarihli bir bildiri ile CentOS geliştirici lideri Karanbir Singh, CentOS'un RedHat ekibine dahil olduğunu bildirmiştir.

### Red Hat Nedir?

Red Hat, açık kaynaklı ve Linux tabanlı profesyonel yazılım şirketidir. Şirket, 1993′te Bob Young ve Marc Ewing tarafından kurulmuştur.

Red Hat tarafından resmi olarak desteklense de, Fedora özgür yazılım geliştiricilerinin katılımıyla varlığını sürdürmektedir ve aynı zamanda Red Hat Enterprise Linux ürünü için bir test ortamı görevi görmektedir.

Red Hat Linux ve dolayısıyla Fedora'yı özel yapan şey kararlı ve bilinen paketlerin, sağlam bilgi ile bir araya getirilmesidir. Paketler güncel değildir; güvenlik güncellemeleri dışında, yeni bir beta versiyon çıktığında paket versiyonları dondurulmaktadır. Sonuç, iyi test edilmiş, nispeten kararlı bir Linux dağıtımıdır. Ayrıca RPM paket yöneticisi, Red Hat'ın Linux'a katkılarından birisidir. Bugün Mandriva, Suse gibi popüler birçok dağıtımın kullandığı RPM paket kurulumu konusunda önemli adımlar atılmasını sağlamıştır.

### [Shell](https://siberoloji.github.io/linux-shell-nedir/ "Shell") Nedir?

Linux işletim sisteminin yapısında, bilgisayarın donanımı ile iletişim kuran yazılıma Kernel (Kabuk) adı verilmektedir. Kullanıcı, doğrudan donanım ile iletişim kuramaz. Kernel e bir komut göndermek ve işlemlerin yapılmasını sağlamak gerekmektedir. Kullanıcı ile Kernel arasında haberleşme, Shell ismi verilen aracı program sayesinde yapılır.

Temel olarak Shell aşağıdaki işlemleri sırasıyla yapan bir döngüye sahiptir.

1. Komutu, komut satırından veya dosyadan oku
2. Komutu değerlendir.
3. Komutu çalıştır veya gerekli programı çalıştır.
4. Sonucu ekrana veya istenen yere yazdır.
5. Birinci adıma geri dön.

### Terminal Nedir?

Terminal, metin tabanlı komutları yazabileceğiniz ve uygulayabileceğiniz bir arayüzdür. Bu arayüz sayesinde komutları çalıştırırız.

### SSH Servisi

İki sistem arasında ister yerel ağdaki bağlantıların isterse uzak bağlantıların güvenli bir şekilde yapılabilmesini sağlayan bir protokoldür. Bağlantı yapılan iki sistemin arasındaki t üm ağ trafiği şifrelenerek verilerin güvenliği sağlanır.

Bağlantı yapılırken kimlik doğrulaması yapılmaktadır. Bu kimlik doğrulamasından sonra istemci ile sunucu arasında bir şifreleme oluşur ve bu şifreleme ile haberleşirler. Ssh için istemci ve sunucuda ssh servisinin yüklü olması gereklidir.[Linux komut satırı - Kemal Demirez]

## KOMUTLAR

### History

Terminalde çalıştırdığımız her komut aslında hemen kaybolmazlar. Bu komutlar bellekte tutulur ve History komutu ile en son verdiğiniz komutları listeleyebilirsiniz.

Verdiğiniz son 10 komutu listeler:

```shell
history 10
```
### Man

Terminalde bir komutun detaylarına erişmek için bu komut kullanılır.

```shell
man exit
```

### Shutdown

Hemen kapat:
```shell
shutdown
```

Kapat ve yeniden aç (restart):

```shell
shutdown -r
```

20 dakika sonra kapat:

```shell
shutdown +20
```

20 dakika sonra restart:

```shell
shutdown -r 20
```

Saat 17:30 da kapat:

```shell
shutdown -h 17:30
```

## Dosya / Klasör İzinleri

### Yetkiler

Terminali açıp bulunduğunuz dizinde **ls -l** komutunu çalıştırır iseniz aşağıdaki çıktıyı alacaksınız.

[![Terminal ls -l](https://i.ibb.co/jh8s5Fm/rwrw.png "Terminal ls -l")](https://i.ibb.co/jh8s5Fm/rwrw.png "Terminal ls -l")

Hemen alt satırda **total 32** yazıyor. Bu iç içe geçmiş dosyalar dahil bütün dosya-klasörleri sayar ve size verir. İlk satıra bakacak olursanız Desktop için izinleri görüyorsunuz. Burada her harfin bir anlamı vardır.

- d -> burası bir dizindir, demektir. Ama eğer d yerine - (tire) olursa bu bir dosya demekti.
- r -> okuma
- w -> yazma
- x -> çalıştırma

İzinlerde dikkatimizi çeken, 3 ana parça şeklinde dağılmış olmaları. Örnek vermek gerekir ise **drwxr - xr - x ** burada tireler ile 3 ana parçaya ayrılmıştır.

- drwxr -> 1. kısım dosya/dizin sahibinin yetkileri.
- xr -> 2. kısım dosya sahibi ile aynı grupta bulunan kullanıcıların yetkileri.
- x -> 3. kısım ise genel kullanıcı yetkilerini belirtir.

### Erişim Yetkilerinin Değiştirilmesi

Erişim yetkileri önemli bir konu olduğu için bu manipülasyon işlemini sadece root kullanıcısı yapabilir. Erişim yetkilerini değiştirirken **chmod** komutu kullanılır.

```shell
chmod <ugoa><+=-><rwxst><dosya/dizin>
```
- u: Dosya ya da dizin sahibi, user.
- g: u ile aynı grupta bulunan kullanıcılar.
- o: Diğer kullanıcılar.
- a: Herkes.
- +: Yetki ekleme.
- -: Yetki çıkartma.
- =: Yetki eşitleme.
- r: Okuma
- w: Yazma
- x: Çalıştırma
- s: Suid biti.
- t: Sticky bit.

### Suid Biti

Bir dosya düşünün, bir kullanıcının yazma yetkisi yok. Fakat o kullanıcının geçici olarak yazması lazım. Suid biti ayarlanan kullanıcılar bu geçici yetkiye sahip olurlar.

Suit biti ayarlama komutu:



```shell
chmod u+s text.txt
```

Sistemdeki suit biti ayarlanmış dosya/dizin bulma komutu:

```shell
find / -perm -4000
```

### Umask Komutu

Yeni oluşturulan dizin/dosyalar için varsayılan olarak verilecek izinleri ayarlamamıza yarar.

```shell
umask rwxr-r--r--
```

### Chattr Komutu

Bir dosya düşünün, config dosyası. Bu dosyanın içinde kesinlikle değişiklil yaplmasın diyorsanız bu komut tam size göre.

```shell
chattr +i text.txt
```

Dosyayı eski haline getirmek için ise;

```shell
chattr -i text.txt
```

Sistemde korumalı dosyalar neler merak ediyorsanız?

```shell
lsattr -R <dizin>
```


### Bir Dosyayı Okuma

Her hangi bir dosyanın içini okumak istiyorsak bunun farklı komutları vardır. Okumak istediğiniz dizinde olmalısınız ya da dizini komuttan sonra belirtmelisiniz.

```shell
cat test.txt
```

ya da 

```shell
cat  ./folder/test.txt
```

ya da 

```shell
tail test.txt
```

şekillerinde kullanıl sağlayabiliriz.

### Dosya Monitoring

Genellikle log dosyalarını izlemek için kullanılan bir komuttur fakat txt dosyalarını izlemek içinde kullanılabilir.

```shell
tail -c 50  text.txt  //50 byte'lık veri görüntüler
tail text.txt -> son //10 satırı görüntüler
tail -f  /var/log/syslog //log izlemek için kullanılır
tail -F text.txt //txt dosyasının değişikliklerini anlık görüntüler ve bilgi verir.
```

### Vim Editörü

Dosyalarınızı açıp düzenleyebileceğiniz bir text editörüdür. Şimdi vim komutlarına yakından bakalım.

Debian base bir linux kullanıyorsanız önce bir install edelim.

```shell
sudo apt-get install vim
```
Açmak istediğiniz dosyayı;

```shell
vim test.txt
```

Şeklinde açabiliyorsunuz.

> Aşağıdaki komutları dosyayı açtıktan sonra veriyorsunuz.

Vim düzenleyicisini kullanmak için verilen bazı komutlar vardır. Tüm komutları ve belgelerini help komutuyla aşağıdaki gibi görebilirsiniz:

```shell
:help
```

Vim bazı modları vardır. Insert modunda dosyaya istediğiniz gibi girdi yapabilirsiniz. Bunun için **i** basmanız yeterlidir.

Verileri bir dosyaya yazdık, şimdi görev, dosyayı kaydedip kapatmak ve bunu yapmak için Esc tuşuna basarak ilk ekleme modundan çıkmak. Bir komut yazmak için önce noktalı virgül (   :   ) yazın ve ardından wq! Ve sonra ENTER'a basın.

```shell
:wq!
```

Dosyayı kaydetmeden dosyadan çıkmak için sadece q komutunu kullanın! Aşağıdaki gibi

```shell
:Q!
```

İmlecin altındaki karakteri silmek için komut modunda **x** tuşu sağlıyoruz. İmleci silinmesi gereken karaktere getirin ve Esc tuşuna basın ve ardından **x** tuşuna basın.

Geri almak için normal modda **u** tuşuna basın. Böylece en son yapılan değişiklik geri alınır. Değişiklikleri ileri sarmak için ise **ctrl+r** kullanılır.

Bir dosyanız var ve binlerce satır var. Arama yapmak istiyorsunuz vim editörü ile şu şekilde arama numaraları vardır.

**ESC** bastıktan sonra;

```shell
:/aranacakkelime
```
Eğer bir sonraki aranan kelimeye geçmek istiyorsanız;

```shell
:n
```

Bende shift + n oldu bu arada :)

Bir önceki eşleşen kelime için ise:

```shell
:N
```
Dosyadaki kelimeyi değiştirmek için;

```shell
:s/arama sözcüğü/değiştirme sözcüğü/
```

Bütün dosyada değişiklik yapmak için: (gc tek tek onay ister sadece g onaysızdır ama güvenli değildir.)

```shell
:%s/arama sözcüğü/değiştirme sözcüğü/gc
```

### Aradığımız Dosyayı Bulma

Bir dizin içerisinde veya bütün işletim sistemi içerisinde isme göre dosya araması yapabiliriz. Ayrıca sadece txt uzantılı dosyalarıda arayabiliriz.

Bunun için **find** komutu kullanıyoruz.

```shell
find ./Desktop -name test.txt
```

Veya txt uzantılı dosyaları arayabiliriz.

```shell
find ./Desktop -name *.txt
```

Veya içinde test geçen dosyaları arayabiliriz bir nevi like gibi.

```shell
find ./Desktop -type f -name "*test*"
```

### Dosya İşlemleri

Dizin işlemlerinde **-r** kullanılmalıdır.

#### Dosya Oluşturma

```shell
mkdir dosya1
```

Dizinli dosya oluşturma

```shell
mkdir dosya1/test
```

İç içe oluşturma

```shell
mkdir -p resim/b1/b2
```

Klasör oluşturma;

```shell
touch text.txt
```

#### Dosya Silme

-r ile kullanılırsa dizin silebiliriz.

```shell
rm -r dosya
```

Sadece dosya silmek için;

```shell
rm dosya 
```

ya da

```shell
rmdir dosya
```

#### Dosya Kopyalama

```shell
cp -r kopyalanan_dosya kopyalancak_konum
```

Eğer bir dizin değil ise;

```shell
cp kopyalanan_dosya kopyalancak_konum
```
#### Dosya Taşıma

Dosyayı olduğu gibi taşımak istiyorsanız;

```shell
mv dosya1 tasinacagi_konum
```

#### Dosya İsim Değiştirme

mv komutu ile yapılabiliyor. İlk önce değiştirmek istediğiniz dosya ya da klasör yazılıyor sonra yeni ismi.

```shell
mv dosya1 yeni_isim
```

### Dosya İçinde Kelime Arama

Bir dosyanız var 1000 satırlık ve içinde şu kelime geçiyor mu bakmak istiyorsunuz.

```shell
grep sorgu dosya
```

Mesela log.txt var elinizde ve içinde error var mı bakmak istiyorsunuz.

```shell
grep error log.txt
```

Büyük / küçük harf ayırmadan arama için;

```shell
grep -i sorgu dosya
```

Ya da kaç tane error kelimesi geçiyor şu log dosyasında bakalım?

```shell
grep -c error log.txt
```

Ya da bir dosyalar dizininiz var acaba diyorsunuz şu error nerde hangi dosyada var?

```shell
grep -l error ./*
```
