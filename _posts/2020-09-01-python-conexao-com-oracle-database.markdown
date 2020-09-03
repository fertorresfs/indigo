# Usando o Python com o Oracle Database 11g

## Criando o arquivo

`$ python connect.py`

### Escrevendo o código

```
import cx_Oracle

uid = "seu_usuario_oracle"
pwd = "sua_senha_oracle"
db = "nome_conf_do_banco"

con = cx_Oracle.connect(uid+"/"+pwd+"@"+db)
con.close()
```
