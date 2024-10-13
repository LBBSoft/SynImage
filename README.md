# SynImage
This code repository includes a novel approach called SynImage that employs molecular images to represent drugs and transforms gene expression data into images to characterize cancer cell lines, to predict synergy scores for drug combinations.
![SynImage](https://raw.githubusercontent.com/maryammehrabani/SynImage/main/synimage.png)

**Enviroment Setup**
You can install the packages 

 ```
pip install pyDeepInsight
pip install torchcam
pip install torch==1.13.*

```
Downloaded pre-trained ImageMol model from GitHub Repository "https://github.com/HongxinXiang/ImageMol"  to extract features from SMILES drugs 

**Usage**

You can download all data from  https://github.com/maryammehrabani/SynImage/tree/main/Data


**Property Prediction Model**

1.Prepare data

```
python cell_line_features.py
```

The outputs generated by cell_line_features.py  has been saved in the Data directory and do not require re-execution if not necessary.

2.Training

```
python SynImage_main.py
```


