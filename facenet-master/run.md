src\classifier.py
训练
```
TRAIN
../data/lfw/lfw_160
../models/20180402-114759.pb
../models/lfw_classifier.pkl
--batch_size
1000
--min_nrof_images_per_class
40
--nrof_train_images_per_class
35
--use_split_dataset
```

测试
```
CLASSIFY
../data/lfw/lfw_160
../models/20180402-114759.pb
../models/lfw_classifier.pkl 
--batch_size 
1000 
--min_nrof_images_per_class 
40 
--nrof_train_images_per_class 
35 
--use_split_dataset
```