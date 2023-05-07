Verisetlerine proje aşağıdaki linkten ulaşabilirsiniz. Veriseti proje başlığının olduğu dosyadadır.
https://drive.google.com/drive/folders/1kZtC0BEIBhlZlcRESfLVdgUveEDFPwsq?usp=share_link


# Recommender System 
 
#### - Association Rule Learning
#### - Content Based Recommendation
#### - Item Based Collaborative Filtering
#### - User Based Collaborative Filtering
#### - Model Based Matrix Factorization

## Association Rule Learning
#### 
Association Rule Learning 
(Birliktelik Kuralları Öğrenme), bir veri kümesindeki öğeler arasındaki sık ilişkileri belirlemek için kullanılan bir makine öğrenmesi tekniklerinden biridir.

Bu yöntem, bir veri kümesindeki öğeler arasındaki ilişkileri analiz etmek ve belirli bir öğe kümesinin diğer öğelerle ne sıklıkta birlikte göründüğünü belirlemek için kullanılır. Örneğin, bir mağazanın satış verilerinde, bir müşterinin belli bir ürünü aldığında diğer hangi ürünleri de satın aldığı gibi ilişkileri belirlemek için kullanılabilir.

Association Rule Learning, genellikle Apriori algoritması gibi yöntemler kullanarak gerçekleştirilir. Bu algoritmalar, bir veri kümesindeki öğelerin sıklıklarını ve ardışık öğelerin sıklığını analiz ederek, sıklık tabloları ve frekans sayıları oluşturur. Daha sonra, belirli bir destek ve güven seviyesi belirlenerek, sıklık tablolarında belirli öğe kümeleri için birliktelik kuralları oluşturulur.

Bu yöntem, özellikle pazarlama, müşteri ilişkileri yönetimi, web madenciliği ve sağlık verileri analizi gibi birçok alanda kullanılır.
## Content Based Recommendation
#### 
Content Based Recommendation
Content-Based Recommendation (İçerik Tabanlı Tavsiye), bir kullanıcının geçmiş davranışlarını veya tercihlerini kullanarak benzer içeriği öneren bir öneri sistemidir. Bu yöntem, bir kullanıcının beğendiği bir öğenin özelliklerine dayalı olarak benzer öğeleri önerir.

Örneğin, bir müşteri bir e-ticaret sitesinde bir tişört satın aldığında, içerik tabanlı bir öneri sistemi, benzer tişörtler veya tişörtlerle uyumlu diğer giyim öğelerini önerir. Bu, tişörtlerin rengi, boyutu, markası, fiyatı gibi özellikleri kullanarak yapılır. Ayrıca, bir film veya TV şovu için de benzer bir yöntem kullanılabilir. Örneğin, bir kullanıcının bir drama filmi izlediği takdirde, içerik tabanlı bir öneri sistemi, diğer dramaları veya aynı oyuncuları içeren filmleri önerir.

Content-Based Recommendation, genellikle özellik tabanlı öneri olarak da adlandırılır ve filtreleme yöntemleri arasında yer alır. Bu yöntem, kullanıcının özelliklerini ve öğelerin özelliklerini birlikte kullanarak benzer öğeleri önerir. Bunun yanı sıra, özelliklerin ağırlıklarının belirlenmesi ve benzerlik puanının hesaplanması için bir dizi teknik kullanılır, örneğin TF-IDF (Terim Frekansı-Ters Belge Frekansı), K-NN (K en Yakın Komşu) ve benzeri.

Content-Based Recommendation, özellikle ürünlerin ve içeriklerin kolayca özelliklerine ayrıştırılabildiği e-ticaret, müzik, film ve kitap endüstrilerinde sıklıkla kullanılır.

## Item Based Collaborative Filtering
####

Item-Based Collaborative Filtering (Öğe Tabanlı İşbirlikçi Filtreleme), bir öneri sistemi yöntemidir. Bu yöntem, benzer öğeleri önermek için bir kullanıcının beğendiği öğeleri kullanır. Bu yöntem, bir kullanıcının benzer öğeleri beğenme olasılığının daha yüksek olduğu varsayımına dayanır.

Örneğin, bir kullanıcının bir filmi beğendiği takdirde, bu yöntem, diğer kullanıcıların da aynı filmi beğendiği takdirde, benzer diğer filmleri önerir. Bu, filmlerin özelliklerine (türü, oyuncuları, yönetmeni, vb.) dayanarak yapılır ve bir kullanıcının benzer özelliklere sahip filmleri de beğeneceği varsayımına dayanır.

