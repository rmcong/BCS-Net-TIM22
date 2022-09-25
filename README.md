# BCS-Net-TIM22
Runmin Cong, Haowei Yang, Qiuping Jiang, Wei Gao, Haisheng Li, Cong Wang, Yao Zhao, and Sam Kwong, BCS-Net: Boundary, context and semantic for automatic COVID-19 lung infection segmentation from CT images, IEEE Transactions on Instrumentation and Measurement, 2022.

# Results of  BCS-NET:
* Results:
  - We provide the resutls of our BCS-NET on COVID-19 CT segmentation dataset, and COVID-19 CT lung and infection segmentation dataset. 
```
Baidu Cloud: https://pan.baidu.com/s/1NZx0RE-cliQ0zJ6bYDqDow   Password: u1v1
```


# Pytorch Code of  BCS-NET:
* Pytorch implementation of  BCS-NET
* Pretrained model:
  - We provide our testing code. If you test our model, please download the pretrained model, unzip it, and put the checkpoint `model_BCS.pth` to `checkpoints/save_weights/` folder 
  and put the pretrained backbone ` res2net50_v1b_26w_4s-3cf99910.pth` to `checkpoints` folder.
  - Pretrained model download:
```
Baidu Cloud: https://pan.baidu.com/s/1NZx0RE-cliQ0zJ6bYDqDow   Password: u1v1
```

## Requirements

* Python 3.7
* Pytorch 1.6.0
* torchvision

## Data Preprocessing
* Please download the test data, and put the data to `Dataset/` folder.
* COVID-19 CT segmentation dataset: https://medicalsegmentation.com/COVID19/,  COVID-19 CT lung and infection segmentation dataset: https://zenodo.org/record/3757476
* NII file processing tool and edge generation tool in `Dataset/` folder. 
* test datasets:
```
Baidu Cloud: https://pan.baidu.com/s/1NZx0RE-cliQ0zJ6bYDqDow   Password: u1v1
```

## Test
```
python test.py
```

* You can find the results in the `'Results/'` folder.

# If you use our BCS-NET, please cite our paper:

    @article{crm/tim22/covid,
       author    = {Runmin Cong and Haowei Yang and  Qiuping Jiang and Wei Gao and Hai{-}Sheng Li and Cong Wang and Yao Zhao andSam Kwong},
       title     = {{BCS-Net}: Boundary, Context, and Semantic for Automatic {COVID-19} Lung Infection Segmentation From {CT} Images},
       journal   = {{IEEE} Trans. Instrum. Meas.},
       volume    = {71},
       pages     = {1--11},
       year      = {2022}
      }

# Contact Us:
If you have any questions, please contact Runmin Cong (rmcong@bjtu.edu.cn) or Haowei Yang (hwyang@bjtu.edu.cn).
