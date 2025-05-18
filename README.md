# Программа (скрипт) для скачивания книг с сайта ЮРАЙТ urait.ru

Для запуска приложения необходимо вписать свои данные от аккаунта в файл **account.txt**

Содержимое файла **account.txt** 

`URAIT_EMAIL=you_email@gmail.com`

`URAIT_PASSWORD=your_password`

# Работа с программой

Вставить ссылку на книгу например (на страницу с книгой, а не на открытую книгу)
*https://urait.ru/book/psihologicheskie-osnovy-vozhatskoy-deyatelnosti-557275*


После окончания скачивания, файл .pdf появится в папке с программой

Библиотеки:
pip install aiohttp
pip install pypdf
pip install svglib
pip install reportlab
pip install python-environ
pip install win11toast   - уведомления в виндовс
