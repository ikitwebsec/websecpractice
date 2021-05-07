# WebSecPractice

Данный репозиторий предназначен для выполнения заданий по WebCTF.

Для прохождения заданий нужно скачать лабораторный комплекс.

Это можно сделать двумя способами: Виртуальная машина/Контейнер Docker. 

---
#### Работа с VM 

Скачайте виртуальную машину по адресу: https://noaddress.yet
(500mb)

---
#### Работа с Docker

Контейнеры Docker стали поддерживать новую технологию WSL2,
позволяющую запускать их на большем количестве систем.

Однако Docker всё ещё имеет ограничения, просьба
ознакомиться с совместимостью с Вашей системой.

Если Docker не работает на Вашей системе, воспользуйтесь
Виртуальной машиной (пункт выше). 

##### Скачайте и установите Docker<br>
https://docs.docker.com/docker-for-windows/install/

##### Скачайте репозиторий

Репозиторий расположен по адресу: https://hub.docker.com/r/ikitwebsec/websecpractice

Скачайте его вводом в консоль следующей команды:
``` script
docker pull ikitwebsec/websecpractice:0.7-SNAPSHOT
```

Или запустите <code>pull.bat</code> из данного репозитория.

##### Запустите контейнер

Введите команду:
``` script
docker pull ikitwebsec/websecpractice:0.7-SNAPSHOT
```

Или запустите <code>run.bat</code>.

##### Использование Docker

Скачанные репозитории можно отслеживать в разделе Images
![Изображение](https://petcube.com/blog/content/images/2017/08/kitten-supplies-cover.jpg)
![Изображение](https://github.com/ikitwebsec/websecpractice/blob/main/docker1.png)

В результате запуска контейнера, его можно увидеть в соответствующем разделе программы Docker. 
![Изображение](https://github.com/ikitwebsec/websecpractice/blob/main/docker2.png)

##### Docker может потреблять ресурсы даже без запущенных контейнеров, поэтому выключайте его по окончании работы.