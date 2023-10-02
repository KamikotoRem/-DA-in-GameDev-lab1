# -DA-in-GameDev-lab2
# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #2 выполнил(а):
- Захаров Данил АНдреевич
- РИ220930
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * |  |
| Задание 2 | * |  |
| Задание 3 | * |  |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Научиться передавать в Unity данные из Google Sheets с помощью Python.


## Задание 1
### Постройка схемы экономической модели.
Ход работы: Выберите одну из компьютерных игр, приведите скриншот её геймплея и краткое описание концепта игры. Выберите одну из игровых переменных в игре (ресурсы, внутри игровая валюта, здоровье персонажей и т.д.), опишите её роль в игре, условия изменения / появления и диапазон допустимых значений. Постройте схему экономической модели в игре и укажите место выбранного ресурса в ней.

### Я выбрал игру Dota 2.


-![image](https://github.com/KamikotoRem/-DA-in-GameDev-lab2/assets/129965242/2dd8949a-f3c4-4df0-baba-f8bcfc7588b6)


Описание:Dota 2-это многопользовательская онлайн-боевая арена (MOBA), в которой две команды из пяти игроков соревнуются, чтобы коллективно уничтожить большую структуру, защищаемую противоположной командой, известной как "Древняя", защищая свою собственную. Как и в Defense of the Ancients, игра управляется с помощью стандартных элементов управления стратегией в реальном времени и представлена на одной карте в трехмерной изометрической перспективе.

Я выбрал переменную "опыт". ОпытXP — это элемент, который герои могут зарабатывать с помощью убийства вражеских существ, или будучи неподалёку в момент смерти вражеских существ. Сам по себе, опыт ничего не делает, но при накоплении, он увеличивает уровень героя и тот становится сильнее. Только герои могут зарабатывать опыт и, тем самым, достигать высоких уровней(максимальный 30, начинают с 1).
С каждым полученным уровнем базовые атрибуты героя улучшаются на статические значения, что делает его сильнее в несколько способов. Также, при повышении уровня, герои могут изучать новые способности, или улучшать уже изученные способности до высших уровней, делая их более мощными. Также, на определённых уровнях, можно изучать таланты, которые ещё больше улучшают характеристики или способности героя.

### Экономическая схема влияния опыта на игровой процесс.



-![image](https://github.com/KamikotoRem/-DA-in-GameDev-lab2/assets/129965242/a3ecc471-a827-4334-b8fb-22fa18428aa6)


## Задание 2
### Заполнить google-таблицу.
Ход работы:С помощью скрипта на языке Python заполните google-таблицу данными, описывающими выбранную игровую переменную в выбранной игре (в качестве таких переменных может выступать игровая валюта, ресурсы, здоровье и т.д.). Средствами google-sheets визуализируйте данные в google-таблице (постройте график, диаграмму и пр.) для наглядного представления выбранной игровой величины.
### Код в питон.
-![image](https://github.com/KamikotoRem/-DA-in-GameDev-lab2/assets/129965242/b57eedae-3e3d-4af1-b362-9b3979aa5161)
### Визуализация данных в экселе.
-![image](https://github.com/KamikotoRem/-DA-in-GameDev-lab2/assets/129965242/fc23e680-32a0-4e8e-973b-5e014f507930)



## Задание 3
### Воспроизведение звуковых файлов.

Ход работы: Настройте на сцене Unity воспроизведение звуковых файлов, описывающих динамику изменения выбранной переменной. Например, если выбрано здоровье главного персонажа вы можете выводить сообщения, связанные с его состоянием.
### Реплики героя во время повышения уровня
-![image](https://github.com/KamikotoRem/-DA-in-GameDev-lab2/assets/129965242/c19e5b70-9002-4640-bff8-c7926f483e10)



## Выводы

В этой работе я научился работать с внутриигровой валютой при помощи google Таблиц(хранящиеся данные) и воспроизведенить их на Unity

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
