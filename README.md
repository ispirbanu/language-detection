# language-detection
Creating a language perception model using the language processing method and the naive Bayes method. 

Dil işleme ile naive_bayes yöntemi kullanılarak bir dil algılama modeli oluşturmak.

Veri seti; https://huggingface.co/datasets/papluca/language-identification/tree/main açık kaynaklı adresten indirilmiştir. Veriler fazla olduğu için modeli sadece test olarak ayrılan dosyadaki verilerden eğittim.

bu veri seti 20 farklı dilin metin detaylarını içeriyor.

Diller; 
* rabic (ar)
* bulgarian (bg)
* german (de)
* modern greek (el)
* english (en)
* spanish (es)
* french (fr)
* hindi (hi)
* italian (it)
* japanese (ja)
* dutch (nl)
* polish (pl)
* portuguese (pt)
* russian (ru)
* swahili (sw)
* thai (th)
* turkish (tr)
* urdu (ur)
* vietnamese (vi)
* chinese (zh)) 

Her dil için değer sayısı;
test veri seti-> 500
validation veri seti -> 500
train veri seti -> 3500
