- É o desempenho que um software possui para completar uma determinada carga
- As unidades de medida para vavailiarmos a perfomance de um software são:
	- Latência ou "response time"
	- Throughput
- Ter um software performático é diferente de ter um software escalável

## Métricas para medir performance

- Diminuindo latência
	- Normalmente medida em milliseconds
	- É afetada pelo tempo de processamento da aplicação, rede e chamadas externas
- Aumentando o throughput
	- Quantidade de requisições
	- Diretamente ligado à latência

## Principais razões para baixa performance

- Processamento ineficiente
- Recursos computacionais limitados
- Trabalhar de forma bloqueante
- Acesso serial a recursos

## Principais formas de aumentar a eficiência

- Escala de capacidade computacional (CPU, Disco, Memória, Rede)
- Lógica por trás do software (Algoritmos, queries, overhead de frameworks)
- Concorrência e paralelismo
- Banco de dados (tipos de bancos, schema)
- Caching

## Diferença entre concorrência e paralelismo

> *Concorrência é sobre lidar com muitas coisas ao mesmo tempo. Paralelismo é fazer muitas coisas ao mesmo tempo*
> - Rob Pike

## Caching

- Cache na borda / Edge Computing
- Dados estáticos
- Páginas web
- Funções internas
	- Evita reprocessamento de algoritmos pesados
	- Acesso ao banco de dados
- Objetos

### Exclusivo vs Compartilhado

- Exclusivo
	- Baixa latência
	- Duplicado entre os nós
	- Problemas relacionados a sessões
- Compartilhado
	- Maior latência
	- Não há duplicação
	- Sessões compartilhadas

## Caching vs Edge Computing

- Cache realizado mais próximo ao usuário
- Evita a requisição chegar até o Cloud Provider / Infra
- Normalmente arquivos estáticos
- CDN - Content Delivery Network
- Cloudflare Workers
- Vercel