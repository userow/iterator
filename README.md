# incrementor

Test task - Dependency Injection, Unit Tests, UI Tests, MVP (Model-View-Presenter).

https://docs.google.com/document/d/1c361UNbQaVI7ZyPSXpaEW-1x0v_eqHEl-_TXxV0AkFg/edit

## Задача для Android/iOS разработчика

Нужно написать Android/iOS-приложение, с двумя экранами. Первый экран будет белый, пустой (кроме меню для перехода на второй). На нем при открытии приложения должна показываться большое черное число 0 (ноль). При каждом тапе пальцем на это число оно увеличивается на один. Число должно переживать перезапуск приложения: если я докликал до 10, то при следующем запуске должно быть 10.

Второй экран -- экран настроек. Настройки нужно сделать следующие:
- Размер инкремента (чтобы увеличивалось не на один, а на два, три или тысячу). Размер инкремента должен быть положительным.
- Размер верхней границы. Если я поставлю ее 1000, то при докликивании до 1000 число сбрасывается на ноль само.
- Кнопка сброса числа до нуля.

В меню и на втором экране должен быть качественный UI по material design (Android) или Apple Guidelines (iOS).

Т.е. приложение очень простое. А теперь сложность: оно должно быть сделано очень хорошо. Т.е. максимально качественно, как только можно. Код должен быть идеальным, все должно быть покрыто unit и ui тестами (это самое обязательное требование), разбито на сервисы, модели, компоненты, окна, т.е. по всем правилам хорошей архитектуры. Все классы и методы должны быть полностью покрыты понятной (т.е. полезной, а не для отписки) javadoc (для Java) или аналогом для Swift документацией. В общем, нужно сделать такой код, который каждый разработчик мечтает получить на поддержку -- идеальный (насколько кандидат способен).

### Обратить внимание на:
- Форматирование кода.
- Нэйминг (названия всех сущностей).
- Покрытие тестами (логика -- unit, интеграция с системой -- functional, экраны -- ui).
- Наличие документации.
- Разделение логики и представления.
- Модульность (в идеале -- DI Dagger на Android, аналог для iOS).
- DRY (включая использование качественных Open Source библиотек).
- Общая читабельность и простота кода.
- Отсутствие переусложнения. Хороший код != сложная, навороченная архитектура.
