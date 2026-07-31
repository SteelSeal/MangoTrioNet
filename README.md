# MangoTrioNet

A project made by Kantaphon Sujjapong to classify a mango leaf image given by the user. (Capable of 3 classes: FaLan, Keaw_Sawoey, NamDokMai_Seethong and including a None class for out-of-distribution detection)

* When running one of these notebooks, you might encounter errors at the import cell. Just restart your colab runtime and run everything again.

*⚠️ This project is under development, please use it at your own risk.*

Key Features

Leaf Classification: Predicts 3 Thai mango leaf types using a fine-tuned MobileNetV3-Large model.

OOD Filtering: Uses a None class to handle non-leaf or irrelevant pictures smoothly.

Auto Preprocessing: Automatically removes background noises with rembg and resizes images to $224 \times 224$ before guessing.

---

### 📂 Datasets
All images dataset (1,700+ images) are available here:
👉 [Google Drive Folder](https://drive.google.com/drive/folders/1NBCI7iu341H14mJHfJU1eNTxNhT9uZq0?usp=sharing)
Medium - https://medium.com/@gunwinner07/mangotrionet-c297a1f1d9f1

---

