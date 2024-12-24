# [BoardScanner]

Bu proje, derin öğrenme ve görüntü işleme tekniklerini kullanarak devre kartları (PCB) üzerindeki elektronik komponentleri otomatik olarak tespit etmeyi amaçlar.

## Proje Tanımı

Bu sistem, devre kartlarındaki dirençleri, kapasitörleri, entegre devreleri (IC), transistörleri ve diğer elektronik komponentleri yüksek doğrulukla tespit edebilmektedir. Proje, elektronik tasarım, üretim, montaj, hata analizi ve kalite kontrol gibi alanlarda kullanılabilir.
![confusion_matrix](https://github.com/user-attachments/assets/cb52aaa7-8662-4b71-a60f-b248562fcefd)
![val_batch0_pred](https://github.com/user-attachments/assets/e724fc50-bfc6-489f-94f6-222ca16f9b59)
![results](https://github.com/user-attachments/assets/ae9f3b3a-d195-46f1-a347-83490d8d15b0)

## Kullanılan Teknolojiler

- **Programlama Dili:** Python
- **Derin Öğrenme Kütüphanesi:** (Örneğin: TensorFlow, PyTorch, Ultralytics YOLO)
- **Görüntü İşleme Kütüphanesi:** OpenCV
- **Veri İşleme Kütüphanesi:** NumPy
- **Diğer:** (Örneğin: Pandas, Matplotlib)

## Kurulum

1.  Python ve gerekli kütüphaneleri kurun:
    ```bash
    pip install -r requirements.txt
    ```
2.  Proje dosyalarını indirin.
3.  Eğitilmiş model dosyasını (`.pt`, `.h5` vb.) doğru konuma yerleştirin.

## Kullanım

1.  Komponentleri tespit etmek istediğiniz devre kartının görüntüsünü proje dizinine yerleştirin.
2.  Aşağıdaki örnek kodu çalıştırarak tespiti gerçekleştirin:

    ```python
    # Örnek tespit kodu buraya
    ```
3.  Tespit sonuçları, konsolda ve/veya çizilmiş bir görüntü olarak kaydedilecektir.

## Katkıda Bulunma

Bu proje açık kaynaklıdır ve katkılarınızı memnuniyetle karşılar. Katkıda bulunmak için lütfen aşağıdaki adımları takip edin:

1.  Projeyi fork edin.
2.  İyileştirmelerinizi ve değişikliklerinizi yapın.
3.  Pull request gönderin.

## Lisans

(Projeniz için bir lisans belirleyebilirsiniz: MIT, Apache 2.0, vb.)

## Uyarı

Bu proje, yalnızca yardımcı bir araç olarak tasarlanmıştır ve herhangi bir ticari kullanım için uygun olmayabilir.
