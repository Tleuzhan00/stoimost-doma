Проект очень простой, учим как предугадывать цены на жилье
Модель весит 132 мб, поэтому я его не добавил
from sklearn.datasets import fetch_california_housing
import pandas as pd

# Загружаем данные
housing = fetch_california_housing(as_frame=True)

# Таблица с данными
df = housing.frame

df.head()

<img width="831" height="194" alt="1" src="https://github.com/user-attachments/assets/43a3cd23-d3c6-48ca-bd47-f74d7f895031" />
Вычисляем сколько строк и столбцов. Далее разделяем данные

<img width="722" height="519" alt="2" src="https://github.com/user-attachments/assets/757d6977-38cb-4fce-aea7-1f6e554bae72" />

Далее обучаем и оцениваем качества модели (0,32 это 32 000 доллоров )

<img width="585" height="539" alt="3" src="https://github.com/user-attachments/assets/1fc2076f-ab16-4d39-93bc-790f81cfa4ca" />

и Сохраняем модель

<img width="682" height="268" alt="5" src="https://github.com/user-attachments/assets/3cec8fa7-4b0b-4c66-96d7-55f3d3d06fec" />
