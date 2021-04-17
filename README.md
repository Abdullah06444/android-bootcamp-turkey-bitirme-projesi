# GDG Turkey Android Bootcamp Bitirme Projesi

Selamlar! Ekip olarak, burada aldığınız tüm eğitimlerin içeriklerini uygulayabileceğiniz bir uygulamayı istemek doğru olacaktır diye düşündük. Uygulamayı yapabilmeniz için tüm içerikleri aşağıda açık bir şekilde açıklamaya çalıştık. Bu aşamada sorularınızı Discord sunucumuz üzerinde #destek kanalına yazarak sorabilirsiniz. Hatırlarsanız, nasıl soru sorabileceğiniz ile ilgili bir webinar yapmıştık. Eğer izlemediyseniz, [bu linkten](https://www.youtube.com/watch?v=XzOtgHwH70U) izleyebilirsiniz.
Projeniz için başlangıç tarihi **17.04.2021 Cumartesi**, bitiş tarihi ise **08.05.2021 Cumartesi**.

Kolay gelsin! :)

# Harcama Takip Uygulaması

Uygulamanın amacı, kullanıcının harcamalarını takip edip, farklı para birimlerini içinde kullanacağı ve kendi ismini uygulama içinde görüntüleyebileceği, bir harcama takibi uygulaması yaratmak. Uygulama içerisinde sizden istediğimiz gereksinimleri alt başlıklarda sıraladık.

## Para Birimi Çevrimlerinin Sağlanabileceği Api

İnternet üzerinde bulduğunuz herhangi bir para birimi çeviren apiyi kendi projenizde kullanabilirsiniz. Burada dikkat etmeniz gereken, kodunuzu gönderirken api için aldığınız bir key var ise bunu belirtmek, keyi reponuzun içinde bir dosyada sağlamak olacaktır. Apinin **TL, Dolar, Euro ve Sterlin para birimlerinin çevrimlerini sağlayabilmesini bekliyoruz**.

