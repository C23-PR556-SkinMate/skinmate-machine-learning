# skinmate-machine-learning
**Facial-skin Problem Detection** <br>
Developing an accurate and efficient machine learning model for facial skin health detection which consists of multiple problems such as acnes, blackheads, dark spots, and wrinkles. <br><br>

# Dataset Structures

    ├── Datasets
        ├── Training
        │   ├── Acnes
        │   ├── Blackheads
        │   ├── Darkspots
        │   ├── Wrinkles
        └── Validation
           ├── Acnes
           ├── Blackheads
           ├── Darkspots
           ├── Wrinkles

<br>

# Final Model
    ├── upload\ test
        └──  Probabilities
            └── Labels → acne, dark spots, wrinkles, and blackheads
<br>

# Datasets
Training Data and Testing Data that were used are sourced from kaggle: <br>
- Acnes:<br>
https://www.kaggle.com/datasets/rutviklathiyateksun/acne-grading-classificationdataset
- Blackheads:<br>
https://www.kaggle.com/datasets/syllaayukusumahati/dataset <Br>
https://www.kaggle.com/datasets/hilmiher/face-disease
- Darkspots:<br>
https://www.kaggle.com/datasets/mohit335448/ageing-dataset<br>
https://www.kaggle.com/datasets/syllaayukusumahati/datasett
- Wrinkles: <br>
https://www.kaggle.com/datasets/mohit335448/ageing-dataset <br>

The dataset contains 1000 images of acne, dark spots, wrinkles, and blackheads <br><br>

| Datasets | Directories | Files |
| ----------- | ----------- | ----------- |
| Training | acnes | 200 |
|  | dark spots | 200 |
|  | blackheads | 200 |
|  | wrinkles | 200 |
| Validation | acnes | 50 |
| | dark spots | 50 |
| | blackheads | 50 |
| | wrinkles | 50 |

<br>

We also create additional datasets by scrapping data from the web. Here's our dataset structure
| Datasets | Directories | Files |
| ----------- | ----------- | ----------- |
Skincare Products | dailyCare | 48 |
| | skinTreatment | 55 |
Articles |  | 4

<br>

For this model, we use Convolutional Neural Networks and reach accuracy <br>

| Type | Accuracy |
| ----------- | ----------- |
| Training Accuracy | 91.50% |
| Validation Accuracy | 90.50% |

<br>

# Prequisites
You don't need to install anything since its written in Google Colab which is a cloud service
- download the dataset from this link https://drive.google.com/file/d/1NvVgLvWm4Y2QmsvfkQ2SCfkfvVADyqel/view?usp=share_link.
- upload the dataset on the notebook as what required
<br><br>

# Built With
Tensorflow Keras - The AI framework used <br><br>

# Authors
- Ardanisa Rachma
- Fathiah Mubina
- Samuel Aditya C <br><br>

# Sources
ACNES (JERAWAT)
- https://www.siloamhospitals.com/en/informasi-siloam/artikel/kenali-penyebab-munculnya-jerawat-dan-cara-mengatasinya#mcetoc_1gvlan1h74of
- https://www.halodoc.com/kesehatan/jerawat
- https://www.mitrakeluarga.com/artikel/artikel-kesehatan/cara-mengatasi-jerawat-mengatasi-jerawat-dengan-benar 

BLACKHEADS (KOMEDO)
- https://doktersehat.com/penyakit-a-z/blackhead-adalah-komedo-hitam/
- https://hellosehat.com/penyakit-kulit/jerawat/komedo-hitam/
- https://www.alodokter.com/kenali-penyebab-dan-cara-mengatasi-blackhead 

DARK SPOTS (NODA HITAM)
- https://www.halodoc.com/artikel/6-cara-ampuh-untuk-menghilangkan-dark-spot-di-wajah
- https://mylife.id/dark-spot-adalah/
- https://www.halodoc.com/artikel/6-cara-ampuh-untuk-menghilangkan-dark-spot-di-wajah 

WRINKLES (KERUTAN)
- https://hellosehat.com/penyakit-kulit/kulit-lainnya/penuaan-kulit/
- https://www.alodokter.com/inilah-6-cara-menghilangkan-kerutan-di-wajah-secara-alami
- https://www.dream.co.id/beauty/ketahui-perbedaan-fine-lines-dan-wrinkles-serta-cara-mengatasinya-210130v.html
- https://www.suara.com/lifestyle/2022/01/08/164508/perawatan-anti-wrinkle-adalah-solusi-awet-muda-apa-bedanya-dengan-perawatan-anti-penuaan 
