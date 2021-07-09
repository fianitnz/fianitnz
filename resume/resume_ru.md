## Никита Александрович Зенкин<img src="photo.jpg" width="245rem" align="left"/><a href="Никита Александрович Зенкин.pdf">.pdf</a>

#### Специализация
Тестирование ПО (Software QA Engineer)

#### Контакты
Email: fianitnz@gmail.com  WgatsApp\Telegram: +7 926 292-39-26 Skype: fianitnz

Репозиторий Git: [https://github.com/fianitnz](https://github.com/fianitnz)

### Навыки
Linux, Windows, Bash, Python, Java(Basic), Git, Issue tracker, Wireshark, Selenium, WebDriver, KVM, QEMU, Docker(Basic), CSV, JSON, API, REST, SOAP, SoapUI(Basic), HTML, CSS, XML, SQL(SoloLearn, sql-ex.ru=6), ORM, English(A1 Elementary)

### Опыт

Создал учебный проект автоматизации тестирования веб панели администратора сервера [Ajenti2](https://github.com/ajenti/ajenti)
<br>Доступен по адресу: [https://github.com/fianitnz/ajenti2-automation-of-web-interface-testing](https://github.com/fianitnz/ajenti2-automation-of-web-interface-testing)
<br>Содержит ***Тест план, Тест кейсы, Найденные проблемы***

#### **В проекте использовал такие инструменты как:**

>**основные:**
>- `selenium.webdriver`, `pytest`, `requests`, `pixelmatch-py`, `multiprocessing`
>
>**вспомогательные:**
>- `PIL.Image`, `pathlib.Path`, `io.BytesIO`, `pytest_check.check`

##### Текстовое описание проекта:
Разделил тестируемую страницу на логические секции, заголовок, контент, меню. В которые включил элементы, такие как поля, кнопки, ссылки. Привязав их через локаторы скомпонованные так же в логические секции страницы.

В качестве локаторов использовал в основном XPath. Имена тегов. И CSS локаторы в JavaScript обертках.

Из библиотеки Selenium использовал By, Keys, expected_conditions, WebDriverWait, Color, ActionChains, разные exceptions.

В связи с отсутствием доступа к псевдоклассам CSS при помощи Selenum, использовал JavaScript.

Написал несколько своих Expected conditions для обработки цвета, трансформации, и выполнения JS в браузере что бы получить значения атрибута псевдокласса CSS.

Использовал pixelmatch-py для сравнения изображений с эталоном при скриншот тестах.
В помощь к скриншот тестам через JS отключаю анимацию путем добавления CSS правил.

Реализовал тестирование логина через API REST при помощи библиотеки requests, в процессе познакомился в работе с ПО SoapUI и протоколом SOAP, попробовал Postman.

#### Обо мне
