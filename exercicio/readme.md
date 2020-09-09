# Exercícios:

## 1) Execute uma consulta SQL ao banco de dados survey e retorne os resultados em um dataframe pandas (select * from person)

Conexão com mysql

```
import MySQLdb

db = MySQLdb.connect(host="127.0.0.1",    
                     user="silvio",         
                     passwd="1234",  
                     db="db1")       

cnx = db.cursor()

```

```
import pandas as pd

df = pd.read_sql_query("select * from person", cnx)
df
```
