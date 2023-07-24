# Виявляння об'єктів дроном - Yolov8 - Виявлення об'єктів

Модель detect_objects_dron для бібліотеки [yolov8](https://github.com/ultralytics/ultralytics)

> Read this in other language: [Український](README.md), [English](README.en.md), [Русский](README.ru.md)

## Вимоги
* python3
* yolov8

## Встановлення
```sh
pip3 install ultralytics
```

## Навчання
```sh
yolo task=detect \
mode=train \
model=yolov8s.pt \
data=data/data.yaml \
epochs=500 \
imgsz=640
```

## Виявлення
```sh
yolo task=detect \
mode=predict \
model=model/model.pt \
conf=0.25 \
source='example.mp4'
```

## Мітки
| Мітка               | 
| :-------------      |
| boat                |
| building            |
| buoy                |
| car                 |
| directionsign       |
| logger              |
| parking             |
| person              |
| roadcone            |
| ship                |
| solarpanel          |
| tractor             |
| truck               |
| wood                |

## Google Colab
```txt
yolov8.ipynb
```

# Подяка
* [Yolov8](https://github.com/ultralytics/ultralytics)
* [LabelStudio](https://github.com/HumanSignal/label-studio)
* [Artlist](https://artlist.io/stock-footage)

## Приклади
![example1](https://github.com/martinjack/detect_objects_dron/blob/master/examples/example1.jpeg?raw=true)

![example2](https://github.com/martinjack/detect_objects_dron/blob/master/examples/example2.png?raw=true)

![example3](https://github.com/martinjack/detect_objects_dron/blob/master/examples/example3.png?raw=true)

![example4](https://github.com/martinjack/detect_objects_dron/blob/master/examples/example4.png?raw=true)

![example5](https://github.com/martinjack/detect_objects_dron/blob/master/examples/example1.gif?raw=true)

![example6](https://github.com/martinjack/detect_objects_dron/blob/master/examples/example2.gif?raw=true)

![example7](https://github.com/martinjack/detect_objects_dron/blob/master/examples/example3.gif?raw=true)

![example8](https://github.com/martinjack/detect_objects_dron/blob/master/examples/example4.gif?raw=true)