# Mermaid-AzureAPIM_Elements
Exemplo de Flowchart criado com Mermaid detalhando o relacionamento de elementos do Azure API Management (APIM): APIs, Products e Subscription Keys.

## Diagrama (código em Mermaid)

```mermaid
graph TD;
    subgraph Produto
        Produto1[Produto 1]
        Produto2[Produto 2]
    end

    subgraph API
        API1[API 1]
        API2[API 2]
        API3[API 3]
    end

    subgraph SubscriptionKey
        Key1[Subscription Key 1]
        Key2[Subscription Key 2]
    end

    Produto1 --> API1
    Produto1 --> API2
    Produto2 --> API3
    Produto2 --> API1

    Key1 --> Produto1
    Key2 --> Produto2
```
