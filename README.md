Case 1 :
- Yukarıdaki Bitcoin grafiğinin görüldüğü ekran’nı min. kaç tane test case ile kontrol
edebiliriz ? bu caseler nelerdir ?
Minimum bir test case ile kontrol edilebilir bu da çalışıp çalışmadığı üzerine olabilir,çalışan bir durumu ele alayım.
7 gün seçeneğini seçerim ve grafikte alttaki zamanın 7 güne yayılıp yayılmadığına bakarım. Expected Results 7 güne yayılmasıdır actual result da 7güne yayılıyor çalışıyor.
Ancak ScreenShotta(SS) te şöyle bir sorun var saat kısmında 19 yazıyor orada 03:00 AM olmalıydı orada bir hata var.

-Yukarıdaki Bitcoin grafiğinin görüldüğü ekran’nı max. kaç tane test case ile kontrol
edebiliriz ? bu caseler nelerdir ?

Aslında maximum olarak şöyle düşünebilirim yakınlaştırma uzaklaştırma grafiğini de katacaksak sonsuzdur ama edge caseler ile birlikte sadece zaman aralıklarını test case 
edeceksem şöyle bir permütasyon hesabı yapılabilir. 6x(5.4.3.2.1) 6x120= 720 olasılık var örneğin bir güne bakarım sonra 1 yıla sonra bir yıldan aza gibi bu sıralamaların
her değişik yolu ayrı bir test casedir farklı bir yazılım durumu olduğundan ve her başlangıç için 5.4.3.2.1 durum ve 6 tane buton olduğundan 720 dedim.


-Yukarıdaki Bitcoin grafiğinin görüldüğü ekran’nın edge caselerine min. 1 örnek
verebilir misin ?

Örneğin: Kullanıcı önce 1 Yıla tıklar grafiğin ve zamanlamanın çalışıp çalışmadığına doğru olup olmadığına bakar ardından Yıl Başından Bugüne ardından 1 Gün'e ardından
1 Ay'a ardından 7 Gün' e tıklayarak test eder ve yazılımın güvenilirliğini kontrol eder yazılımın bozuk olup olmadığına bakar UI tarafından.
