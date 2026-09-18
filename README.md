# Classes de Rede IPv4 — A, B e C | Cisco Packet Tracer

## Descrição

Projeto acadêmico desenvolvido para estudar o modelo tradicional de endereçamento IPv4 por classes, abordando as **Classes A, B e C**, suas faixas de endereçamento, máscaras padrão, divisão entre identificação da rede e dos hosts e capacidade de dispositivos em cada tipo de rede.

Além do estudo teórico, foi realizada uma demonstração prática utilizando o **Cisco Packet Tracer**, permitindo visualizar a configuração de uma rede IPv4 e testar a comunicação entre os dispositivos.

> **Observação:** as Classes A, B e C fazem parte do modelo histórico de endereçamento IPv4 conhecido como *classful addressing*. Atualmente, o endereçamento IPv4 utiliza principalmente o modelo **CIDR (Classless Inter-Domain Routing)**, baseado em prefixos como `/8`, `/16`, `/24` e outros.

---

## Objetivo

O objetivo da atividade foi compreender os principais conceitos relacionados ao endereçamento IPv4, incluindo:

- estrutura de um endereço IPv4;
- identificação da rede e do host;
- características das Classes A, B e C;
- funcionamento das máscaras de sub-rede;
- quantidade de hosts disponíveis em cada classe;
- configuração manual de endereços IPv4;
- utilização do gateway padrão;
- testes de conectividade utilizando o comando `ping`;
- aplicação prática desses conceitos no Cisco Packet Tracer.

---

## Contexto da atividade

Esta atividade foi realizada **em grupo**, como parte de um estudo sobre fundamentos de redes e endereçamento IPv4.

A entrega oficial do trabalho ocorreu por meio de uma **apresentação em vídeo**, na qual os conteúdos foram divididos entre os integrantes do grupo.

Minha responsabilidade foi estudar e apresentar a **Classe B**, incluindo:

- faixa de endereçamento;
- máscara padrão `/16`;
- divisão entre rede e hosts;
- quantidade de hosts disponíveis;
- configuração dos dispositivos no Cisco Packet Tracer;
- funcionamento do gateway;
- testes de comunicação utilizando `ping`.

Além disso, produzi um **material de estudo em PDF** reunindo as Classes A, B e C.

Esse PDF não foi a entrega oficial do trabalho. Ele foi elaborado por mim como material de apoio para compreender melhor o conteúdo, organizar as informações estudadas e auxiliar na preparação e divisão da apresentação do grupo.

---

# Conceitos estudados

## Endereço IPv4

Um endereço IPv4 possui **32 bits**, normalmente representados por quatro números decimais separados por pontos.

Exemplo:

```text
192.168.1.10
