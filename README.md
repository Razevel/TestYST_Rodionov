---

# Тестовое задание - Магазин

[Перейти на сайт](http://www.testyst.somee.com/ "TestYST.com")

---

## Контакты

email: <krowstel@gmail.com>

---

Версия .NET - 4.5

---
## Задание
#### Использовать следующие технологии :
+ Entity Framework (Code First) + LINQ для запросов
+ Identity
+ ASP.NET Core или ASP.NET MVC 5
#### Задача:
Есть 4 сущности:
<ol>
  <li> Товар 
    <ul>
      <li> Код </li>
      <li> Наименование </li>
      <li> Артикул </li>
      <li> Цена </li>
      <li> Цена партнера </li>
    </ul>
  </li>
  <li> Склад 
    <ul>
      <li> Код </li>
      <li> Наименование </li>
    </ul>
  </li>
  <li> Остаток на складе
    <ul>
      <li> Склад </li>
      <li> Остаток </li>
    </ul>
  </li>
  <li> Корзина
    <ul>
      <li> Идентификатор сессии </li>
      <li> Товар </li>
      <li> Количество </li>
    </ul>  
  </li>
</ol>

#### Требования:
1. Верстку реализовать на Bootstrap3 или 4.
2. На сайте использовать авторегистрацию пользователей (хранить данные
через Identity).
3. Показать список с пагинацией таких товаров, которые есть хотя бы на одном
складе. В списке отображать артикул, цену , остаток, наименование
4. В списке реализовать фильтр товаров по артикулу и наименованию
5. Для зарегистрированных пользователей через Idenity хранить признак
«Партнер» (булево)
6. Если признак у пользователя включен, то в списке товаров показывать
цену партнера
7. Реализовать добавление в корзину товара (привязать к идентификатору
сессии клиента)
8. Реализовать просмотр корзины в виде списка с возможностью удаления
товара из корзины

---
