Сервис облочного хранилища, в котором авторизировшись можно хранить файлы разных типов.

**Ограничения:**
* Размер файла до 20 мб;
* Нельзя заливать .php;
* Объем хранилища на одного юзера 100мб.

### Доступные URL:
* /api/user/{id} - предоставляет информацию о конкретном юзере;
* /api/users - предоставляет информацию о всех юзерах;
* /folder - каталог всех папок и файлов;
* /folder/create - создание новой папки;
* /folder/{id}/show - каталок конкретной папки;
* /file/upload - загрузка файла в хранилище;
* /file/{id}/download - скачинивае файла;
* /file/{id}/delete - удаление файла;
* /file/{id}/rename - ренейм файла;
* [dev] /upload - позволяет заливать файлы в обход авторизации.

Данные для авторизации: d@d:d (на демке, которая не встала :( )

## Инструкция по запуску:

