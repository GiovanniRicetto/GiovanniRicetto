Com vasta experiência em automação de testes 🤖 (API e Web UI) e testes de carga, garanto a qualidade e o desempenho do software em todas as etapas. Minha paixão por tecnologia me leva a dominar diversas linguagens (Ruby, Python) e ferramentas (RSpec, Selenium, JMeter, etc.), assegurando a robustez e escalabilidade das aplicações.

Sou analítico 🧠 e estratégico 🎯, contribuindo ativamente para a tomada de decisões e buscando sempre a evolução da equipe. Proativo, implemento e otimizo processos de CI/CD 🔄, IaC 🏗️ e gerenciamento de recursos na nuvem (AWS) ☁️, com foco em eficiência e controle de custos.

Desenvolvo AWS Lambdas, aplicações Google AppScript e bots 🤖, demonstrando versatilidade e adaptabilidade. Minha atenção aos detalhes e busca por aprimoramento resultam em trabalho de alta qualidade ✨.

Em resumo:

QA completo com expertise em automação, DevOps, Cloud e programação.
Líder e colaborativo, sempre em busca de aprendizado.
Apaixonado por impulsionar a qualidade e inovação no desenvolvimento de software.
Vamos construir algo incrível juntos? 🤝

## Habilidades e Ferramentas:

QA: Automação de Testes (API e Web UI), Testes de Carga, Planejamento de Testes, Testes Manuais
DevOps/Cloud: CI/CD, IaC, AWS, Azure DevOps, GitHub Actions, CloudFormation, FinOps
Programação: Ruby, Python, JavaScript/TypeScript
Ferramentas: RSpec, Selenium, Capybara, Cucumber, SitePrism, JMeter, Postman, Zeplin, Figma, Git
## Contato:

[LinkedIn](https://www.linkedin.com/in/ricetto/)]
## Projetos em Destaque:

###Automação de subida do ambiente de qualidade

Inspirado pelo serviço de uma equipe dentro da empresa que trabalho, que automatiza a subida do ambiente, desligamento e também orquestra o deploys.
O ambiente em questão possuia apenas uma tela web com as VMs e botões para ligar e desligar, outro problema avaliado era que tem uma ordem específica para ligar as máquinas para que o ambiente funcione corretamente; Falando da tela de VMs, o serviço era antigo e descontinuado, nenhum dev/qa que estava atualmente na empresa sabia dar manutenção e sem contar que era delicado fazer muita alteração no serviço. Então com uma simples ideia de modernizar o serviço utilizei Lambda+EventBridge(AWS), Google Chat (Workspace) e Apps Script.

Lambda ficou com a parte de código em serverless e o EventBridge com o gatilho de horário.
Google Chat foi dividido em 2 partes. Notificação do lambda executar com sucesso e receber comando em um bot para que os qas pudessem orquestrar ligamento e desligamento dos ambientes.
Apps Script foi utilizado para desenvolver o bot mencionado anteriormente.

O resultadodo projeto são os QAs com mais tempo podendo testar e usar o ambiente. Menos tempo do ambiente indisponível por ser ligado na ordem errada e principalmente modernização do legado para algo mais simples e de facil manutenção.]

###Bot de links úteis internos
O que era um site, hospedado em uma máquina na AWS que não recebia atualizações se tornou um bot, prático, serveless (com custo 0 para empresa) e que ainda conta com um rolador de dados!
Assim como o Prometheus, minha primeira criação, pensei... Por que não inovar uma tela velha e sem graça para um bot assim como o outro? Detalhe que agora apenas precisava trazer links, não mais requisitar AWS Lambdas e esperar Webhooks em uma sala.

Então assim nasceu AlexandriaBot, tendo seu nome inspirado na biblioteca do império romano. Um bot que de forma simples todos usuários da organização conseguem acessar links úteis e mantendo em sigílo tudo, pois algumas informações sensíveis não podem ficar expostas, e já que apenas pode ser acessado atravéz do Google Chat da organização, as informações ficam guardadas em segurança.



"A qualidade nunca é um acidente; é sempre o resultado de um esforço inteligente." - John Ruskin
