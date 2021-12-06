[![Code style: black](/images/mkb.PNG)](https://github.com/psf/black)

# Задача хакатона
Спрогнозировать вероятность невыполнения
контракта поставщиком

# Описание 
Банковская гарантия — соглашение, по которому банк обязан выплатить долг клиента, если тот не выполнил своих обязательств. Выдача гарантий банком происходит после одобрения клиентской заявки.

Задача — построить аппликационную модель оценки вероятности предъявления по гарантии, чтобы минимизировать потери от кредитного риска. В качестве предикторов для моделирования используются анкетные данные клиента и его финансовые показатели.

Решения оцениваются по метрике ROC/AUC Score. Среди 10 лучших решений экспертная комиссия выберет трёх победителей.

# Метрика

Решения оцениваются по метрике ROC/AUC Score (англ. Area Under Curve, площадь под кривой) — площадь, ограниченная ROC-кривой и осью доли ложных положительных классификаций. wikipedia.org, scikit-learn.org. ROC-кривая – графичеcкая характеристика качества бинарного классификаторa.

# Оценка решений

Общий зачет будет проведен в 2 этапа:
* в отборочном этапе определятся топ-10 финалистов
* в финале экспертная комиссия выбирает победителей
При оценке решений ключевое значение отводится соответствию критериям, с помощью которых можно будет получить наиболее качественный и интерпретируемый прототип решения задачи.


# Результат 

[![Code style: black](/images/top_6.PNG)](https://github.com/psf/black)


# Решение 

[Смотри приложенный Jupyter Notebook](top_2_solution_Milenkin.ipynb)

