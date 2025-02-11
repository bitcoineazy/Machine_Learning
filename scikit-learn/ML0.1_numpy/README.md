### 0.1. Основы работы с numpy

#### Цель работы

Освоить основные приемы работы с библиотекой numpy.

#### Задания для выполнения

Вам даны данные результатов ЕГЭ по различным предметам. Выполните следующие действия:

1. Загрузите данные в ноутбук
2. Сделайте описательную статистику по набранному баллу
3. Найдите процент учащихся, выполнивших работу ниже среднего
4. Найти процент учащихся не сдавших экзамен
5. Постройте круговую диаграмму, показывающую распределение сдавших и не сдавших экзамен
6. Постройте ядерную оценку плотности распределению баллов за экзамен
7. Найдите процентное соотношение учащихся, сдавших экзамен на «отлично», «хорошо», «удовлетворительно», «неудовлетворительно».
8. Какое процентное соотношение юношей и девушек писало данный экзамен? 
9. Сколько школ принимало участие в экзамене?

#### Методические указания

Ознакомьтесь с официальной документацией по библиотеке numpy. Обратите особое внимание на примеры из [официального руководства numpy](https://docs.scipy.org/doc/numpy/user/quickstart.html). Рекомендуется повторить эти примеры, чтобы лучше разобраться с механизмами и приемами работы этой библиотекой.

#### Дополнительные задания

1. Сколько всего заданий с кратким ответом? С развернутым ответом?
2. Пусть задания с кратким ответом будут задания типа В. Соответственно всего по экзамену вопросов класса В: В 1 … В к Посчитайте процент выполненных и невыполненных заданий по каждому вопросу класса В. 
3. Аналогично и с типом С (ответы с развернутым ответом)
4. Сделайте анализ по двум школам:
    1. по всем выполненным заданиям типа В
    2. по заданиям типа С больше 50%
    3. по среднему баллу юношей и девушек

#### Контрольные вопросы

1. Какое свойство содержит количество элементов массива по измерениям?
2. Напишите функцию, создающую ndarray из массива [0, 1, 2, 3, 4]
3. Как создать нулевой 4-мерный вектор?
4. Как создать единичную диагональную матрицу 3х4?
5. Сколько операций умножения матриц существует в numpy?
6. Напишите инструкцию, выбирающую каждый третий элемент массива А начиная с 10-го и заканчивая 45-м
7. Напишите инструкцию создания матрицы 4х3 из плоского массива из 12 элементов