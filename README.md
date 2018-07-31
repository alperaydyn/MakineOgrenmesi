# Makine Öğrenmesi
Makine Öğrenmesi konularında yeni öğrenen birisinin gözüyle, gerçek hayat örneklerinin uygulamalı olarak ele aldığım ortamdır. Makine Öğrenmesi ile ilgili eğitim kaynakları, algoritmalar ve açıklamaları, gerçek hayat uygulamaları ve alternatif algoritmaların karşılaştırılması gibi konularda mümkün olduğu ölçüde konuyu yeni öğrenmeye başlayanların anlayabileceği düzeyde açıklamaya gayret edeceğim.

Bu başlık altında ele alacağım konuları özellikle Türkçe içerik olarak hazırlayıp orjinal terimlerini de berabernde sağlamayı amaçlıyorum. Bu konuda Deep Learning Türkiye ekibinin hazırladığı [turkce-yapay-zeka-terimleri](https://github.com/deeplearningturkiye/turkce-yapay-zeka-terimleri) deposu faydalı bir kaynak oluşturmaktadır.

Makine Öğrenmesi üç temel unsurdan oluşmaktadır.
1. Gözetimli Öğrenme (Supervised Learning): sahip olduğumuz verilerden ulaşmak istediğimiz sonuçları elde edebilmek için makineye daha önceden bilinen veri ve sonuç setinin verilerek aralarındaki ilişkinin öğretildiği öğrenme türüdür. Örneğin, hava sıcaklığı, nem seviyesi ve rüzgar hızı verilerini kullanarak yağmur yağıp yağmayacağı tahminine ulaşmak istiyoruz. Bunun için geçmiş döneme ait sıcaklık, nem, rüzgar ve ölçümün yapıldığı günlerdeki yağmur durumu verilerini makineye öğretip bugünkü sıcaklık, nem ve rüzgar verileri ile yağmur ihtimalini hesaplayabiliriz. Buradaki ana konu daha makinenin öğrenebilmesi için önceden gözlemlenmiş verilern olması gerekliliğidir.
2. Gözetimsiz Öğrenme (Unsupervised Learning): Gözetimli Öğrenmenin aksine, burada makienye verilen hazır bir veri ilişkisinin bulunmayışıdır. Bu öğrenme tipinde makine kendisine sağlanan verinin içerdiği desenleri (pattern) ve gizli ilişkileri bulmaya çalışır. Örneğin elimizde bir grup müşteriye ait veriler mevcut (KVKK izinleri alınmış olan :) ). Bu müşterilere daha iyi hizmet sunabilmek için anlamlı gruplara ayırmak istiyoruz. Böyle bir amaç için bu öğrenme yöntemine başvuruyoruz.
3. Takviyeli (Pekiştirmeli) Öğrenme (Reinforcement Learning): Takviyeli öğrenmede ise durum biraz daha farklılaşıyor. Burada makine (ajan (agent) olarak adlandırılır) bilmediği bir ortamda (environment) belirli hareketler (actions) ile ve belirli bir amaca (goal) ulaşmak için hareket ederken kazandığı ödülü (reward) en yüksek seviyeye çıkartmak ister (maximize). 

Bu konuların detaylarına ilgili başlıklarda yer veriyor olacağım.

Makine Öğrenmesi ile ilgili konuları aşağıdaki makalede yer alan akış ile oluşturmayı amaçlamaktayım. Yeri geldikçe fayalandığım tüm kaynakları paylaşmaya devam edeceğim.

[By: Vishakha Jha](https://www.techleer.com/articles/203-machine-learning-algorithm-backbone-of-emerging-technologies/)
<img alt="Machine Learning Algorithm" src="https://s3.ap-south-1.amazonaws.com/techleer/207.jpg">
