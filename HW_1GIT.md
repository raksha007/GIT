JSON 4. Створити зовнішній репозиторій з назвою JSON

```
1. На сайтеі github.com в розділі Repositories,в полі Repository name написати JSON і  натиснути "Create repository"
```

5. Клонувати репозиторій JSON на локальний комп'ютер.

```bash
git clone git@github.com:raksha007/JSON.git
```

6. Всередині локального JSON створити  файл “new.json”.

```bash
cd JSON
touch new.json
```

7. Добавити файл під гіт.

```bash
git add new.json
```

8. Закоммітити файл.

```bash
git commit -m "add new file"
```

9. Відправити файл на зовнішній GitHub репозиторій.

```bash
git push
```

10. Відрегатувати зміст файла “new.json” - написати информацію про себе (ПІБ, вік, кількість домашніх тварин, майбутня бажана зарплатня). Все написати в форматі JSON.

```bash

cat > new.json

{
 "Name":"Stepan",
 "Age":"24",
 "Pets":"1",
 "Salary":"8000$"
}

^C

```

11. Відправити зміни на зовнішній репозиторій.

```bash
git commit -am "Edit file new.json"
git push
```

12. Створити файл preferences.json

```bash
touch preferences.json
```


13. В файл preferences.json додати информацію щодо  своїх вподобань (Улюблений фільм, улюблений серіал, улюблена їжа, улюблена  пора року, країна яку хотіли би відвідати) в форматі JSON.


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

14. Створити файл skills.json додати информацію про скіли які будут вивчені на курсі в форматі JSON

```bash
touch skills.json

vim skills.json

Натиснути на клавішу "I" - INSERT MODE
{
"1.": "Базова теорія (Що таке тестування, багрепорти, документація, види, методи, напрямки тестування і т.д.) SDLC, STLC",
"2.": "Що таке кліент-серверна архітектура",
"3.": "HTTP Методи запитів на сервер",
"4.": "Коди відповідей HTTP серверу",
"5.": "Структури HTTP запитів та відповідей",
"6.": "Що таке JSON, XML. Їх структура",
"7.": "Тестування API через Postman (JS, автотести API)",
"8.": "Зняття та читання логів з зовнішнього сервера",
"9.": "Сніфінг http web трафіка через Charles и Fiddler",
"10.": "Dev Tools веб браузерів (Google Chrome, FireFox)",
"11.": "VPN. (Як працює, навіщо потрібен, як використовувати, варіанти інструментів)",
"12.": "Мобільне тестування",
"13.": "Особливість iOS, Android, гайдлайни",
"14.": "Збірка iOS додатків на XCode. (В кого немає Mac комп'ютера, просто подивляться)",
"15.": "Збірка Android додатків на Android Studio",
"16.": "ADB (керування андроїд девайсами)",
"17.": "Настройка проксі и vpn на iOS и Android",
"18.": "Перехоплення (сніффінг) мобильного трафіка через Charles и Fiddler на iOS и Android",
"19.": "Командна строка (terminal) Linux (копіювання, створення, перегляд, переміщення файлів на серверах без графічного інтерфейсу)",
"20.": "Основи bash скріптинг, автоматизація рутинних задач на сервері",
"21.": "Доступ до віддалених серверів",
"22.": "Основи SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)",
"23.": "База даних Postgres (встановлення, налаштування і використання)",
"24.": "Нереляційна база даних Redis (встановлення, налаштування і використання)",
"25.": "Навантажувальне тестування в Jmeter",
"26.": "Методологія разробки Scrum",
"27.": "Python. (Вивчення основ.Створення кліент серверного додатку)"
}


Esc
:wq

```

15. Відправити зразу 2 файли на зовнішній репозиторій.

```bash
git add skills.json preferences.json
git commit -m "add new files preferences.json skills.json"
git push

```

16. На веб интерфейсі створити файл bug_report.json.
17. Зробити Commit changes (зберегти) зміни на веб интерфейсі.

```bash

Зайти на сайт github.com

Відкрити репозиторій JSON
Нажатина кнопку Add file
Выбрати в меню Create new file
В полі name написать bug_report.json
В поліCommit new file написати Create bug_report.json
Натиснути на кнопку Commit new file

```

18. На веб интерфейсі модифікувати файл bug_report.json, добавити баг репорт в форматі JSON.
19. Зробити Commit changes (зберегти) зміни на веб интерфейсі.
    Натиснути іконку "Олівець"

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

