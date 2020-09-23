## Requirements

Python 3.7 or later with the following `pip3 install -U -r requirements.txt` packages:

numpy >= 1.18.2
pandas >= 1.0.3
torch >= 1.4.0
transformers >= 2.8.0

Убедитесь что уже установлена и работает `CUDA`

## О работе:

- Обучение модели (`Train_model.ipynb`) производилось на Google Colaboratory, если достаточно мощная видеокарта, можно запустить GPU локальной машины
- Используется многоязыковая модель `BERT-base` с предобученными весами из библиотеки `transformers`

## Перед запуском `Test_model.ipynb`

[Скачиваем](https://drive.google.com/file/d/1nGDOjb2Gj8Wi6BRFw2MeQwNtLpsV_48Z/view?usp=sharing) и распаковываем 'best_model_state.zip' в папку Model

## Результат работы моделе на тестовой выборке:

```bash
Test_out.csv
```
