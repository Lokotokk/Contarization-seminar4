# Урок 4. Dockerfile и слои
### Задание: необходимо создать Dockerfile, основанный на любом образе (вы в праве выбрать самостоятельно).  
### В него необходимо поместить приложение, написанное на любом известном вам языке программирования (Python, Java, C, С#, C++).  
### При запуске контейнера должно запускаться самостоятельно написанное приложение.  

Создаем папку в домашней директории и входим в неё:  
![](https://github.com/Lokotokk/Contarization-seminar4/blob/main/1.png)  

Cоздаём Dockerfile и открываем его в редакторе nano:  
![](https://github.com/Lokotokk/Contarization-seminar4/blob/main/2.png)  

Cоздаем базовый слой, использую инструкцию FROM. Используем образ ubuntu последней версии.  
Устанавливаем новые программные пакеты, обновляя существующие.  
Копируем файл с кодом на python в контейнер в папку hmsem4  
Делаем папку hmsem4 рабочей директорией контейнера.  
С помощью инструкции CMD предоставляем Docker команду, которую необходимо выполнить непосредственно при запуске контейнера.  
![](https://github.com/Lokotokk/Contarization-seminar4/blob/main/3.png)  

Запускаем файл со скриптом на python с помощью редактора nano.  
![](https://github.com/Lokotokk/Contarization-seminar4/blob/main/4.png)
![](https://github.com/Lokotokk/Contarization-seminar4/blob/main/5.png)  

Компилируем комнтейнер.  
![](https://github.com/Lokotokk/Contarization-seminar4/blob/main/6.png)  

Запускаем контейнер.  
![](https://github.com/Lokotokk/Contarization-seminar4/blob/main/7.png)  


