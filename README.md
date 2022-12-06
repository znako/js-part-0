# Домашнее задание по JS, первая лекция

## Кому и когда сдавать

Иван Петропольский, фронтенд-разработчик в команде Монетизации.

Домашки принимаются до 20-го декабря включительно в Mattermost в личке.

Можно пользоваться чем угодно, главное не списывать у коллег.


## Задание

1) Сделайте форк репозитория https://github.com/ipetropolsky/js-part-0
2) Склонируйте его к себе на машину, создайте ветку от master.
3) Поправьте функцию `test()` так, чтобы она работала с массивами примитивов.
4) Запускайте код в консоли браузера (это неудобно) или любым другим способом.
5) Добавьте отсутствующий код так, чтобы проходили все тесты.
6) Сделайте пулл-реквест *в своём репозитории*, поставьте меня ревьювером и скиньте линк на него.

### Опционально

* Поставьте Node.js: https://nodejs.org/en/download/
* Запускайте код в терминале: `node index.js` (это удобно).
* Добавьте недостающих тестов на своё усмотрение (отдельным коммитом).

## Что должно получиться

```
# getType

  [OK] Boolean
  
  [OK] Number
  
  [OK] String
  
  [OK] Array
  
  [OK] Object
  
  [OK] Function
  
  [OK] Undefined
  
  [OK] Null
  
# allItemsHaveTheSameType

  [OK] Values with the same type
  
  [OK] Values with various types
  
  [OK] Values like a number
  
  [OK] Values like an object
  
# getTypesOfItems VS getRealTypesOfItems

  [OK] Check basic types
  
  [OK] Check real types
  
# everyItemHasAUniqueRealType

  [OK] All value types in the array are unique
  
  [OK] Two values have the same type
  
  [OK] There are no repeated types in knownTypes
  
# countRealTypes

  [OK] Count unique types of array items
  
  [OK] Counted unique types are sorted
```
