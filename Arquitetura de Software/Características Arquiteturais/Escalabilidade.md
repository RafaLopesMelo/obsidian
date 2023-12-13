Escalabilidade é a capacidade de sistemas suportarem o aumento (ou a redução) dos workloads incrementando (ou reduzindo) o custo em menor ou igual proporção.
# Escalabilidade Vs Performance

Enquanto performance tem o foco em reduzir a latência e aumentar o throughput, a escalabilidade visa termos a possibilidade de aumentar ou diminuir o thorughput adicionando ou removendo a capacidade computacional.
# Escalando Software - Descentralização

- Disco efêmero
- Servidor de aplicação vs Servidor de assets
- Cache centralizado
- Sessões centralizadas
- Upload/Gravação de arquivo

# Escalando banco de dados

- Aumento de recursos computacionais
- Distribuindo responsabilidades (escrita vs leitura)
- Shards de forma horizontal
- Serverless

## Otimização de queries e índices

- Trabalhe com índices de forma consciente
- APM (Application performance monitoring) nas queries
- EXPLAIN nas queries
- CQRS (Command Query Responsability Segregation)

# Proxy Reverso

Um proxy reverso é um servidor que fica na frente dos servidores web e encaminha as solicitações do cliente (por exemplo, navegador web) para esses servidores web.
## Soluções populares de Proxy Reverso

- Nginx
- HAProxy (HA = High Availability)
- Traefik