# send2watch

Uma aplicação simples de **Watch Together** que permite que usuários assistam a vídeos enviados em uma sala compartilhada.

## Visão Geral

Este projeto permite que um usuário faça upload de um vídeo e crie uma sala compartilhada para que outras pessoas assistam ao mesmo vídeo em sincronia. Os controles de reprodução (play, pause, seek) do usuário principal são transmitidos em tempo real para todos os participantes. A priori, a aplicação é funcional e não visa grande escalabilidade.

## Funcionalidades

- **Upload de Vídeo**: Suporte para formatos MP4 e MKV.
- **Criação de Sala**: O usuário principal cria uma sala única para o vídeo e compartilha o link com outros participantes.
- **Sincronização em Tempo Real**: Todos os participantes da sala assistem ao vídeo no mesmo ponto, sincronizados com o usuário principal.
- **Reconexão Automática**: Em caso de perda de conexão, o cliente tenta se reconectar automaticamente e se alinha ao ponto correto do vídeo.

## Tecnologias Utilizadas

- **Frontend**: Vue.js
- **Backend**: Node.js - Estudar a possibilidade de back com Python
- **Comunicação em Tempo Real**: WebSocket para sincronização dos controles de reprodução

## Pré-requisitos

A definir.