В полі Commit changes написать Update bug_report.json
Натиснути на кнопку Commit changes
```

20. Синхронізувати зовнішній і локальний репозиторій JSON

```bash
git pull
```

XML 21. Створити зовнішній репозиторій з назвою XML.

```
1. На сайті github.com в розділі Repositories,в полі Repository name написати XML і  натиснути "Create repository"
```

22. Клонувати репозиторій XML на локальний комп'ютер.

```bash
git clone git@github.com:raksha007/XML.git
```

23. Всередині локального XML створити файл “new.xml”.

```bash
cd XML
touch new.xml
```

24. Додати файл під гит.

```bash
git add new.xml
или
git add .
```

25. Закоммітити файл.

```bash
git commit -m "add new file new.xml"
```

26. Відправити файл на зовнішній GitHub репозиторій.

```bash
git push
```

27. Відредактувати  зміст файлу “new.xml” - написати информацію про себе (ПІБ, вік, кількість домашніх тварин, майбутня бажана заробітня плата). Все написати в форматі XML.

```xml
cat > new.xml

<name>Stepan</name>
<age>24</age>
<pets>1</pets>
<salary>800$</salary>

^C
```

28. Відправити зміни на зовнішній репозиторій.

```bash
git add
git commit -m "modify new.xml"
git push
```

29. Створити файл preferences.xml

```bash
touch preferences.xml
```


30. В файл preferences.xml добавити информацію про свої вподобання (Улюблений фільм, улюблений серіал, улюблена їжа, улюблена  пора року, країна яку хотіли би відвідати) в форматі XML.


```xml
 cat > preferences.xml
 

<Favorite_film> The Shining </Favorite_film>
<Favorite_serial> Everyones Hates Chris </Favorite_serial>
<Favorite_food> Salo </Favorite_food>
<Favorite_season> Winter </Favorite_season>

<Favorite_country> Japan </Favorite_country>

^C
```

31. Створити файл sklls.xml додати информацію про скіли які будут вивчені на курсі в форматі XML

```bash
 touch skills.xml
 cat > skills.xml
 
 <skills>
   <item_1>Базова теорія (Що таке тестування, багрепорти, документація, види, методи, напрямки тестування і т.д.) SDLC, STLC> </item_1>
   <item_2>Що таке кліент-серверна архітектура</item_2>
   <item_3>HTTP Методи запитів на сервер</item_3>
   <item_4>Коди відповідей HTTP серверу</item_4>
   <item_5>Структури HTTP запитів і відповідей</item_5>
   <item_6>Що таке JSON, XML. Їх структура</item_6>
   <item_7>Тестування API через Postman (JS, автотести API)</item_7>
   <item_8>Зняття і читання логів з зовнішнього серверу</item_8>
   <item_9>Сніфінг http web трафіку через Charles та Fiddler</item_9>
   <item_10>Dev Tools веб браузерів (Google Chrome, FireFox)</item_10>
   <item_11>VPN. (Як працює, навіщо потрібен, як використовувати, варіанти інструментів)</item_11>
   <item_12>Мобільне тестування</item_12>
   <item_13>Особливість iOS, Android, гайдлайни</item_13>
   <item_14>Збірка iOS додатків на XCode. (В кого немає Mac комп'ютера, просто подивляться)</item_14>
   <item_15>Сборка Android додатків на Android Studio</item_15>
   <item_16>ADB (Керування андроїд девайсами)</item_16>
   <item_17>Налаштування проксі та vpn на iOS і Android</item_17>
   <item_18>Перехоплення (сніффінг) мобільного трафіка через Charles та Fiddler на iOS і Android</item_18>
   <item_19>Командна строка (terminal) Linux (копіювання, створення, перегляд, переміщення файлів на серверах без графічного інтерфейсу)</item_19>
   <item_20>Основы bash скриптинг, автоматизация рутинных задач на сервере</item_20>
   <item_21>Доступ к удалённым серверам</item_21>
   <item_22>Основи SQL Create, Delete, Drop, Insert Into, Select, From, Where, Join)</item_22>
   <item_23>База даних Postgres (встановлення, налаштування та використання)</item_23>
   <item_24>Нереляційна база даних Redis (встановлення, налаштування та використання)</item_24>
   <item_25>Навантажувальне тестування в Jmeter</item_25>
   <item_26>Методологія розробки Scrum</item_26>
   <item_27>Python. (Вивчення основ. Створення клієнт серверного додатку)</item_27>
 </skills>

