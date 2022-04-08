# data_split

## This folder is the directory used to store training samples
### The steps to use are as follows:
* (1) Create a new folder "--filename--your own file name" under the data_set folder
* (2) Click on the link to download the flower classification dataset [http://download.tensorflow.org/example_images/flower_photos.tgz](http://download.tensorflow.org/example_images/flower_photos.tgz)
* (3) Unzip the dataset to the --filename-- folder
* (4) Execute the "split_data.py" script to automatically divide the dataset into training set train and validation set val

```
├── --filename--
        ├── photos (decompressed dataset folder)
        ├── train (generated training set)
        └── val (generated validation set)
```

# 数据打包方法

## 该文件夹是用来存放训练样本的目录
### 使用步骤如下：
* （1）在data_set文件夹下创建新文件夹"--filename--你自己的的文件名"
* （2）点击链接下载花分类数据集 [http://download.tensorflow.org/example_images/flower_photos.tgz](http://download.tensorflow.org/example_images/flower_photos.tgz)
* （3）解压数据集到--filename--文件夹下
* （4）执行"split_data.py"脚本自动将数据集划分成训练集train和验证集val    

```
├── --filename--  
       ├── photos（解压的数据集文件夹）  
       ├── train（生成的训练集）  
       └── val（生成的验证集） 
```
