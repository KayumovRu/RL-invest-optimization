
# Portfolio Optimization using Reinforcement Learning

HSE Project,
Ruslan Kayumov

## О чем работа?

Исследование и разработка сервиса для перебалансировки инвестиционного портфеля с использованием методов глубокого обучения с подкреплением (DRL).

Инвестиционные активы: акции, облигации, валюты, криптовалюты, золото


## Результаты

* Исследованы DRL-алгоритмы, протестирована модели глбуокого обучения с подкреплением, отобрана модель DDPG
* Реализованный сервис - [Portfolio_optimize](https://github.com/KayumovRu/Portfolio_optimize)

## Ход работы
* Исследование существующего опыта
* Отбор базовых моделей
* MVP-эксперимент - отбор DRL-моделей с помощью фреймворка FinRL из списка: A2C, PPO, DDPG
* Финальный эксперимент - нативная имплментация (без использования фреймворков) отобранной модели DDPG и сравнение ее с базовыми моделями
* Реализация сервиса на стэке: FastAPI, Streamlit, PostgressSQL

## Важные файлы

* /REVIEWS - промежуточные отчеты
* /NOTEBOOKS    
	* Разведочный анализ - [download_and_EDA.ipynb](https://github.com/KayumovRu/RL-invest-optimization/blob/master/notebooks/download_and_EDA.ipynb)
	* Ребалансировка по Марковицу со скользящим окном - [Markowitz_rebalance.ipynb](https://github.com/KayumovRu/RL-invest-optimization/blob/master/notebooks/Markowitz_rebalance.ipynb)
	* Проведение эксперимента MVP - [FinRL_02_tests.ipynb](https://github.com/KayumovRu/RL-invest-optimization/blob/master/notebooks/FinRL_02_tests.ipynb)
    * Результаты эксперимента MVP - [FinRL_03_mvp_results.ipynb](https://github.com/KayumovRu/RL-invest-optimization/blob/master/notebooks/Markowitz_rebalance.ipynb)

