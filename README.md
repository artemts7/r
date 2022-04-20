# Слепое тестирование, Стоун
Для запуска можно установить и переключиться на пустое виртуальное окружение:

``` 
python -m venv venv 
source venv/bin/activate
```

#### Не забыть при этом отключить другие окружение (e.g. conda deactivate)
 
Далее установить необходимые зависимости командой
```
pip install -r requirements.txt
```

Информация о том, как устроен скрипт доступна при его вызове следующей командой:
```
python predict.py -h
```

Например:
```
python predict.py data/data_for_blind_testing.xlsx
python predict.py --flag_metrics --path_output 'predictions_full_dataset.xlsx' data/data_2017_2020.xlsx
```