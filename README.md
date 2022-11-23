## Командная задача (обязательная)

Это задание вы будете решать в команде из двух человек. 
Одного человека обозначим как **участник A**, второго - **участник Б**.

:warning: Эта задача является продолжением [задачи про исключения](./EXC.md), поэтому для выполнения этой необходимо сперва получить по ней зачёт.


| Этап | Участник А | Участник Б |
| ---- | ---------- | ---------- |
| 1 | Создаёт у себя публичный репозиторий, в настройках репозитория даёт право на запись участнику Б | -- |
| 2 | -- | Берёт своё решение [домашней работы по исключениям](./EXC.md) и заливает его на репозиторий в ветку `main` |
| 3 | Отводит ветку `minus`, добавляет возможность вводить отрицательное количество товара, что будет означать его уменьшение в корзине, или число 0, что будет означать его обнуление. Коммитит и пушуит в свою ветку. | Отводит ветку `sale`. В программе теперь появится новый массив из названий товаров, которые продаются по принципу "3 по цене 2х". Таким образом, за каждые три штуки товара из массива в корзине цена должна начисляться как за два. Коммитит и пушит в свою ветку |
| 4 | -- | Создаёт PR к `main` и делает мёрж |
| 5 | Сливает изменения `main` в `minus`, разрешая конфликты. Создаёт PR к `main` но не делает мёрж | -- |
| 6 | -- | Изучает PR, пишет в комментарии ОК и сливает изменения если согласен или описывает почему он считает изменения для слияния неправильными |
| 7 | Исправляет замечания если такие были, делая новый PR и переходя к этапу 6. Иначе работу можно считать завершённой | -- |

Итого: прикрепите ссылку на свой репо и на два смёрженных PR.
