# **ios-focusstart2017**
Focus Start 2017

## **Тестовое задание Focus Start iOS 2017**

Дан файл messages.json, который содержит массив объектов, представляющих собой сообщения в вымышленной социальной сети. 
Объекты могут быть нескольких типов:
- text
- image
- social

Требуется отобразить список сообщений в виде таблицы, отсортированных в хронологическом порядке, начиная с самых новых.

Запись в таблице должна содержать:
- Дату сообщения
- Заголовок сообщения
- В зависимости от типа, содержимое сообщения:
- Для типа text – текст сообщения
- Для типа image – изображение, загруженное по ссылке
- Для типа social – иконку соцсети (возможные варианты: twitter, facebook, vkontakte)
При нажатии на строку таблицы с типом сообщения image требуется изображение в полный экран.

При нажатии на строку таблицы с типом social требуется открыть ссылку в браузере.
Приложение не должно блокировать интерфейс пользователя на время выполнения трудоемких операций.

## **Технические требования**
Приложение должно быть написано на Objective-C либо Swift.
Приложение должно выполняться на iOS версии 9 и выше, поддержка iPad будет плюсом. Не допускается использование сторонних библиотек.
