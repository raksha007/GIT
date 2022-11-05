JSON 4. Создать внешний репозиторий c названием JSON

```
1. На сайте github.com в разделе Repositories,в поле Repository name написать JSON и  нажать "Create repository"
```

5. Клонировать репозиторий JSON на локальный компьютер.

```bash
git clone git@github.com:raksha007/JSON.git
```

6. Внутри локального JSON создать файл “new.json”.

```bash
cd JSON
touch new.json
```

7. Добавить файл под гит.

```bash
git add new.json
```

8. Закоммитить файл.

```bash
git commit -m "add new file"
```

9. Отправить файл на внешний GitHub репозиторий.

```bash
git push
```

10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

```bash
vim new.json
Press the button "i"

{
 "Name":"Stepan",
 "Age":"24",
 "Pets":"1",
 "Salary":"8000$"
}
Esc
:wq
```

11. Отправить изменения на внешний репозиторий.

```bash
git commit -am "Edit file new.json"
git push
```

12. Создать файл preferences.json

```bash
touch preferences.json
```

13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страну которую хотели бы посетить) в формате JSON.

```bash
vim preferences.json
Press the button "i"

{   "Favorite film":   "The Shining.",
   "Favorite serial": "Everybody Hates Chris",
   "Favorite food":   "Salo" ,
   "Favorite season": "Winter" ,
   "Favorite country": "Japan"
}
Esc
:wq
```

14. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

```bash
touch skills.json
vim skills.json
Нажать на клавишу "I" - INSERT MODE
{
"1.": "Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC",
"2.": "Что такое клиент-серверная архитектура",
"3.": "HTTP Методы запросов на сервер",
"4.": "Коды ответов HTTP сервера",
"5.": "Структуры HTTP запросов и ответов",
"6.": "Что такое JSON, XML. Их структура",
"7.": "Тестирование API через Postman (JS, автотесты API)",
"8.": "Снятие и чтение логов c внешнего сервера",
"9.": "Снифинг http web трафика через Charles и Fiddler",
"10.": "Dev Tools веб браузеров (Google Chrome, FireFox)",
"11.": "VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)",
"12.": "Мобильное тестирование",
"13.": "Особенность iOS, Android, гайдлайны",
"14.": "Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)",
"15.": "Сборка Android приложений на Android Studio",
"16.": "ADB (управление андройд девайсами)",
"17.": "Настройка прокси и vpn на iOS и Android",
"18.": "Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android",
"19.": "Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)",
"20.": "Основы bash скриптинг, автоматизация рутинных задач на сервере",
"21.": "Доступ к удалённым серверам",
"22.": "Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)",
"23.": "База данных Postgres (установка, настройка и использование)",
"24.": "Нереляционная база данных Redis (установка, настройка и использование)",
"25.": "Нагрузочное тестирование в Jmeter",
"26.": "Методология разработки Scrum",
"27.": "Python. (Изучение основ. Создание клиент серверного приложения)"
}

Esc
:wq

```

15. Отправить сразу 2 файла на внешний репозиторий.

```bash
git add skills.json preferences.json
git commit -m "add new files preferences.json skills.json"
git push

```

16. На веб интерфейсе создать файл bug_report.json.
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```bash
Зайти на сайт github
Открыть репозиторий JSON
Нажать на кнопку Add file
Выбрать в меню Create new file
В поле name написать bug_report.json
В поле Commit new file написать Create bug_report.json
Нажать на кнопку Commit new file

```

18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
    Нажать иконку "Карандаш"

```bash
{
   "navigator": {
  "vendorSub": "",
  "productSub": "20030107",
  "vendor": "Google Inc.",
  "appCodeName": "Mozilla",
  "appName": "Netscape",
  "appVersion": "5.0 (Macintosh; Intel Mac OS X 11_0_0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/86.0.4240.80 Safari/537.36",
  "platform": "MacIntel",
  "product": "Gecko",
  "userAgent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 11_0_0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/86.0.4240.80 Safari/537.36",
  "language": "en-US"
}

В поле Commit changes написать Update bug_report.json
Нажать на кнопку Commit changes
```

20. Синхронизировать внешний и локальный репозиторий JSON

```bash
git pull
```

XML 21. Создать внешний репозиторий c названием XML.

