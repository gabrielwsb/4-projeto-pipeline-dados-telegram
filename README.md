# O QUE É ESTE PROJETO
Atualmente, a maioria das empresas possui um sistema de atendimento ao consumidor chamados de chatbot. O usuário manda mensagem para tirar alguma dúvida ou resolver alguma situação e ao invés de ter uma pessoa pronta para atende-lo, ela irá conversar com um robo já programado pela própria empresa que é capaz de solucionar as dúvidas mais frequentes que os clientes tem. Se o robo não conseguir solucionar a situação então é passado para um atendente real.

A ideia deste projeto é oferecer uma solução para poder analisar as mensagens recebidas por um chatbot para tirar conclusões que possam ajudar o negócio, por exemplo:

Qual a dúvida ou situação mais frequente?
Qual horário mais acessado pelos usuários?
Existe alguma forma de aprimorar o bot para diminuir os atendimentos reais?
E outras que possam surgir..

Ao longo do processo, foram aplicados conceitos fundamentais de engenharia de dados, como:

* Integração com APIs externas via webhook,

* Processamento serverless com AWS Lambda (Python),

* Armazenamento estruturado e particionado no Amazon S3,

* Conversão de dados semi-estruturados (JSON) para um formato mais eficiente (Parquet).

Com pequenas adaptações, esta solução pode ser aplicada em contextos reais de empresas que utilizam chatbots para atendimento ao cliente, permitindo análises como:

* Identificação de dúvidas mais recorrentes,

* Melhoria da performance do bot,

* Entendimento de padrões de uso.
