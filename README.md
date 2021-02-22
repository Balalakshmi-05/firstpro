import pandas as pd

df=pd.read_csv('Documents\\titanic_original.csv')
print('age mean=',df['age'].mean())
print('age median=',df['age'].median())
femal=0
mal=0
print(df['sex'].value_counts())
print('no of died=',df['survived'].value_counts()[0])
print('total fares=',df['fare'].sum())
