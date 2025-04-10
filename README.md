# 📊 Анализ фильмов: данные ivi и Кинопоиска

## О проекте

Этот проект был выполнен в рамках курса **"Введение в открытые данные"** и посвящён анализу данных о фильмах с платформ **ivi** и **Кинопоиск**. Основная цель — исследовать характеристики фильмов, провести сравнение платформ и выявить инсайты с помощью визуализации и предобработки данных. Данные получены двумя способами: неофициальный API Кинопоиска api.kinopoisk.dev и постраничный html парсинг BeautifulSoup.

## 📁 Структура проекта

- `df_ivi_films.csv` — исходный набор данных с ivi  
- `films_df_cleaned.csv` — очищенный и предобработанный датафрейм  
- `films_df_exploded.csv` — датасет, в котором фильмы с несколькими режиссерами продублированы отдельно для каждого режиссера
- `ivi_final.csv` / `kp_final.csv` — финальные таблицы для анализа по платформам  
- `Итоговый_проект_Введение_в_открытые_данные.ipynb` — Jupyter Notebook с кодом, визуализациями и выводами  

## 🔍 Что сделано

- Объединение и очистка данных из разных источников  
- Анализ жанров, рейтингов, продолжительности и других параметров  
- Сравнение платформ по количеству фильмов, популярности и оценкам  
- Построение визуализаций с помощью `matplotlib`,  `seaborn`  и   `plotly`

## 🛠️ Используемые технологии

- Jupyter Notebook  
- Библиотеки:  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`
  - `plotly`
  - `requests`
  - `BeautifulSoup`
  - `tqdm`
  - `time`

## 🚀 Установка и запуск

1. Клонируйте репозиторий:

```bash
git clone https://github.com/yourusername/film-analysis.git
cd film-analysis
```

2. Установите зависимости (рекомендуется использовать виртуальное окружение):

```bash
pip install -r requirements.txt
```

> Если файла `requirements.txt` нет, используйте ручную установку:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Запустите Jupyter Notebook:

```bash
jupyter notebook
```

4. Откройте файл `Итоговый_проект_Введение_в_открытые_данные.ipynb` и выполните ячейки.

## 📌 Выводы

Проект будет полезен начинающим продюсерам, поможет понять, какого режиссера можно позвать на фильм, чтобы получить наибольшее внимание зрителя. 
В потенциале проект можно развивать, добавляя также оценки кассовых сборов и прочие бизнесовые метрики

## 🧠 Автор

Проект выполнен в рамках обучения и анализа открытых данных.  
Если у вас есть предложения или вопросы — буду рада обратной связи!
