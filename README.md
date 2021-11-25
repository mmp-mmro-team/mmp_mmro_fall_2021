# Семинары по машинному обучению для бакалавров 3 курса кафедры ММП и магистров 1 курса кафедр ИИТ и МФ факультета ВМК МГУ, осенний семестр 2021/2022
В репозитории находятся материалы и домашние задания по семинарам "ММРО 2021/2022"

<p align="center">
<img src="http://funzoo.ru/uploads/posts/2009-11/1258648863_tn.jpg" height=200pt> <img src="https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/trash/kernel_trick.jpg" height=200pt>
</p>

:white_check_mark: **Курс сдается через систему [anytask](https://anytask.org/course/846). Инвайт можете получить у преподавателя**

:white_check_mark: На семинары и работу ассистентов можно [оставить отзыв](https://docs.google.com/forms/d/e/1FAIpQLSeCww7kQZRBbPDFW_dTRpKdBl1pL0jx4nezhciAof8b22O05Q/viewform)

:white_check_mark: **Полезные ссылки:**

* Текущие связанные курсы
    * [Курс Практикума на ЭВМ, осень](https://github.com/mmp-practicum-team/mmp_practicum_fall_2021)
    * [Общий курс ML 2021](https://github.com/MSU-ML-COURSE/ML-COURSE-21-22)

* Материалы прошлых лет:
  * [Раз](https://github.com/esokolov/ml-course-msu)
  * [Два](https://github.com/esokolov/ml-course-hse)
  * [Курс лекций по ММРО](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D1%80%D0%B0%D1%81%D0%BF%D0%BE%D0%B7%D0%BD%D0%B0%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F_%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%92.%D0%92.%D0%9A%D0%B8%D1%82%D0%BE%D0%B2%29)
  * [Курс ММРО 19/20, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2019)
  * [Курс ММРО 20/21, осень](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020)

# Правила выставления оценок

:white_check_mark: **По этому курсу (ММРО) в конце семестра будет экзамен**

Общая оценка по нему выставляется по следующей формуле:
![](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/trash/formula.png)
, где 

* Check — 5 * <сумма баллов за проверочные> / <суммарный макс балл за проверочные>
* Labs — min(5, 5 * <сумма баллов за лабораторные + конкурсы + теор. дз.> / <суммарный макс балл за (лабораторные + конкурсы + теор.дз) (без бонусов)>
* Exam — оценка за экзамен, до 5 баллов

Причем
* Для общей оценки 5 необходимо сдать **все (5)** _лабораторные работы (4) и теор. дз. (1)_ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за эказамен не меньше 4;
* Для общей оценки 4 необходимо сдать **не менее 3-х** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* Для общей оценки 3 необходимо сдать **не менее 2-x** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов)) **и** получить за экзамен не меньше 3;
* floor — округление дробного числа до ближайшего целого вниз.

**Обратите внимание,** что округление общей оценки (и только ее) производится вверх.

:white_check_mark: **По курсу лекций в конце семестра будет зачет без оценки**

Для получения этого зачета вам необходимо сдать **не менее 2-x** работ из _всего множества лабораторных работ и теор. дз._ на оценку (без учета штрафа) >= floor(1/3 * (макс. балл за работу без учета бонусов))

# Занятия

| Дата | Номер | Тема | Материалы | ДЗ |
| :---: | :---: | --- | --- | --- |
| 13 сентября  | Семинар 1 | Вводная лекция. Основы Pandas | [Ноутбук по pandas](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/seminars/sem01-pandas.ipynb) | [Прак.1 Pandas, numpy, matplotlib](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/homework-practice/numpy-pandas-matplotlib.ipynb) |
| 20 сентября  | Семинар 2 | Быстрый поиск ближайших соседей | <ul><li>[Семинар](https://github.com/esokolov/ml-course-hse/blob/master/2020-spring/lecture-notes/lecture20-knn.pdf)</li><li>[Записи с лекций](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/seminars/sem02/knn.pdf)</li></ul>|  ¯\\\_(ツ)\_/¯ |
| 27 сентября  | Семинар 3 | Особенности knn и разновидности метрик | [Семинар](https://github.com/esokolov/ml-course-hse/blob/master/2020-spring/seminars/sem19-knn.pdf)|  ¯\\\_(ツ)\_/¯ |
| 4 октября | Семинар 4 | Sklearn и особенности линейной регрессии | [Ноутбук](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/seminars/sem02-sklearn-linregr.ipynb) | [Прак.2 Линейная регрессия, исследовательский анализ данных](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/homework-practice/homework-practice-02-linregr.ipynb) |
| 11 октября | Семинар 5 | Векторное дифференцирование | [Хороший cheat sheet по дифференцированию](https://github.com/mmp-mmro-team/mmp_mmro_fall_2020/blob/master/seminars/sem05_vect_matrix_diff.pdf) | ¯\\\_(ツ)\_/¯ |
| 18 октября | Семинар 6 | Логистическая регрессия: оценивание вероятностей и вывод функционала | [Семинар (раздел 1)](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/lecture-notes/lecture05-linclass.pdf) | [Теор.1 Матричное дифференцирование](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/homework-theory/matr_diff.pdf) |
| 25 октября | Семинар 7 | Условная оптимизация, теорема ККТ | <ul><li>[Семинар](https://github.com/esokolov/ml-course-hse/blob/master/2020-spring/seminars/sem13-kkt.pdf)</li><li>[Заметки о решении задачи условной оптимизации](https://raw.githubusercontent.com/mmp-mmro-team/mmp_mmro_fall_2019/master/lecture-notes/Sem11_conditional_optimization.pdf)</li><ul> | ¯\\\_(ツ)\_/¯  |
| 1 ноября | Семинар 8 | Ядровые обобщения методов, задачи на ядра | [Семинар](https://github.com/esokolov/ml-course-hse/blob/master/2020-spring/seminars/sem14-kernels.pdf) | [Прак.3 SVM и логистическая регрессия](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/homework-practice/hw-practice-03-svm-linclass.ipynb)  | 
| 8 ноября | Семинар 9 | Метрики качества классификации, задачи на площади под кривыми | [Семинар](https://github.com/esokolov/ml-course-hse/blob/master/2021-fall/seminars/sem05-linclass-metrics.pdf) | ¯\\\_(ツ)\_/¯ |
| 15 ноября | Семинар 10 | Вывод критериев информативности для деревьев, разглядывание картинок про деревья | <ul><li>[Семинар](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/seminars/sem07-trees.pdf)</li><li>[Ноутбук](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/seminars/sem07-trees.ipynb)</li></ul>| ¯\\\_(ツ)\_/¯ |
| 22 ноября | Семинар 11 | Разложение ошибки на смещение и разброс | [Семинар](https://github.com/esokolov/ml-course-hse/blob/master/2020-fall/lecture-notes/lecture08-ensembles.pdf) | [Прак.4 BVD + град. бустинг](https://github.com/mmp-mmro-team/mmp_mmro_fall_2021/blob/main/homework-practice/hw-practice-4.ipynb) |
   

   

