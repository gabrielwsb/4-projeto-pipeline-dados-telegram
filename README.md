# 4º Projeto - Pipeline de Dados de um grupo no Telegram

## O que é este projeto
Atualmente, a maioria das empresas possui um sistema de atendimento ao consumidor chamados de chatbot. O usuário manda mensagem para tirar alguma dúvida ou resolver alguma situação e ao invés de ter uma pessoa pronta para atende-lo, ela irá conversar com um robo já programado pela própria empresa que é capaz de solucionar as dúvidas mais frequentes que os clientes tem. Se o robo não conseguir solucionar a situação então é passado para um atendente real.

A ideia deste projeto é oferecer uma solução para poder analisar as mensagens recebidas por um chatbot para tirar conclusões que possam ajudar o negócio, por exemplo:

Qual a dúvida ou situação mais frequente? Qual horário mais acessado pelos usuários? Existe alguma forma de aprimorar o bot para diminuir os atendimentos reais? E outras que possam surgir..


Neste projeto, utilizo as seguintes bibliotecas do **Python**:
* **JSON** para trabalhar com o formato das mensagens recebidas.
* **OS** para acessar variaveis de ambientes no **AWS LAMBDA**.
* **LOGGING** para registrar possíveis mensagens de erro.
* **GETPASS** para esconder dados de acesso.
* **DATETIME** para organizar as pastas criadas no Bucket do **AWS S3** pela data.
* **BOTO3** para interagir com os serviços da **Amazon AWS**.
* **REQUESTS** para fazer requisições na web, neste caso com o **Telegram**.
* **PYARROW** para compactar arquivos **.json**, converter os dados para um formato tabular e salvar como **.parquet**.


Ao longo do processo, foram aplicados conceitos fundamentais de engenharia de dados, como:

* Integração com APIs externas via webhook.
* Processamento serverless com **AWS Lambda (Python)**.
* Armazenamento estruturado e particionado no **Amazon S3**.
* Conversão de dados semi-estruturados (JSON) para um formato mais eficiente (Parquet).

Com pequenas adaptações, esta solução pode ser aplicada em contextos reais de empresas que utilizam chatbots para atendimento ao cliente, permitindo análises como:

* Identificação de dúvidas mais recorrentes.
* Melhoria da performance do bot.
* Entendimento de padrões de uso.

  ## Executar

  O arquivo *Projeto_Final_Pipeline_Dados_Telegram.ipynb* é próprio para rodar no Google Colab. Basta baixar, importar e executá-lo.

  O projeto foi postado no Kaggle, [clique aqui](https://www.kaggle.com/code/gabrielwsb/4-projeto-pipeline-de-dados-no-telegram)

  A pasta *projeto* contém as imagens usadas para evidenciar o que estava sendo feito. Para acompanhar basta acompanhar a numeração das imagens.
