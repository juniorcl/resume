# Clébio Júnior

### Engenheiro de IA

E-mail: clebiomojunior@gmail.com

LinkedIn: linkedin.com/in/clebiojunior

GitHub: github.com/juniorcl

Blog: medium.com/@juniorcl

## Resumo Profissional

Engenheiro de IA e Cientista de Dados com mais de 5 anos de experiência no desenvolvimento de soluções de inteligência artificial, machine learning e NLP aplicadas a problemas reais de negócio. Experiência na construção de aplicações com LLMs, incluindo sistemas de RAG (Retrieval-Augmented Generation) com busca híbrida, embeddings, bancos vetoriais FAISS e orquestração de fluxos com LangChain e LangGraph. Atuação prática em pipelines de ingestão e processamento de documentos não estruturados com OCR e NLP, além de modelagem preditiva de ponta a ponta, do problema de negócio ao deploy em API. Mestre em Ciências Naturais, com sólida base quantitativa e foco em soluções mensuráveis e confiáveis.

## Competências Técnicas

- **IA Generativa e LLMs:** RAG (Retrieval-Augmented Generation), LangChain, LangGraph, Ollama, LLMs locais e via API, Prompt Engineering, Embeddings, Sentence Transformers, Busca Semântica, Busca Híbrida (BM25 + vetorial), Reranking com Cross-Encoder, Chunking e Indexação de Documentos, Agentes e Fluxos com Estado
- **Bancos Vetoriais e Recuperação:** FAISS, Indexação Vetorial, BM25, Avaliação de Sistemas de Recuperação
- **NLP:** spaCy, NLTK, Classificação de Texto, Reconhecimento de Entidades (NER), Tokenização, Lematização, Sumarização de Textos, OCR (Tesseract / pytesseract), pdfplumber, Expressões Regulares (Regex)
- **Machine Learning:** scikit-learn, XGBoost, LightGBM, CatBoost, Aprendizado Supervisionado e Não Supervisionado, Modelagem Preditiva, Feature Engineering, Otimização de Hiperparâmetros (Optuna), Interpretabilidade (SHAP)
- **Linguagens de Programação:** Python, SQL, C/C++
- **Engenharia e Deploy:** Flask, APIs REST, Docker, Git, GitHub, Linux, MLOps, Versionamento e Serviço de Modelos
- **Dados e Análise:** pandas, NumPy, SciPy, Análise Exploratória de Dados, Séries Temporais, Estatística Aplicada, SAS, Jupyter Notebook

## Experiência Profissional

### Cientista de Dados | Soluções de IA e NLP — Vert Analytics
**Outubro/2024 – Atual | Remoto**

- Desenvolvi sistema de recomendação de defesas jurídicas baseado em NLP, embeddings e busca vetorial com FAISS, que sugere automaticamente a tese de defesa mais adequada para cada parecer, reduzindo o tempo de pesquisa manual e aumentando a acurácia das decisões.
- Construí pipelines de ingestão e estruturação de documentos não estruturados em PDF, incluindo arquivos digitalizados, combinando pdfplumber, Tesseract OCR e expressões regulares para transformar texto bruto em dados analisáveis.
- Implementei solução de classificação e análise de texto com spaCy para categorizar reclamações de clientes em redes sociais, aplicando tokenização, lematização, remoção de stopwords e normalização, gerando insights estratégicos para produto e atendimento.
- Conduzo análises de séries temporais e detecção de anomalias sobre os dados extraídos, com entrega de resultados em dashboards interativos em SAS.

### Cientista de Dados — Datarisk
**Janeiro/2022 – Agosto/2024 | Remoto**

- Desenvolvi modelo de credit scoring baseado em machine learning para estimar a probabilidade de pagamento a partir do histórico financeiro, aprimorando os critérios de concessão de crédito e a eficiência da gestão de risco.
- Criei modelo de regressão para previsão de volume de vendas, com pré-processamento, feature engineering e otimização de hiperparâmetros, passando a apoiar o planejamento estratégico da área comercial.
- Apliquei algoritmos de clustering para segmentação da base de clientes, identificando perfis comportamentais distintos e viabilizando estratégias de relacionamento direcionadas.
- Atuei em todo o ciclo de vida dos modelos, da definição do problema de negócio à validação dos resultados junto às áreas usuárias.