Item-Based Collaborative Filtering, bir kullanıcının geçmiş davranışlarını kullanarak, öğeler arasındaki benzerliklerin belirlenmesiyle gerçekleştirilir. Bu yöntem, kullanıcının beğendiği öğelerin benzerliklerini hesaplar ve bu benzerlikleri kullanarak diğer öğeleri önerir.

Örneğin, bir kullanıcının bir filmi beğenmesi, o filmin özelliklerine (tür, yönetmen, oyuncular vb.) dayalı olarak, diğer filmlerle karşılaştırılabilir. Bu yöntem, özellikle, kullanıcının geçmiş davranışlarının sınırlı olduğu ve bir kullanıcının daha önce beğendiği öğelerin sayısının az olduğu durumlarda etkilidir.

Item-Based Collaborative Filtering, genellikle Matrix Factorization (Matris Ayrıştırma) ve benzeri tekniklerle birleştirilerek kullanılır. Bu yöntem, özellikle ürün ve içerik önerisi gibi e-ticaret, müzik ve film endüstrilerinde yaygın olarak kullanılır.

## User Based Collaborative Filtering
####
User-Based Collaborative Filtering (Kullanıcı Tabanlı İşbirlikçi Filtreleme), bir öneri sistemi yöntemidir. Bu yöntem, benzer kullanıcıların benzer öğeleri beğendiği varsayımına dayanır ve bir kullanıcının önceki tercihlerine dayanarak benzer kullanıcıları bulur ve bu kullanıcıların beğendiği öğeleri önerir.

Örneğin, bir kullanıcının bir filmi beğendiği takdirde, bu yöntem, benzer özelliklere sahip diğer kullanıcıların da aynı filmleri beğendiği varsayımına dayanarak, benzer diğer filmleri önerir. Bu, bir kullanıcının benzer özelliklere sahip kullanıcıları bulması, bu kullanıcıların beğendiği öğeleri bulması ve benzerlik puanlarını hesaplamasıyla yapılır.

User-Based Collaborative Filtering, bir kullanıcının geçmiş davranışlarını kullanarak benzer kullanıcıları bulur. Bu yöntem, bir kullanıcının geçmiş davranışlarının benzer özelliklere sahip kullanıcıların davranışlarına benzer olması durumunda, bu kullanıcıların beğendiği öğeleri önerir.

Örneğin, bir kullanıcının bir filmi beğenmesi, o filmin özelliklerine (türü, yönetmeni, oyuncuları vb.) dayalı olarak, benzer özelliklere sahip diğer kullanıcıların da o filmleri beğendiği varsayımına dayanır.

User-Based Collaborative Filtering, genellikle Matrix Factorization (Matris Ayrıştırma) ve benzeri tekniklerle birleştirilerek kullanılır. Bu yöntem, özellikle, kullanıcının geçmiş davranışlarının çok sayıda olduğu ve kullanıcıların tercihlerinin birbirinden farklı olduğu durumlarda etkilidir. Özellikle sosyal ağlarda, müzik ve film sitelerinde kullanıcıların birbirlerini takip ettiği durumlarda kullanılır.

## Model Based Matrix Factorization
#### 

Model-Based Matrix Factorization, bir öneri sistemi yöntemidir. Bu yöntem, büyük ölçekli veri kümelerinde, özellikle seyrek matrislerde, öneri yapmak için kullanılır. Bu yöntem, verilerdeki desenleri belirlemek ve özellikleri tanımlamak için bir matris ayrıştırma yaklaşımı kullanır.

Model-Based Matrix Factorization, bir matrisi iki alt matrise ayırır. İlk matris, kullanıcıların öğelere verdiği dereceleri içerir. İkinci matris, öğelerin özelliklerini içerir. Bu matrisler, birbirleriyle çarpılarak öneri sistemine temel oluşturan bir matris oluşturur.

Bu yöntem, özellikle ürün önerisi gibi işlemlerde kullanılır. Örneğin, bir e-ticaret sitesi, bir kullanıcının daha önceki alışverişleri ve diğer kullanıcıların benzer alışverişlerine dayanarak bir öneri yapabilir. Bu yöntem, bir kullanıcının beğenilerini daha iyi tahmin edebilir, çünkü kullanıcının daha önceki davranışlarını ve benzer özelliklere sahip diğer kullanıcıların davranışlarını analiz ederek benzerlik puanlarını hesaplar.

Model-Based Matrix Factorization, genellikle Gradient Descent (Gradyan İniş) ve benzeri tekniklerle birleştirilerek kullanılır. Bu yöntem, özellikle büyük veri kümelerinde etkili olabilir, çünkü matrislerdeki eksik verileri doldurabilir ve yeni özellikleri tanımlayabilir.