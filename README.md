<h1 align="center">Jhonnes Amaral Soares Toledo</h1>

<p align="center">
  <strong>Cientista de Dados</strong> · Físico (MSc, UFJF) — SQL, modelagem preditiva e aplicações em produção
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jhastoledo"><img alt="LinkedIn: jhastoledo" src="https://img.shields.io/badge/LinkedIn-jhastoledo-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:jas_toledo@hotmail.com?subject=Contato%20via%20GitHub"><img alt="E-mail: jas_toledo@hotmail.com" src="https://img.shields.io/badge/E--mail-jas__toledo%40hotmail.com-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white"></a>
  <a href="#projetos-em-destaque"><img alt="Projetos em destaque" src="https://img.shields.io/badge/Projetos-em%20destaque-1F6FEB?style=flat-square&logo=github&logoColor=white"></a>
  <img alt="Localização: Juiz de Fora, MG — aberto a realocação" src="https://img.shields.io/badge/Juiz%20de%20Fora%2C%20MG-aberto%20a%20realoca%C3%A7%C3%A3o-2DA44E?style=flat-square">
</p>

---

Mestre em Física pela UFJF e especialista em Ciência de Dados, com portfólio de projetos ponta a ponta — do modelo relacional em SQL ao aplicativo publicado.

Trabalho com dados tabulares, séries temporais e texto em português, sempre com a mesma disciplina: **baseline honesto antes do modelo complexo, a métrica certa para o problema** (PR-AUC sob desbalanceamento, QWK em alvo ordinal, RMSPE em previsão de vendas) **e SHAP para explicar o que o modelo aprendeu.**

Procuro posição de **Cientista de Dados Júnior** ou **Analista de Dados**.

---

## Stack

**Núcleo**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=000000)

