Анализ отзывов по детским площадкам для проверки гипотез и для открытия новых взаимосвязей

Первоначальные задачи:

1.Выявить гипотезы

2.Извлечь данные из открытых источников (карты Google, Яндекс, Youtube)

3.Кластеризация 

4.Выявление корреляций

5.Итоги.

Проблемы, возможности и решения выявленные в процессе:

1.Пол не указан в отзыве
Возможность: По имени и фамилии разбить по полу

2.Не со всех платформ есть возможность извлечь оценку
Возможность: Провести сентиментный анализ по тексту отзыва (обучение с учителем, разбиение на негативный, позитивный, нейтральный) 

3.Малая выборка для обучения
Решение: Выгрузить данные по паркам, как самые близкие по теме и обучать на них

4.Несбалансированность данных для обучения
	Решение: Выровнить данные, случайным выбором, по меньшему классу
	
5.Средняя точность на тестовой выборке, из-за близости позитивных с нейтральными и негативных с нейтральными, но на датасете с детскими площадками, показан хороший результат
	
Итоговые задачи: 
1.Извлечь данные из открытых источников (карты Google, Яндекс, Youtube)

2.Соединить отзывы. Разбить по полу по имени и фамилии 

3.Провести сентиментный анализ по отзывам на парки (обучение с учителем, разбиение на негативный, позитивный, нейтральный) 
3.1 Выровнять данные, случайным выбором, по меньшему классу
3.2 Применить обученную логистическую регрессию и обученную сеть на датасет

4.Анализ данных 

4.1 Кластеризация 

4.2 Выявление корреляций

4.3 Опровергнуть первоначальные гипотезы (опасения заказчиков), что:

1. Вода - всегда грязь

2. Сыпучее покрытие = грязь

3. Оборудование опасно для использования

4.4 Итоги
