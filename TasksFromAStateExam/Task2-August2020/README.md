## Държавен изпит ФМИ, специалност Компютърни науки - 05.08.2020.

**2 задача:**  Цикличен едносвързан списък наричаме линеен едносвързан списък, в който указателят за следващ елемент на последния елемент сочи към първия елемент, вместо да е нулев. Да се реализира функция 
void unite(Node* list), която получава като параметър указател към елемент на цикличен едносвързан списък от символни низове, описан от следната структура:
```
struct Node {
    std::string text;
    Node* next;
};
```
Функцията да обединява всички двойки последователни елементи на списъка, за които последният символ на единия елемент съвпада с първия символ на непосредствено следващия го елемент, в общ елемент, чийто низ е съставен от слепването на низовете на двата елемента, разделени с тире.
Да се демонстрира работата на функцията в кратка програма, която прочита низове от стандартния вход (по един на ред), добавя ги в съответния цикличен списък, подава го на функцията unite и извежда последователно елементите на променения списък на стандартния изход, започвайки от лексикографски най-малкия низ. <br />
#### Пример: <br />
**Вход:** <br />
street <br />
taxi <br />
ink <br />
dog <br />
smile <br />
eat <br />
tall <br />
pass <br />
<br />
**Изход:** <br />
dog <br />
smile-eat-tall <br />
pass-street-taxi-ink <br />

### Демонстрация: ###
![](/TasksFromAStateExam/Task2-August2020/demonstration.gif)
