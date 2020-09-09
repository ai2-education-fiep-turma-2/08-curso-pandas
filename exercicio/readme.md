# Exercícios:

## 1) Execute uma consulta SQL ao banco de dados survey e retorne os resultados em um dataframe pandas (select * from person)

```
import pandas as pd

df = pd.read_sql_query("select * from person", cnx)
df
```
