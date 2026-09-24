* ⊹₊˚‧︵‿₊୨ NextVolt ୧₊‿︵‧˚₊⊹ *

Sistema inteligente de gerenciamento de recarga de veículos elétricos para ambientes comerciais.

Sobre o Projeto 𓇼

O NextVolt é uma plataforma web desenvolvida para realizar o gerenciamento inteligente da recarga de veículos elétricos.

O sistema monitora a demanda energética e redistribui automaticamente a potência entre os carregadores, considerando a energia disponível na rede e a geração de energia solar.

Problema 𓇼

O carregamento simultâneo de vários veículos elétricos pode gerar picos de demanda e sobrecarga na rede elétrica.

Além disso, a falta de gerenciamento adequado pode resultar no baixo aproveitamento da energia solar disponível.

Solução 𓇼

O NextVolt utiliza um Smart Charging Engine (SCE) para controlar e distribuir a energia entre os veículos conectados.

O sistema considera:

Quantidade de veículos conectados;
Potência disponível na rede;
Energia solar disponível;
Prioridade dos veículos;
Nível de demanda.

A potência é redistribuída automaticamente conforme as condições do sistema.

Como Funciona 𓇼

A simulação utiliza uma potência fixa de 80 kW da rede elétrica e uma quantidade variável de energia solar.

A distribuição básica é calculada por:

P_por_veículo = (P_rede + P_solar) / nº de veículos

Quando a demanda ultrapassa o limite definido, o sistema ativa o modo de balanceamento restritivo e limita carregadores de baixa prioridade a 50% da potência nominal.

Arquitetura 𓇼
Dashboard Web
      ↓
Smart Charging Engine
      ↓
Balanceador de Potência
      ↓
Distribuição Inteligente de Energia
Funcionalidades
Visualização da potência da rede;
Visualização da energia solar disponível;
Adição e remoção de veículos;
Redistribuição automática de potência;
Alerta de alta demanda;
Simulação de aumento da geração solar.
Tecnologias 𓇼
Tecnologia	Utilização
HTML5	Estrutura da interface
CSS3	Estilização e responsividade
JavaScript	Lógica do sistema
GitHub	Versionamento e documentação
Demonstração 𓇼

Vídeo de demonstração:

https://youtu.be/pmkZl2mJKxg?is=wo_aOTlxjLD-TTzR

Equipe 𓇼
Nome	RM
Gabriel Jurado Nogueira	571236
Guilherme Henrique de Almeida	568708
Guilherme Garbelini	571150
Mariana Carminato	573258
Vinicius Torralles Ferreira Conduta	570911
Observação 𓇼

O NextVolt é uma prova de conceito funcional. O projeto simula a lógica de gerenciamento e balanceamento de energia, não possuindo integração com carregadores físicos.

FIAP — Disruptive Architectures: IoT, IoB & Generative AI — 2025

