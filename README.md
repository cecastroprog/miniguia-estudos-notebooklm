# 📘 Miniguia de Estudos: Python Aplicado a Dados e Cibersegurança

> **Projeto Prático — Desafio DIO:** Explorando o Poder do NotebookLM para Criação de Cadernos Temáticos Inteligentes.

---

## 📌 Contexto e Objetivos

### 🎯 Contexto
Com a ascensão da Inteligência Artificial Generativa e a necessidade constante de análise estratégica de informações, a linguagem **Python** consolidou-se como ferramenta indispensável para integração entre **Análise de Dados**, **Automação** e **Cibersegurança**.

Este repositório documenta a criação e estruturação de um **Caderno Temático no NotebookLM** (Google), desenvolvido como um assistente de estudos inteligente para centralizar, cruzar e sintetizar documentações técnicas, artigos e códigos focados em Python.

### 🚀 Objetivos de Estudo
1. **Sintetizar Fundamentos e Ferramentas:** Mapear o ecossistema Python voltado à manipulação de dados (`Pandas`, `NumPy`), análise de logs e automação.
2. **Potencializar o Aprendizado com GenAI:** Utilizar o NotebookLM para realizar consultas contextuais, gerar resumos executivos e criar questionários de fixação baseados exclusivamente nas fontes carregadas.
3. **Consolidar Práticas de Estudo Contínuo:** Estabelecer um fluxo de trabalho onde ferramentas de IA atuem como copilotos na jornada de transição e aprimoramento em Dados e Cibersegurança.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **[NotebookLM](https://notebooklm.google.com/):** Plataforma de IA baseada em fontes personalizadas para síntese e geração de insights.
* **[Python](https://www.python.org/):** Linguagem foco dos materiais de estudo agregados.
* **[Markdown](https://www.markdownguide.org/):** Documentação e estruturação deste miniguia.
* **[GitHub](https://github.com/):** Versionamento e compartilhamento do conhecimento.

---

## 📂 Curadoria de Fontes Selecionadas

Para garantir alta relevância, precisão e embasamento técnico nas consultas realizadas pelo NotebookLM, o caderno temático foi alimentado com as seguintes fontes primárias:

- 🐍 **[Tutorial Oficial do Python (v3.13)](https://docs.python.org/pt-br/3.13/tutorial/index.html):** Documentação oficial em português cobrindo sintaxe, estruturas de dados nativas, controle de fluxo e fundamentos da linguagem.
- 🔢 **[NumPy Basics: Broadcasting Guide](https://numpy.org/doc/stable/user/basics.broadcasting.html):** Documentação técnica do NumPy detalhando o funcionamento de operações de *broadcasting* entre arranjos multidimensionais para computação numérica eficiente.
- 📊 **[Pandas Cheat Sheet (Dataquest)](https://www.dataquest.io/wp-content/uploads/2024/10/Pandas-Cheat-Sheet.pdf):** Guia rápido e prático de referência cobrindo manipulação, filtragem, transformação e limpeza de estruturas de dados (*DataFrames* e *Series*).
- 🛡️ **[Análise de Logs de Rede Sem Fio (Artigo Acadêmico / PDF)](./analise_logs_rede.pdf):** Estudo focado em automação, processamento de logs e segurança da informação aplicada à infraestrutura de TI.

---

## 💡 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta etapa, explorei como refinar as perguntas no NotebookLM para extrair respostas precisas e estritamente baseadas nos documentos carregados.

### 🧪 Teste 1: Comparativo de Estruturas de Dados
* **Prompt Inicial (Genérico):** `"Me fale sobre listas e tuplas em python."`
* **Resultado / Dificuldade:** A resposta foi muito básica e não conectou o uso das estruturas ao contexto de Análise de Dados.
* **Prompt Refinado (Eficaz):** `"Com base na documentação do Python carregada, crie uma tabela comparativa entre Listas, Tuplas e Dicionários focando em mutabilidade, performance e casos de uso típicos em análise de dados."`
* **Aprendizado:** Prompts que especificam a estrutura de saída (ex: tabela) e a aplicação prática (ex: análise de dados) trazem respostas significativamente mais úteis.

### 🧪 Teste 2: Análise de Logs de Cibersegurança
* **Prompt Inicial (Genérico):** `"Como o artigo analisa os logs de rede?"`
* **Resultado / Dificuldade:** O NotebookLM trouxe um resumo genérico sem citar os métodos ou ferramentas específicas usadas no estudo.
* **Prompt Refinado (Eficaz):** `"Extraia do artigo 'Análise de Logs de Rede' o passo a passo utilizado para o tratamento de dados não estruturados de logs de rede, citando as métricas de segurança identificadas e como Python auxilia na tomada de decisão."`
* **Aprendizado:** Citar o nome da fonte exata e pedir o passo a passo obriga a IA a realizar uma leitura profunda no PDF sem alucinações fora de escopo.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📄 Resumo Estruturado dos Tópicos
* **Fundamentos e Estruturas:** O aprendizado de Python para Dados inicia na escolha correta da estrutura de dados. Listas para coleções mutáveis de itens, Tuplas para imutabilidade e Dicionários para mapeamentos chave-valor.
* **Vetorização e Broadcasting (NumPy):** O *broadcasting* permite que o NumPy realize operações aritméticas entre arranjos de formatos diferentes sem a necessidade de loops `for` explícitos em Python, otimizando drasticamente a performance computacional.
* **Manipulação de Dados (Pandas):** Através de *DataFrames*, é possível filtrar, agrupar (`groupby`), tratar valores nulos e consolidar dados brutos em relatórios analíticos.
* **Análise de Logs & Cibersegurança:** O uso de Python para parsing de arquivos de log possibilita identificar acessos não autorizados, comportamentos anômalos na rede e automatizar alertas de segurança.

### 📚 Glossário de Conceitos Aprendidos
* **Broadcasting:** Mecanismo do NumPy que alinha dimensões de matrizes/vetores para executar operações elemento a elemento de forma otimizada.
* **DataFrame:** Estrutura de dados bidimensional, mutável e rotulada (semelhante a uma planilha/tabela de banco de dados) disponibilizada pelo Pandas.
* **Mutabilidade:** Propriedade de um objeto em Python de ter seu conteúdo alterado após a criação (ex: Listas são mutáveis; Tuplas são imutáveis).
* **Parsing de Logs:** Processo de leitura, filtragem e conversão de dados brutos de texto de logs em um formato estruturado para análise.

### 🔄 Prompts Reutilizáveis para Revisão Futura
```text
1. "Elabore um questionário com 5 perguntas de múltipla escolha e gabarito comentado sobre operações com DataFrames no Pandas com base nas fontes."
2. "Explique o conceito de broadcasting no NumPy como se eu fosse um iniciante, utilizando uma analogia simples e um exemplo de código de 3 linhas."
3. "Gere um checklist de segurança em Python para validação e sanitização de dados de entrada em scripts de automação."
```
### 📊 Principais Insights e Aprendizados

* **Análise Contextual Sem Ruído:** O grande diferencial do NotebookLM em relação aos chats tradicionais é a capacidade de responder estritamente com base nos documentos carregados, eliminando alucinações de informações fora de contexto.
* **Agilidade no Estudo Ativo:** A geração automática de perguntas, flashcards e resumos acelerou a fixação da sintaxe da linguagem e o entendimento de bibliotecas de manipulação de dados.
* **Visão Transversal:** Permitiu unir os conceitos de lógica de programação em Python recém-adquiridos a cenários práticos de automação e segurança da informação exigidos no Bootcamp Bradesco.

---

## 📈 Conclusão e Próximos Passos

O uso do NotebookLM provou ser uma estratégia altamente eficiente para organizar a rotina de estudos em tecnologia, atuando como um repositório vivo de conhecimento que evolui conforme novas fontes são adicionadas.

**Próximos passos:**
- [ ] Expandir o caderno com fontes avançadas sobre consumo de APIs e raspagem de dados (*Web Scraping*).
- [ ] Aplicar os conceitos sintetizados no desenvolvimento do projeto final (**Assistente Virtual Financeiro**).
- [ ] Construir scripts práticos em Python e versioná-los neste/em novos repositórios.

---

## ✉️ Contato e Conexão

Desenvolvido por **Carlos Eduardo de Castro** 👋

- **LinkedIn:** [Meu Perfil do LinkedIn](https://www.linkedin.com/in/carlos-eduardo-de-castro-a4a94b27)
- **GitHub:** [@cecastroprog](https://github.com/cecastroprog)
