# Sistema de Chat com JMS

Aplicação de chat em tempo real desenvolvida em Java, utilizando Java Message Service (JMS) e Apache ActiveMQ como broker de mensagens, com interface gráfica em JavaFX.

## Visão Geral

O projeto simula um sistema de comunicação entre múltiplos clientes, utilizando mensageria para envio e recebimento de mensagens de forma assíncrona.

A comunicação é baseada no modelo publish/subscribe, permitindo que diferentes clientes recebam mensagens em tempo real sem acoplamento direto entre eles.

## Arquitetura

A aplicação é estruturada com base em mensageria:

- Produtores JMS responsáveis pelo envio de mensagens
- Consumidores JMS responsáveis pela recepção
- Broker (ActiveMQ) intermediando a comunicação
- Uso de tópicos para distribuição das mensagens entre clientes

Esse modelo permite desacoplamento entre os componentes e maior escalabilidade da aplicação.

## Tecnologias

- Java  
- JavaFX  
- JMS (Java Message Service)  
- Apache ActiveMQ  

## Funcionalidades

- Envio e recebimento de mensagens em tempo real  
- Comunicação entre múltiplos clientes conectados  
- Interface gráfica para interação  
- Distribuição de mensagens via tópicos (publish/subscribe)  

## Como Executar

1. Baixe e inicie o Apache ActiveMQ

2. Clone o repositório:
   git clone https://github.com/begiudicelli/seu-repositorio

3. Abra o projeto em uma IDE (Eclipse, IntelliJ, etc.)

4. Execute múltiplas instâncias da aplicação para simular diferentes usuários

## Objetivo

Projeto com foco educacional, desenvolvido para praticar:

- Comunicação assíncrona  
- Sistemas distribuídos  
- Uso de mensageria com JMS  
- Integração com broker (ActiveMQ)  

## Possíveis Melhorias

- Implementação de autenticação de usuários  
- Criação de salas de chat  
- Persistência de mensagens  
- Migração para arquitetura baseada em microserviços  
