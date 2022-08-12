# E-POS Online App
Version: 1.0.2  
Author: [E-POS Systems LTD.](https://epos.uz)  

## Changelog
### v1.0.2
#### Исправлено:
- Некорректное масштабирование чеков при печати (`58мм` и `80мм`).
- Невозможность сохранить параметры печати без заполнения текстовых полей в настройках.
- Поле "Маркировка" больше не выводится в чеке пустым.
- Текст уведомления после окончания обновления приложения.

### v1.0.1
#### Добавлено:
- Логирование запросов и ошибок в файле test.log (C:/Users/%USERNAME%/.EPOS/test.log)  
- Анимация загрузки при ожидании ответа на запрос.  
- Более детальные сообщения об ошибках.

#### Изменено:
- Обновлена база ИКПУ на более актуальную (на 2022-08-06).
- `staffName` больше не является обязательным полем.
- `refundInfo` больше не является обязательным объектом.
- Изменено название базы данных (больше не нужно удалять базу при установке).

### v1.0.0
- Initial release
