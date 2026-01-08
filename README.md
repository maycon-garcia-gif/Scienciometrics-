# Cienciometria
Repositório dedicado à cienciometria, com análises desenvolvidas em R utilizando o pacote **bibliometrix**. O projeto explora métricas de produção científica a partir de artigos, livros e outras publicações, permitindo avaliar produtividade por autor, palavras-chave, redes de colaboração e indicadores bibliométricos.

**A partir do pacote Biblimetrix é possível analisar metricas de artigos de diferentes base de dados** 

# Baixando dados de artigos de diferentes base de dados 

É possível baixar os artigos de diferentes banco de dados como o Scopus e Web of science. 
As buscas podem ser baixadas em arquivos do tipo .csv e .txt. 

Após download dos arquivos, os resultados são analisados no R com o pacote **bibliometrix** 

# Script em R 
O Script em R está disponível em R: https://github.com/maycon-garcia-gif/Scienciometrics-/blob/main/R%20script 

# Análise de dados cienciométricos 

**Países mais produtivos**

O gráfico a seguir nos permite avaliar os países que mais contribuiram para o tópico em estudo, nesse caso, avaliei a publicação de artigos e documentos científicos publicados sobre um arbovírus negligenciado. 
O país que mais publicou artigos sobre esse vírus foi o Brasil, em seguida, dos Estados Unidos. Especula-se que essa maior contribuição para a contribuição científica do Brasil, seja consequência do maior número de casos nessa região. 


<img width="501" height="511" alt="Rplot01" src="https://github.com/user-attachments/assets/21361f8d-e68f-4cd3-83ee-fedb49fba856" />

**Autores mais produtivos**

Além dos países e regiões mais produtivas, é possível avaliar os autores que mais contribuiram com artigos e publicações científicas. Dos dados avaliados, foi observado uma média de 7.9 co-autores por artigo, com cerca de 550 autores entre os anos de 1946 e 2025. 


<img width="501" height="511" alt="Rplot02" src="https://github.com/user-attachments/assets/a8a3d6ed-23ca-465b-b133-411ac96a7cba" />

# Produção científica Anual 

Além das métricas de produção dos países e autores, com o pacote bibliometrix também é possível **avaliar a produção cientifica anual ao longo dos anos.** Nesse caso, avalei a quantidade de artigos publicados entre os anos 1946 e 2025 sobre um arbovírus negligenciado. 


<img width="501" height="511" alt="Rplot03" src="https://github.com/user-attachments/assets/6dce5c26-d8e8-4393-b51f-421ea5fe49ef" />

# Co-occurrence Network

Um Co-occurrence Network (rede de coocorrência) é um gráfico que representa relações entre termos com base na frequência com que aparecem juntos em um mesmo contexto, geralmente no título, resumo (abstract) ou palavras-chave de artigos científicos. O gráfico a seguir demonstra uma rede de conexões entre o arbovírus negligenciado. As palavras mais frequentes estão relacionadas aos flavivírus, vírus transmitidos por mosquitos e sintomatologia causada pela infecção viral.  


<img width="1984" height="1176" alt="Co_occurrenceNetwork-_2026-01-05161734 439987" src="https://github.com/user-attachments/assets/8bbf5b82-922e-4b1d-86d7-60e37a20a366" />

Por fim, o pacote bibliometrix permite analisar uma variadade de métricas relacionadas a produção de artigos de forma bastante simples e rápida. Vale ressaltar, que as análises podem ser realizadas de qualquer tópico da literatura, desde que, a procura nas bases de dados seja feita da maneira correta e ética. 
 
