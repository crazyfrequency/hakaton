# ТЗ для хакатона PSUTI+
### Цель: Разработать бота для ставок на киберспортивные турниры `digital noise eSports`.
Разрешённые языки: <span style="color:#3572A5">python</span>, <span style="color:#f1e05a">js</span>, <span style="color:#3178C6">ts</span>, <span style="color:#F34B7D">c++</span>, <span style="color:#DEA584">rust</span>, <span style="color:#B07219">java</span>, <span style="color:#A97BFF">kotlin</span>.

Бот должен поддерживать `telegram` и/или `ВК`. За реализацию обоих дополнительные баллы.

> [!IMPORTANT]
Все основные настройки(токены и т.д.) желательно вынести в отдельный(ые) файлы.

> [!CAUTION]
> В боте используется виртуальная валюта. Виртуальную валюту `нельзя` `конвертировать`/`обменять`/`продать`!!!

Возможности бота:
- Валюта `AdaCoins`. На начальном этапе игроку выдаётся определённое количество виртуальной валюты. После исчерпания валюты полностью, у игрока должна быть возможность получить новую по прошествии времени.
- Реализовать возможность создавать турниры с названием, командами(в том числе с составом) и начальными коэффициентами.
- Реализовать систему коэффициентов в зависимости от сделанных ставок.
- Можно делать ставку на общий счёт матча или на конкретную встречу в рамках матча, ставки делаются перед началом матча и встречи соответственно.
- Пользователь должен иметь возможность узнать, какие сейчас проходят матчи, а также иметь возможность сделать ставку.
- Реализовать возможность обмена виртуальной валюты на сувенирную продукцию.
- сделать API для доступа к данным коэффициентов(чтобы можно было выводить на трансляциях).

> [!NOTE]
> `digital noise eSports` - это киберспортивный клуб ПГУТИ, который проводит турниры с трансляциями и имеет собственные команды по `CS 2`, `Dota 2`

Можно сделать админ панель в виде сайта или отдельных кнопок в боте(у администратора).

> [!WARNING]
Чем проработанней получится проект, тем лучше. Проект расчитан на команды по 1-3 человека.
