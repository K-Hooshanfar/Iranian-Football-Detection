# Soccer Detection

# Train YOLOv5
In this project, we try the YOLOV5 model on our custom data set. To train the model, we utilize the GPU in Colab. The properties of this GPU are shown below:
```
Tue Aug 16 06:47:37 2022       
+-----------------------------------------------------------------------------+
| NVIDIA-SMI 460.32.03    Driver Version: 460.32.03    CUDA Version: 11.2     |
|-------------------------------+----------------------+----------------------+
| GPU  Name        Persistence-M| Bus-Id        Disp.A | Volatile Uncorr. ECC |
| Fan  Temp  Perf  Pwr:Usage/Cap|         Memory-Usage | GPU-Util  Compute M. |
|                               |                      |               MIG M. |
|===============================+======================+======================|
|   0  Tesla T4            Off  | 00000000:00:04.0 Off |                    0 |
| N/A   38C    P8     9W /  70W |      0MiB / 15109MiB |      0%      Default |
|                               |                      |                  N/A |
+-------------------------------+----------------------+----------------------+
                                                                               
+-----------------------------------------------------------------------------+
| Processes:                                                                  |
|  GPU   GI   CI        PID   Type   Process name                  GPU Memory |
|        ID   ID                                                   Usage      |
|=============================================================================|
|  No running processes found                                                 |
+-----------------------------------------------------------------------------+
```
# Data set preparation
Our data set contains 100 images in 2 Player, and Ball classes. We use this data set to customize the YOLO algorithm weights based on some related categories of images with our dataset.

![Alt text](Images/Data-set.png)

* 80% of images were placed in the training set, and 20% were separated as validation and test sets.

# How to contribute to Soccer-Detection
We use the Fork and Pull Request model for contribution. For more information read the [CONTRIBUTE.md](https://github.com/klammhsa/Soccer-Detection/blob/main/CONTRIBUTE.md).

## Contributors
- [Kiana Hooshanfar](https://www.github.com/K-Hooshanfar)
- [Mahsa Kalam](https://www.github.com/klammhsa)
