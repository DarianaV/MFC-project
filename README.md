01.Задача за изпълнение:

Да се изчете и прилага SQL Coding Guidelines - CSoft Knowledge Base

Да се изготви database за приложение PhoneBook

Да се добавят всички нужни индекси, PK и FK

Да се вмъкнат примерни данни + транзакции

Да се направят примерни JOINS и Views

Да се изготви диаграма със всички връзки в нея

Да се запознаете със смисъла и основните типове SQL LOCKS

Скриптовете трябва да могат да се изпълняват многократно без грешка:

Скрипт за създаване на структурата на базата данни

Скрипт за попълване на базата данни с данни и модификация на тези данни

Скрипт със примерни сложни SELECT-и, JOIN-ове и т.н.

02.Задача за изпълнение:

Да се разпишат дисковите структури на всички таблици от разработената база данни

Да се разпишат typedef-ове на CTypedPtrArray за всички дискови структури

Да се запознаете и да разпишете примери, на които да упражните и debug със:

- CString

- CArray

- CPtrArray

- CTypedPtrArray

- CMap*

03.Задача за изпълнение:

CCitiesTable public медоди:

 BOOL SelectAll(CCitiesArray& oCitiesArray);

 BOOL SelectWhereID(const long lID, CITIES& recCities);

 BOOL UpdateWhereID(const long lID, const CITIES& recCities);

 BOOL Insert(const CITIES& recCities);

 BOOL DeleteWhereID(const long lID);

04.Задача за изпълнение:

Имплементация на цялата Document-View архитектура за регистър Градове

 Table клас – CCitiesTable

 Data клас (Бизнес логика) – CCitiesData

 Наследник на CDocument - CCitiesDocument

 Наследник на CListView - CCitiesView

 Наследник на CDialog – CcitiesDialog

05.Задача за изпълнение:

 Запознаване с различните транзакционни изолации (Transaction Isolation)
 Реализация на оставащите таблични класове (Persons, PhoneNumbers, PhoneTypes)
 Реализация на Document-View архитектурата за Persons и свързаните му таблици, по примера, реализиран със Cities
 Реализация на транзакционно записване на свързаните регистри (Persons, PhoneNumbers)
 Реализация на диалози за редакция на Person (всичките му атрибути) и неговите номера