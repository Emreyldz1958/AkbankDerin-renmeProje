# AkbankDerin-renmeProje


/*

CNN ile Görüntü Sınıflandırma Bu proje, görüntü verilerini sınıflandırmak için bir Konvolüsyonel Sinir Ağı (CNN) modeli oluşturmayı amaçlamaktadır. TensorFlow ve Keras kütüphaneleri kullanılarak modelin doğruluğunu artırmak için çeşitli görüntü işleme ve veri artırma teknikleri uygulanmıştır.

Proje Özeti Model Türü: Konvolüsyonel Sinir Ağı (CNN) Kullanılan Kütüphaneler: TensorFlow, Keras, NumPy, Pandas, Matplotlib, Seaborn, PIL Veri Ön İşleme: Görüntü verilerinin yeniden boyutlandırılması, etiketleme ve kategorik veri dönüştürme Veri Artırma: ImageDataGenerator kullanarak veri seti üzerinde veri artırma teknikleri Değerlendirme: Karışıklık matrisi ve sınıflandırma raporu kullanarak model performansı Kullanılan Kütüphaneler numpy ve pandas: Veri ve matris işlemleri matplotlib ve seaborn: Görselleştirme train_test_split: Veri setini eğitim ve test olarak ayırma confusion_matrix, classification_report: Model performans değerlendirmesi Sequential, Conv2D, MaxPooling2D, Dense, Dropout, Flatten: CNN model katmanları ImageDataGenerator: Veri artırma LabelEncoder, to_categorical: Etiketlerin sayısal verilere dönüştürülmesi PIL: Görüntü işleme Model Yapısı Model, aşağıdaki katmanlardan oluşmaktadır:

Konvolüsyon (Conv2D) Max Pooling (MaxPooling2D) Düzleştirme (Flatten) Tam Bağlantılı Katmanlar (Dense) Dropout Katmanları (Overfitting'i önlemek için) Eğitim ve Test Model, eğitim ve test setlerine ayrılan veri üzerinde eğitilmiştir. Eğitim sırasında gerçek zamanlı veri artırma teknikleri kullanılmıştır.

Sonuçlar Karışıklık matrisi ve sınıflandırma raporu ile modelin doğruluğu ve performansı değerlendirilmiştir.

Kaggle Proje Linki : https://www.kaggle.com/code/ahmetcoban17/proje-son-hal

*/
