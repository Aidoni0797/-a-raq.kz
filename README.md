Мой успех - https://stepik.org/course/128626, молодец iDONi

https://playwright.dev/python/ - Link to the documentation. aiDoni учи...
____________________________________________________________________________________________________________________________________________________________________________________

Analysis of main.py
____________________________________________________________________________________________________________________________________________________________________________________
```python
from playwright.sync_api import Playwright, sync_playwright, expect -

эти строки кода пишем с целью  чтобы получить доступ ко всем функциям,
методам и классам playwright - это весело, хех. aiDoni учи моя дорогая!!!

____________________________________________________________________________________________________________________________________________________________________________________
Запускаем браузер, такое понятие есть оказывается запуск браузера.
Только кликая не будешь умным.
Смотри какая ты молодец знаешь запуск браузера. Далбаеб осының бәрін баяғыдан оқитын адамсың ғой.
Как можно бір адамға знать все. Менің миым жетпейді. Нервыма тиесін барғой.

browser = playwright.chromium.launch(headless=False)

____________________________________________________________________________________________________________________________________________________________________________________
Последующие строки кода отвечают за создание в нем контекста

context = browser.new_context()

page = context.new_page()
______________________________________________________________________________________________________________________________________________________________________________________
Метод page.goto() необходим, чтобы открыть веб-сайт.


click()- эмулирует клик левой кнопкой мышки по веб-элементу


fill() - этот метод вводит значения, переданные ему в качестве аргумента в веб-элемент. В нашем случае это текст  - "Создать первый сценарий playwright"


press("Enter") - эмулирует нажатие клавиши Enter на клавиатуре.
______________________________________________________________________________________________________________________________________________________________________________________
playwright codegen --help - эту команду использует ну как ты сама думаешь помощь это как бы обяснить тебе надо просто интуитивно поннимать. Понимаешь. Само слово за себя отвечает
помощь. Краткое описание выдает как ответ. Никто тебя не застяавляет чтобы ты зубрила. Просто надо понимать смысл или логику. Думай aiDoni. Тупо не делай. Это ведь помощь.

______________________________________________________________________________________________________________________________________________________________________________________
playwright codegen --viewport-size=800,600 https://demo.playwright.dev/todomvc/#/ - это отвечает за размер браузера. Ты даешь значение сколько в каком объеме. Прикольно ведь да.
Но пойми если ты поставишь туда малые значения тогда это будет мало, а когда большие значения будет размер окна много. Это как если вкладываешь больше получаешь больше.
Вкладываешь меньше и получаешь меньше. Нельзя так относиться к размеру браузера безразлично.

______________________________________________________________________________________________________________________________________________________________________________________
Что такое локарторы озадумалась сегодня aiDoni и пришла к выводу на основании курса из stepik следующим выводам

Локаторы  - предоставляют способы поиска веб-элементов на странице.
______________________________________________________________________________________________________________________________________________________________________________________


