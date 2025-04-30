Análise de Logs do PostgreSQL

Durante a implementação da observabilidade, os logs foram configurados para exibir informações como conexões, consultas executadas e eventos de erro.

Exemplos de análise

Conexão ao banco
```log
2025-04-30 12:00:00.000 UTC [32] LOG:  connection received: host=172.19.0.1 port=5432
```

Execução de query
```log
2025-04-30 12:00:05.000 UTC [32] LOG:  statement: SELECT * FROM exemplo;
```