```
1. На сайте github.com в разделе Repositories,в поле Repository name написать XML и  нажать "Create repository"
```

22. Клонировать репозиторий XML на локальный компьютер.

```bash
git clone git@github.com:raksha007/XML.git
```

23. Внутри локального XML создать файл “new.xml”.

```bash
cd XML
touch new.xml
```

24. Добавить файл под гит.

```bash
git add new.xml
или
git add .
```

25. Закоммитить файл.

```bash
git commit -m "add new file new.xml"
```

26. Отправить файл на внешний GitHub репозиторий.

```bash
git push
```

27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

```xml
cat > new.xml

<name>Stepan</name>
<age>24</age>
<pets>1</pets>
<salary>800$</salary>

^C
```

28. Отправить изменения на внешний репозиторий.

```bash
git add
git commit -m "modify new.xml"
git push
```

29. Создать файл preferences.xml

```bash
touch preferences.xml
```

30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

```xml
 cat > preferences.xml
 

<Favorite_film> The Shining </Favorite_film>
<Favorite_serial> Everyones Hates Chris </Favorite_serial>
<Favorite_food> Salo </Favorite_food>
<Favorite_season> Winter </Favorite_season>
<Favorite_coutry> Japan </Favorite_coutry>

^C
```

31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

```bash
 touch skills.xml
 cat > skills.xml
 
 <skills>
   <item_1>Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC> </item_1>
   <item_2>Что такое клиент-серверная архитектура</item_2>
   <item_3>HTTP Методы запросов на сервер</item_3>
   <item_4>Коды ответов HTTP сервера</item_4>
   <item_5>Структуры HTTP запросов и ответов</item_5>
   <item_6>Что такое JSON, XML. Их структура</item_6>
   <item_7>Тестирование API через Postman (JS, автотесты API)</item_7>
   <item_8>Снятие и чтение логов c внешнего сервера</item_8>
   <item_9>Снифинг http web трафика через Charles и Fiddler</item_9>
   <item_10>Dev Tools веб браузеров (Google Chrome, FireFox)</item_10>
   <item_11>VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)</item_11>
   <item_12>Мобильное тестирование</item_12>
   <item_13>Особенность iOS, Android, гайдлайны</item_13>
   <item_14>Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)</item_14>
   <item_15>Сборка Android приложений на Android Studio</item_15>
   <item_16>ADB (управление андройд девайсами)</item_16>
   <item_17>Настройка прокси и vpn на iOS и Android</item_17>
   <item_18>Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android</item_18>
   <item_19>Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)</item_19>
   <item_20>Основы bash скриптинг, автоматизация рутинных задач на сервере</item_20>
   <item_21>Доступ к удалённым серверам</item_21>
   <item_22>Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)</item_22>
   <item_23>База данных Postgres (установка, настройка и использование)</item_23>
   <item_24>Нереляционная база данных Redis (установка, настройка и использование)</item_24>
   <item_25>Нагрузочное тестирование в Jmeter</item_25>
   <item_26>Методология разработки Scrum</item_26>
   <item_27>Python. (Изучение основ. Создание клиент серверного приложения)</item_27>
 </skills>

^C
```

32. Сделать коммит в одну строку.

```bash
git add . && git commit -m "add 2 new XML files"
```

33. Отправить сразу 2 файла на внешний репозиторий.

```bash
git push
```

34. На веб интерфейсе создать файл bug_report.xml.
35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```bash
-Зайти на сайт github.com
-Открыть репозиторий XML
-Нажать на кнопку Add file
-Выбрать в меню Create new file
-В поле name написать bug_report.xml
-В поле Commit new file написать Create bug_report.xml
-Нажать на кнопку Commit new file
```

36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```xml

 Нажать иконку "Карандаш"
 
<?xml version="1.0" encoding="UTF-8"?>

<bugs xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="XML-Schema-Rules.xsd">
   
    <bug priority="low">
        <bugnr>1</bugnr>
        <project>Web Application 1</project>
        <reporter>Andreas</reporter>
        <description>Application does not start.</description>   
    </bug>
   
    <bug>
        <bugnr>2</bugnr>
        <project>Web Application 1</project>
        <reporter>Andreas</reporter>
        <description>Login does not work.</description>
    </bug>
   
    <bug priority="high">
        <bugnr>3</bugnr>
        <project>Web Application 1</project>
        <reporter>Michael</reporter>
        <description>Registration does not work</description>
    </bug>
   
</bugs>

 В поле Commit changes написать Update bug_report.xml
 Нажать на кнопку Commit changes

```