### Cientista de Dados — Be.X!
**Março/2021 – Janeiro/2022 | Remoto**

- Desenvolvi algoritmos de machine learning para geração automatizada de insights a partir de dados estruturados e não estruturados de clientes.
- Processei grandes volumes de dados textuais não estruturados com expressões regulares para limpeza e extração de informação, aumentando significativamente a disponibilidade de dados para tomada de decisão.
- Implementei algoritmos de detecção de outliers baseados em regras de negócio para sinalizar anomalias operacionais, contribuindo para a mitigação de riscos.
- Desenvolvi modelo preditivo de probabilidade de atraso na entrega de pedidos, utilizando métricas de ranqueamento para priorizar casos de maior risco e viabilizar ações preventivas na operação logística.

## Projetos Selecionados

- **Legal Decision RAG — Sistema de RAG Híbrido para Documentos Jurídicos** — Sistema de Retrieval-Augmented Generation para consulta em linguagem natural a decisões administrativas de recursos de multas. Arquitetura completa com ingestão e chunking de PDFs, geração de embeddings, índice vetorial FAISS, recuperação híbrida (BM25 + busca semântica), reranking com cross-encoder e orquestração em LangGraph, incluindo roteamento de consultas, decomposição de perguntas complexas, reescrita de queries ambíguas e loop de crítica das respostas geradas. Execução com LLMs locais via Ollama. (github.com/juniorcl/legal-decision-rag)
- **DSToolkit — Biblioteca Python de Ciência de Dados** — Biblioteca modular com API inspirada no scikit-learn, reunindo pipelines de AutoML para classificação, regressão e clustering, otimização de hiperparâmetros, métricas de avaliação (ROC, PR, KS, curvas de calibração) e ferramentas de interpretabilidade e feature engineering. (github.com/juniorcl/data-science-toolkit)
- **Previsão de Prazo de Entrega em E-commerce (Olist)** — Pipeline completo de ML com dados consumidos via SQL de banco containerizado em Docker, seleção de variáveis com mRMR, modelo LightGBM otimizado com Optuna e interpretabilidade com SHAP. Redução de 66% no MAE frente à regra de negócio vigente, com deploy em API Flask. (github.com/juniorcl/olist-delivery-forecast)
- **Detecção de Fraude em Transações** — Modelo de classificação em dados altamente desbalanceados com feature engineering, seleção de variáveis com Boruta e tuning de hiperparâmetros. O modelo final em XGBoost alcançou 91,5% de acurácia balanceada e 94,4% de precisão em dados não vistos. Projeto com mais de 220 estrelas no GitHub. (github.com/juniorcl/transaction-fraud-detection)
- **Reconhecimento de Textos com OCR** — Estudo aplicado de extração de texto de imagens e documentos digitalizados com Tesseract e Python, base técnica para os pipelines de documentos usados em produção.

Portfólio completo disponível em juniorcl.github.io e github.com/juniorcl.

## Formação Acadêmica

**Mestrado em Ciências Naturais — Ciência Ambiental**
Universidade Estadual do Norte Fluminense (UENF) | 2017 – 2019

**Licenciatura em Ciências Naturais — Física**
Instituto Federal Fluminense (IFF) | 2010 – 2016

## Certificações e Cursos

- Quickstart: LangGraph Essentials — Python
- LangChain Academy — LangGraph
- Reconhecimento de Textos com OCR e Python
- Sumarização de Textos com Processamento de Linguagem Natural
- Clustering: Extraindo Padrões de Dados
- MLOps: Deploy de Modelos e APIs de Machine Learning
- Formação em Ciência de Dados — Comunidade DS

## Idiomas

- **Português:** Nativo
- **Inglês:** Profissional completo
- **Esperanto:** Profissional completo
