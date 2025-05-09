# 🧾 Анализ пользовательского поведения и A/A/B-тестирование в мобильном приложении магазина продуктов питания (Yandex.Practicum project).

---

## 📌 Описание проекта  
Анализ логов событий пользователей мобильного приложения магазина продуктов питания. Построение воронки действий и проведение A/A/B-теста, направленного на выявление влияния изменения шрифта интерфейса на пользовательское поведение.

## 🎯 Цель исследования  
Оценить, как пользователи взаимодействуют с приложением, и выявить возможное влияние визуальных изменений на ключевые метрики вовлечённости и конверсии.

## 🔍 Ход исследования

### 1. Загрузка и предобработка данных:
- приведение типов, переименование столбцов, создание признаков даты и времени;
- анализ полноты данных и фильтрация по периоду.

### 2. Исследование пользовательской активности:
- расчёт количества событий и пользователей;
- анализ "выбросов", описание статистик активности;
- оценка влияния аномальных пользователей.

### 3. Построение воронки:
- выделение последовательности событий;
- расчёт конверсии между этапами;
- выявление ключевых точек оттока.

### 4. A/A/B-тест:
- проверка гипотез о различии между группами;
- расчёт статистической значимости по основным метрикам;
- интерпретация результатов эксперимента.

## ✅ Общий вывод  
Изменение шрифта в приложении не оказало статистически значимого влияния на поведение пользователей. При этом воронка показала, что основное количество пользователей отсекается уже на этапе перехода из главной страницы в каталог. Рекомендовано внести изменения в первый экран и изучить “тяжёлых” пользователей с высокой активностью.

---

### 🛠 Используемые библиотеки

`pandas`, `numpy`, `matplotlib`, `scipy`, `plotly`

📘 [Открыть ноутбук проекта](https://github.com/AlexEgorova/da-projects/blob/main/Потребительское%20поведение%20(AAB-тест)/da-AAB-behavour.ipynb)
