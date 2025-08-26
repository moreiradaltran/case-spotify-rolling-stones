Este projeto, desenvolvido como parte de uma aula de (EDA - Exploratory Data Analysis) na FIAP, oferece uma EDA do catálogo musical da banda Rolling Stones.

# Objetivo e motivação:
O objetivo principal foi explorar e entender os dados de áudio das músicas da banda, descobrindo padrões, tendências e relações entre diferentes características musicais. A análise busca responder:
- Duração das faixas por álbum.
- Álbuns com maior duração média de faixas.
- Músicas mais populares.
- Data do primeiro e último lançamento.
- Porcentagem de popularidade por álbum na última década.
- Distribuição sobre o barulho das músicas em álbuns ao vivo VS os gravados em studio.
- Relação entre as outras colunas a média valence dos álbuns.
- Testes de hipóteses para ver se de fato os albuns gravados em studio possuem menos barulho do que os ao-vivo.
- Matriz de correlação com a média de cada álbum, se as faixas são mais positivas ou negativas.
  
### Tecnologias utilizadas:

| Categoria | Ferramenta |
|---|---|
| **Linguagem** | Python |
| **Análise de Dados** | Pandas, SciPy |
| **Visualização** | Matplotlib, Seaborn |

### Conclusão: 
Os códigos mostram que a análise exploratória é fundamental para obter insights valiosos. Foi possível comprovar, de forma estatística, que a percepção de "barulho" nas músicas é diferente entre gravações de estúdio e ao vivo, podemos confirmar que os albuns gravados em studio, de fato, são menos barulhentos do que quando são ao-vivo. Além disso, foi identificada uma forte correlação positiva entre a "valência" média das músicas de um álbum e sua "dançabilidade". Conseguimos entender que a banda com qual estamos trabalhando costuma fazer músicas bem energéticas, rápidas e com bastante barulho. 

- Faixas com alta valência soam mais positivas (por exemplo, alegres, alegres, eufóricas), enquanto faixas com baixa valência soam mais negativas (por exemplo, tristes, deprimidas, zangadas).
- Dançabilidade descreve o quanto uma faixa é adequada para dançar com base em uma combinação de elementos musicais, incluindo andamento, estabilidade do ritmo, força da batida e regularidade geral. Um valor de 0,0 é menos dançável e 1,0 é o mais dançável.

















