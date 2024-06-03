# Создание интерактивных мультфильмов/историй про животных.
Звуки животных представляют собой важный аспект в изучении биологии, экологии и поведения животных. Анализ звуков может помочь в понимании коммуникации среди животных, выявлении их местоположения, мониторинге популяций и т.д.
На основе разметки, структурирования и обогащения описаных ниже данных можно создавать системы для генерации историй/сказок/мультипликаций для детей

## Определение состава аннотационной схемы
### 1.1. Модальности.
* Текстовые описания [chatGPT.com](https://chat.openai.com) * Изображения [Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/animal-image-dataset-90-different-animals) * Аудио [Kaggle](https://www.kaggle.com/datasets/caoofficial/animal-sounds) * Текстовые произведения

### 1.2. Основные сущности, объекты или явления для аннотирования.
Текстовые описания:
Животные (именованные сущности)
Описание (атрибуты и характеристики животных)
Изображения:
Объекты (животные на изображениях)
Детали (особенности животных, детали окружающей среды)
Аудио:
Фрагменты (отдельные звуки животных)
Тип звука (пение, рычание, кукарекание и т.д.)
Текстовые произведения:
Сюжетные элементы
Герои (животные)
Локации

1.3. Таблица аннотационной схемы.
Модальность	Уровень 1	Уровень 2	Уровень 3
Текстовые описания	Именованная сущность	Атрибут/характеристика	Токен/слово
Изображения	Объект	Область	Деталь
Аудио	Фрагмент	Тип звука	Сегмент/подсегмент
Текстовые произведения	Сюжетный элемент	Герои	Локации

Шаг 2: Требования к аннотациям
2.1. Требования к аннотациям для каждой модальности.
Текстовые описания.
Именованные сущности:
Типы: Животные
Атрибуты: Название, Вид
Атрибут/характеристика:
Типы: Описание внешности, Среда обитания
Атрибуты: Цвет, Размер
Токен/слово:
Типы: Отдельные слова
Атрибуты: Часть речи, Лемма

Изображения
Объект:
Типы: Животные
Атрибуты: Вид
Деталь:
Типы: Особенности животных
Атрибуты: Шерсть, Перья, Рога

Аудио
Фрагмент:
Типы: Звуки животных
Атрибуты: Длительность, Частота
Тип звука:
Типы: Пение, Рычание, Кукарекание
Атрибуты: Интенсивность, Тональность

Текстовые произведения
Сюжетные элементы:
Типы: Введение, Завязка, Кульминация, Развязка
Атрибуты: Основные события, Конфликты
Герои:
Типы: Животные
Атрибуты: Название, Вид, Пол, Возраст, Роль в сюжете
Локации:
Типы: Места действия
Атрибуты: Название, Описание, Важность в сюжете