**Modelagem**

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-1A7F5A?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-2E7D32?style=flat-square)
![statsmodels](https://img.shields.io/badge/statsmodels-2C5F8A?style=flat-square)
![Prophet](https://img.shields.io/badge/Prophet-1877F2?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-BERTimbau-6C3483?style=flat-square)

**Interpretabilidade e otimização**

![SHAP](https://img.shields.io/badge/SHAP-6D28D9?style=flat-square)
![Optuna](https://img.shields.io/badge/Optuna-3860AB?style=flat-square)
![Ray Tune](https://img.shields.io/badge/Ray%20Tune-028CF0?style=flat-square&logo=ray&logoColor=white)

**Visualização e geoespacial**

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square)
![Folium](https://img.shields.io/badge/Folium-77B829?style=flat-square)

**Entrega**

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![JupyterLab](https://img.shields.io/badge/JupyterLab-F37626?style=flat-square&logo=jupyter&logoColor=white)
![conda](https://img.shields.io/badge/conda-44A833?style=flat-square&logo=anaconda&logoColor=white)

---

## Projetos em destaque

| Projeto | Problema e resultado | Técnicas |
|---|---|---|
| **Olist — Analytics em SQL**<br>[repositório](https://github.com/jhastoledo/olist_sql_analytics) · [30 consultas](https://github.com/jhastoledo/olist_sql_analytics/tree/main/sql) | Modelagem relacional de 9 tabelas com PK/FK sobre ~100 mil pedidos de e-commerce. **17,6% dos vendedores concentram 80% da receita**; atraso de entrega só derruba a nota acima de 7 dias (média cai de 4,29 para 1,71). | SQL (CTEs, window functions, subqueries correlacionadas, `EXPLAIN QUERY PLAN`), SQLite, pandas |
| **Rossmann — previsão de vendas**<br>[repositório](https://github.com/jhastoledo/rossmann_forecast) · [app](https://rossmannforecast-mjpv8pupftrelfitrrm44n.streamlit.app/) | Previsão de 42 dias para **1.115 lojas**. Um LightGBM global atinge **RMSPE 0,1321 / MAPE 9,7%** e vence o SARIMAX especializado em 3 das 4 séries — usando 1 modelo onde a via estatística exigiria 1.115. | Validação walk-forward, guarda anti-vazamento, Ray Tune + Optuna, SHAP |
| **King County — preço de imóveis**<br>[repositório](https://github.com/jhastoledo/house_prices_kc) · [app](https://housepriceskc-4dp6hcnpzqvubocewirhfh.streamlit.app/estimador) | Regressão sobre 21.613 imóveis de Seattle: **R² 0,911 e MAPE 11,5%** no teste. O SHAP mostra a **latitude como variável nº 1**, à frente de tamanho e qualidade — uma fronteira norte-sul de preço. | XGBoost, Ray Tune + Optuna, transformação log, GeoPandas, Folium, estimador por clique no mapa |
| **Olist — PLN de avaliações (pt-BR)**<br>[repositório](https://github.com/jhastoledo/olist_reviews_nlp) · [app](https://olistreviewsnlp-hgzovmxzounkw66isguhmt.streamlit.app/) | Previsão de nota 1–5★ a partir do texto, alvo **ordinal**. BERTimbau **QWK 0,8640** contra 0,8169 do TF-IDF + SVM — mas o SVM é ~147x mais rápido e dispensa GPU: a escolha depende do cenário, não só da métrica. | PyTorch, BERTimbau (fine-tuning), TF-IDF, QWK, análise de erro comparada |
| **Fraude em cartão de crédito**<br>[repositório](https://github.com/jhastoledo/credit_card_fraud) · [app](https://creditcardfraud-cmcvsav6capkwmbjkeuthe.streamlit.app/) | 284.807 transações com desbalanceamento de **578:1**. XGBoost afinado: **PR-AUC 0,826** no teste, recall 0,811 e precisão 0,951 no limiar 0,264. | `Pipeline` sklearn, Optuna, seleção de limiar, PR-AUC em vez de ROC-AUC, SHAP |
| **iFood — propensão de resposta em CRM**<br>[repositório](https://github.com/jhastoledo/ifood-crm-case) · [app](https://ifood-crm-case-jgmyhbrhvezg2ynhfptape.streamlit.app/) | Campanha piloto com 2.240 clientes deu prejuízo de **-3.046 MU**. Otimizando o limiar por lucro (0,45), o modelo entrega **+279 MU** — 90% do teto teórico. | Regressão logística, `Pipeline` sklearn, PR-AUC, limiar por função de lucro, K-Means, SHAP |

Também no perfil: [Wine Quality — capstone](https://github.com/jhastoledo/wine_quality_capstone) (regressão, classificação e clusterização no mesmo dado) · [IBM HR Attrition](https://github.com/jhastoledo/ibm-attrition) · [Segmentação de clientes — RFM](https://github.com/jhastoledo/customer_segmentation_online_retail).

---

## Como trabalho

Todos os projetos acima seguem a mesma arquitetura, e ela é deliberada:

- **6 a 7 notebooks numerados**, na ordem EDA → engenharia de atributos → *baseline* → tuning → interpretabilidade → relatório. Dá para ler a decisão, não só o resultado.
- **`Pipeline` do scikit-learn como espinha dorsal.** Pré-processamento e modelo viajam juntos em um único artefato: dado cru entra, previsão sai, sem transformação solta fora do treino.
- **Pacote `src/` modular** (`data`, `features`, `metrics`, `config`, `report`) — o notebook orquestra, o código mora em módulo testável.
- **Baseline explícito sempre.** *Dummy*, *seasonal naive* ou classe majoritária, para que o ganho do modelo seja um número, não uma impressão.
- **App Streamlit publicado**, porque modelo que não sai do notebook não vale nada para quem vai usá-lo.

---

## Formação

**Especialização em Ciência de Dados** — UNINASSAU · **Mestrado e Bacharelado em Física** — UFJF

Os anos de Física aplicada são a base direta do trabalho com dados: modelagem matemática de sistemas complexos, rigor estatístico e o hábito de atacar problema mal definido até ele virar pergunta respondível.

---

## Contato

Estou em busca de posição de **Cientista de Dados Júnior** ou **Analista de Dados** — presencial em Juiz de Fora e região, remoto ou com realocação para qualquer estado.

- **LinkedIn:** [linkedin.com/in/jhastoledo](https://www.linkedin.com/in/jhastoledo)
- **E-mail:** [jas_toledo@hotmail.com](mailto:jas_toledo@hotmail.com?subject=Contato%20via%20GitHub)
- **Disponibilidade:** imediata

Se algum projeto acima for parecido com um problema seu, me chame — explico as decisões por trás dele em 15 minutos.
