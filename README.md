# DLE_FXML
FXML DLE киносайт для ForkPlayer с балансеров и прямых ссылок. 

Настройка списка дополнительных полей для ваших плееров находится в файле engine/modules/fxml.php

Обновление от 08.11.2019
 - По умолчанию в модуле обрабатываются доп.поля tortuga и directlink (ссылки на плеер и прямые ссылки на видео)
 - автоматическая вставка изображений из short_story если доп. поле poster пустое или отсутствует
 - переход на следующую страницу поиска
 - кнопки меню Добавить портал в Глоб. поиск и закладки
 
Установка на DLE версии 13 и выше

Скачайте архив https://github.com/alexkdpu/DLE_FXML/blob/master/DLE_FXML-plugin.zip.
Откройте на вашем сайте в админпанели Утилиты / Управление плагинами и загрузите этот ZIP архив.

Для версий ниже необходимо вручную выполнить замены кода с файла fxml-dle-dlja-kinosajtov.xml и загрузить шаблон и модуль fxml


В ForkPlayer сайт открывать по той же ссылке что и ваш сайт, информация по установке ForkPlayer на смарт тв http://wiki.forkplayer.tv/wiki/Установить_ForkPlayer

ИНФОРМАЦИЯ ПО ЗАПИСЯМ вашей DLE
Необходимо создать дополнительные поля 
tortuga и directlink, для каждой вашей записи добавлять в эти поля ссылки на плеера балансеров и прямых ссылок на видео
Для иконки используется дополнительное поле poster

Реклама VAST2.0
В шаблоне templates/fxml/main.tpl по умолчанию установлена рекламная ссылка, ее можно изменить на свою (описание формата VAST https://specs.adfox.ru/page/221 ) или удалить
