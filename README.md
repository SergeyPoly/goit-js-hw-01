# HW1

**Завдання 1**

Оголоси функцію makeTransaction, яка очікує два параметри, значення яких будуть
задаватися під час її виклику:

- quantity — перший параметр, число, що містить кількість замовлених дроїдів,
- pricePerDroid — другий параметр, число, що містить вартість одного дроїда.

Доповни код функції так, щоб вона повертала рядок з повідомленням про покупку
ремонтних дроїдів: "You ordered _quantity_ droids worth _totalPrice_ credits!",
де:

- quantity — це кількість замовлених дроїдів
- totalPrice — це загальна вартість замовлення, тобто вартість усіх замовлених
  дроїдів

**Завдання 2**

Оголоси функцію getShippingMessage, яка очікує три параметри, значення яких
будуть задаватися під час її виклику:

- country — перший параметр, рядок, що містить країну доставки,
- price — другий параметр, число, що містить загальну вартість товару,
- deliveryFee — третій параметр, число, що містить вартість доставки товару.

Доповни код функції так, щоб вона повертала рядок з повідомленням про доставку
товару в країну користувача: "Shipping to _country_ will cost _totalPrice_
credits", де:

- country — це країни доставки,
- totalPrice — це загальна вартість замовлення, що включає вартість товару і
  його доставки.

**Завдання 3**

Оголоси функцію getElementWidth, яка очікує три параметри, значення яких будуть
задаватися під час її виклику:

- content — перший параметр, ширина контенту,
- padding — другий параметр, значення горизонтального падінгу для кожної зі
  сторін,
- border — третій параметр, значення товщини бордера для кожної зі сторін.

Значення всіх параметрів будуть рядками формату Npx де N — це довільне число,
ціле або дробове.

Доповни код функції так, щоб вона повертала число — загальну ширину елемента.
При розрахунку загальної ширини орієнтуйся на те, що значення box-sizing
дорівнює border-box.
