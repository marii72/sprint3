
# ⚡ ChargeGrid Intelligence

> Sistema inteligente de gerenciamento de recarga de veículos elétricos para ambientes comerciais.

---

## 📋 Sobre o Projeto

O *ChargeGrid Intelligence* é uma plataforma web que transforma carregadores tradicionais de veículos elétricos em um sistema inteligente capaz de:

- Monitorar dados de sessões de recarga em tempo real
- Controlar e redistribuir a demanda energética automaticamente
- Priorizar o uso de energia solar fotovoltaica
- Alertar operadores em situações de alta demanda
- Reduzir desperdícios e sobrecarga na rede elétrica

---

## 🚨 Problema

Com o crescimento da mobilidade elétrica, ambientes comerciais enfrentam desafios críticos quando múltiplos veículos carregam simultaneamente:

| Problema | Consequência |
|----------|-------------|
| Sobrecarga na rede elétrica | Interrupções e multas por excesso de demanda |
| Múltiplos VEs carregando ao mesmo tempo | Picos de potência descontrolados |
| Baixo aproveitamento de energia solar | Desperdício de energia renovável disponível |
| Dificuldade de monitoramento | Decisões reativas e ineficientes |

---

## 💡 Solução

O ChargeGrid Intelligence utiliza um *Dashboard Web* conectado a um mecanismo chamado *Smart Charging Engine (SCE)*, responsável pela distribuição inteligente de potência entre os carregadores.

O SCE considera em tempo real:

- Quantidade de veículos conectados
- Potência disponível na rede elétrica
- Energia solar disponível no momento
- Prioridade de carregamento de cada veículo
- Risco de alta demanda

---

## 🏗️ Arquitetura da Solução


Usuário
   ↓
Dashboard Web  (HTML + CSS + JavaScript)
   ↓
Smart Charging Engine  (lógica de decisão e balanceamento)
   ↓
Balanceador de Potência  (redistribuição proporcional entre carregadores)
   ↓
Redução de sobrecarga + melhor uso da energia renovável


---

## ⚙️ Como Funciona

A simulação parte de uma *potência fixa de rede (80 kW)* e uma quantidade variável de *energia solar*.

Quando novos veículos são conectados, o SCE recalcula automaticamente a potência distribuída para cada carregador usando a fórmula:


P_por_veículo = (P_rede + P_solar) / nº de veículos


Se o número de veículos exceder o limiar de alta demanda, o sistema:

1. Exibe um *alerta visual* no dashboard
2. Ativa o *modo de balanceamento restritivo*
3. Limita carregadores de baixa prioridade a 50% da potência nominal

---

## 🖥️ Protótipo Funcional

O protótipo web permite:

- ✅ Visualizar potência da rede e energia solar disponível
- ✅ Adicionar e remover veículos conectados
- ✅ Simular carregadores ativos com redistribuição automática de potência
- ✅ Exibir alerta de alta demanda
- ✅ Simular aumento da geração solar

---

## 🚀 Como Executar

1. Clone o repositório:
bash
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git


2. Acesse a pasta do projeto:
bash
cd chargegrid-intelligence


3. Abra o arquivo index.html em qualquer navegador moderno (Chrome, Firefox, Edge).

> Nenhuma instalação de dependências é necessária.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|------------|-----|
| HTML5 | Estrutura da interface |
| CSS3 | Estilização e responsividade |
| JavaScript | Lógica do Smart Charging Engine |
| GitHub | Versionamento e documentação |
| YouTube | Demonstração em vídeo |

---

## 🌱 Sustentabilidade

| Pilar | Contribuição do ChargeGrid |
|-------|--------------------------|
| Energia Renovável | Priorização automática de energia solar |
| Eficiência Energética | Balanceamento elimina ociosidade e desperdício |
| Automação Inteligente | Decisões em tempo real sem intervenção manual |
| Mobilidade Elétrica | Ambiente de recarga mais confiável e escalável |
| Redução de Emissões | Substituição de picos de demanda por energia solar |

---

## 👥 Equipe

| Nome | RM |
|------|----|
| Gabriel Jurado Nogueira | 571236 |
| Guilherme Henrique de Almeida | 568708 |
| Guilherme Garbelini | 571150 |
| Mariana Carminato | 573258 |
| Vinicius Torralles Ferreira Conduta | 570911 |

---

## 🎥 Demonstração

📺 [Assista ao vídeo no YouTube](https://youtu.be/CWKiFh6vI1I)

---

## ⚠️ Observação

Este projeto é uma *prova de conceito funcional*. Ele não representa integração real com carregadores físicos, mas sim uma simulação técnica da lógica de balanceamento inteligente de energia proposta para o ChargeGrid Intelligence.

Em versões futuras, as regras de decisão do SCE poderão ser substituídas por modelos de IA capazes de prever horários de pico e otimizar a distribuição energética de forma autônoma.

---

FIAP — Disruptive Architectures: IoT, IoB & Generative AI — 2025

---

Só lembrar de substituir SEU_USUARIO/SEU_REPOSITORIO pelo caminho real do repositório de vocês no GitHub antes de publicar.
