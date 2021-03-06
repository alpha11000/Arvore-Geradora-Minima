# Trabalho para a disciplina de Teoria e Aplicação de Grafos

## Para encontrar a árvore geradora mínima foram criados diversos algoritmos para encontrá-la de forma eficiente. Dessa forma, a fim de analisar o desempenho dos algoritmos de Prim e Kruskal, implementou-se ambos os algoritmos na linguagem de programação python.

### OBJETIVOS GERAIS

- Analisar o tempo gasto para encontrar a Árvore geradora mínima em diversos grafos, sendo eles completos e não-completos.

### OBJETIVOS ESPECÍFICOS

- Testar o desempenho para grafos não-completos tais quais com 5, 8, 11, 15 e 20 vértices.
- Testar o desempenho para grafos completos tais quais com 5, 8 ,11, 15 e 20 vértices.

> Primeiramente foi testado o funcionamento dos algoritmos, onde se utilizaram diversos grafos para a realização do mesmo. Um dos que foram utilizados, por exemplo, foi o seguinte:

![Grafo](https://github.com/alpha11000/Arvore-Geradora-Minima/blob/main/Trabalho_Grafos/images/image3.jpg "Grafo")


> Onde, por meio da execução dos dois algoritmos se conseguiu chegar em um mesmo resultado, sendo a Árvore Geradora Mínima obtida a seguinte:


![Grafo](https://github.com/alpha11000/Arvore-Geradora-Minima/blob/main/Trabalho_Grafos/images/image4.jpg "Grafo")

_A qual pode ser representada pela seguinte matriz de adjacência:_

```
            0    0    0    0    0    0    0    1
            0    0    0    0    0    1    0    3
            0    0    0    0    3    0    4    0
            0    0    0    0    0    2    0    0
            0    0    0    0    0    0    0    2
            0    0    0    0    0    0    0    0
            0    0    0    0    0    0    0    0
            0    0    0    0    0    0    0    0
```
### Logo em seguida, com a comprovação do funcionamento dos mesmos, passou-se a verificar o desempenho destes, utilizando-se um total de 10 grafos, os quais foram gerados por meio de algoritmos tanto de geração de grafos completos quanto de incompletos.

- Os resultados obtidos através dos algoritmos para grafos incompletos de 5, 8, 11, 15 e 20 vértices foram os seguintes:

    ![Tempo Incompleto](https://github.com/alpha11000/Arvore-Geradora-Minima/blob/main/Trabalho_Grafos/images/image5.png)

- O tempo foi medido em nanossegundos para cada quantidade de vértice, em que a diferença de desempenho pode ser vista mais facilmente com o gráfico abaixo:

    ![Grafico Incompleto](https://github.com/alpha11000/Arvore-Geradora-Minima/blob/main/Trabalho_Grafos/images/image2.png)

- Testando os algoritmos para grafos completos de 5, 8, 11, 15 e 20 vértices:

    ![Tempo Completo](https://github.com/alpha11000/Arvore-Geradora-Minima/blob/main/Trabalho_Grafos/images/image6.png)

- O tempo foi medido em nanossegundos para cada quantidade de vértice, em que a diferença de desempenho pode ser vista mais facilmente com o gráfico abaixo:

    ![Grafico Completo](https://github.com/alpha11000/Arvore-Geradora-Minima/blob/main/Trabalho_Grafos/images/image1.png)

### Após vários testes como acima mostrados, pode-se concluir que o desempenho do algoritmo de kruskal é bem superior nos mais variados tipos de teste, tornando-o mais indicado em qualquer circunstância que envolva encontrar a Árvore Geradora Mínima.

# Obrigado pela Leitura!!