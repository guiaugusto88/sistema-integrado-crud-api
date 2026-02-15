# 🚀 Sistema de Gerenciamento e Consultas - Streamlit

## 📝 Descrição
Este projeto é um ecossistema desenvolvido em Python utilizando o framework Streamlit. A aplicação integra um sistema de cadastro de clientes com persistência em banco de dados local e um consultor de ativos financeiros que consome dados em tempo real via API externa.

## 🚀 Funcionalidades
- **Home**: Página de apresentação com perfil profissional e canais de contato.
- **Cadastro de Clientes**: Interface de formulário para inclusão de dados (Nome, Idade, Profissão) com salvamento direto em banco de dados.
- **Consulta de Investimentos**: Integração com API para busca de cotações de ativos (Ex: MXRF11, HGLG11) e armazenamento de histórico de preços.
- **Calculadora Interativa**: Ferramenta utilitária com lógica de operações matemáticas e feedback visual dinâmico.

<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cea435b6-083a-48e8-8ac4-419c3abbc7ce" alt="Demonstração do Sistema" width="850">
  <br>
  <em>Demonstração em tempo real: Consulta de ativos via API e salvamento automático no SQLite.</em>
</p>

<br>

## 🛠️ Tecnologias Utilizadas
- **Python**: Linguagem principal para lógica e integração.
- **Streamlit**: Framework para criação da interface web interativa.
- **SQLite**: Banco de dados relacional para persistência de dados local.
- **Pandas**: Biblioteca para manipulação e visualização de tabelas de dados.
- **Requests**: Realização de requisições HTTP para consumo de APIs financeiras.

## 📂 Estrutura do Projeto
O projeto foi organizado de forma modular para garantir a escalabilidade e manutenção do código:
- `home.py`: Arquivo principal e ponto de entrada da aplicação.
- `pages/`: Diretório contendo as páginas secundárias do sistema.
- `servico/`: Módulo dedicado à lógica de banco de dados e funções auxiliares.

## 🔧 Como Executar o Projeto
1. Certifique-se de ter o Python instalado em sua máquina.
2. Instale as bibliotecas necessárias:
   ```bash
   pip install streamlit requests pandas

