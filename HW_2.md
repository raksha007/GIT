_1. На локальному репозиторії зробити гілки для:_
- _Postman_ - __git branch Postman__
- _Jmeter_ - __git branch Jmeter__
- _CheckLists_ - __git branch Checklists__
- _Bug Reports_ - __git branch Bugreports__
- _SQL_ - __git branch SQL__
- _Charles_ - __git branch Charles__
- _Mobile testing_ - __git branch Mobile_testing__

_2. Запушити всі шілки на зовніщній репозиторій:_
- __git push --all__

_3. В гілці Bugreports зробити текстовий документ зі структурою баг репорту:_ 
- __git checkout Bugreports__ 
- __vim bugreports.txt__
 

```bash
- 1.Короткий опис (Summary)
- Короткий опис проблеми, який явно вказує на причину та тип помилкової ситуації.__
- 2.Проєкт (Project)      Назва проєкта який тестуємо 
- 3.Компонент додатку (Component)      Назва частини чи функції  продукту який тестуємо
- 4.Номер версії (Version)        Версія на якій була знайдена помилка
- 5.Серйозність (Severity)
- 6.Найбільш поширена п'ятирівнева система градації серйозності дефекту:

S1 Блокуючий (Blocker)
S2 Критичний (Critical)
S3 Значний (Major)
S4 Незначний (Minor)
S5 Трівіальний

- 7.Пріоритет (Priority)
Пріоритет дефекту:

P1 Високий (High)
P2 Середній (Medium)
P3 Низький (Low)

- 8.Статус (Status)       Статус бага. Залежить від процедури що використовується  та життєвого циклу бага (bug workflow and life cycle)

- 9.Автор (Author)        Створювач баг репорту

- 10.Призначений на (Assigned To)    Ім'я співробітника, призначеного  на вирішення проблеми

- 11.Оточення
ОС / Сервіс Пак и т.д. / Браузера + версія / ...        Информація про оточення, на якому було знайдено баг: операційна система, сервіс пак, для WEB тестування - ім'я та версія браузеру і т.д.
...

- 12.Опис
Кроки відтворення (Steps to Reproduce)       Кроки, за якими можна легко відвторити ситуацію, що призвела  до помилки.
Фактичний Результат (Result)  Результат, отриманий після проходження кроків до  відтворення  
Очікуваний результат (Expected Result)   Очікуваний правильний результат
Доповнення
Прикріплений файл (Attachment) Файл с логами, скріншот чи любий другий документ, який може  допомогти прояснити причину помилки  чи вказати на спосіб вирішення проблеми
```
- __Esc + :wq__  

_4. Запушити структуру багрепорту на зовнішній репозиторій_ 
- __git add  bugreports.txt __   
- __git commit -m "Create bugrreport.txt"__
- __git push __  

_5. Вмержити гілку Bag Reports в Main:_ 
- __git checkout main__
- __git merge Bugreports__  

_6. Запушити main на зовніщній репозиторій:_ 
- __git push__

_7. В гілці Checklists накидати структуру чек ліста:_ 
- __git_checkout Checklists__
- __cat> checklist.txt__
```bash
ID
Summary
Section
Enviroment
Expected Result
Status
Bug report link
```
- __Ctrl+c__  

_8. Запушити структуру на зовнішній репозиторій_
- __git add .__   
- __git commit -m "Create checklist.txt"__
- __git push -u origin CheckLists__  

_9. На зовнішній репозиторії зробити Pull Request гілки Checklists в main:_
- __на зовнішньому репозиторії клікнути на  кнопку "Compare&Pull request"__
- __в полі для комментаря оставити комментарій "Branch is ready to be merged"__
- __клікнути на кнопку "Create pull request"__
- __клікнути на кнопку "Merge pull request"__
- __клікнути на кнопку "Confirm merge"__  

_10. Синхронізувати зовніншню та Локальну гілку Main:_
- __git checkout main__
- __git fetch__
- __git pull__
