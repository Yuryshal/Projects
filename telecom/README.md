# Прогноз оттока клиентов оператора связи

Оператор связи хочет научиться прогнозировать отток клиентов.

## Данные

Команда оператора предоставила нам персональные данные о некоторых клиентах, информацию об их тарифах и договорах:
- дата начала и конца договора
- тип и способ оплаты
- ежемесячные и суммарные траты на услуги
- пол, семейное положение и наличие детей
- пенсионный статус
- тип интернет подключениия и перечень доп.услуг

## Задача

Необходимо спрогнозировать, уйдёт клиент от оператора в ближайшее время или нет, т.е. построить модель для задачи классификации.

## Вывод

Представлены статистика поведения и портрет нелояльного клиента на основе анализа данных. Определены важность признаков и оптимальная модель для прогноза оттока клиентов. Обнаружена утечка целевого признака.

## Используемые библиотеки
*python pandas seaborn matplotlib phik imblearn sklearn lightgbm catboost*
