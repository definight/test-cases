## Here's examples of my bug reports

 <details>
  <summary>1</summary>

| Идентификатор      |   case-001  |
| ----------- | ----------- |
| Статус   |   Успешно пройден      |
| Приоритет   |     Низкий    |
| Дата создания   |    12.12.2022     |
| Дата выполнения   |    12.12.2022     | 
| Название   |    Заказ товара зарегистрированным пользователем     |
| Предусловия   |   Открыта страница http://qa.skillbox.ru/module09/practice4/Catalog/index.html      |
| Шаги воспроизведения   |    Ожидаемый результат     |
|1. Нажать на карточку товара   |   Открывается страница с товаром      |
|2. Нажать на кнопку "Купить"  |     Появляется веб-форма для ввода данных покупателя    |
|3. Ввести номер телефона   |   Кнопка "Позвоните мне" становится активной   |
| Постусловия   |    -    |

</details>

<details>
  <summary>2</summary>

| Идентификатор      |    case-002     |
| ----------- | ----------- |
| Статус   |     Запланирован    |
| Приоритет   |     Низкий    |
| Дата создания   |    12.12.2022     |
| Дата выполнения   |    12.12.2022     | 
| Название   |     Отправка отзыва на товар незарегистрированным пользователем    |
| Предусловия   |   1. Открыта страница http://qa.skillbox.ru/module09/practice4/Catalog/index.html <p> 2. Пользователь зарегистрирован      |
| Шаги воспроизведения   |         |
| 1. Нажать на карточку товара   |     Открывается страница с товаром    |
| 2. Нажать на кнопку "Оставить отзыв о товаре"  |     Открывается веб-форма для ввода данных о товаре    |
| 3. Выставить любую оценку   |   Выставленная оценка отображается в поле   |
| 4. Ввести в поле "Имя" любую последовательность символов   |  Введённая последовательность отражается в поле    |
| 5. Выбрать любую дату покупки до текущей даты   |  Выбранная дата покупки отражается в поле    |
| 6. Выбрать любюй период использования   |    Период использования отображается в поле  |
| 7. Ввести в поле для отзыва любую последовательность символов   |   Введённая последовательность отображается в поле   |
| 8. Нажать на кнопку "Отправить"   |    Отображается подтверждение отправки и благодарность за отзыв  |
| Постусловия   |     -    |

</details>


<details>
  <summary>3</summary>

| Идентификатор      |  case-003   |
| ----------- | ----------- |
| Статус   |     Провален    |
| Приоритет   |     Низкий    |
| Дата создания   |     12.12.2022    |
| Дата выполнения   |     12.12.2022    | 
| Название   |    Отправка отзыва на сайт незарегистрированным пользователем    |
| Предусловия   |     Открыта страница http://qa.skillbox.ru/module09/practice4/Kontakty/index.html    |
| Шаги воспроизведения   |         |
|1. Ввести в поле "Имя" любую последовательность символов   |      Введённая последовательность отражается в поле   |
| 2.Ввести в поле "e-mail" валидный адрес почтового ящика  |    Введённый электронный ящик отражается в поле     |
| 3. Ввести в поле для отзыва любую последовательность символов   |    Введённая последовательность отображается в поле  |
| 4. Нажать на кнопку "Отправить"   |     Отображается подтверждение отправки и благодарность за отзыв    |
| Постусловия   |    -     |

</details>

<details>
  <summary>4</summary>

| Идентификатор      |   case-004  |
| ----------- | ----------- |
| Статус   |     Заблокирован    |
| Приоритет   |     Высокий    |
| Дата создания   |      12.12.2022   |
| Дата выполнения   |     12.12.2022    | 
| Название   |    Регистрация нового пользователя     |
| Предусловия   |      Открыта страница https://lm.skillbox.cc/qa_tester/module05/homework1/   |
| Шаги воспроизведения   |    Ожидаемый результат     |
|1. Заполнить поля корректными данными   |    В полях отображаются введённые данные     |
| 2. Согласиться с обработкой персональных данных  |    Появляется отметка в чекбоксе "Согласен на обработку персональных данных"     |
| 3. Нажать "Зарегистрироваться"   |   Отображается страница с подтверждением регистрации   |
| Постусловия   |      -   |

</details>

<details>
  <summary>5</summary>

| Идентификатор      |  case-005   |
| ----------- | ----------- |
| Статус   |     Отложен    |
| Приоритет   |     Высший    |
| Дата создания   |     12.12.2022    |
| Дата выполнения   |     12.12.2022    | 
| Название   |     Выполнение SQL-инъекции в форме авторизации    |
| Предусловия   |    Открыть страницу http://api-qa.skillbox.ru/practicesqli/auth.php     |
| Шаги воспроизведения   |     Ожидаемый результат    |
|1. Ввести в поле "Имя пользователя" tester'  |    Введенное имя пользователя отражается в поле     |
| 2. Ввести в поле "Пароль" 5s1rgNTs  |   В поле отображается соответствующее количеству символов пароля количество символов-масок      |
| 3. Нажать кнопку "Войти"   |    Отображается ошибка о некорректном заполненом поле "Имя пользователя"  |
| Постусловия   |   -      |

