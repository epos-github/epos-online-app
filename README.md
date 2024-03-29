# E-POS Online App
Version: 1.0.2  
Author: [E-POS Systems LTD.](https://epos.uz)  
Documentation: [E-POS Online App Docs](https://docs.epos.uz/epos-online-app/)

## Changelog
### v1.0.4
#### Исправлено:
- `[Критично]` Ошибка с кодами состояния.

### `v1.0.3` [2022-08-16]
#### Изменено:
- Обновлена база ИКПУ на более актуальную [2022-08-15].
- Усовершенствован процесс логирования.
- Строгая типизация полей запроса изменена на динамическую.
#### Исправлено:
- Теперь все ответы приходят с кодом ответа `200`.
- Ошибка с `receivedCash` и `receivedCard`.

### `v1.0.2` [2022-08-12]
#### Исправлено:
- Некорректное масштабирование чеков при печати (`58мм` и `80мм`).
- Невозможность сохранить параметры печати без заполнения текстовых полей в настройках.
- Поле "Маркировка" больше не выводится в чеке пустым.
- Текст уведомления после окончания обновления приложения.

### `v1.0.1` [2022-08-09]
#### Добавлено:
- Логирование запросов и ошибок в файле test.log (C:/Users/%USERNAME%/.EPOS/test.log)  
- Анимация загрузки при ожидании ответа на запрос.  
- Более детальные сообщения об ошибках.

#### Изменено:
- Обновлена база ИКПУ на более актуальную (на 2022-08-06).
- `staffName` больше не является обязательным полем.
- `refundInfo` больше не является обязательным объектом.
- Изменено название базы данных (больше не нужно удалять базу при установке).

### `v1.0.0` [2022-08-06]
- Initial release
