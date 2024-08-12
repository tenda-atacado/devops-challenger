# Desafio DevOps: Implementação de Stack ELK para Coleta de Logs

## Descrição do Desafio

Este projeto consiste na criação e configuração de uma stack ELK (Elasticsearch, Logstash e Kibana) para a coleta e visualização de logs gerados por uma aplicação simples. O objetivo é demonstrar habilidades em DevOps, especialmente no uso de Docker e/ou Kubernetes, e na aplicação de boas práticas de configuração e documentação.

## Requisitos do Desafio

1. **Criação de uma Aplicação Geradora de Logs:**
   - Desenvolva ou utilize uma aplicação simples que gere logs de forma contínua ou em intervalos regulares.
   - Configure a aplicação para enviar os logs para o Logstash.

2. **Configuração da Stack ELK:**
   - Configure os serviços Elasticsearch, Logstash e Kibana usando Docker ou Kubernetes.
   - Certifique-se de que todos os serviços estão conectados e funcionando corretamente.
   - Elasticsearch deve receber e indexar os logs processados pelo Logstash.
   - Kibana deve ser utilizado para visualizar e analisar os logs.

3. **Criação de Dockerfiles e Docker Compose/Kubernetes Manifestos:**
   - Crie Dockerfiles para a aplicação, Elasticsearch, Logstash e Kibana.
   - Crie um arquivo `docker-compose.yml` ou manifestos Kubernetes para orquestrar e conectar todos os containers.
   - Todos os containers devem ser conectados e configurados corretamente.

4. **Documentação:**
   - Inclua um arquivo `README.md` detalhando:
     - Como subir os serviços passo a passo.
     - Descrição da aplicação geradora de logs.
     - Como verificar se os logs estão sendo gerados e processados corretamente.
     - Como acessar o Kibana e visualizar os logs.
     - Qualquer outra informação relevante para a execução do projeto.

5. **Entrega:**
   - Faça o upload de todo o código em um repositório público no GitHub.
   - Certifique-se de que o repositório permite a clonagem e execução dos serviços conforme documentado.
