# 🏁 Trabalho Final — Redes de Computadores

## 📌 Descrição

Este projeto foi desenvolvido como trabalho final da disciplina de **Redes de Computadores**, com foco na implementação prática de comunicação entre sistemas utilizando programação em Python.

O trabalho simula um ambiente de rede baseado no modelo **cliente-servidor**, permitindo a troca de mensagens entre diferentes aplicações conectadas.

## 🎯 Objetivo

Aplicar conceitos fundamentais de redes de computadores, como:

- Comunicação entre processos
- Arquitetura cliente-servidor
- Uso de sockets
- Transmissão de dados em rede

A programação de redes com sockets permite criar aplicações capazes de estabelecer conexões e trocar informações entre máquinas, sendo uma base importante para sistemas distribuídos :contentReference[oaicite:0]{index=0}.

## 🛠️ Tecnologias utilizadas

- Python 🐍  
- Biblioteca `socket`  
- Conceitos de redes (TCP/IP)

## ⚙️ Funcionamento do sistema

O projeto é dividido em duas partes principais:

### 🔹 Servidor
- Responsável por aguardar conexões de clientes  
- Recebe requisições  
- Processa e responde às mensagens  

### 🔹 Cliente
- Conecta-se ao servidor  
- Envia mensagens ou comandos  
- Recebe respostas do servidor  

A comunicação ocorre por meio de troca de dados via rede, simulando o funcionamento de aplicações reais como chats e sistemas distribuídos.

## 🚀 Como executar

1. Execute o servidor:

python servidor.py

2. Em outro terminal, execute o cliente:

python cliente.py

3. Interaja enviando mensagens entre cliente e servidor

## 📂 Estrutura do projeto

📁 Trabalho Final/
├── servidor.py
├── cliente.py

## 📚 Conceitos aplicados

- Modelo cliente-servidor  
- Comunicação em rede  
- Protocolos de transporte (TCP)  
- Programação com sockets  

## 👨‍💻 Autores

- Pedro Dutra  
- Pedro Pignata  
