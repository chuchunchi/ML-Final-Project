# ML-Final-Project
## Tabular Playground Series - Aug 2022

### Reproducing Submission
1. Clone this repository.
2. Download the [pre-train model](https://drive.google.com/file/d/1jgrwX8ZtBEcTeN7if1GT_Voe_o7DdTvG/view?usp=share_link)
3. Requirements: (Already included in .ipynb)
```bash
%pip install pandas
%pip install numpy
%pip install -U scikit-learn
```
4. Run 109550027_Final_inference.ipynb.
5. The submission.csv will be store in the directory.
6. The result: 0.59021 on private score in [Kaggle competition](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/overview)

### Training process
1. Clone this repository.
2. Requirements: (Already included in .ipynb)
```bash
%pip install pandas
%pip install numpy
%pip install -U scikit-learn
```
3. Run 109550027_Final_train.ipynb.
4. The trainmodel{epoch}.pt will be store in the directory.
5. Change "PATH" variable to <MODEL_DIR> in 109550027_Final_inference.ipynb.
6. Run 109550027_Final_inference.ipynb.
7. Get your own result in submission.csv.
