# RSS_Reader

Исполняемый файл -  Reader.py

В строку "Feed URL" вставляем адресс RSS и нажимаем "Get Feed"
В окне слева появляются последние 10 статей. Если кликнуть мышкой, то появится краткое содержание статьи, если сделать дабл клик, то статья откроется в виджете браузера.

Можно осуществлять поиск по ключевым словам в названиях статей полученных после "Get Feed". Также возможно осуществлять поиск по ключевым словам в кратком содержании статей.

При нажатии на зеленый плюс можно добавить категорию, после чего выбрать статью кликом мышки и нажать красный плюс. В таком случае выбранная статья будет добавлена в базу данных, которую можно просмотреть при нажатии на кнопку с изображением двух листов.

# Список импортируемых модулей:

wx, feedparser, os, unidecode, wx.html2, re, sqlite3, sys, ObjectListView 

# Для работы программы на Windows:

pip install -U wxPython

pip install feedparser

pip install unidecode

pip install ObjectListView

# Для работы программы на Linux:

$ pip install pygame --user

$ pip install wheel --user

$ pip install -U \
      -f https://extras.wxpython.org/wxPython4/extras/linux/gtk3/ubuntu-16.04 \
      wxPython

$ pip install wxpython --user

$ pip install feedparser

$ pip install unidecode

# Если консоль пишет, что pip не найдет, попробуйте pip2
# Или же укажите полный путь:
C:\Python34\Tools\Scripts\pip.exe install feedparser



