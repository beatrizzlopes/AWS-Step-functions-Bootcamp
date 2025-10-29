# Introdução

Este repositório possui o desafio: consolidar seus workflows automatizados com AWS Step Functions, também contém minhas anotações e insights adquiridos durante o 7° módulo do bootcamp Santander Code Girls com a DIO, focado em computação em nuvem com AWS.

# Material presente no repositório

README.md: Explicação detalhada do desafio e anotações do módulo de Gerenciamento de Instâncias EC2.

experiência: Contém anotações sobre minha experiência prática do desafio.

Imagens: Captura de tela do Desafio.

# Anotações

### Amazon Lambda 

O AWS Lambda é um serviço da Amazon Web Services (AWS) que permite executar código sem precisar gerenciar servidores. Por isso, ele é chamado de uma plataforma serverless (“sem servidor”).

### ECS e EKS

O ECS é adequado para organizações que estão começando a usar contêineres com arquiteturas de baixa ou média complexidade.

O EKS é voltado para casos de uso corporativo, atendendo a aplicativos complexos baseados em microsserviços distribuídos.

### O Amazon Step Functions

O Amazon Step Functions é um serviço da AWS que permite orquestrar fluxos de trabalho (workflows) distribuídos de forma visual, coordenando diferentes serviços da AWS, como Lambda, S3, DynamoDB, ECS, SNS, SQS, entre outros. Ele é ideal para automatizar processos complexos, com controle de execução, paralelismo, tratamento de erros e monitoramento.

### Amazon SQS e SNS

O Amazon SNS funciona como um sistema de transmissão, o que o torna ideal para alertar rapidamente os usuários de um determinado produto

O Amazon SQS funciona como uma fila de mensagens, fornecendo dados a vários componentes de aplicativos de forma ordenada e independente.

# Desafio: Consolidar seus workflows automatizados com AWS Step Functions

Na imagem abaixo contém o conteúdo do meu workflow. Este projeto é sobre um sistema de aluguel de livros que decide se o pedido será aprovado ou não, usando SQS, Lambda, Choice, DynamoDB e SNS.

![image alt](https://github.com/beatrizzlopes/AWS-Step-functions-Bootcamp/blob/ca294685665d3caf2a4234d16980f52b9e1a4efc/Imagem/stepfunctions_graph.png)

Para mais informações sobre a minha experiência prática acesse nosso arquivo: [Experiência](https://github.com/beatrizzlopes/AWS-Step-functions-Bootcamp/blob/main/Experi%C3%AAncia)

# Insights

Durante esse projeto do desafio, eu percebi como a automação facilita tudo. Com o Step Functions e o Lambda, o fluxo de aluguel de livros acontece de um jeito bem prático, sem precisar fazer tudo manualmente e isso é algo muito valioso. O Choice é como o “cérebro” deste processo, decidindo se o pedido vai ou não seguir, de acordo com o pagamento. E com o SQS e o SNS, o sistema consegue se comunicar direitinho. É nítido a rapidez, organização e a confiança!

# Autora
Beatriz Lopes

# Referência
https://web.dio.me/track/santander-code-girls-2025
