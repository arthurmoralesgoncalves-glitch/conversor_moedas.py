# 💰 Currency Converter Pro - Real-Time API

Este é um sistema de consulta e conversão de moedas em tempo real, desenvolvido para demonstrar a integração entre Python e serviços de API externos (REST). O projeto conta com uma interface de linha de comando (CLI) otimizada e um sistema de navegação por menus.

## 🚀 Funcionalidades
- **Cotações em Tempo Real:** Consumo de dados da AwesomeAPI para obter valores atualizados de Dólar (USD), Euro (EUR) e Bitcoin (BTC).
- **Interface Interativa:** Menu de navegação que permite ao usuário escolher qual moeda deseja consultar ou converter.
- **Cálculo de Conversão:** Lógica integrada para converter valores em Reais (BRL) para a moeda selecionada com precisão de até 8 casas decimais (foco em BTC).
- **Standalone:** O projeto foi compilado em um executável (.exe), permitindo o uso em qualquer ambiente Windows sem a necessidade de instalação do Python.

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python 3.13
- **Biblioteca de Requisições:** `requests` (para comunicação com a API)
- **Integração:** REST API (JSON)
- **Compilação:** PyInstaller (para geração do .exe)

## 📂 Como Executar
1. Instale a biblioteca necessária:
   ```bash
   pip install requests
