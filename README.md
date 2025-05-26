# RNA_PP2
Repositório destinado à publicação das atividades da parte 2 do 2° Projeto Prático de Redes Neurais Artificiais 2025.1  
**Data de criação:** 24/05/2025
**Última atualização:** 26/05/2025 

Este projeto tem por objetivo a exploraração da base de dados Forest Cover Type, disponível em ![Dataset](https://www.kaggle.com/datasets/uciml/forest-cover-type-dataset), com foco nas seguintes práticas:
1. Análise e manipulação de dados do dataset;
2. Avaliação de redes neurais artificiais MLP para classificação de dados categóricos ou não;
3. Busca em grade mediante validação K-Fold.

## Tecnologias Utilizadas
- **Anaconda:** Gerenciamento de ambientes virtuais;
- **Python:** Execução do algoritmo, utilizando as seguintes bibliotecas:
  - **Pandas:** Manipulação de dados;
  - **Numpy:** Processos matriciais otimizados; 
  - **Json:** Armazenamento de dados; 
  - **Joblib:** Armazenamento de modelo de rna, processamento paralelo; 
  - **Sci-kit learn:** Métricas de treinamentos do neurônio;
  - **Matplotlib:** Plotagem de gráficos;
  - **Pretty-table:** Organização e plotagem de dados tabulares.

## Estrutura do Projeto
```plaintext
RNA_PP2/
├── boxplot_melhores_redes/                                   # Plotagem em boxplot das métricas das 6 melhores redes para dados categóricos
├── buscas_em_grade/                                          # JSONs contendo melhores modelos obtidos das 6 buscas em grade, além dos demais resultados
├── matriz_de_confusao_top6/                                  # Plotagem das matrizes de confusão das 6 melhores redes para dados categóricos
├── .gitignore                                                # Manipulação de git para evitar conflitos de output na branch main
├── covtype                                                   # Dataset Forest Cover Type
├── PP2.2.1 - Conhecendo o Conjunto de Dados.ipynb            # Jupyter Notebook de exploração de dados do Dataset
├── PP2.2.2 - Proposição e Avaliação de RNAs                  # Jupyter Notebook de análise de diferentes Redes Neurais Artificiais
├── PP2.2.3 - Validação Cruzada e Busca em Grade              # Jupyter Notebook de busca em grade, armazenamento e recuperação do melhor modelo
├── resultado_arquiteturas                                    # JSON contendo métricas das arquiteturas propostas segundo a pirâmide geométrica
├── resultado_arquiteturas_propostas                          # JSON contendo métricas das arquiteturas propostas sem o uso da pirâmide geométrica
├── resultado_melhores_arquiteturas                           # JSON contendo métricas das 6 melhores arquiteturas propostas
├── resultado_melhores_redes                                  # JSON contendo métricas das 6 melhores arquiteturas propostas para dados categóricos
└── README.md                                                 # Documentação do projeto
```


## Autores
- Elloá B. Guedes (orientadora);
- Guilherme Goncalves Moraes;
- Ian Garrido Reis;
- Pedro Vitor Barros Maranhão;
- Rita De Cassia Brasil Alves;
- Yago De Oliveira Feitoza.
