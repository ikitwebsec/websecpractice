# WebSecPractice

Данный репозиторий предназначен для выполнения заданий по WebCTF.

Для прохождения заданий нужно скачать лабораторный комплекс.

Это можно сделать двумя способами: Виртуальная машина/Контейнер Docker. 


## Установка

#### Работа с VM 

##### Скачайте VMware

https://www.vmware.com/products/workstation-player.html

##### Скачайте виртуальную машину

https://drive.google.com/drive/folders/1PozDhOAxXuxABhQbbbCyC6BctBsXo2ZO
(725mb)

Для добавления VM запустите файл WebSecVM.ovf

##### Запустите VM

Требуется зайти в систему:
``` script
root
Пароль: websecikit_091
```

##### Узнайте адрес виртуальной машины
```
ifconfig
```

![Изображение](https://github.com/ikitwebsec/websecpractice/blob/master/images/vm1.png)


##### Запустите сервис
```
service labboot
```

##### Вход на сайт

Для входа на сайт нужно вводить в адресную строку:
```
<Адрес>:8080
```

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

После завершения работы контейнер можно закрыть через Docker.

##### Использование Docker

Скачанные репозитории можно отслеживать в разделе Images

![Изображение](https://github.com/ikitwebsec/websecpractice/blob/master/images/docker1.png)

В результате запуска контейнера, его можно увидеть в соответствующем разделе программы Docker. 

![Изображение](https://github.com/ikitwebsec/websecpractice/blob/master/images/docker2.png)

##### Docker может потреблять ресурсы даже без запущенных контейнеров, поэтому выключайте его по окончании работы.

## Работа с задачами

При полной настройке практикума, появляется доступ к веб-сайту.

Его можно открыть в браузере на основной системе. 

![Изображение](https://github.com/ikitwebsec/websecpractice/blob/master/images/task1.png)
