# Sistema de recomendação para jogos de celular

## Visão Geral

Neste projeto, vamos analisar os dados disponíveis, O conjunto de dados de 17.007 jogos de estratégia na Apple App Store. Foram coletados em 3 de agosto de 2019, usando a API do iTunes e o mapa do site da App Store. Esses são os dados de 17.007 jogos de estratégia na Apple App Store.

Você pode conferir o dataset e o projeto na íntegra clicando abaixo:

Link dataset: https://www.kaggle.com/datasets/tristan581/17k-apple-app-store-strategy-games/data

Link do código do projeto: https://github.com/gustavoptavares/Jogos-de-Celular/blob/main/Jogos_de_Celular.ipynb

## Problema e Solução

Vamos analisar os dados o conjunto de dados de estratégia na Apple App Store. Com os dados de 17.007 jogos de estratégia na Apple App Store, vamos entender, no detalhe, aspectos relacionados aos conteúdos pesquisados, como:

• Enteder o conjunto de dados e a recomendação baseada em conteúdo.

• O sistema então recomenda itens com características semelhantes que provavelmente irão atrair o usuário.

## O Processo

O primeiro passo do projeto foi adquirir os dados. Utilizamos os dados do portal Kaagle, carregando-o no Google Colab, para a exploração e análise dos dados utilizando a linguagem de programação Python e suas bibliotecas, como Pandas, Matplotlib e Scikit-Learn. Neste projeto foi feito, uma análise exploratória, e foi criado um sistema de recomendação baseado em descrição usando a técnica de Processamento de Linguagem Natural (PLN), e foi utilizado o método de vetorização TF-IDF e a métrica de similaridade do cosseno.

## Resultados

Resultados do sistema de recomendação

Exemplo 1: Para o jogo " Sudoku", os jogos recomendados incluem " Color Sudoku", " Expert Sudoku", " Sudoku (Free)", entre outros. A precisão do sistema para essa entrada é de 0,82 e a revocação é de 0,93.

Exemplo 2: Para o jogo " Reversi", os jogos recomendados incluem " Fresh Reversi", " CraniumCrush: Reversi", " Nip ~ Circular Reversi ~", entre outros. A precisão do sistema para essa entrada é de 0,80 e a revocação é de 0,97.

Exemplo 3: Para o jogo "Othello Classic Plus", os jogos recomendados incluem "Five in a Line Free", "Flatris - The Legendary Game", "Bit Chess", entre outros. A precisão do sistema para essa entrada é de 0,68 e a revocação é de 0,62.

Exemplo 4: Para o jogo "Morocco", os jogos recomendados incluem "Morocco HD", "FlipItOver", "CraniumCrush: Reversi", entre outros. A precisão do sistema para essa entrada é de 0,85 e a revocação é de 1,00.

## Conclusões

O sistema de recomendação baseado em descrição desenvolvido neste notebook utiliza técnicas de Processamento de Linguagem Natural, especificamente vetorização TF-IDF e similaridade do cosseno, para recomendar jogos com base na descrição. A eficácia das recomendações é avaliada supondo que jogos do mesmo gênero são considerados semelhantes. Os resultados obtidos nos exemplos mostram que o sistema é capaz de fornecer recomendações relevantes com uma precisão e revocação razoáveis.

No entanto, a verdadeira eficácia do sistema pode ser melhor avaliada com feedback real dos usuários e/ou um conjunto de dados de avaliação mais robusto.​
