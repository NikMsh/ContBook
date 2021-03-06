# UML Диаграммы
1. [Диаграмма прецедентов](#6)<br>
1.1 [Актёры](#6.1)<br>
1.2 [Варианты использования](#6.2)<br>
1.2.1 [Поиск контакта](#6.2.1)<br>
1.2.2 [Просмотр и редактирование контакта](#6.2.2)<br>
2. [Диаграмма активности](#2)
3. [Диаграмма последовательности](#3)
4. [Диаграмма состояний](#4)
5. [Диаграмма классов](#5)
6. [Диаграмма развертывания и компонентов](#6)

### Глоссарий 

|Термин|Определение|
|:---|:---|
|Пользователь|Человек, который использует данный веб-ресурс|

### 1. Диаграмма прецедентов<a name="1"></a>
Диаграмма прецедентов представляет собой следующую диаграмму: 
![Use Case](https://github.com/evgenyv13/ContBook/blob/master/docs/Project%20Documentation/UMLDiagrams/IMG/usecase.png)
#### 1.1 Актёры<a name="1.1"></a>
Актёр | Описание
--- | ---
Пользователь|Человек, использующий систему

#### 1.2 Варианты использования<a name="1.2"></a>
##### 1.2.1 Поиск контакта<a name="1.2.1"></a>
**Описание.** Вариант использования "Поиск контакта" позволяет пользователю найти контакты подходящие по введенным параметрам.
Поток выполнения:
1. Пользователь нажимает клавишу "Поиск".
2. На странице появляется модальное окно с полями доступными для поиска.
3. Пользователь вводит необходимые данные.
4. Пользователь нажимает кнопку поиск.
5. Конец.
##### 1.2.2 Просмотр и редактирование контакта<a name="1.2.2"></a>
**Описание.** Вариант использования "Просмотр и редактирование контакта" позволяет пользователю просматривать и редактировать контакт.
Поток выполнения:
1. Пользователь, на главной странице, нажимает на имя контакта.
2. Происходит переадрессация на страницу редактирования контакта.
3. В случае необходимости пользователь редактирует необходимую информацию и нажимает кнопку "Сохранить"
4. В случае необходимости работы с контактами, пользователь добавляет/удаляет/редактирует контактные телфоны.
5. В случае необходимости работы с приложениями к контакту, пользователь загружает/скачивает или изменяет название загруженных файлов.
6. Конец.

### 2. Диаграмма активности<a name="2"></a>
Диагаммы активности более подробно расписаны в следующем документе: [диаграммы активности](https://github.com/evgenyv13/ContBook/blob/master/docs/Project%20Documentation/UMLDiagrams/IMG/Activity%20Diagram/README.md)
 
### 3. Диаграмма последовательности<a name="3"></a>
Диаграмма последовательности создания нового контакта представляет из себя следующую диаграмму:
[Диаграмма последовательности создания нового контакта](https://github.com/evgenyv13/ContBook/blob/master/docs/Project%20Documentation/UMLDiagrams/IMG/Sequence%20Diagram/createContact.png)

Диаграмма последовательности удаления контактов представляет из себя следующую диаграмму:
[Диаграмма последовательности удаления контактов](https://github.com/evgenyv13/ContBook/blob/master/docs/Project%20Documentation/UMLDiagrams/IMG/Sequence%20Diagram/deleteContact.png)

Диаграмма последовательности поиска контактов представляет из себя следующую диаграмму:
[Диаграмма последовательности поиска контактов](https://github.com/evgenyv13/ContBook/blob/master/docs/Project%20Documentation/UMLDiagrams/IMG/Sequence%20Diagram/findContact.png)

### 4. Диаграмма состояний<a name="4"></a>

Диагаммы состояний более подробно расписаны в следующем документе: [диаграммы состояний](https://github.com/evgenyv13/ContBook/blob/master/docs/Project%20Documentation/UMLDiagrams/IMG/State/README.md)

### 5. Диаграмма классов<a name="5"></a>

![Class](https://github.com/evgenyv13/ContBook/blob/master/docs/Project%20Documentation/UMLDiagrams/IMG/classDiagram.png)

### 6. Диаграмма развертывания и компонентов<a name="6"></a>

Диаграмма развёртывания и компонентов представляет собой следующую диаграмму: 

![Deployment](https://github.com/evgenyv13/ContBook/blob/master/docs/Project%20Documentation/UMLDiagrams/IMG/deployment.png)

