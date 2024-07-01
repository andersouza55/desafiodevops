1. Cluster Health:
Decisão de design: Este painel é uma linha simples que serve como um cabeçalho para os painéis de saúde do cluster. Ele não contém nenhum gráfico ou métrica, mas serve para organizar o dashboard e facilitar a navegação.
Consideração de performance: Como é apenas um cabeçalho, não há impacto de performance.
2. Cluster Pod Usage:
Decisão de design: Este painel usa um gráfico "Singlestat" para mostrar a porcentagem de pods em uso no cluster. Ele usa cores para indicar diferentes níveis de uso, com verde para baixo uso, amarelo para uso médio e vermelho para alto uso.
Consideração de performance: O gráfico "Singlestat" é leve e rápido de carregar, pois ele exibe apenas um único valor. A consulta Prometheus é otimizada para retornar apenas a informação necessária, o que também contribui para a performance.
3. Cluster CPU Usage:
Decisão de design: Similar ao painel anterior, este painel usa um gráfico "Singlestat" para mostrar a porcentagem de CPU em uso no cluster. Ele também usa cores para indicar diferentes níveis de uso.
Consideração de performance: O gráfico "Singlestat" é leve e rápido de carregar, e a consulta Prometheus é otimizada para performance.
4. Cluster Memory Usage:
Decisão de design: Este painel usa um gráfico "Singlestat" para mostrar a porcentagem de memória em uso no cluster. Ele também usa cores para indicar diferentes níveis de uso.
Consideração de performance: O gráfico "Singlestat" é leve e rápido de carregar, e a consulta Prometheus é otimizada para performance.
5. Cluster Disk Usage:
Decisão de design: Este painel usa um gráfico "Singlestat" para mostrar a porcentagem de disco em uso no cluster. Ele também usa cores para indicar diferentes níveis de uso.
Consideração de performance: O gráfico "Singlestat" é leve e rápido de carregar, e a consulta Prometheus é otimizada para performance.
6. Cluster Pod Capacity:
Decisão de design: Este painel usa um gráfico de linhas para mostrar a capacidade de pods no cluster, incluindo a capacidade total, a capacidade alocada e a capacidade solicitada.
Consideração de performance: O gráfico de linhas é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento. A consulta Prometheus é otimizada para retornar apenas a informação necessária.
7. Cluster CPU Capacity:
Decisão de design: Este painel usa um gráfico de linhas para mostrar a capacidade de CPU no cluster, incluindo a capacidade total, a capacidade alocada e a capacidade solicitada.
Consideração de performance: O gráfico de linhas é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento. A consulta Prometheus é otimizada para retornar apenas a informação necessária.
8. Cluster Mem Capacity:
Decisão de design: Este painel usa um gráfico de linhas para mostrar a capacidade de memória no cluster, incluindo a capacidade total, a capacidade alocada e a capacidade solicitada.
Consideração de performance: O gráfico de linhas é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento. A consulta Prometheus é otimizada para retornar apenas a informação necessária.
9. Cluster Disk Capacity:
Decisão de design: Este painel usa um gráfico de linhas para mostrar a capacidade de disco no cluster, incluindo a capacidade total e a capacidade usada.
Consideração de performance: O gráfico de linhas é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento. A consulta Prometheus é otimizada para retornar apenas a informação necessária.
10. Deployments:
Decisão de design: Este painel usa uma tabela para mostrar o número de réplicas de cada deployment no cluster. Ele também mostra o número de réplicas atualizadas e o número de réplicas indisponíveis.
Consideração de performance: A tabela é configurada para exibir apenas os últimos dados, o que reduz o tempo de carregamento. A consulta Prometheus é otimizada para retornar apenas a informação necessária.
11. Node:
Decisão de design: Este painel contém vários gráficos "Singlestat" para mostrar informações sobre os nós do cluster, como o número de nós, o número de nós com falta de disco, o número de nós indisponíveis.
Consideração de performance: Os gráficos "Singlestat" são leves e rápidos de carregar, e as consultas Prometheus são otimizadas para performance.
12. Pods:
Decisão de design: Este painel contém vários gráficos "Singlestat" para mostrar informações sobre os pods no cluster, como o número de pods em execução, o número de pods pendentes, o número de pods com falha, o número de pods com sucesso e o número de pods desconhecidos.
Consideração de performance: Os gráficos "Singlestat" são leves e rápidos de carregar, e as consultas Prometheus são otimizadas para performance.
13. Containers:
Decisão de design: Este painel contém vários gráficos "Singlestat" para mostrar informações sobre os containers no cluster, como o número de containers em execução, o número de containers em espera, o número de containers encerrados e o número de reinicializações de containers nos últimos 30 minutos.
Consideração de performance: Os gráficos "Singlestat" são leves e rápidos de carregar, e as consultas Prometheus são otimizadas para performance.
14. Jobs:
Decisão de design: Este painel contém vários gráficos "Singlestat" para mostrar informações sobre os jobs no cluster, como o número de jobs com sucesso, o número de jobs ativos e o número de jobs com falha.
Consideração de performance: Os gráficos "Singlestat" são leves e rápidos de carregar, e as consultas Prometheus são otimizadas para performance.