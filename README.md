# Arquitetura Cliente-Servidor utilizando Máquinas Virtuais
Este projeto demonstra a implementação de uma arquitetura cliente-servidor utilizando máquinas virtuais para simular um ambiente real de rede.
Foi configurado um servidor Linux responsável por responder às requisições do cliente, permitindo testes de conectividade, acesso remoto e hospedagem de serviços.

## Objetivo
Simular um ambiente de rede real para compreender na prática como ocorre a comunicação entre cliente e servidor, além de desenvolver habilidades em configuração de sistemas e diagnóstico de rede.

<p align="center">
<img width="550" alt="Diagrama Cliente Servidor" src="https://github.com/user-attachments/assets/eb81d88c-834e-4351-a3bc-0ad9bbd402e0"/>
</p>

O cliente foi configurado em uma máquina Kali Linux responsável por realizar requisições ao servidor Ubuntu.
A comunicação ocorreu via rede NAT, permitindo testes de conectividade e acesso aos serviços hospedados.

## Tecnologias

- VirtualBox
- Kali Linux
- Ubuntu Server
- SSH
- Protocolo TCP/IP
- Configuração de rede NAT

## 🚨 Etapas do Projeto

- Criação das máquinas virtuais
- Instalação do sistema operacional Linux
- Configuração de IP e rede
- Instalação do servidor web
- Liberação de portas no firewall
- Testes de comunicação entre cliente e servidor

## Testes

✔ Ping entre as máquinas  
✔ Acesso ao servidor via navegador  
✔ Conexão remota utilizando SSH  
✔ Validação das portas abertas


## Desafios

Durante a implementação, a máquina cliente não conseguia acessar o servidor.

Após análise, identifiquei que o firewall estava bloqueando a comunicação.  
A solução foi ajustar as regras utilizando o UFW para liberar a porta 80.

## Aprendizados

- Funcionamento prático do modelo cliente-servidor
- Configuração de redes virtuais
- Noções de segurança com firewall
- Diagnóstico de falhas de conectividade

## Como reproduzir o projeto:

1. Criar duas VMs no VirtualBox
2. Configurar rede NAT
3. Instalar Ubuntu Server
4. Instalar Nginx
5. Liberar porta 80 no UFW



