# 📊 Azure AI na Controladoria: Análise de Sentimentos e Speech-to-Text

Este repositório documenta meu laboratório prático de **Azure Cognitive Services (Speech & Language Studio)**. O foco desta execução foi aplicar Inteligência Artificial em cenários reais de Finanças Corporativas e FP&A (Planejamento e Análise Financeira).

## 🎯 Objetivo Financeiro (Business Case)
Na Controladoria moderna, grandes riscos estão ocultos em dados não estruturados. O objetivo foi validar como a IA da Microsoft pode analisar:
1. **Language Studio:** Avaliar o sentimento em textos (ex: justificativas de estouro de orçamento ou e-mails de negociação com fornecedores).
2. **Speech Studio:** Transcrever áudios longos (ex: *Earnings Calls* ou Reuniões de Conselho) para extração rápida de compromissos financeiros.

## 🚀 O Que Eu Fiz na Prática (Execução do Laboratório)
Durante este projeto prático, realizei as seguintes etapas no ambiente Azure:
1. **Provisionamento de Recursos:** Criei os recursos de `Cognitive Services` no portal do Azure, garantindo a configuração correta de chaves de API e região.
2. **Teste de NLP (Language Studio):** - Inseri textos simulando justificativas de gestores para variações de *Budget* (Orçado vs Realizado).
   - Utilizei a ferramenta para extrair Entidades, Frases-chave e analisar o Sentimento (Positivo/Negativo/Neutro) para classificar automaticamente o nível de risco daquela justificativa.
3. **Teste de Áudio (Speech Studio):**
   - Utilizei o recurso *Speech-to-Text* (Conversão de fala em texto) com áudios simulando apresentações de resultados trimestrais.
   - Avaliei a precisão da IA em capturar jargões de negócios e números de forma estruturada.

## 🧠 O Que Eu Aprendi (Visão de Controller)
- **Agilidade na Auditoria:** A transcrição automatizada reduz drasticamente o tempo gasto mapeando atas de reuniões para encontrar promessas de redução de custos (Cost Savings).
- **Análise Preditiva de Risco:** Integrar a análise de sentimentos do Azure com o Power BI permite que a equipe de FP&A cruze dados financeiros quantitativos com dados qualitativos de mercado de forma automática.
- **Governança de Dados em Nuvem:** Entendi como estruturar serviços cognitivos na nuvem mantendo a segurança e o controle de acesso exigidos pelo *Compliance* financeiro.

## 🛠️ Ferramentas Utilizadas
- Microsoft Azure Portal
- Azure Language Studio
- Azure Speech Studio
