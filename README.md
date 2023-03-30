# point-cloud-project
My first Point Cloud Project on [this Dataset](https://www.kaggle.com/datasets/kmader/point-cloud-segmentation) which is originally a part of [Semantic3D](http://semantic3d.net/) Dataset

My pet project features several models, that I have benchmarked: KNN, CatBoots, BERT and GCNN

Cross val Scores: 
| Model    | Balanced accuracy    | Accuracy         | F1 weighted      |
| -------- | -------------------- | ---------------- | ---------------- |
| KNN      | 0.2906±9.4184e-4     | 0.7345±1.3572e-4 | **0.6863**±8.2797e-5 |
| CatBoost | 0.2445±2.5108e-3     | 0.7777±4.9769e-5 | 0.6807±2.8747e-5 |
| BERT     | 0.2408±3.3442e-3     | **0.7778**±1.4369e-5 | 0.6807±1.2974e-5 |
| GСNN     | **0.7559**±3.3613e-2     | 0.2895±9.0011e-3 | 0.2710±1.3595e-2 |
