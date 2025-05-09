# 🛒 A/B-тестирование гипотез для увеличения выручки интернет-магазина (Yandex.Practicum project).

---

## 📌 Описание проекта  
Анализ приоритизированных маркетинговых гипотез и проведение A/B-теста для увеличения выручки крупного интернет-магазина. В проекте использованы методы аналитики, визуализации и статистической проверки значимости.

## 🎯 Цель исследования  
Оценить и упорядочить гипотезы по приоритету, провести A/B-тест, выявить значимые изменения в пользовательском поведении и предложить решения для роста бизнеса.

## 🔍 Ход исследования

### 1. Загрузка и предобработка данных:
- загрузка таблиц с гипотезами и результатами теста;
- корректировка форматов и проверка на пропуски и дубликаты.

### 2. Приоритизация гипотез:
- расчёт ICE и RICE приоритетов;
- анализ различий между методами и вывод ключевых гипотез.

### 3. A/B-тестирование:
- построение графиков кумулятивных метрик: выручка, средний чек, конверсия;
- выявление аномалий, расчёт 95-го и 99-го перцентилей;
- анализ «сырых» и «очищенных» данных (без выбросов).

### 4. Статистическая проверка гипотез:
- проверка значимости различий между группами по среднему чеку и количеству заказов;
- принятие решения по результатам A/B-теста.

## ✅ Общий вывод  
Конверсия в группе B была стабильно выше на 13%, несмотря на незначительное снижение среднего чека. Аномалии повлияли на данные, но после очистки тенденции сохранились. Рекомендуется зафиксировать победу группы B и реализовать изменения, повышающие конверсию.

---

### 🛠 Используемые библиотеки

`pandas`, `numpy`, `matplotlib`, `scipy`

📘 [Открыть ноутбук проекта](https://github.com/AlexEgorova/da-projects/blob/main/Выручка%20интернет-магазина%20(АВ-тест)/da-business-decision-ishop.ipynb)
