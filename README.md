# IJCAI2018_SSDH
This is the code for our paper: "Semantic Structure-based Unsupervised Deep Hashing" IJCAI 2018.

Author: E. Yang, C. Deng, T. Liu, W. Liu, and D. Tao.

To run the code, you should download the dataset and specify the image path and labels in the corresponding txt file.
For example, for training dataset, all image path should be given in img_train.txt:

>\path\to\train_img1.png

>\path\to\train_img2.png 

>...
The corresponding labels should be indicated in label_train.txt:

>0 1 0 1 0 1

>0 1 0 1 1 0

>.......

After setting the running environment and dataset information, our method can be evaluated by:

```
python2 main.py
```

If your find the code usfull, you can cite our paper, and if you have any questions, please feel free to contact Erkun Yang (erkunyang@gmail.com)
