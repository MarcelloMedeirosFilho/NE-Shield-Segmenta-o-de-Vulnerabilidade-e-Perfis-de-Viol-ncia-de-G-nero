# NE-Shield: Segmentação de Vulnerabilidade e Perfis de Violência de Gênero

🛡️ Sobre o Projeto
Este projeto foi desenvolvido para a Câmara Temática de Segurança Pública do Consórcio Nordeste. O objetivo é mapear e segmentar perfis de violência contra a mulher na região, utilizando técnicas de Machine Learning (Clustering) para identificar padrões de comportamento de agressores e barreiras de acesso ao Estado (Saúde e Segurança).

A análise diferencia as dinâmicas de vulnerabilidade entre áreas urbanas e rurais, permitindo a criação de políticas públicas direcionadas e preventivas.

📊 Principais Descobertas
Através do agrupamento hierárquico (Ward), identificamos 4 perfis críticos:

Cluster 0 (Dominação Psicológica): Foco em humilhação pública e ameaças.

Cluster 1 (Conflito Verbal): Prevalência de gritos e xingamentos.

Cluster 2 (Baixa Intensidade): Casos esporádicos ou de monitoramento.

Cluster 3 (Risco de Letalidade): Concentra agressões físicas graves e uso de armas. Apresenta a maior concentração em áreas rurais e o menor índice de busca por socorro médico.

🛠️ Tecnologias Utilizadas
Linguagem: Python

Bibliotecas de Ciência de Dados: pandas, numpy

Machine Learning: scikit-learn (AgglomerativeClustering, PCA)

Visualização: plotly, seaborn, matplotlib

📈 Metodologia Aplicada
Pré-processamento: Conversão de dados categóricos em binários e tratamento de valores nulos (interpretados como ausência de evento).

Clusterização: Aplicação do algoritmo de Agrupamento Hierárquico para definir perfis de risco.

Redução de Dimensionalidade: Uso de PCA para visualização espacial dos agrupamentos.

Análise de Coocorrência: Geração de Heatmaps para entender a conexão entre diferentes tipos de violência.

🚀 Como Executar
Clone o repositório.

Certifique-se de ter o arquivo df_2019 (base da PNAD/PNS) carregado no ambiente.

Execute o Jupyter Notebook ou script Python principal para gerar os dashboards interativos.

📄 Conclusões Estratégicas
O projeto conclui que a violência física grave é proporcionalmente mais severa em regiões isoladas (rurais), onde a rede de saúde possui baixa capilaridade, exigindo unidades móveis de atendimento e o fortalecimento das Patrulhas Maria da Penha no interior do Nordeste.
