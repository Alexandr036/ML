# Портфолио по машинному обучению

__Описание проекта__

В данном репозитории собраны одни из способов решения заданий при изучении курса машинное обучение. При решении задач использовались разные библиотеки и приемы, которые были изучены в рамках курса. Решение заданий помогают закрепить полученные знания по каждому из разделов обучения.

__Структура репозитория__

В репозитории представленные следующие файлы:
1. Курсовой проект -  Рассчитать данные по энергопотреблению.ipynb 
В данном файле отражен способ решения задания с поставленной задачей следующего содержания:

* Загрузите данные и посчитайте модели линейной регрессии для 50 зданий по ансамблю регрессионных моделей: в первой модели весь оптимальный набор метеорологических данных, во второй - дни недели и праздники, в третьей - недели года, в четвертой - месяцы. Финальное значение показателя рассчитайте как взвешенное арифметическое среднее показателей всех моделей, взяв веса для первой и второй модели как 3/8, а для третьей и четвертой - как 1/8.

* Загрузите данные решения, посчитайте значение энергопотребления для требуемых дат для тех зданий, которые посчитаны в модели, и выгрузите результат в виде CSV-файла (submission.csv).

Поставленная задача была разбита на более мелкие подзадачи и решена поэтапно. 

2. Курсовой проект - Финальное решение - Ансамбль стекинга.ipynb 
В данном файле отражен способ решения задания с поставленной задачей следующего содержания:

* Загрузите данные, приведите их к числовым, заполните пропуски, нормализуйте данные и оптимизируйте память.

* Сформируйте параллельный ансамбль из CatBoost, градиентного бустинга, XGBoost и LightGBM. Используйте лучшие гиперпараметры, подобранные ранее, или найдите их через перекрестную проверку. Итоговое решение рассчитайте на основании самого точного предсказания класса у определенной модели ансамбля: выберите для каждого класса модель, которая предсказывает его лучше всего.

* Проведите расчеты и выгрузите результат в виде submission.csv

___В этой версии итоговое решение было рассчитано на основании весов (вероятностей) (с использованием np.argmax от вероятности класса каждой модели (ее собственной уверенности в том, какой это класс), что является не верным решением, так как в задании требуется "выберите для каждого класса модель, которая предсказывает его лучше всего".___

3. v 2 Курсовой проект - Финальное решение - Ансамбль стекинга.ipynb 
В данном файле отражен способ решения задания с поставленной задачей из предыдущего пункта. 

* Для определения модели с самым точным предсказанием для каждого класса, были построены матрицы неточности, чтобы визуально определить, какая модель, какие классы предсказывает лучше остальных, а так-же для проверки выводов, произведена перекрестная проверка по всем данным, которая подтвердила выводы которые были сделаны на основании матриц неточности.

4. Курсовой проект - Сегментация облаков по изображениям Fish.ipynb 
В данном файле отражен способ решения задания с поставленной задачей следующего содержания:

* Постройте сегментацию изображений облаков типа Fish, используя сети Unet, PSPNet или FPN. В качестве базовых сетей можно использовать ResNet, MobileNet, DenseNet или любые другие подходящие. Можно использовать обученные модели сетей (входные размеры 384х256).

* Постройте ансамбль предсказаний, выбирая среднее значение из нескольких. Выгрузите результаты предсказания в требуемом формате (sample_submission.csv).

5. Курсовой проект - Выделение факторов и предсказание.ipynb 
В данном файле отражен способ решения задания с поставленной задачей следующего содержания:

* Соберите случайный ансамбль из нескольких методов выделения факторов - корреляции, взаимной информации, важности признаков, главных компонент, независимых компонент и др. Получите не менее 3 наборов из 5 наиболее важных признаков.

* Соберите для каждого набора ансамбль стекинга для задачи, используя (но не ограничиваясь) решающими деревьями, CatBoost, линейной регрессией - всего не менее 3 ансамблей стекинга, каждый из которых состоит из большого числа разнородных моделей.

* Используя эти ансамбли, предскажите продолжительность жизни на 2019 год.

6. Курсовой проект - Прогноз срока экспозиции объявления 
В данной папке собран способ решения задания с поставленной задачей следующего содержания:
* Используя исходные или очищенные данные, сформируйте предсказание класса объявления из множества exposition_test.tsv.gz
В папке находятся файлы решения в формате ipynb, что позволило внести все необходимые прояснения к методам решения. 

7. Курсовой проект - Самостоятельный агент 
В данной папке собран способ решения задания с поставленной задачей следующего содержания:
* Выберите одно из окружение AI Gym - Classic Control или Box2D. Изучите действия агента в заданной среде. Постройте алгоритм машинного обучения с подкреплением, который решает поставленную задачу после нужного количества обучающих эпизодов.
В папке находятся файлы решения в формате ipynb, что позволило внести все необходимые прояснения к методам решения. 

__Файлы решения находится в формате ipynb, что позволило как поэтапно решать поставленную задачу, так и вносить все необходимые прояснения к методам решения.__

__Запуск проекта__

Для запуска любого из проектов необходимо воспользоваться программой Jupyter notebook. Предварительно установив Python версии 3. Установить дополнительные библиотеки, которые используются в примерах решения, их можно установить через консоль по команде pip install “Название модуля”.

__Зависимости__

В процессе выполнения заданий дополнительно могут потребоваться следующие библиотеки: numpy, pandas, sklearn, scipy, os, catboost, xgboost, lightgbm, keras, segmentation_models, sys