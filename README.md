# KYC-Navigator 🧭

Caderno temático desenvolvido no NotebookLM com foco em **KYC (Know Your Customer)** — 
processo regulatório essencial no mercado financeiro para identificação, análise e 
classificação de clientes e seus respectivos perfis de risco.

[Acessar o KYC-Navigator](https://notebooklm.google.com/seu-link-aqui)

---

## 📌 Contexto e Objetivos

O processo de **KYC (Know Your Customer)** é uma etapa regulatória obrigatória 
no mercado financeiro, presente em bancos, fintechs, corretoras e demais 
instituições que captam clientes. Seu objetivo central é identificar, analisar 
e classificar clientes e seus respectivos perfis de risco, garantindo conformidade 
com as exigências de PLD/FT (Prevenção à Lavagem de Dinheiro e Financiamento 
ao Terrorismo).

Apesar de sua importância, o KYC ainda representa uma dor operacional real 
para muitos profissionais — seja pela complexidade regulatória, pelo volume 
de informações a serem processadas ou pela necessidade de atualização constante 
frente às normativas vigentes.

O **KYC-Navigator** foi desenvolvido como um caderno temático no NotebookLM, 
com o objetivo de organizar e centralizar conhecimento relevante sobre o tema, 
auxiliando profissionais financeiros na consulta e compreensão do processo KYC. 
A ferramenta não substitui o julgamento profissional — retorna fatos, não verdades.

O caderno foi estruturado para atender dois perfis:

- **Iniciantes** — estagiários e profissionais em início de carreira que buscam 
compreender os fundamentos do KYC e do ambiente regulatório brasileiro.
- **Consolidados** — analistas e gestores que necessitam de referências 
regulatórias e operacionais atualizadas para apoio no dia a dia.
---

## 📚 Curadoria de Fontes

As fontes foram selecionadas para atender dois perfis de profissionais: 
iniciantes que buscam compreender os fundamentos do KYC, e profissionais 
consolidados que necessitam de referências regulatórias e operacionais atualizadas.

---

### 1. 🏛️ Carta de Serviço do COAF
**Nível:** Introdutório  
**Link:** [gov.br/coaf](https://www.gov.br/pt-br/orgaos/conselho-de-controle-de-atividades-financeiras)

Esta fonte foi escolhida por ser o ponto de entrada ideal para compreender 
o principal órgão regulador de PLD/FT no Brasil. Apresenta a missão, 
estrutura e serviços do COAF, oferecendo contexto institucional essencial 
antes de avançar para as normativas técnicas.

---

### 2. 📋 Resolução COAF nº 041/2022
**Nível:** Regulatório Nacional  
**Link:** [Resolução COAF 041](https://www.gov.br/coaf/pt-br/acesso-a-informacao/Institucional/a-atividade-de-supervisao/regulacao/supervisao/normas-1/resolucao-coaf-no-041-de-08-08.2022)

Esta fonte foi escolhida por estabelecer obrigações específicas relacionadas 
à Prevenção à Lavagem de Dinheiro e ao Financiamento ao Terrorismo (PLD/FT), 
tema diretamente vinculado ao processo KYC. Normativa nacional vigente e de 
consulta obrigatória para profissionais da área.

---

### 3. 🏦 Circular BACEN nº 3.978/2020
**Nível:** Regulatório Nacional  
**Link:** [Circular BACEN 3.978](https://abac.org.br/servicos/Cir0090A-CIRCULARN%C2%B03.978,DE23DEJANEIRODE2020.pdf)

Esta fonte foi escolhida por ser a principal regulamentação do Banco Central 
do Brasil sobre política de PLD/FT para instituições financeiras. Define os 
procedimentos e controles internos exigidos, representando a base operacional 
do KYC no contexto bancário brasileiro.

---

### 4. 🌍 FATF Recommendations (40 Recomendações do GAFI)
**Nível:** Internacional / Profundo  
**Link:** [FATF Recommendations](https://www.fatf-gafi.org/content/dam/fatf-gafi/recommendations/fatf-recommendations-2012.pdf)

Esta fonte foi escolhida por representar o padrão global de referência em 
combate à lavagem de dinheiro e financiamento ao terrorismo. As 40 
recomendações do GAFI são a base sobre a qual todas as regulamentações 
nacionais, incluindo as brasileiras, são construídas.

---

### 5. 🔍 Beneficial Ownership of Legal Persons — FATF/GAFI
**Nível:** Internacional / Técnico  
**Link:** [Beneficial Ownership](https://www.fatf-gafi.org/content/dam/fatf-gafi/guidance/Guidance-Beneficial-Ownership-Legal-Persons.pdf.coredownload.pdf)

Esta fonte foi escolhida por tratar especificamente da identificação de 
beneficiários finais de pessoas jurídicas — um dos aspectos mais complexos 
e críticos do processo KYC. Guia técnico do GAFI com aplicação direta na 
análise e classificação de risco de clientes corporativos.

---

## 🧪 Engenharia de Prompts e Cicatrizes

### Perguntas e Respostas

---

**Prompt 1 — Introdutório**
> "O que é KYC e qual é o seu papel no mercado financeiro brasileiro?"

**Resumo da resposta:** O NotebookLM definiu KYC como conjunto de procedimentos 
para identificar, qualificar e classificar clientes, regulamentado pela Circular 
BACEN 3.978 e Resolução COAF 41. Estruturou o papel do KYC em seis frentes: 
identificação, beneficiário final, qualificação e risco, monitoramento contínuo, 
reporte ao COAF e mitigação de riscos institucionais.  
**Fontes citadas:** Circular BACEN nº 3.978, Resolução COAF nº 41.

---

**Prompt 2 — Regulatório Nacional**
> "Quais são as obrigações específicas que uma instituição financeira brasileira 
deve cumprir segundo a Circular BACEN 3.978 no processo de KYC?"

**Resumo da resposta:** A resposta detalhou cinco obrigações principais — 
identificação de clientes com dados mínimos exigidos, qualificação com análise 
de PEP, identificação do beneficiário final com limite de 25% de participação, 
classificação de risco e formalização via manual aprovado pela diretoria.  
**Fontes citadas:** Circular BACEN nº 3.978.

---

**Prompt 3 — Cruzamento de Fontes**
> "Como o processo de identificação de beneficiário final de pessoas jurídicas 
se relaciona com as recomendações do GAFI?"

**Resumo da resposta:** O NotebookLM cruzou duas fontes simultaneamente, 
relacionando a Circular BACEN 3.978 com as Recomendações 10 e 24 do GAFI. 
Destacou a abordagem multifacetada do GAFI, os três critérios de qualidade 
da informação (adequada, acurada e atualizada) e a abordagem baseada em risco.  
**Fontes citadas:** Circular BACEN nº 3.978, FATF Recommendations, 
Beneficial Ownership of Legal Persons.

---

**Prompt 4 — Avançado**
> "Quais são os indicadores de risco que uma instituição financeira deve 
considerar para classificar um cliente como alto risco no processo de KYC, 
e como isso impacta os controles aplicados?"

**Resumo da resposta:** Listou indicadores de alto risco — PEP, estruturas 
societárias complexas, shell companies, clientes não residentes e capacidade 
financeira incompatível. Detalhou seis medidas de Devida Diligência Reforçada 
(EDD) aplicáveis, incluindo aprovação hierárquica, monitoramento intensificado 
e restrições operacionais.  
**Fontes citadas:** Circular BACEN nº 3.978, FATF Recommendations.

---

**Prompt 5 — Caso Real**
> "Um novo cliente pessoa jurídica solicitou abertura de conta. Durante o 
processo de KYC, identificou-se que o beneficiário final é uma Pessoa Exposta 
Politicamente. Quais são os passos que a instituição deve seguir?"

**Resumo da resposta:** Retornou sete passos sequenciais orientados à decisão 
— da conclusão da identificação à comunicação específica ao COAF, passando 
por aprovação hierárquica, verificação de origem dos recursos e monitoramento 
intensificado. Resposta mais aplicada e próxima do uso real da ferramenta.  
**Fontes citadas:** Circular BACEN nº 3.978, Resolução COAF nº 41, 
FATF Recommendations.

---

### ⚠️ Cicatrizes — Dificuldades Encontradas

**1. Processamento inicial lento**
Na primeira interação, o NotebookLM apresentou demora para retornar a resposta. 
Comportamento esperado no carregamento inicial das fontes, mas que pode 
confundir usuários menos familiarizados com a ferramenta.

**2. Limitação de julgamento**
O caderno retorna fatos baseados nas fontes carregadas — não emite opiniões 
nem recomendações. Em perguntas mais aplicadas, como o caso do PEP, a resposta 
é procedimental mas não substitui o julgamento profissional do analista.

**3. Dependência da qualidade das fontes**
A qualidade das respostas é diretamente proporcional à abrangência das fontes 
carregadas. Temas não cobertos pelas fontes resultam em respostas incompletas 
ou ausentes — reforçando a importância de uma curadoria criteriosa.
---

## 📖 Miniguia de Estudo

### 📝 Resumos Estruturados

**O que é KYC**
Conjunto de procedimentos obrigatórios adotados por instituições financeiras 
para identificar, qualificar e classificar clientes e seus perfis de risco. 
No Brasil é regulamentado principalmente pela Circular BACEN nº 3.978 e pela 
Resolução COAF nº 41, alinhadas às recomendações internacionais do GAFI.

**Pilares do KYC**
O processo se estrutura em cinco frentes: identificação e verificação do 
cliente, identificação do beneficiário final, qualificação e análise de risco, 
monitoramento contínuo e subsídio ao reporte de suspeitas ao COAF.

**Beneficiário Final**
Pessoa natural que em última instância possui ou controla uma pessoa jurídica. 
A Circular BACEN 3.978 exige que a cadeia societária seja analisada até o 
limite de 25% de participação. O GAFI reforça esse conceito nas Recomendações 
10 e 24, exigindo que a informação seja adequada, acurada e atualizada.

**Classificação de Risco**
Clientes são classificados em categorias de risco — baixo, médio ou alto — 
com base em seu perfil, localização geográfica e natureza das operações. 
Clientes de alto risco, como PEPs ou empresas com estruturas societárias 
complexas, estão sujeitos a Devida Diligência Reforçada (EDD).

**PEP e Devida Diligência Reforçada**
Pessoas Expostas Politicamente e seus relacionados exigem aprovação hierárquica 
superior, verificação da origem dos recursos, monitoramento intensificado e 
comunicação específica ao COAF quando necessário.

---

### 📚 Glossário

| Termo | Definição |
|---|---|
| **KYC** | Know Your Customer — processo de identificação, qualificação e classificação de clientes |
| **PLD/FT** | Prevenção à Lavagem de Dinheiro e ao Financiamento do Terrorismo |
| **PEP** | Pessoa Exposta Politicamente — agentes públicos e seus relacionados |
| **Beneficiário Final** | Pessoa natural que efetivamente possui ou controla uma pessoa jurídica |
| **CDD** | Customer Due Diligence — Devida Diligência do Cliente |
| **EDD** | Enhanced Due Diligence — Devida Diligência Reforçada, aplicada a clientes de alto risco |
| **COAF** | Conselho de Controle de Atividades Financeiras — órgão regulador brasileiro de PLD/FT |
| **GAFI/FATF** | Grupo de Ação Financeira — organismo internacional que define padrões globais de PLD/FT |
| **BACEN** | Banco Central do Brasil — regulador do sistema financeiro nacional |
| **Source of Wealth** | Origem do patrimônio do cliente |
| **Source of Funds** | Origem dos recursos envolvidos nas transações |
| **Nominee** | Acionista nominal — pessoa que figura como sócio em nome de outra |
| **Shell Company** | Empresa de fachada sem operações ou ativos reais |
| **Multi-pronged Approach** | Abordagem multifacetada do GAFI para coleta de informações sobre beneficiários finais |

---

### 🔁 Prompts Reutilizáveis

Perguntas que podem ser usadas para futuras consultas e revisões no KYC-Navigator:

1. "O que é KYC e qual é o seu papel no mercado financeiro brasileiro?"

2. "Quais são as obrigações específicas que uma instituição financeira brasileira 
deve cumprir segundo a Circular BACEN 3.978 no processo de KYC?"

3. "Como o processo de identificação de beneficiário final de pessoas jurídicas 
se relaciona com as recomendações do GAFI?"

4. "Quais são os indicadores de risco que uma instituição financeira deve 
considerar para classificar um cliente como alto risco no processo de KYC, 
e como isso impacta os controles aplicados?"

5. "Um novo cliente pessoa jurídica solicitou abertura de conta. Durante o 
processo de KYC, identificou-se que o beneficiário final é uma Pessoa Exposta 
Politicamente. Quais são os passos que a instituição deve seguir?"
---

## 🛠️ Tecnologias e Ferramentas

- [NotebookLM](https://notebooklm.google.com/) — Google
- GitHub — documentação e portfólio

---

*Projeto desenvolvido como parte do bootcamp Corpay/Sem Parar em parceria com a DIO.*
