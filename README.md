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

    'Город': ['Moscow', 'Saint-Petersburg', 'Novosibirsk', 'Krasnoyarsk']

df = pd.DataFrame(data)

selected_columns = ['Имя', 'Город']
result_df = df[selected_columns]
print(result_df)
22.01.25
import pandas as pd
x = int(input("введите строчку"))
y = int(input("введите столбец"))
df_exel = pd. read_exel('Книга1.exel')
print(df_exel.iloc[x,y])




25.12.24
1.
import pandas as pd
df_excel = pd.read_excel('dataset(5).xlsx')
print(df_excel.head(5))
2.
import pandas as pd
df_excel = pd.read_excel('dataset(5).xlsx')
print(df_excel.tail(5))
3.
import pandas as pd
df_excel = pd.read_excel('dataset(5).xlsx')
print(df_excel.sample(5))
4.
a=int(input("напишите номер строки"))
df_excel = pd.read_excel('dataset(5).xlsx')
print(df_excel)
22.01.25
import pandas as pd
x = int(input("введите строчку"))
y = int(input("введите столбец"))

df_exel = pd. read_exel('Книга1.exel')
print(df_exel.iloc[x,y])






