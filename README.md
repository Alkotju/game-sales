# Video Game Sales Analysis

## Overview
This repository contains a Jupyter Notebook for analyzing video game sales data. The dataset includes information about sales across various platforms and regions, providing insights into trends, platform popularity, and regional preferences.

## Repository Contents
- **`LICENSE`**: Project license file.
- **`README.md`**: This file with instructions and project description.
- **`vgsales-12-4-2019-short.csv`**: CSV file containing video game sales data.
- **`vgsales.ipynb`**: Main notebook containing code for data analysis and visualization.

## Features
- Data preprocessing and cleaning.
- Statistical analysis of sales data.
- Visualization of trends and findings, including:
  - Best-selling games by platform.
  - Sales distribution by genre.
  - Yearly trends in video game sales.

## Requirements
To run the notebook, ensure you have:
- Python 3.7 or higher
- Jupyter Notebook
- The following Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn

## Setup Instructions
1. Download the repository contents.
2. Ensure Jupyter Notebook is installed on your computer.
3. Install the required Python libraries if not already installed:
   ```bash
   pip install pandas numpy matplotlib seaborn ipywidgets
   ```
4. Open Jupyter Notebook and load the `vgsales.ipynb` file.
5. Execute the code blocks sequentially, starting from the first cell, to set up the environment and load data from `vgsales-12-4-2019-short.csv`.

## Usage
1. Load the `vgsales-12-4-2019-short.csv` dataset provided in the repository (or your own dataset with a similar structure).
2. Follow the steps outlined in the **`vgsales.ipynb`** to process and analyze the data.
3. Customize the analysis and visualizations as needed to achieve your goals.