Bu tür apilerin bedava ya da freemium([.bkz](https://tr.wikipedia.org/wiki/Freemium)) versiyonlarını Google üzerinden basit bir arama ile ya da bu apileri listeleyen ve sağlayan siteler aracılığı ile bulabilirsiniz. Bu aracılardan birine [buraya](https://rapidapi.com/marketplace) tıklayarak ulaşabilirsiniz. Örnek olarak [buradaki](https://www.currencyconverterapi.com/docs) apiye göz atabilirsiniz.

## Uygulamanın Genel Gereksinimleri

Uygulamanın tabii ki tüm derslerin işlendiği **Kotlin** dili ile yazılmasını ve en az Android SDK API 21 desteklemesini bekliyoruz. Kodunuzu yazarken testlerini de yazmanız sizin için artı puan anlamına gelecektir ama **zorunlu değil**. Uygulamanın aynı zamanda offline kullanılabilir olmasını bekliyoruz.

Uygulama içerisinde **Room Database, Navigation, View Binding ya da Data Binding, Retrofit ve RecyclerView** kullanmanızı bekliyoruz.

Uygulama simgenizin varsayılan Android uygulama simgesinden farklı olması gerekiyor. Bunun için basitçe ikon sağlayan sitelerin birinden yararlanabilirsiniz([.bkz](https://www.flaticon.com/)).

## Splash Screen - Onboarding Screen

Uygulamanızın açılışında bir [splash screen](https://www.geeksforgeeks.org/android-creating-a-splash-screen/) görmeyi ve uygulamanın **ilk kez açılışında** bir [onboarding screen](https://material.io/design/communication/onboarding.html) görmeyi bekliyoruz.

![Splash Screen](https://lh3.googleusercontent.com/cB1zZlmXO0em1SxPBMpP5SU-gjnJSrQ9LdB7_2xA3V6Eg29cxLZAod_FQIW-7IQVlS1QAcSACa5Qct5bCWFrncQv_nXs6Sj_1xDuYVCAz6XQ2-ym7svQlZLZBax1hjQ1ITUlBsPde8d3t2t0kKh_gPux6_tfn5ZV2gMlu-vYRRGPC4ryM2wvT-98AAKS897Mc7oi9Qr_MUY0-jYrv2RiExusqs31jskyTaUbWD2X_XkbRQmRKiR7l87LMObgxOkQynV13dQgQJ3J3zgtc5f593jIzWAQyb1XLg98aYhPG_D92XIznkuH0t1YmJbSNTGhy8kATJk1rm5gWZyTCpR6xQ_9UCjOmC9WUo4Hyhpra2DjTKZbPKdIJNwk1V59KiJtBQu7IBS5TKZr6KwvhsPZpDg5qg2DQ7SjszmlyUm0U0hh5DwyZItBRqx0LKfp3aalr_fwE-706Qmy6HYXkiZicKCHf73eALSJKgpKeOXFw4vpiG1ufV4ToDNeOg7-RxTqCFcigdz5iRRaqyTm_Kh-GGhSvI3B3UnfL3EjSggQ_okd1EWxNWfp6lfTKNEfIA1Km424_Fx1kpnOZNAPIii03LQcrsjfzlpAbwqyWucneEPx0O5Z-TB0545QlCyps2svvaVHkUKV2dBPMQ-tbjjFX9Y7MNKRIrjz_kF2UyVkIBUM6_QaY-LJmjlVCg3OeLPBHpsQmiFDrfr99Hk5XVEZHHXl=w464-h952-no)

![Onboarding Screen](https://lh3.googleusercontent.com/pw/ACtC-3fajqS2wfjTzVo04QXb1XxwAsWX_gh2pSB_Xze2eEZFT-QngGGEluuooaHDcRSGo2dLXWCTmriybwamxihxG9T-KigSl6wgT5ZKNu3Y4_ocxz0yxZgr5uGgFx0I-jiBN2CNPUw4wtgUJ9IQYo6nc0N_=w464-h952-no)

## Para Birimleri

Uygulamanız içinde **TL, Dolar, Euro ve Sterlin olmak üzere en az 4 para birimi çevrimi ve girişine imkan vermenizi bekliyoruz**. Para birimi sayınız daha fazla olabilir, fakat yukarıda belirtilen 4 para birimini bulundurmanız zorunludur.

## Sayfa Gereksinimleri

Uygulamanız içerisinde bir adet harcama ekleme ekranı, bir adet isim ve cinsiyet değiştirme ekranı, bir adet harcama detayı görüntüleme ekranı ve para birimlerinin her biri için, o sayfaya ait para birimine çevrilmiş olarak harcamaların listelendiği genel bir ekran olmasını bekliyoruz.

Harcama ekle ekranının içinde en az 3 harcama tipi(Fatura, Kira, Diğer vb.) ve para biriminin seçilebilmesini, harcama ismi ve tutarının seçilen para birimine göre girilmesini bekliyoruz.

![Harcama ekleme ekranı](https://lh3.googleusercontent.com/pw/ACtC-3fyfWj76QN8UEdNsxMy48M1qZmquz-3_EWTISPDV9M-fcLCT6cOLVn_ngsyJR0zqh18zkwxnRzLRTQrPqjWVXCMPYx4xb020W11i6g5KZLs0Bu_kG8FuC1M4Yq2HBwD0Vclz-2P8BKAgAO5vNVsOKsV=w464-h952-no?authuser=0)

İsim ve cinsiyetin seçildiği ekran içerisinde ismin girilebildiği bir alan, kadın, erkek ya da belirtmek istemiyorum seçeneklerinin olduğu bir radio group olmasını istiyoruz.

![İsim ve cinsiyet ekranı](https://lh3.googleusercontent.com/pw/ACtC-3f3Pl8IpopEZcAnPtDtJnjEmmNOdGZu_E6S9DBSl5ZrtDsPbYSEqSE0y_ou6wzINZ9z140GvfysCAtEKPADftA6co7USg9jaIqNMfLzSBf_LmxtPCuifvN3VF8M0mCp2A2C26Q2g7jqoxsmpHPNIbw8=w464-h952-no?authuser=0)

Para birimlerine göre ayrılmış listelenme ekranının yukarısında kullanıcı ismi ile cinsiyetinin birleşimine göre oluşturulmuş bir yazı ve toplam harcamaların görülebileceği bir kart olmasını bekliyoruz. Alt kısımda ise harcamaların seçilen para biriminde listeleneceği bir kısım olmalıdır. Burada para birimi değiştiğinde Recycler içindeki bütün veriler ve harcama toplamı da para birimine göre değişmelidir.

![TL harcama listesi](https://lh3.googleusercontent.com/pw/ACtC-3d2bNbZUluUqB5QqeRAZCVqwTT-tyVwUl1bIvctbx5F8Nt5KpPgp-akgrQCCW8_97DWKY_mo3g6tKCNXzotmSj8ugNhKldgv8_AQ5jjlGbdRe6QIBOxwZUsiTEw7JxPE-OIWIGjvrUvQjSi6krENwS_=w491-h1009-no?authuser=0)

![Dolar harcama listesi](https://lh3.googleusercontent.com/pw/ACtC-3c0pQQiIQv6519nRUvZvS4w1ZNRPiDbAdnN5PHACWMU-BbprLix2eeaBmpQVMWQVl1KqBiflWLvn2siYwYSAIK_ILxlWI6fXPRB-aDHuHde3noPaAY6ipC7CUT2-8j_dQTMyCxfko5D7D_06-vSM_Ws=w491-h1009-no?authuser=0)

Harcama detayında ise o harcamanın türüne göre bir ikon, harcamanın adı ve görüntülenen para biriminin gösterildiği bir ekran bekliyoruz. Bu sayfada aynı zamanda harcamanın silinebildiği bir buton olması gerekiyor.

![Harcama detayı](https://lh3.googleusercontent.com/pw/ACtC-3fTha6VXyaLHStb06OaJR_liQKlDUKSkN4en-2_SWCgNmVu1wYcGzqk1_4-T-JzNhWi72--1ILVsxrWlcwTH5YAI44nwonkaed8Di38kogEAjdeMJCYZRQ3gM5ItrXHSbnbJb5Oamgs24pH6fBFjgT8=w491-h1009-no?authuser=0)

## Uygulama Teslimi

Uygulamanızı tamamladığınızda belirli bir formatta teslim etmeniz gerekiyor.
Uygulamanızı gerekli tüm dosyalar ve `.gitignore` dosyası ile birlikte bir GitHub reposunda public olarak paylaşmanızı bekliyoruz. Eğer bir api kullandıysanız, aldığınız ücretsiz token ya da api keyi dosyalarınızın içine koymayı unutmayın. Lütfen reponuzun ismi "deneme", "adana" gibi anlamsız kelimeler içermesin. İsim içerisinde "Android Bootcamp Turkey" kelimelerini geçirebilirsiniz. Uygulamanızın reposu içinde uygulamanın nasıl yüklenip çalıştırılacağına dair bir `README.md` dosyası(bu dokümanı okuduğunuz dosya gibi, Markdown dili ile yazılmış.) size ek puan getirecektir. Örnek readme formatlarını [buradan](https://github.com/matiassingers/awesome-readme) bulabilirsiniz. Readme içerisinde uygulamanıza ait resimler ve uygulamanın bir anlatımı da bulunabilir.

Uygulamanızı kendinize ait bir repoya yükledikten sonra yapmanız gereken [buradaki](https://forms.gle/GALfAEQeg7WSXdWA7) formu doldurmak.

Her şey hazır! Uygulamanızı reponuza yükleyip form ile bize ilettiğinizde yapmanız gereken başka bir şey yok.

## Notlar

Yukarıdaki dokümanın video ile anlatımı için [buradaki](https://www.youtube.com/watch?v=5_pkeUdSNIE&t=4429s) linke göz atabilirsiniz.
Lütfen soruları sormak için Discord sunucumuzu kullanmaktan çekinmeyin. Sorularınızı soru sorma şekillerine uygun olarak sormayı unutmayın 😊

Son olarak, bu süreci sonuna kadar bizimle birlikte ilerlettiğiniz için teşekkürler! Sizinle tanıştığımız için çok mutlu olduk 🥳
