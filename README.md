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
- Samuel Aditya C
