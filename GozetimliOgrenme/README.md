# Gözetimli Öğrenme (Supervised Learning)

Supervised learning is the machine learning task of learning a function that maps an input to an output based on example input-output pairs 

Gözetimli öğrenme, örnek girdi ve çıktı çiftlerini birbiri ile ilişkilendirerek öğrenen bir fonksiyonun makine öğrenmesi işlemidir.
[Wikipedia](https://en.wikipedia.org/wiki/Supervised_learning#cite_note-1)


Gözetimli öğrenme temel olarak daha önceden gözlemlenen durumlara ait verilerden yola çıkarak girdiler ile çıktılar arasındaki ilişkiyi tanımlamaktır. Gözlem veri seti iki unsurdan oluşur, bağımsız değişkenler, bağımlı değişkenler. Bağımsız değişken(ler) birbirleri arasında bilinen bir ilişki bulunmayan ve gözlemler esnasında elde edilen verilerken, Bağımlı değişken(ler) değerleri bağımlı değişkenler ile ilişkili olarak dğeişkenlik gösterdiği düşünülen verilerdir. Amaç bu değişkenliği formüle etmektir.

Bir örnek ile açıklayalım. Haftanın günü, ayın kaçıncı günü, yola çıkış saati, yağmur durumu, resmi tatil olup olmadığı verilerinden yola çıkarak trafik yoğunluğu yaşanıp yaşanmayacağı sonucuna ulaşmak istiyoruz. 

Burada bağımsız değişkenler;
* Haftanın günü
* Ayın kaçıncı günü
* Yola çıkış saati
* Yağmur durumu
* Resmi tatil mi değil mi?

Bağımsız değişken ise;
* Trafik yoğun mu değil mi?

Veri setimiz aşağıdaki gibi görünecektir;

|Haftanın Günü|Ayın Günü|Saat|Yağmur|Resmi Tatil|Trafik Yoğun mu?|
|---          |---      |--- |---   |---        |           ---: |
|4            |1        |7   |Yok   |Hayır      |**Evet**        |
|5            |2        |6   |Var   |Hayır      |**Evet**        |
|6            |3        |8   |Yok   |Evet       |**Evet**        |
|7            |4        |8   |Yok   |Evet       |**Hayır**       |
|1            |5        |9   |Yok   |Hayır      |**Hayır**       |
|2            |6        |6   |Yok   |Hayır      |**Evet**        |
|3            |7        |7   |Var   |Hayır      |**Hayır**       |
|4            |8        |9   |Var   |Hayır      |**Evet**        |

Gözetimli öğrenmede amacımız bağımsız değişkenler ile bağımlı değişkenler arasındaki ilişkiyi formüle dökmekdir.

Takip eden başlıklarda bu ilişkinin nasıl kurulacağını inceliyor olacağız. 

Gözetimli Öğrenmeyi aşağıdaki başlıklarda inceleyeceğiz;
* Sınıflandırma (Classification)
* Regresyon (Regression)
