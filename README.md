# Бот-расписание занятий в «СТАНКИН» для ВКонтакте
Основная цель проекта заключается в упрощении взаимодействия с расписанием занятий в университете.

Изученные и интегрированные инструменты
* SQLite 3
* cURL
* Json (библиотека nlohmann)
* Библиотека для SQLite (SqliteModernCpp)
* VK API
* Ну и сам C++11
* Библиотека для Python: openpyxl

### Было сделано
* Поддержка работы с VK API (например, для отправки сообщений)
* Поддержка работы с Bots Long Poll API (например, для принятия сообщений)
* База данных пользователей (примитивная, на .json)
* База данных расписаний на (примитивная, на .json)
* Установка готовых расписаний занятий
* Отправка уведомлений о предстоящем занятии/перерыве
* Внедрить СУБД (SQLite)
* Возможность узнать информацию о ближаших занятиях (09.11)
* Скрипт для экспорта расписания (.pdf) в БД (SQLite)
* Возможность «Найти преподавателя»
