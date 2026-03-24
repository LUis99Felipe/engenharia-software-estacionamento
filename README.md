# engenharia-software-estacionamento

Aqui está seu conteúdo organizado em um **README.md** bem estruturado para GitHub 👇

---

# 🚗 Sistema de Controle de Estacionamento

## 📌 Declaração do Escopo

O sistema tem como objetivo controlar o acesso de milhares de usuários a um estacionamento, gerenciando entradas, saídas e ocupação de vagas de forma eficiente.

---

## 👥 Integrantes do Projeto

| Nome                          | Cargo         | Contato                                                                                               | RA      |
| ----------------------------- | ------------- | ----------------------------------------------------------------------------------------------------- | ------- |
| Enzo Panassol Zapparolli      | Desenvolvedor | [enzo.zapparolli@aluno.faculdadeimpacta.com.br](mailto:enzo.zapparolli@aluno.faculdadeimpacta.com.br) | 2500187 |
| Romeo Alho de Brito           | Desenvolvedor | [romeo.brito@aluno.faculdadeimpacta.com.br](mailto:romeo.brito@aluno.faculdadeimpacta.com.br)         | 2501494 |
| Luis Felipe de Souza Oliveira | Desenvolvedor | [luis.sfelipe@aluno.impacta.edu.br](mailto:luis.sfelipe@aluno.impacta.edu.br)                         | 2501173 |
| Gustavo Calado Soares         | Desenvolvedor | [gustavo.calado@aluno.impacta.edu.br](mailto:gustavo.calado@aluno.impacta.edu.br)                     | 2501613 |

---

## ⚙️ Requisitos do Produto

### 🔹 Funcionalidades Principais

* Registrar entrada do veículo com:

  * Placa
  * Modelo
  * Marca
  * Data e hora de entrada
* Verificar disponibilidade de vagas antes da entrada
* Gerar recibo de entrada com:

  * Data e hora
  * Valor da hora
* Exibir vagas disponíveis e ocupadas
* Indicar vaga livre para o manobrista
* Registrar vaga ocupada pelo veículo
* Registrar saída do veículo
* Calcular valor total com base no tempo de permanência
* Liberar vaga automaticamente após saída
* Gerar relatórios:

  * Ocupação
  * Veículos por período
  * Tempo médio de permanência

---

### 📏 Regras do Produto

* Não permitir entrada sem vagas disponíveis
* Todo veículo deve estar vinculado a uma vaga
* Uma vaga só pode ser ocupada por um veículo por vez
* O valor cobrado deve seguir a taxa por hora do dia

---

### ✅ Qualidade Esperada

* Interface simples e rápida
* Atualização em tempo real das vagas
* Facilidade de uso para recepcionistas e manobristas

---

## 🛠️ Requisitos de Projeto

### 📌 Escopo do Projeto

* Desenvolver sistema de controle de entrada, saída e ocupação
* Reduzir tempo de busca por vagas
* Melhorar organização do estacionamento
* Suportar até **5.000 vagas**

---

### ⚠️ Restrições

* Interface simples para usuários operacionais
* Funcionamento com duas portarias
* Suporte a múltiplos usuários simultâneos

---

### 🎯 Critérios de Sucesso

* Redução do tempo de localização de vagas
* Menos erros na alocação de veículos
* Melhor controle de vagas
* Fluxo mais eficiente de entrada e saída

---

## 🧱 Requisitos de Arquitetura

### 🏗️ Estrutura do Sistema

O sistema deve conter módulos de:

* Cadastro de entrada de veículos
* Controle de vagas
* Registro de saída
* Emissão de recibos
* Relatórios

---

### 🗄️ Banco de Dados

Deve armazenar:

* Veículos
* Vagas
* Movimentações (entrada e saída)
* Valores cobrados

---

### ⚡ Desempenho

* Suportar até 5.000 vagas
* Atualização rápida do status das vagas
* Suporte a múltiplos acessos simultâneos

---

### 🔐 Segurança

* Autenticação obrigatória
* Registro de logs de operações
* Controle de acesso a dados sensíveis

---

### 🟢 Disponibilidade

* Sistema disponível durante todo o funcionamento
* Evitar inconsistência entre portarias

---

### 📊 Integração e Visualização

* Visualização centralizada das vagas
* Atualização em tempo real
* Possibilidade de painel com mapa de vagas

---

Se quiser, posso te ajudar a complementar esse README com:

* 📊 Diagrama ER (modelo conceitual)
* 🧾 Scripts SQL
* 🖥️ Estrutura de pastas do projeto

Só falar 👍
