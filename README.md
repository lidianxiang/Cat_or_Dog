# Cat_or_Dog

## 利用AI模型（PNASNET模型）识别图像是桌子、猫、狗还是其它

### 使用TensorFlow 1.X版本的TF-slim接口,在ImgNet数据集上训练好的PNASNet模型来识别物体。

* models模型独立于TensorFlow项目，在使用时需要额外下载。下载地址请[点击这里](https://github.com/tensorflow/models)
* 下载PNASNet模型，下载地址请[点击这里](https://github.com/tensorflow/models/tree/master/research/slim),
* 预训练模型PNASNet模型是在ImagNet数据集上训练好的，在利用模型进行分类时，还需要配合与其对应的标签文件一起使用。在Slim文件夹中，将获得标签文件的封装到了代码里面，在使用时直接调用即可。

### 将预训练模型文件、Slim文件、代码文件、中文标签都准备好了，其目录文件结构如图所示。