38. Синхронизировать внешний и локальный репозиторий XML

```bash
    git pull
```

TXT

1. Создать внешний репозиторий c названием TXT.

```
1. На сайте github.com в разделе Repositories,в поле Repository name написать TXT и  нажать "Create repository"

```

2. Клонировать репозиторий TXT на локальный компьютер.

```bash
 git clone git@github.com:raksha007/TXT.git

```

3. Внутри локального TXT создать файл “new.txt”.

```bash
cd TXT
touch new.txt
```

4. Добавить файл под гит.

```bash
git add new.txt
```

5. Закоммитить файл.

```bash
git commit -m "add  new.txt"
```

6. Отправить файл на внешний GitHub репозиторий.

```bash
git push
```

7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.

```bash
cat > new.txt


name:Stepan,
age:24,
Pets:1,
salary:800$.

^C

8. Отправить изменения на внешний репозиторий.

```bash
git add . | git commit -m "update file new.txt"
git push
```

9. Создать файл preferences.txt

```bash
touch preferences.txt
```

10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

```bash
cat > preferences.txt


Favorite film: "The shining"
Favorite serial: "Everyone Hates Chrise"
Favorite food: Salo
Favorite season: Winter
Favorite coutry: Japan

^C
```

11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

```bash
touch skills.txt
cat > skills.txt


1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.
2. Что такое клиент-серверная архитектура.
3. HTTP Методы запросов на сервер.
4. Коды ответов HTTP сервера.
5. Структуры HTTP запросов и ответов.
6. Что такое JSON, XML. Их структура.
7. Тестирование API через Postman (JS, автотесты API).
8. Снятие и чтение логов c внешнего сервера.
9. Снифинг http web трафика через Charles и Fiddler.
10. Dev Tools веб браузеров (Google Chrome, FireFox).
11. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
12. Мобильное тестирование.
13. Особенность iOS, Android, гайдлайны.
14. Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)
15. Сборка Android приложений на Android Studio.
16. ADB (управление андройд девайсами).
17. Настройка прокси и vpn на iOS и Android.
18. Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.
19. Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)
20. Основы bash скриптинг, автоматизация рутинных задач на сервере.
21. Доступ к удалённым серверам.
22. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).
23. База данных Postgres (установка, настройка и использование).
24. Нереляционная база данных Redis (установка, настройка и использование).
25. Нагрузочное тестирование в Jmeter.
26. Методология разработки Scrum.
27. Python. (Изучение основ. Создание клиент серверного приложения)

^C
```

12. Сделать коммит в одну строку.

```bash
 git add . && git commit -am "add 2 files .txt"
```

13. Отправить сразу 2 файла на внешний репозиторий.

```bash
 git push
```

14. На веб интерфейсе создать файл bug_report.txt.
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

```
-Зайти на сайт github.com
-Открыть репозиторий TXT
-Нажать на кнопку Add file
-Выбрать в меню Create new file
-В поле name написать bug_report.txt
-В поле Commit new file написать Create bug_report.txt
-Нажать на кнопку Commit new file
```

16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
    Нажать иконку "Карандаш"

```
  
Bug-reports	
ID	BR000001
Summary	Не меняется язык в tooltip в поисковой строке после смены языка на сайте
Pre-conditions	Открыть сайт https://ldubgd.edu.ua/
Steps to Reproduce	1.Нажать на флаг Великой Британии в правом углу(cмена языка)
	2.Навести курсор на поисковую строку
	
	
	
Expected result	Страница должна была перевестиcь на англ язык
Actual result	Смена локализации не работает должным образом
Post-condition	Закрыть страницу
Environment	"Chrome 104.0.5112.81 (Официальная сборка), (64 бит)
"
Severity	Trivial
Priority	Low
Submit Date	16.08.2022
Reporter	Stepan Sheihas
Attachment	


В поле Commit changes написать Update bug_report.xml
Нажать на кнопку Commit changes
```

18. Синхронизировать внешний и локальный репозиторий TXT

```bash
git pull
```