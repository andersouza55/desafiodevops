1. Instale Node.js:
Importância: Essa etapa garante que o ambiente de build tenha a versão correta do Node.js instalada. Isso é fundamental para que o projeto Node.js seja compilado e executado corretamente. Sem a versão correta do Node.js, o projeto pode falhar durante a instalação de dependências, build ou execução de testes.

2. npm install e build:
Importância: Essa etapa instala as dependências do projeto e executa o script de build.
npm install: Garante que todas as bibliotecas e ferramentas necessárias para o projeto estejam disponíveis. Sem essas dependências, o projeto não pode ser compilado ou executado.
npm run build: Gera os arquivos de produção do projeto, otimizando o código para desempenho e preparando-o para implantação. Essa etapa é crucial para garantir que a aplicação seja implantada com a versão correta do código e que esteja pronta para produção.

3. npm run test:
Importância: Essa etapa executa os testes do projeto. Os testes garantem que o código funcione como esperado e que não haja erros ou falhas. Executar testes antes da implantação ajuda a prevenir problemas e bugs em produção, garantindo a qualidade do software.

4. Kubectl apply:
Importância: Essa etapa aplica as configurações do Kubernetes para implantar o projeto no cluster.
kubectl apply: Aplica as definições de deployments, serviços, pods e outros recursos Kubernetes. Essa etapa é crucial para que a aplicação seja implantada no cluster e esteja disponível para os usuários.