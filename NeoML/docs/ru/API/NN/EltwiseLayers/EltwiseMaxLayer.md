# Класс CEltwiseMaxLayer

<!-- TOC -->

- [Класс CEltwiseMaxLayer](#класс-celtwisemaxlayer)
    - [Настройки](#настройки)
    - [Обучаемые параметры](#обучаемые-параметры)
    - [Входы](#входы)
    - [Выходы](#выходы)

<!-- /TOC -->

Класс реализует слой, считающий максимумы соответствующих элементов всех своих входов.

## Настройки

Слой не имеет настроек.

## Обучаемые параметры

Слой не имеет обучаемых параметров.

## Входы

Слой имеет не менее двух входов. Все размерности у блобов разных входов должны совпадать.

## Выходы

Единственный выход содержит блоб тех же размеров, что и блобы входов. Каждый элемент блоба результата содержит максимум среди соответствующих элементов блобов всех входов.