image_path: BASE_DIR köküne göre kaynak görüntü yolu.
split_image_path: SPLIT_DIR köküne göre test kopyası yolu.
sample_index: ortak veri dizisindeki indeks; test_position: predictions.npz test sırası.
is_correct=False: hatalı sınıflandırma. FN/FP, positive_class'a göre tanımlıdır.
Soft skorlar ortalama olasılık; hard skorlar oy oranıdır ve güven olasılığı değildir.
Hard tie soft kuralıyla çözülürse seçilen sınıfın oy oranı 0.5 olabilir.
misclassified_all.csv içinde aynı görüntü birden fazla deneyde yer alabilir.
