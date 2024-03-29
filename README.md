# Определение возраста покупателей
  * [Описание исследования](#Описание-исследования)
  * [Общий вывод](#Общий-вывод)
## Описание исследования
Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей.<br>
Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:<br>
- Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
- Контролировать добросовестность кассиров при продаже алкоголя.

## Общий вывод
* Испоьзовалась предобученная модель ResNet50, можно улучшить, подобрав более подходящий слой pooling или немного увеличив количество эпох.
* Процесс обучения не занял много времени.
* Тестовое MAE — 6.5959 — проходит порог качества (< 8).
* Ошибка модели в среднем на 6.6 лет подойдёт для решения поставленной задачи, так как нам надо вычислить возрастную группу, а не точный возраст.
***
_Работа над проектом велась в PyCharm 2021.3.2 (Professional Edition)_<br>
_формат ячеек Markdown различается в веб-версии и в PyCharm_