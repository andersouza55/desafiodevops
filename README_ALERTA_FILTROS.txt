Criando Alertas

Acesse a aba "Alerting" do seu dashboard: No menu lateral do Grafana, clique em "Alerting".
Crie um novo alerta: Clique no botão "New Alert" para criar um novo alerta.
Configure o alerta: Na tela de configuração do alerta, você precisa definir:
Nome do alerta: Dê um nome descritivo para o seu alerta.
Painel: Selecione o painel do dashboard que você quer monitorar.
Condição: Defina a condição que irá disparar o alerta. Você pode usar uma consulta Prometheus para definir a condição, por exemplo:

        sum(kube_pod_status_phase{namespace=~"$namespace", phase="Pending"}) > 10


Essa consulta irá disparar o alerta se o número de pods pendentes no namespace especificado for maior que 10.

Notificações: Defina como você quer ser notificado quando o alerta for disparado. Você pode escolher entre:

E-mail: Envie um e-mail para o seu endereço de e-mail.
Slack: Envie uma mensagem para um canal do Slack.
Alerta de dashboard: Exiba um alerta no dashboard.
Salve o alerta: Clique no botão "Save" para salvar o alerta.

Criando Filtros:

Acesse a aba "Variables" do seu dashboard: No menu lateral do Grafana, clique em "Variables".
Crie uma nova variável: Clique no botão "New Variable" para criar uma nova variável.
Configure a variável: Na tela de configuração da variável, você precisa definir:
Nome da variável: Dê um nome descritivo para a sua variável.
Tipo: Selecione o tipo da variável. Para filtrar por namespace, por exemplo, você pode usar o tipo "Query".
Consulta: Defina a consulta que irá retornar os valores possíveis para a variável. Para filtrar por namespace, você pode usar a seguinte consulta:

        label_values(kube_pod_info, namespace)

Salve a variável: Clique no botão "Save" para salvar a variável.