</details>

<details>
  <summary>6</summary>

| Идентификатор      |  case-006   |
| ----------- | ----------- |
| Статус   |     Успешно выполнен    |
| Приоритет   |     Средний    |
| Дата создания   |     12.12.2022    |
| Дата выполнения   |     12.12.2022    | 
| Название   |     Соответствие дизайна блока "Клиенты" в макете Figma и в приложении    |
| Предусловия   |    Открыть страницу http://qa.skillbox.ru/module19/     |
| Шаги воспроизведения   |     Ожидаемый результат    |
|1. Нажать на кнопку "Клиенты" в хэдере страницы  |    Страница прокручена до блока Клиенты     |
| 2. Открыть макет страницы https://www.figma.com/file/SexnFVxMVxh6h5vWispMKt/Online-cinema?node-id=0%3A1  |   Открыт макет страницы      |
| 3. Сравнить заголовки в макете и на странице   |    Дизайн макета и страницы идентичны  |
| Постусловия   |   -      |

</details>

<details>
  <summary>7</summary>

| Идентификатор      |  case-007   |
| ----------- | ----------- |
| Статус   |     Провален    |
| Приоритет   |    Высокий     |
| Дата создания   |     12.12.2022    |
| Дата выполнения   |     12.12.2022    | 
| Название   |     Работоспособность приложения при статусе сети "Поиск сети"    |
| Предусловия   |    Открыть Android Studio    |
| Шаги воспроизведения   |     Ожидаемый результат    |
|1. Изменить в Android Studio статус сети на "Поиск сети"  |    Статус сети изменен     |
| 2. Открыть приложение  |  Приложение открыто      |
| Постусловия   |   -      |

</details>

<details>
  <summary>8</summary>

| Идентификатор      |  case-008   |
| ----------- | ----------- |
| Статус   |     Отложен    |
| Приоритет   |     Низкий    |
| Дата создания   |     12.12.2022    |
| Дата выполнения   |     12.12.2022    | 
| Название   |     Отображение приложения на дисплеях с горизонтальным разрешением менее 920 пикселей    |
| Предусловия   |    Открыть страницу https://qa.skillbox.ru/module15/bignotes#/     |
| Шаги воспроизведения   |     Ожидаемый результат    |
|1. Открыть DevTools  |    DevTools открыт     |
| 2. Включить Toggle Device Toolbar  |   Toogle Device Toolbar включен      |
| 3. Выбрать горизонтальное разрешение 920 пикселей и менее   |    Страница отображается корректно, все элементы доступны для взаимодействия  |
| Постусловия   |   -      |

</details>

<details>
  <summary>9</summary>

| Идентификатор      |  case-009   |
| ----------- | ----------- |
| Статус   |     Высокий    |
| Приоритет   |     Провален    |
| Дата создания   |     12.12.2022    |
| Дата выполнения   |     12.12.2022    | 
| Название   |     Сохранение логина и пароля пользователя в cookie-файлах    |
| Предусловия   |    Открыть страницу http://qa.skillbox.ru/module16/autorization1/     |
| Шаги воспроизведения   |     Ожидаемый результат    |
|1. Заполнить все поля корректными данными  |    Данные отображены в полях     |
| 2. Нажать кнопку "Войти"  |   Пользователь авторизован      |
| 3. Открыть DevTools   |    DevTools открыт  |
| 4. Открыть вкладку Application   |    Вкладка Application открыт  |
| 5. Выбрать раздел Cookies | Вкладка Cookies открыта и не содержит логина и пароля пользователя
| Постусловия   |   -      |

</details>

<details>
  <summary>10</summary>

| Идентификатор      |  case-010   |
| ----------- | ----------- |
| Статус   |     Успешно выполнен    |
| Приоритет   |     Средний    |
| Дата создания   |     12.12.2022    |
| Дата выполнения   |     12.12.2022    | 
| Название   |     Удаление добавленного в корзину курса    |
| Предусловия   |    1. Открыть страницу http://qa.skillbox.ru/module16/maincatalog/  <p> 2. Пользователь авторизован    |
| Шаги воспроизведения   |     Ожидаемый результат    |
| 1. Добавить в корзину любой курс |    Курс добавлен в корзину     |
| 2. Нажать на имя пользователя  |   Открывается личный кабинет      |
| 3. Нажать на кнопку "Отложенные курсы"   |   Открывается список добавленных в корзину курсов  |
| 4.  Нажать на кнопку "Отказаться" в блоке курса| Курс удален из корзины |
| Постусловия   |   -      |

</details>
