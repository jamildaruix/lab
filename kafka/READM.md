#Documentacao Oficial Kakfa

https://kafka.apache.org/documentation/

https://www.enterpriseintegrationpatterns.com/MessageBroker.html


## Concepção e Terminologia

- **Events registra fatos de algo que aconteceu**
    - Event Key
    - Event Value
    - Event timespan
    - Optional Event metadata

- **Producer (Publish)**
    - Tem a função de escrever o event no kafka (broker)**

- **Consumer (Subscribe)**
    - Tem a função de ler e processar o event escrito no kafka (broker)

- **Topics**
    - Similar a um diretório dentro de um systema de arquivos (Windows, Linux).
    - Os Eventos são armazenados dentro deste diretório (topic).

- **Events**
    - Eventos são organizados e armazenado para serem duravéis dentro de um tópico.
    - São como arquivos armazenados dentro de um tópico e equivalente aos arquivos gerados dentro do diretório.

- **Partitioned**
    - 
