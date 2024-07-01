1. Visão Geral (Overview):
Status do Nó (Node Status): Um painel "Stat" que mostra o status de cada nó (UP ou DOWN).
Decisão de design: Usar um painel "Stat" para uma visão rápida e fácil de entender do status dos nós.
Consideração de performance: A consulta Prometheus é otimizada para ser rápida e eficiente.
Rastreamento de Status (Status Trace): Um painel "State Timeline" que mostra o histórico de status de cada nó.
Decisão de design: Usar um painel "State Timeline" para visualizar o histórico de status dos nós e identificar possíveis problemas.
Consideração de performance: O painel "State Timeline" é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento.
Tráfego Total da Rede (Total Network Traffic): Um gráfico de pizza que mostra o tráfego total da rede de cada nó.
Decisão de design: Usar um gráfico de pizza para visualizar a proporção do tráfego de rede de cada nó.
Consideração de performance: O gráfico de pizza é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento.
Gráfico de Transferência de Bytes Total (WAN Transfer Bytes Total): Um gráfico de linhas que mostra o tráfego de rede total de cada nó.
Decisão de design: Usar um gráfico de linhas para visualizar o tráfego de rede total de cada nó ao longo do tempo.
Consideração de performance: O gráfico de linhas é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento.
Tempo de Funcionamento (Uptime): Um painel "Stat" que mostra o tempo de funcionamento de cada nó.
Decisão de design: Usar um painel "Stat" para uma visão rápida e fácil de entender do tempo de funcionamento dos nós.
Consideração de performance: A consulta Prometheus é otimizada para ser rápida e eficiente.
CPU Ocupada (CPU Busy): Um painel "Gauge" que mostra a porcentagem de CPU ocupada de cada nó.
Decisão de design: Usar um painel "Gauge" para visualizar a porcentagem de CPU ocupada de cada nó em tempo real.
Consideração de performance: O painel "Gauge" é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento.
RAM Usada (Used RAM Memory): Um painel "Bar Gauge" que mostra a porcentagem de RAM usada de cada nó.
Decisão de design: Usar um painel "Bar Gauge" para visualizar a porcentagem de RAM usada de cada nó em tempo real.
Consideração de performance: O painel "Bar Gauge" é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento.
Gráfico de Transferência de Bytes Total (VPN Transfer Bytes Total): Um gráfico de linhas que mostra o tráfego de rede total de cada nó.
Decisão de design: Usar um gráfico de linhas para visualizar o tráfego de rede total de cada nó ao longo do tempo.
Consideração de performance: O gráfico de linhas é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento.
Gráfico de Transferência de Bytes Total (LAN Transfer Bytes Total): Um gráfico de linhas que mostra o tráfego de rede total de cada nó.
Decisão de design: Usar um gráfico de linhas para visualizar o tráfego de rede total de cada nó ao longo do tempo.
Consideração de performance: O gráfico de linhas é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento.
Clientes WiFi (WIFI Clients): Um painel "Stat" que mostra o número de clientes WiFi conectados a cada nó.
Decisão de design: Usar um painel "Stat" para uma visão rápida e fácil de entender do número de clientes WiFi conectados a cada nó.
Consideração de performance: A consulta Prometheus é otimizada para ser rápida e eficiente.
Núcleos da CPU (CPU Cores): Um painel "Stat" que mostra o número de núcleos da CPU de cada nó.
Decisão de design: Usar um painel "Stat" para uma visão rápida e fácil de entender do número de núcleos da CPU de cada nó.
Consideração de performance: A consulta Prometheus é otimizada para ser rápida e eficiente.
RAM Total (Total RAM): Um painel "Stat" que mostra a quantidade total de RAM de cada nó.
Decisão de design: Usar um painel "Stat" para uma visão rápida e fácil de entender da quantidade total de RAM de cada nó.
Consideração de performance: A consulta Prometheus é otimizada para ser rápida e eficiente.
Rastreamento de Tráfego de Rede (Network Traffic Trace (MB)): Um painel "State Timeline" que mostra o histórico de tráfego de rede de cada nó.
Decisão de design: Usar um painel "State Timeline" para visualizar o histórico de tráfego de rede dos nós e identificar possíveis problemas.
Consideração de performance: O painel "State Timeline" é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento.
Qualidade do WiFi (Wifi Quality): Um painel "Stat" que mostra a qualidade média do sinal WiFi de cada nó.
Decisão de design: Usar um painel "Stat" para uma visão rápida e fácil de entender da qualidade média do sinal WiFi de cada nó.
Consideração de performance: A consulta Prometheus é otimizada para ser rápida e eficiente.
Arquiteturas (Architectures): Um painel "Stat" que mostra a arquitetura de cada nó.
Decisão de design: Usar um painel "Stat" para uma visão rápida e fácil de entender da arquitetura de cada nó.
Consideração de performance: A consulta Prometheus é otimizada para ser rápida e eficiente.
2. CPU e Memória (CPU Memory):
Gráfico Básico da CPU (CPU Basic ($node)): Um gráfico de linhas que mostra o uso da CPU de cada nó.
Decisão de design: Usar um gráfico de linhas para visualizar o uso da CPU de cada nó ao longo do tempo.
Consideração de performance: O gráfico de linhas é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento.
Gráfico Básico da Memória (Memory Basic ($node)): Um gráfico de linhas que mostra o uso da memória de cada nó.
Decisão de design: Usar um gráfico de linhas para visualizar o uso da memória de cada nó ao longo do tempo.
Consideração de performance: O gráfico de linhas é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento.
3. Network Traffic
Network Traffic by Bytes. Ele é um gráfico de linhas que mostra o tráfego de rede de cada nó em bytes.
Decisão de design: Usar um gráfico de linhas para visualizar o tráfego de rede de cada nó ao longo do tempo, com a opção de exibir os dados em bytes.
Consideração de performance: O gráfico de linhas é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento.
Receive Bytes Total
Decisão de design: Usar um gráfico de linhas para visualizar a quantidade total de bytes recebidos por cada nó ao longo do tempo.
Consideração de performance: O gráfico de linhas é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento.
Transmit Bytes Total
Decisão de design: Usar um gráfico de linhas para visualizar a quantidade total de bytes transmitidos por cada nó ao longo do tempo.
Consideração de performance: O gráfico de linhas é configurado para exibir apenas os últimos dados, o que reduz o tempo de carregamento.