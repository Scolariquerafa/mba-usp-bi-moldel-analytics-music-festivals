# Business Intelligence e IA para Maximizar a Performance de Marcas em Festivais de Música

**Autor:** Rafael de Sousa Scolarique
**Orientadora:** Liliana Fusco Hemzo
*Trabalho de Conclusão de Curso apresentado ao MBA em Business Intelligence & Analytics da Escola de Comunicações e Artes da Universidade de São Paulo (ECA/USP).*

---

## Visão Geral do Projeto

Este projeto não se caracteriza como um estudo de caso, mas sim como o desenvolvimento e a validação de um modelo analítico ponta-a-ponta projetado para aplicação em casos reais. O framework integra fontes de dados heterogêneas para otimizar a performance de marcas em grandes festivais de música. O objetivo é superar as análises descritivas realizadas de forma isolada, aplicando técnicas de Analytics e Inteligência Artificial para gerar uma visão 360° da jornada do cliente, extrair insights estratégicos acionáveis e maximizar a atuação das marcas nos megaeventos.

### Objetivos Específicos

- **Desenvolver um Pipeline de Dados:** Criar um fluxo de trabalho completo e reprodutível para geração, limpeza, enriquecimento e armazenamento de dados.
- **Integrar Fontes Heterogêneas:** Unificar dados estruturados e não estruturados para criar uma visão 360° do cliente.
- **Aplicar Modelos Preditivos:** Utilizar Machine Learning para quantificar os drivers de lealdade e segmentar o público em personas.
- **Gerar Insights Prescritivos:** Fornecer recomendações baseadas em simulações de cenários "what-if".

### Principais Insights Gerados

- **Desconexão Digital-Físico:** Comprovação de que o alto engajamento em campanhas digitais não possui correlação direta com a satisfação do cliente na experiência física.
- **Drivers de Lealdade:** Identificação, via Machine Learning, dos verdadeiros fatores que impulsionam a recomendação da marca.
- **ROI de Ações Prescritivas:** Simulação que demonstrou que a melhoria na qualidade dos brindes pode aumentar a propensão à recomendação em mais de 20%.
- **Personas de Clientes:** Segmentação do público em três personas distintas com perfis de consumo e satisfação diferentes.

### Tecnologias e Ferramentas

- **Linguagem:** Python 3.x
- **Bibliotecas Principais:** Pandas, NumPy, Scikit-learn, SHAP, Pysentimiento, Matplotlib, Seaborn, Plotly.
- **Ambiente:** Google Colab / Jupyter Notebook
- **Versionamento:** Git & GitHub

---

## Pipeline de Dados e Metodologia

O projeto foi implementado através de um pipeline de dados em Python, composto por cinco etapas sequenciais:

- 1_ Geração das bases sintéticas
- 2_ Unificação
- 3_ Pré-processamento
- 4_ Enriquecimento
- 5_ Armazenamento


---

## Estrutura do Repositório

- **/scripts**: Contém o notebook Jupyter (`.ipynb`) que executa todo o pipeline de ETL.
- **/notebooks**: Contém o notebook Jupyter (`.ipynb`) com toda a análise de resultados e visualizações.
- **/data/analytics**: Contém os datasets finais e limpos no formato `.parquet`.
- **/visualizations**: Contém o fluxograma do pipeline e os principais gráficos gerados.
- `requirements.txt`: Lista das bibliotecas Python necessárias para executar o projeto.

---