## Dataset
The analysis is designed to work with datasets structured similarly to [the video game sales dataset on Kaggle](https://www.kaggle.com/code/kerneler/starter-video-games-sales-2019-7e3189f9-4/input).

### Example Dataset Structure:

| Rank | Name                | Genre       | ESRB_Rating | Platform | Publisher | Developer     | Critic_Score | User_Score | Total_Shipped | Global_Sales | NA_Sales | PAL_Sales | JP_Sales | Other_Sales | Year |
|------|---------------------|-------------|-------------|----------|-----------|---------------|--------------|------------|----------------|--------------|----------|-----------|----------|-------------|------|
| 1    | Wii Sports          | Sports      | E           | Wii      | Nintendo  | Nintendo EAD  | 7.7          |  | 82.86          |     |   |   |   |     | 2006 |
| 2    | Super Mario Bros.   | Platform    |     | NES      | Nintendo  | Nintendo EAD  | 10.0         |  | 40.24          |     |   |   |   |     | 1985 |
| 44    | Halo 3   | Shooter    |  M   | X360      | Microsoft Game Studios  | Bungie Studios  | 9.6         | 9.5 | 14.5          |     |   |   |   |     | 2007 |
| 98    | Call of Duty: Black Ops IIII  | Shooter    | M   | PS4      | Activision  | Treyarch  |          |  |           | 9.32   | 4.05 | 3.28 | 0.5 | 1.49   | 2018 |

## Contribution
Suggestions and improvements are welcome! If you have ideas, please:
1. Fork the repository.
2. Create a new branch.
3. Submit a pull request with a detailed description of your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The original dataset was provided by Kaggle.
- Libraries used: pandas, numpy, matplotlib, seaborn.

---
If you have any questions or issues, please create an issue in this repository or contact the administrator directly via email:
- daniil.yanchuk@ivkhk.ee
- aleksandra.kotjuzinskaja@ivkhk.ee




# Анализ Продаж Видеоигр

## Обзор
Этот репозиторий содержит Jupyter Notebook для анализа данных о продажах видеоигр. Данные включают информацию о продажах на различных платформах и в разных регионах, предоставляя информацию о тенденциях, популярности платформ и региональных предпочтениях.

## Содержимое репозитория
- **`LICENSE`**: Файл лицензии проекта.
- **`README.md`**: Этот файл с инструкциями и описанием проекта.
- **`vgsales-12-4-2019-short.csv`**: CSV-файл с данными о продажах видеоигр.
- **`vgsales.ipynb`**: Основной файл, содержащий код для анализа и визуализации данных.

## Возможности
- Предварительная обработка и очистка данных.
- Статистический анализ данных о продажах.
- Визуализация тенденций и выводов, включая:
  - Самые продаваемые игры по платформам.
  - Распределение продаж по жанрам.
  - Ежегодные тенденции в продажах видеоигр.

## Необходимые компоненты
Для запуска убедитесь, что у вас установлено:
- Python 3.7 или выше
- Jupyter Notebook
- Необходимые библиотеки Python:
  - pandas
  - numpy
  - matplotlib
  - seaborn

## Инструкции по настройке
1. Скачайте содержимое репозитория.
2. Убедитесь, что на вашем компьютере установлен Jupyter Notebook.
3. Установите необходимые библиотеки Python, если они ещё не установлены:
   ```bash
   pip install pandas numpy matplotlib seaborn ipywidgets
   ```
4. Откройте Jupyter Notebook и загрузите файл `vgsales.ipynb`.
5. Выполните блоки кода по порядку, начиная с первых ячеек, чтобы настроить окружение и загрузить данные из файла `vgsales-12-4-2019-short.csv`.

## Использование
1. Загрузите набор данных `vgsales-12-4-2019-short.csv`, который предоставлен в репозитории (или свой собственный набор данных с аналогичной структурой).
2. Следуйте шагам, описанным в **`vgsales.ipynb`**, чтобы обработать и проанализировать данные.
3. Настраивайте анализ и визуализации по мере необходимости для достижения ваших целей.

## Набор данных
Анализ рассчитан на работу с наборами данных, структурированными аналогично [набору данных о продажах видеоигр на Kaggle](https://www.kaggle.com/code/kerneler/starter-video-games-sales-2019-7e3189f9-4/input).

### Пример структуры набора данных:

| Rank | Name                | Genre       | ESRB_Rating | Platform | Publisher | Developer     | Critic_Score | User_Score | Total_Shipped | Global_Sales | NA_Sales | PAL_Sales | JP_Sales | Other_Sales | Year |
|------|---------------------|-------------|-------------|----------|-----------|---------------|--------------|------------|----------------|--------------|----------|-----------|----------|-------------|------|
| 1    | Wii Sports          | Sports      | E           | Wii      | Nintendo  | Nintendo EAD  | 7.7          |  | 82.86          |     |   |   |   |     | 2006 |
| 2    | Super Mario Bros.   | Platform    |     | NES      | Nintendo  | Nintendo EAD  | 10.0         |  | 40.24          |     |   |   |   |     | 1985 |
| 44    | Halo 3   | Shooter    |  M   | X360      | Microsoft Game Studios  | Bungie Studios  | 9.6         | 9.5 | 14.5          |     |   |   |   |     | 2007 |
| 98    | Call of Duty: Black Ops IIII  | Shooter    | M   | PS4      | Activision  | Treyarch  |          |  |           | 9.32   | 4.05 | 3.28 | 0.5 | 1.49   | 2018 |


## Вклад
Приветствуются предложения и улучшения! Если у вас есть идеи, пожалуйста:
1. Сделайте форк репозитория.
2. Создайте новую ветку.
3. Отправьте pull request с подробным описанием ваших изменений.

## Лицензия
Этот проект лицензирован под лицензией MIT. Подробнее см. в файле [LICENSE](LICENSE).

## Источники
- Исходный набор данных предоставлен Kaggle.
- Используемые библиотеки: pandas, numpy, matplotlib, seaborn.

---
Если у вас есть вопросы или предложения, пожалуйста, создайте issue в этом репозитории или свяжитесь с нами напрямую через электронную почту daniil.yanchuk@ivkhk.ee или aleksandra.kotjuzinskaja@ivkhk.ee .


