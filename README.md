# ✨ Derin Öğrenme Nedir? Ne İşe Yarar? ✨

Bu depo, yapay zekanın en heyecan verici ve dönüştürücü alanlarından biri olan **Derin Öğrenme (Deep Learning)** hakkında kapsamlı bilgileri bulacaksınız. Derin öğrenme, günümüz teknolojisinde karşılaştığımız birçok akıllı sistemin (sesli asistanlar, yüz tanıma, otonom araçlar vb.) temelini oluşturur.

---

## 🧠 Derin Öğrenme Nedir?

Derin öğrenme, **Yapay Sinir Ağlarının (Artificial Neural Networks - ANN)** çok katmanlı, yani "derin" yapılarını kullanan bir **Makine Öğrenmesi (Machine Learning)** alt dalıdır. İnsan beyninin çalışma prensibinden ilham alan bu ağlar, büyük veri setlerinden karmaşık örüntüleri ve hiyerarşik özellikleri otomatik olarak öğrenme yeteneğine sahiptir.

**Neden "Derin"?** 🤔
Bir sinir ağı "derin" olarak adlandırıldığında, bu, girdi ve çıktı katmanları arasında birden fazla **"gizli katmana"** sahip olduğu anlamına gelir. Bu katmanlar sayesinde model, verilerdeki soyut ve karmaşık ilişkileri katman katman öğrenir, tıpkı beynimizin bilgiyi işlediği gibi.

---

## 🚀 Derin Öğrenme Ne İşe Yarar?

Derin öğrenmenin uygulama alanları son derece geniştir ve neredeyse her sektörde devrim yaratmaktadır:

### 📸 Bilgisayar Görüsü (Computer Vision)
* **Görüntü Sınıflandırma:** Bir resmin ne olduğunu (kedi mi, köpek mi?) veya ne içerdiğini (nesneler, kişiler) otomatik olarak tanımlama.
    * Örnekler: Google Photos'ta arama yapma, tıbbi görüntülerde hastalık tespiti.
* **Nesne Algılama:** Bir görüntüdeki birden fazla nesnenin konumunu ve türünü belirleme.
    * Örnekler: Otonom araçlarda yayaları ve trafik işaretlerini tanıma, güvenlik sistemlerinde anormal durum tespiti.
* **Görüntü Oluşturma (Generative AI):** Gerçekçi ama var olmayan görüntüler üretme.
    * Örnekler: GAN'ler ile yapay insan yüzleri oluşturma, sanatsal görüntüler yaratma.

### ✍️ Doğal Dil İşleme (Natural Language Processing - NLP)
* **Makine Çevirisi:** Bir dildeki metni başka bir dile çevirme.
    * Örnekler: Google Translate, çeviri uygulamaları.
* **Metin Sınıflandırma:** Metinleri belirli kategorilere ayırma (örneğin, spam tespiti, duygu analizi).
    * Örnekler: E-posta filtreleme, müşteri geri bildirim analizi.
* **Metin Üretimi ve Özetleme:** İnsan benzeri metinler yazma veya uzun metinleri özetleme.
    * Örnekler: Sohbet robotları (chatbotlar), içerik oluşturma asistanları.
* **Soru Cevaplama Sistemleri:** Belirli bir metinden sorulara yanıt bulma.
    * Örnekler: Akıllı asistanlar, bilgi tabanlı sistemler.

### 🗣️ Konuşma Tanıma (Speech Recognition)
* Sesli komutları metne dönüştürme.
    * Örnekler: Siri, Google Assistant, akıllı hoparlörler.

### 📊 Zaman Serisi Analizi ve Tahminleme
* Gelecekteki eğilimleri tahmin etmek için zamana bağlı verileri analiz etme.
    * Örnekler: Finansal piyasa tahminleri, hava durumu tahmini, satış öngörüleri.

### 🤖 Robotik ve Otonom Sistemler
* Robotların çevrelerini algılaması, karar vermesi ve eylemler gerçekleştirmesi.
    * Örnekler: Otonom araçlar, endüstriyel robotlar.

### 🔬 Bilimsel Keşifler
* İlaç keşfi, genom analizi ve malzeme bilimi gibi alanlarda karmaşık veri setlerini analiz etme.
    * Örnekler: Hastalık teşhisi, yeni molekül tasarımları.

---

## 🛠️ Temel Derin Öğrenme Kavramları

* **Nöronlar ve Katmanlar:** Sinir ağlarının temel yapı taşları.
* **Aktivasyon Fonksiyonları:** Nöronların çıktılarında doğrusal olmayan dönüşümler sağlayan fonksiyonlar (ReLU, Sigmoid, TanH).
* **İleri Yayılım (Forward Propagation):** Verinin ağdan geçerek tahmin üretme süreci.
* **Geri Yayılım (Backpropagation):** Modelin hatalarını kullanarak ağırlıklarını güncelleme süreci.
* **Kayıp Fonksiyonları (Loss Functions):** Modelin tahminleri ile gerçek değerler arasındaki farkı ölçen metrikler (MSE, Binary Crossentropy).
* **Optimizasyon Algoritmaları (Optimizers):** Modelin ağırlıklarını en uygun şekilde ayarlamak için kullanılan yöntemler (Adam, SGD).
* **Aşırı Uyum (Overfitting):** Modelin eğitim verisini ezberleyip yeni verilerde kötü performans göstermesi.
* **Dropout:** Aşırı uyumu engellemek için eğitim sırasında nöronları rastgele devre dışı bırakma tekniği.
* **Transfer Öğrenme (Transfer Learning):** Büyük veri setleri üzerinde eğitilmiş modellerin (örn. ImageNet'teki VGG, ResNet) başka bir göreve adapte edilerek kullanılması.

---

## 🌟 Derin Öğrenme Model Mimarileri

* **Evrişimli Sinir Ağları (Convolutional Neural Networks - CNN):** Görüntü işleme için tasarlanmış, özellikle filtreler (kernels) ve havuzlama (pooling) katmanları kullanan ağlar.
* **Tekrarlayan Sinir Ağları (Recurrent Neural Networks - RNN):** Sıralı verileri (metin, zaman serisi) işlemek için tasarlanmış, "hafızaya" sahip ağlar.
* **Uzun Kısa Süreli Bellek (Long Short-Term Memory - LSTM) / Geçitli Tekrarlayan Birim (Gated Recurrent Unit - GRU):** RNN'lerin uzun vadeli bağımlılıkları öğrenme sorununu çözen gelişmiş versiyonları.
* **Transformer Modelleri:** Dikkat mekanizması (Attention Mechanism) kullanarak sıralı verileri paralel işleyebilen, NLP'de devrim yaratan modeller (BERT, GPT serisi).
* **Üretken Çekişmeli Ağlar (Generative Adversarial Networks - GAN):** Birbirine karşı yarışan iki ağdan (Üretici ve Ayırt Edici) oluşan ve yeni veri örnekleri üretebilen modeller.
* **Autoencoder'lar:** Girdi verisini sıkıştırılmış bir temsile dönüştürüp sonra yeniden oluşturarak veri sıkıştırma ve öznitelik öğrenimi yapan ağlar.

---

Bu depo, derin öğrenmenin heyecan verici dünyasına açılan bir kapıdır. Umarım buradaki bilgiler, kendi derin öğrenme yolculuğunuzda size ilham verir ve yardımcı olur!
