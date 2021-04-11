# E-commerce-checkout
E-commerce usando  micros serviços em Java
Criando uma solução de e-commerce com microsserviços em Java
Neste projeto foi desenvolvida uma solução de e-commerce com a arquitetura de microsserviços, com a integração orientada a eventos utilizando o Apache Kafka e o Schema Registry para garantir a compatibilidade na comunicação.

Arquitetura

📑 Requisitos
Docker
Java JDK 14
📝 Instruções
Prepare a infraestrutura:

Crie e inicie os containers docker configurados no arquivo docker/docker-compose.yml seguinte comando:

docker-compose up --build -d
Docker

Parar e remover todos os containers e recursos relacionados no arquivo de configuração:

docker-compose down
Inicie a CheckoutApplication dentro do projeto ecommerce-checkout-api.

Inicie a PaymentApplication dentro do projeto ecommerce-payment-api.

Inicie um servidor web para a página contida em ecommerce-frontend-web.

📚 Referências
Apache Kafka
Apache ZooKeeper
Registro de esquema
