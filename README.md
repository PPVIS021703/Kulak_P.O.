# Лабораторная работа №3

## Тема: Объектная модель в разработке программной системы. Исключения.
## Цель: Получить навыки проведения объектно-ориентированного анализа предметной области.

  Выбрать вариант задания, провести объектно-ориентированный анализ предметной области,<br/>
выделить классы и связи между ними. На основании объ ектной модели реализовать программу<br/>
на С++ в соответствии с требованиями варианта задания.<br/>
Общие требования к выполнению лабораторной работы:
- использование наследования;
- использование полиморфизма;
- использование обработки исключений при возникновении ошибочных ситуаций.<br/>
При выполнении этой лабораторной работы студентам не стоит бояться выделять классы,<br/>
даже если они небольшие (например, состоят из одного поля), потому что в этой работе изуча-<br/>
ется объектно-ориентированный подход.

### Вариант(1) - Модель банкомата

При выборе этого варианта студенту необходимо изучить работу банкомата «Беларусь-<br/>
банк». После этого необходимо выявить взаимодействующие объекты в рамках сессии работы<br/>
банкомата. На основе выявленных объектов сформировать объектную модель, которая описы-<br/>
вает работу банкомата. В данном варианте необходимо обратить особое внимание на классы<br/>
для представления экранов банкомата. Именно они будет формировать основную иерархию<br/>
классов данного варианта.<br/>
Разработанная объектная модель должна соответствовать следующим требованиям:
- включать классы для представления основных взаимодействующих сущностей в процессе<br/>
работы банкомата (например, карточка, пользователь, сессия, банк, кард-счет и др.);
- включать иерархию классов для представления экранов банкомата.
Реализованная на основе объектной модели программа должна:
- получать в качестве командных аргументов файл с описанием карточки клиента и файл<br/>
с описанием базы данных банка;
- моделировать работу банкомата в консольном режиме.

### Поправки:
- Сделать логгирование при помощи паттерна проектирования синглтон.<br/>
- ✅ Отрефакторить код когда происходит перевод с карты на карту.
