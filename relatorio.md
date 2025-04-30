 Relatório Técnico – Observabilidade com PostgreSQL no Docker

Decisões Tomadas
- Utilizamos Prometheus para coleta de métricas e Grafana para visualização.
- Escolhemos o postgres_exporter oficial da comunidade.
- Criamos um ambiente completo com Docker Compose.

Desafios Encontrados
- Conectar corretamente o exporter ao banco, respeitando a string de conexão.
- Garantir que os serviços estivessem visíveis na mesma rede Docker.

Lições Aprendidas
- Prometheus e Grafana se integram facilmente com PostgreSQL.
- Um ambiente com logs e métricas permite detectar problemas rapidamente.
- Docker facilita muito a criação e destruição do ambiente de testes.
