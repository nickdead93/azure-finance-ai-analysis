# 📊 Azure AI na Controladoria: Análise de Sentimentos e Speech-to-Text

Este repositório documenta o laboratório prático de **Azure Cognitive Services (Speech & Language Studio)**, com foco na aplicação de Inteligência Artificial para Finanças Corporativas e FP&A (Planejamento e Análise Financeira).

## 🎯 Objetivo Financeiro (Business Case)
Na Controladoria moderna, grande parte dos dados que impactam o DRE e o Fluxo de Caixa não estão em planilhas, mas em dados não estruturados (textos e áudios). O objetivo deste lab foi explorar como a IA pode analisar:
1. **Language Studio:** Análise de sentimentos em feedbacks de clientes e e-mails de negociação de fornecedores para prever riscos de *Churn* (perda de receita) ou quebras de contrato.
2. **Speech Studio:** Transcrição automática de *Earnings Calls* (reuniões de apresentação de resultados) e reuniões de conselho (*Board Meetings*) para extração rápida de compromissos financeiros e *guidance*.

## 🛠️ Ferramentas Utilizadas
- **Microsoft Azure Portal:** Criação e gestão dos recursos de IA.
- **Azure Language Studio:** Processamento de Linguagem Natural (NLP) para extração de entidades, palavras-chave e análise de sentimento.
- **Azure Speech Studio:** Conversão de Áudio para Texto (Speech-to-Text) de alta precisão.

## 💡 Insights e Possibilidades para FP&A
Durante o laboratório, identifiquei oportunidades claras de integração destas tecnologias com as rotinas de uma Diretoria Financeira:

* **Auditoria de Variações (Budget vs Actuals):** Automatizar a leitura de centenas de justificativas textuais de gestores de centro de custo, classificando se as justificativas para estouro de orçamento são baseadas em fatores internos ou externos (macroeconomia).
* **Análise de Risco de Crédito:** Utilizar a extração de frases-chave (*Key Phrase Extraction*) em relatórios de auditores independentes e notas explicativas para mapear riscos ocultos de inadimplência.
* **Integração com Power BI:** O *output* (arquivos JSON com o grau de "sentimento" positivo/negativo) do Azure pode ser conectado via Power Query ao Power BI para cruzar "Sentimento do Cliente" vs "Queda de Receita" na mesma tela.

## 📝 Conclusão
A proficiência em ferramentas de IA Generativa e Cognitiva na nuvem (Azure) deixa de ser uma exclusividade de times de TI e passa a ser uma alavanca estratégica para profissionais de Finanças e Controladoria que buscam governança, agilidade e previsibilidade.
