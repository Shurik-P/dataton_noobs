# SkillFactory dataton (решение от команды Noobs)
## Цель задачи: Определить породу собаки по фотографии.

### Для достижения целей использовали:
Датасет [120 Dog Breeds - classification](https://www.kaggle.com/datasets/amandam1/120-dog-breeds-breed-classification)

#### Предобученные модели из пакета *torchvision.models*:
* [MobileNet V3](https://pytorch.org/vision/main/models/mobilenetv3.html)
* [EfficientNetV2](https://pytorch.org/vision/main/models/efficientnetv2.html)
* [ResNet50](https://pytorch.org/vision/main/models/resnet.html)
* [VisionTransformer](https://pytorch.org/vision/main/models/vision_transformer.html)

#### Изменяемые параметры:
* Learning rate
* Scheduller
* N epochs
* N Frosen layers

#### Оптимизатор
Adam

**С результатом проведенной работы можно ознакомиться в ноутбуке, который находится в данном репозитории.**
[dog_shazam.ipynb](https://github.com/Shurik-P/dataton_noobs/blob/main/dog_shazam.ipynb)
