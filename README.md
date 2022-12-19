# Портфолио по машинному обучению

__Описание проекта__

В данном репозитории собраны одни из способов решения заданий при изучении курса машинное обучение. При решении задач использовались разные библиотеки и приемы, которые были изучены в рамках курса. Решение заданий помогают закрепить полученные знания по каждому из разделов обучения.

__Структура репозитория__

В репозитории представленные следующие файлы:
1. Курсовой проект -  Рассчитать данные по энергопотреблению.ipynb 
В данном файле отражен способ решения задания с поставленной задачей следующего содержания:

Загрузите данные и посчитайте модели линейной регрессии для 50 зданий по ансамблю регрессионных моделей: в первой модели весь оптимальный набор метеорологических данных, во второй - дни недели и праздники, в третьей - недели года, в четвертой - месяцы. Финальное значение показателя рассчитайте как взвешенное арифметическое среднее показателей всех моделей, взяв веса для первой и второй модели как 3/8, а для третьей и четвертой - как 1/8.

Загрузите данные решения, посчитайте значение энергопотребления для требуемых дат для тех зданий, которые посчитаны в модели, и выгрузите результат в виде CSV-файла (submission.csv).

Поставленная задача была разбита на более мелкие подзадачи и решена поэтапно. 

Файл решения находится в формате ipynb, что позволило как поэтапно решать ее, так и внести все необходимые прояснения к методам решения. 

__Запуск проекта__

Чтобы запустить проект необходимо воспользоваться программой Jupyter notebook. Предварительно установив Python версии 3. Также можно воспользоваться программой VS Code, которая без проблем понимает формат ipynb, а также любой другой средой разработки Python, но совместимость не гарантируется. Установить дополнительные библиотеки, которые используются в примерах решения, их можно установить через консоль по команде pip install “Название модуля”.

__Зависимости__

В процессе выполнения заданий дополнительно могут потребоваться следующие библиотеки: numpy, pandas, sklearn, scipy, os. 