^C
```

32. Зробити комміт в одну строку.

```bash
git add . && git commit -m "add 2 new XML files"
```

33. Відправити зразу 2 файли на зовнішній репозиторій.

```bash
git push
```

34. На веб интерфейсі створити файл bug_report.xml.
35. Зробити Commit changes (зберегти) зміни на веб интерфейсі.

```bash
-Зайти на сайт github.com
-Відкрити репозиторій XML
-Натиснути на кнопку Add file
-Выбрати в меню Create new file
-В полі name написати bug_report.xml
-В полі Commit new file написати Create bug_report.xml
-Натиснути на кнопку Commit new file
```

36. На веб интерфейсі модифікувати файл bug_report.xml, добавити баг репорт в форматі XML.
37. Зробити Commit changes (зберегти) зміни на веб интерфейсі.

```xml

 Натиснути іконку "Олівець"
 
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

 В полі Commit changes написать Update bug_report.xml
 Натиснути на кнопку Commit changes

```

38. Синхронізувати зовнішній і локальний репозиторій XML

```bash
    git pull
```

TXT

1. Створити зовнішній репозиторій з назвою TXT.

```
1. На сайті github.com в розділі Repositories,в полі Repository name написати TXT  і натиснути "Create repository"

```

2. Клонувати репозиторій TXT на локальний комп'ютер.

```bash
 git clone git@github.com:raksha007/TXT.git

```

3. Всередині локального TXT створити файл “new.txt”.

```bash
cd TXT
touch new.txt
```

4. Додати файл під гіт.

```bash
git add new.txt
```

5. Закоммітити файл.

```bash
git commit -m "add  new.txt"
```

6. Відправити файл на зовнішній GitHub репозиторій.

```bash
git push
```

7. Відредактувати зміст  файлу “new.txt” - написати информацію про себе (ПІБ, вік, кількість домашніх тварин, майбутня бажана заробітня плата). Все написати в форматі TXT.

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


10. В файл preferences.txt додати інформацію про свої вподобання (Улюблений фільм, улюблений серіал, улюблена їжа, улюблена  пора року, країна яку хотіли би відвідати) в форматі TXT.

```bash
cat > preferences.txt


Favorite film: "The shining"
Favorite serial: "Everyone Hates Chrise"
Favorite food: Salo
Favorite season: Winter
Favorite coutry: Japan

^C
```

11. Створити файл sklls.txt додати інформацію про скіли які будут вивчені на курсі в форматі TXT

```bash
touch skills.txt
cat > skills.txt


1. Базова теорія (Що таке тестування, багрепорти, документація, види, методи, напрямки тестування і т.д.) SDLC, STLC
2. Що таке кліент-серверна архітектура
3. HTTP Методи запитів на сервер
4. Коди відповідей HTTP серверу
5. Структури HTTP запитів та відповідей
6. Що таке JSON, XML. Їх структура
7. Тестування API через Postman (JS, автотести API)
8. Зняття та читання логів з зовнішнього сервера
9. Сніфінг http web трафіка через Charles и Fiddler
10. Dev Tools веб браузерів (Google Chrome, FireFox)
11. VPN. (Як працює, навіщо потрібен, як використовувати, варіанти інструментів)
12. Мобільне тестування
13. Особливість iOS, Android, гайдлайни
14. Збірка iOS додатків на XCode. (В кого немає Mac комп'ютера, просто подивляться)
15. Збірка Android додатків на Android Studio
16. ADB (керування андроїд девайсами)
17. Настройка проксі и vpn на iOS и Android
18. Перехоплення (сніффінг) мобильного трафіка через Charles и Fiddler на iOS и Android
19. Командна строка (terminal) Linux (копіювання, створення, перегляд, переміщення файлів на серверах без графічного інтерфейсу)
20. Основи bash скріптинг, автоматизація рутинних задач на сервері
21. Доступ до віддалених серверів
22. Основи SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)
23. База даних Postgres (встановлення, налаштування і використання)
24. Нереляційна база даних Redis (встановлення, налаштування і використання)
25. Навантажувальне тестування в Jmeter
26. Методологія разробки Scrum
27. Python. (Вивчення основ.Створення кліент серверного додатку)

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
