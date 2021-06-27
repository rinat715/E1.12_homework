# E1.12 Домашнее задание

## Общий функционал
Приложение «загадывает» одно из следующих слов: skillfactory, testing, blackbox, pytest, unittest, coverage. И показывает количество букв в нём.

Игрок пытается угадать слово буква за буквой. Если человек называет букву, которой нет в слове, у него появляется штрафное очко. А если букву, которая есть в слове, то она открывается (и все её вхождения).

Например, было загадано слово testing. На первом ходу игроку показывают: _ _ _ _ _ _ _.

Допустим, пользователь предположил, что в этом слове есть буква a. Изображение слова остаётся такое же: _ _ _ _ _ _ _, но у пользователя появляется штрафное очко.

Допустим, на следующем ходу пользователь предлагает букву t. Тогда изображение слова меняется, игроку открывается буква t: T _ _ T _ _ _.

Если набирается 4 штрафных очка и слово не отгадано, игра проиграна.

Приложение должно управляться через командную строку.

## Основные технологии
* Python
* fire

## Установка 
```
pip install gallows_game-0.1.0.tar.gz
```

## Использование
```
gallows_game
```
[![Travis][build-badge]][build]

[build-badge]: https://img.shields.io/travis/ azat715 / E1.12_homework /master.png?style=flat-square

[build]: https://travis-ci.org/ azat715 / E1.12_homework