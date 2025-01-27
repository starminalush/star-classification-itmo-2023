## Классификатор звезд

## Постановка задачи
Бизнес-цель: реализовать модель для автоматической классификации звезд, галактик и квазаров по их признакам.

Постановка задачи ML: многоклассовая классификация.

Набор данных: [Sloan Digital Sky Survey DR14](https://www.kaggle.com/datasets/lucidlenn/sloan-digital-sky-survey)

## Метрика качества
Задача будет оцениваться по следующим метрикам:
ML:
 - precision
 - recall
 - F1
   
Это метрики, которые позволяют максимально правдоподобно оценить качество ML модели, так как:
 - precision покажет, как хорошо отделяются классы друг от друга
 - recall покажет способность находить класс вообще
 - f1 выступает как среднее гармоническое между precision и recall
