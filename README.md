# CV2023_lab5 
#  Классификация

Команда:
* Никурашин Алексей
* Горбунова Екатерина 
* Горцуева Александра
* Чернышев Артем
* Терешин Данил
  
## Датасет
[Датасет](https://drive.google.com/file/d/1PwK2oz_NbJU0NsT42Wr_Yv6rcZcJa5Uc/view?usp=sharing) представляет из себя набор подводных аннотированных снимков(исходные изображения - dataset/images, аннотации - dataset/masks), всего 1525 изображений и 8 категорий объектов:  
![image](https://github.com/compfee/CV_2023_lab5/assets/55783463/32eed333-d053-4378-a459-2ee1882ddd7a)

## Описание задачи
Язык программирования - Python  
Разрешено использовать любую библиотеку для машинного обучения (PyTorch, TensorFlow, Keras и др.)  
Необходимо создать модель для сегментации изображений с определением класса выделенной области  
Измерить время работы модели на тестовом датасете и посчитать необходимые метрики  
## Ограничения
Запрещено использование готовых архитектур "из коробки" одной строчкой. В коде должны быть прописаны слои вашей модели
## Метрики
Метрики оценки качества сегментации:  
IoU:  
![image](https://github.com/compfee/CV_2023_lab5/assets/55783463/b78b3cdc-4b02-48dd-a474-c8ec7845f5d2)  
​Per-class IoU:  
IoU по каждому из 8 классов  
Per-pixel accuracy:  
![image](https://github.com/compfee/CV_2023_lab5/assets/55783463/4093f270-9ca5-4fc8-a7de-10c93e1c44dd)  
 

| Ссылка на решение | Результат %| 
|-------------------|-----------|
| [ноутбук](https://colab.research.google.com/drive/1GEqhrpSFc_z5BXQPv6ZgoVvpgUcPiNKL#scrollTo=YA1mnnp7ipX_) | 0,84 |
| [ноутбук](https://colab.research.google.com/drive/1BMN4zeCy2Hbp66rpzKiw8-UZUfQiMv0f?usp=sharing) | 0,93 |
