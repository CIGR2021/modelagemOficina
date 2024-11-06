# Oficina Mecânica Project

## Descrição

Este projeto é um sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica. Ele permite o registro de clientes, veículos, ordens de serviço, serviços executados e peças utilizadas, facilitando o controle e a gestão das atividades do escritório.

## Funcionalidades

- **Cadastro de Clientes**: Armazena informações como nome, endereço e telefone dos clientes.
- **Cadastro de Veículos**: Cadastra informações sobre os veículos dos clientes, incluindo placa, modelo e ano.
- **Ordem de Serviço (OS)**: Criação e gerenciamento das ordens de serviço, com dados de remessa, status, dados de conclusão e valor total.
- **Serviços e Peças**: Inclusão de serviços e peças no OS, com base em uma tabela de referência de mão-de-obra e valores de peças.
- **Equipes e Mecânicos**: Organização dos mecânicos em equipes para identificação e execução dos serviços.

## Diagrama de Entidade e Relacionamento (DER)

![Diagrama DER](https://github.com/CIGR2021/modelagemOficina/blob/main/ER%20Diagram%20-%20Oficina.pdf)

O diagrama inclui as seguintes entidades:

- **Cliente** - Representa os clientes que utilizam os serviços do escritório.
- **Veículo** - Informações sobre os veículos dos clientes.
- **Ordem de Serviço** - Dados da ordem de serviço, incluindo serviços e peças.
- **Serviço** - Tabela de referência para cada tipo de serviço disponível.
- **Peça** - Tabela com informações das peças usadas nas ordens de serviço.
- **Equipe e Mecânico** - Representam as equipes e os mecânicos responsáveis ​​pela execução das ordens.

## Tecnologias Utilizadas

- **Banco de Dados**: MySQL Workbench

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/CIGR2021/modelagemOficina
