# home-work
home work
import pandas as pd


# Чтение Excel-файла
df_excel = pd.read_excel('Оценки (1).xlsx')

# Посмотреть первые 5 строк
print(df_excel.head())

# Посмотреть информацию о таблице
print(df_excel.info())


data = {'Имя': ['Ilia', 'Karina', Masha', 'Oleg'],
        'Возраст': [31, 52, 17, 15]}
df = pd.DataFrame(data)

print(df.tail(2))
