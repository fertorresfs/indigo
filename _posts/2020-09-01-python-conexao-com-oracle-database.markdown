# Usando o Python com o Oracle Database 11g

## Criando o arquivo

$ python connect.py

### Escrevendo o código

`
import cx_Oracle
    con = cx_Oracle.connect('root/root@127.0.0.1/orcl')
  print con.version
    con.close()
`
