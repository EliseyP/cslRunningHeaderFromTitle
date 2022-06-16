# cslRunningHeaderFromTitle

`LibreOffice`-расширение для запуска `gui`-диалога, позволяющего оперировать колонтитулом для документа из шаблона `Гимнография 20 новый` из проекта [csl_odt2tex](https://github.com/EliseyP/csl_odt2tex).

Для запуска диалога есть своя кнопка ![](images/install_16.png) на отдельной `toolbar`-панели, а также подменю в `Menu|Сервис|Addons`.

После запуска диалога в поле `Заглавие` автоматически помещается текст, оформленный стилем `Заглавие` (первый найденный). Также есть кнопка `Из текста`, для проведения этой операции **вручную** (если например, текст заглавия был изменен).

У поля `Колонтитул` есть кнопка `Из Заглавия`, которая позволяет скопировать текст заглавия в поле колонтитула. Текст может редактироваться.

По нажатии кнопки `Обновить`, содержимое полей `Заглавие` и `Колонтитул` заносятся в `user`-поля `TitleInText` и `RunningHeader` соответственно. Содержимое поля `RunningHeader` при этом автоматически помещается в колонтитулы документа.

В данном примере укорочен текст Заглавия, слишком длинный для колонтитула.

<img src="images/example.jpeg" width="800" height="220">



