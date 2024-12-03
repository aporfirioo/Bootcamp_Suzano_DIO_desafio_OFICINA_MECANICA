# 🔧 Sistema de Gerenciamento de Oficina Mecânica

## 📝 Descrição do Projeto

Este projeto consiste em um esquema conceitual para um sistema de controle e gerenciamento de execução de ordens de serviço (OS) em uma oficina mecânica, desenvolvido com base em uma narrativa específica de gerenciamento de serviços automotivos.

## 🎯 Objetivo

Criar um modelo conceitual que permita o controle eficiente do fluxo de serviços mecânicos, desde a entrada do veículo até a conclusão da ordem de serviço.

## 🚗 Escopo do Sistema

O sistema abrange o gerenciamento completo de:
- Clientes
- Veículos
- Mecânicos
- Ordens de Serviço
- Serviços realizados
- Peças utilizadas

## 📊 Modelo Conceitual

### Entidades Principais

1. **Cliente**
   - Informações de identificação e contato
   - Relação com múltiplos veículos

2. **Veículo**
   - Dados de identificação e características
   - Histórico de ordens de serviço

3. **Mecânico**
   - Detalhes pessoais
   - Especialização
   - Histórico de serviços

4. **Ordem de Serviço**
   - Controle de execução dos serviços
   - Rastreamento de status
   - Gestão de custos

5. **Serviço**
   - Catálogo de serviços
   - Precificação de mão de obra

6. **Peça**
   - Controle de estoque
   - Detalhamento de componentes

## 🔗 Relacionamentos

- Um cliente pode possuir múltiplos veículos
- Cada veículo pode ter várias ordens de serviço
- Cada ordem de serviço pode incluir múltiplos serviços e peças
- Mecânicos executam diferentes ordens de serviço

## 🛠️ Funcionalidades Principais

- Registro de clientes e veículos
- Criação e acompanhamento de ordens de serviço
- Cálculo automático de valores de serviços
- Registro de peças utilizadas
- Controle de mecânicos e suas especialidades

## 📋 Regras de Negócio

- Autorização do cliente antes da execução dos serviços
- Cálculo de valores baseado em tabela de referência
- Mesma equipe avalia e executa os serviços



**Desenvolvido como parte de um desafio de modelagem de banco de dados**
