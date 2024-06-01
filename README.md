# Rock_Classification-Using-ViTs

Dataset: https://www.kaggle.com/datasets/salmaneunus/rock-classification

Set Up Step
1. Download dataset
2. Extract 7 subdirectory from 3 main directory. Then you'll get dataset directory with 7 classes directory.
   classes - Basalt, Coal, Granite, Limestone, Marble, Quartzite, Sandstone
4. install library/framework
   - Augmentor                    0.2.12
   - datasets                     2.14.6
   - evaluate                     0.4.0
   - matplotlib                   3.8.2
   - numpy                        1.26.2
   - pandas                       2.1.3
   - pyarrow                      15.0.0
   - scikit-learn                 1.3.2
   - seaborn                      0.13.0
   - torch                        2.2.0+cu118
   - torchaudio                   2.2.0+cu118
   - torchvision                  0.17.0+cu118
   - transformers                 4.26.1
   - typing_extensions            4.8.0

Training step
1. Run Data_Clean&Split.ipynb for cleaning,balancing,partioning dataset
2. Run ViT.ipynb for training
