# Анализ и прогнозирование рейтинга отелей

Данный проект посвящён анализу данных об отелях и построению модели для прогнозирования рейтинга на основе отзывов гостей. Работа выполнена в Jupyter Notebook: [EDA+FE_Project-3.ipynb](EDA+FE_Project-3.ipynb).

## Содержание

- [Исследование данных](#исследование-данных)
- [Создание новых признаков](#создание-новых-признаков)
- [Кодирование категориальных признаков](#кодирование-категориальных-признаков)
- [Анализ мультиколлинеарности](#анализ-мультиколлинеарности)
- [Общий вывод](#общий-вывод)

## Краткое описание этапов

### [Исследование данных](#исследование-данных)
Проведена первичная обработка данных: проверка на пропуски, дубликаты, анализ структуры и распределения признаков.

### [Создание новых признаков](#создание-новых-признаков)
Добавлены новые признаки, отражающие сезонность, страну, национальность, особенности поездки, длительность проживания и др., что позволило расширить исходные данные и повысить качество модели.

### [Кодирование категориальных признаков](#кодирование-категориальных-признаков)
Категориальные признаки были закодированы с помощью one-hot, порядкового и меточного кодирования для корректной работы моделей машинного обучения.

### [Анализ мультиколлинеарности](#анализ-мультиколлинеарности)
Проведён анализ взаимосвязей между признаками, удалены избыточные и скоррелированные признаки для повышения устойчивости модели.

### [Общий вывод](#общий-вывод)
Построена и обучена модель прогнозирования рейтинга отелей, проведена оценка её качества. Полученные результаты показывают, что созданные признаки вносят вклад в объяснение вариации рейтингов, а подход может быть использован для дальнейшего улучшения сервиса и персонализации предложений для клиентов гостиничного бизнеса.

---

Для подробностей см. ноутбук: [EDA+FE_Project-3.ipynb](EDA+FE_Project-3.ipynb)