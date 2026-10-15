# 📧 Automação de Relatórios de Vendas via Python e Pandas

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)

## 🎯 Objetivo do Projeto
Este projeto consiste em um script de automação em Python desenvolvido para consolidar dados diários de vendas a partir de bases de dados em planilhas (.xlsx) e gerar relatórios executivos consolidados, enviando-os automaticamente via e-mail para a diretoria/gerência.

A solução reduz o tempo gasto com tarefas operacionais repetitivas de análise de dados e montagem manual de relatórios.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas
- **Python 3.x**: Linguagem principal do projeto.
- **Pandas**: Leitura, manipulação, limpeza e agregação de dados.
- **PyWin32 (`win32com.client`)**: Integração automatizada com o Microsoft Outlook para disparo dos relatórios.

---

## 📊 Indicadores Gerados Automaticamente
O script processa a base de dados e calcula as seguintes métricas por estabelecimento/loja:
1. **Faturamento Total** por Loja.
2. **Quantidade de Produtos Vendidos** por Loja.
3. **Ticket Médio** (Valor Médio por Venda) por Loja.

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/Dellarno221/automacao_email1.0.git](https://github.com/Dellarno221/automacao_email1.0.git)
   cd automacao_email1.0
