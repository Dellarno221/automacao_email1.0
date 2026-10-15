# 📧 Automação de Relatórios de Vendas com Python e Pandas

[🇧🇷 Versão em Português](README.pt.md) | [🇺🇸 English Version](README.md)

---

## 🎯 Objetivo do Projeto
Este script de automação em Python foi desenvolvido para consolidar dados diários de vendas a partir de planilhas (.xlsx), calcular os principais indicadores de desempenho do negócio e gerar/enviar automaticamente um relatório executivo formatado por e-mail para a diretoria.

A solução reduz significativamente o tempo gasto com tarefas operacionais de análise de dados e montagem manual de relatórios.

---

## 🛠️ Tecnologias Utilizadas
- **Python 3.x**: Linguagem principal do projeto.
- **Pandas**: Leitura, manipulação, limpeza e agregação de dados.
- **PyWin32 (`win32com.client`)**: Integração automatizada com o Microsoft Outlook para envio dos e-mails.

---

## 📊 Indicadores Gerados Automaticamente
O script processa a base de dados e calcula as seguintes métricas por estabelecimento/loja:
1. **Faturamento Total** por loja.
2. **Quantidade de Produtos Vendidos** por loja.
3. **Ticket Médio** (Valor Médio por Venda) por loja.

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/Dellarno221/automacao_email1.0.git](https://github.com/Dellarno221/automacao_email1.0.git)
   cd automacao_email1.0
