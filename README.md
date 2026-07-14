# Assistente-de-Delivery-com-AWS-Step-Functions-e-Bedrock
Foi criando um Assistente de Delivery com a ajuda de um Agent da DIO no Antigravity. 

# Assistente de Delivery com AWS Step Functions e Amazon Bedrock

Este projeto apresenta a criação de um assistente virtual de delivery para pizzaria utilizando a orquestração de serviços com **AWS Step Functions** e modelos de inteligência artificial generativa com **Amazon Bedrock**.

## 🚀 Arquitetura do Fluxo

O fluxo é sequencial e utiliza o modelo **Llama 3 (meta.llama3-8b-instruct-v1:0)** para processar as seguintes etapas:

1. **Geração do Menu:** Apresenta boas-vindas e sugere pizzas.
2. **Recomendação de Bebidas:** Harmoniza uma bebida com base na pizza recomendada.
3. **Fechamento do Pedido:** Cria uma mensagem final com o resumo e tempo estimado de entrega.

![Fluxo de Trabalho](./workflow.png)

## 🛠️ Tecnologias Utilizadas

- **AWS Step Functions:** Orquestração de microsserviços.
- **Amazon Bedrock:** Execução de modelos de IA generativa (Llama 3).
- **JSONata:** Linguagem de consulta e transformação de dados entre estados.

- <img width="1366" height="768" alt="states" src="https://github.com/user-attachments/assets/c7d2ef43-2d18-46ed-a1dd-ccb56875dd0a" />
<img width="1366" height="768" alt="workflow" src="https://github.com/user-attachments/assets/59a51d0c-66dd-4e2f-857f-19eb45e0202e" />

