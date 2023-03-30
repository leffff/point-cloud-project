# point-cloud-project
My first Point Cloud Project on [this Dataset](https://www.kaggle.com/datasets/kmader/point-cloud-segmentation) which is originally a part of [Semantic3D](http://semantic3d.net/) Dataset

My pet project features several models, that I have benchmarked: KNN, CatBoots, BERT and GCNN

Cross val Scores: 
| Model    | Balanced accuracy    | Accuracy          | F1 weighted       |
| -------- | -------------------- | ----------------- | -----------       |
| KNN      | 0.2917±6.1318e-4     | 0.7346±9.5060e-5 | 0.6864±9.7508e-5 |
| CatBoost | 0.2386±7.096e-3      | 0.7777±6.8989e-5 | 0.6807±6.0206e-5 |
| BERT     | 0.2408±3.3442e-3     | 0.7778±1.4369e-5 | 0.6807±1.2974e-5 |
| GСNN     | 0.7559±3.3613e-2     | 0.2895±9.0011e-3  | 0.2710±1.3595e-2  |
