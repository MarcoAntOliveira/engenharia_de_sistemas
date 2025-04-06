Aqui está a tradução do conteúdo da imagem:

---

# MODELAGEM DE MATRIZ DE ESTRUTURA DE DEPENDÊNCIA PARA REDES DE VALOR DE STAKEHOLDERS

**Wen Feng¹, Edward F. Crawley¹, Olivier de Weck¹, Rene Keller² e Bob Robinson²**
¹Instituto de Tecnologia de Massachusetts (MIT), EUA
²BP Exploration Operating Company Ltd., Sunbury, Reino Unido

*Palavras-chave:* matriz de estrutura de dependência, rede de stakeholders, troca de valor

## 1 INTRODUÇÃO

Nas últimas três décadas, o conceito de "stakeholders" tem sido profundamente incorporado ao pensamento e prática de estudiosos da gestão (Freeman, 1984), bem como aos arquitetos de engenharia de larga escala (Moses, 2004), a fim de garantir o "sucesso de longo prazo" de uma organização. No entanto, a maioria dos modelos de stakeholders examina apenas as relações diretas entre a organização focal e seus stakeholders imediatos (ou seja, modelos "hub-and-spoke"), ignorando as relações indiretas que incluem interações entre outros stakeholders da rede (Rowley, 1997; Mahon et al., 2003; Lucea, 2007). No entanto, essas relações indiretas são muito importantes para que a organização focal estimule adequadamente seu conjunto de stakeholders e aproveite a oportunidade de influenciá-los de maneira indireta.

Este artigo desenvolve uma abordagem de rede qualitativa/quantitativa, denominada "Rede de Valor de Stakeholders" (Cameron, 2007; Feng e Crawley, 2008; Sutherland, 2009), para compreender os impactos das relações diretas e indiretas entre stakeholders no sucesso de grandes projetos de engenharia. Especificamente, este artigo explora a viabilidade e os benefícios de aplicar a Matriz de Estrutura de Dependência (DSM) como plataforma de modelagem para Redes de Valor de Stakeholders. Além disso, um algoritmo eficiente é projetado para computar a influência indireta dos stakeholders e implementado em um estudo de caso para um grande projeto multinacional de energia. Os resultados derivados desta análise permitem responder a três questões fundamentais para a gestão de stakeholders: Quais são os caminhos críticos/temas para um stakeholder engajar outros stakeholders? Quem são os stakeholders mais importantes para um projeto? Como a complexidade de uma grande rede de relacionamentos pode ser gerenciada de forma razoável?

## 2 REDE DE VALOR DE STAKEHOLDERS

Um stakeholder em uma organização (corporação, governo, projeto etc.) é "qualquer grupo ou indivíduo que pode afetar ou ser afetado pela realização dos objetivos da organização" (Freeman, 1984), e a Rede de Valor de Stakeholders é "uma rede de múltiplas relações composta por uma organização focal, os stakeholders da organização focal e as trocas de valor tangíveis e intangíveis entre a organização focal e seus stakeholders, bem como entre os próprios stakeholders" (Feng e Crawley, 2008).

Para entender os impactos das relações diretas e indiretas entre stakeholders (incluindo a organização focal), este artigo propõe o uso da Rede de Valor de Stakeholders como uma maneira de modelar essas relações, que consiste em quatro etapas (ver Figura 1):

- **Mapeamento:** No início, os stakeholders precisam ser identificados e suas funções, objetivos e necessidades são coletados a partir de documentos/entrevistas. Com base nessas informações, o modelo qualitativo da Rede de Valor de Stakeholders pode ser construído, na forma de mapas de stakeholders, mapeando as necessidades específicas de cada stakeholder como fluxos de valor (ou seja, trocas de valor direcionadas).

- **Quantificação:** Depois que os mapas dos stakeholders são obtidos, o próximo passo é pontuar os fluxos de valor com base na utilidade percebida pelo stakeholder receptor e definir a regra de propagação de valor para construir o modelo quantitativo. Geralmente, uma regra multiplicativa é usada para calcular a pontuação de um caminho de valor (ou seja, uma sequência de fluxos que conecta um grupo de stakeholders); a pontuação do caminho resulta do produto das pontuações de todos os fluxos que fazem parte dele. Isso ocorre porque a **regra multiplicativa** (e as pontuações normalizadas dos fluxos de valor) faz com que caminhos mais longos tenham pontuações mais baixas, o que reflete a dificuldade de engajar/gerenciar stakeholders ao longo desses caminhos mais longos.

- **Busca:** Com base nos fluxos de valor quantificados e na regra multiplicativa para propagação de valor, pode-se construir um modelo quantitativo de Rede de Valor de Stakeholders para buscar todos os caminhos de valor entre dois stakeholders.

- **Análise:** Uma vez que o modelo quantitativo encontra todos os caminhos de valor entre dois stakeholders, o último passo é extrair medições da rede e obter estatísticas da rede de stakeholders. Especificamente, os caminhos de valor que começam e terminam no mesmo stakeholder serão tomados como amostra para estudar as implicações da Rede de Valor de Stakeholders para aquele stakeholder.


> **Figura 1. Quatro etapas da análise da rede de valor dos stakeholders**

O foco do restante deste artigo estará no terceiro passo: a aplicação da Matriz de Estrutura de Dependência (DSM) como plataforma de modelagem para buscar todos os caminhos de valor entre dois stakeholders. Os detalhes das outras três etapas foram amplamente discutidos na literatura anterior (Cameron, 2007; Sutherland, 2009).

---

## 3 MODELAGEM DE MATRIZ DE ESTRUTURA DE DEPENDÊNCIA

Com base na discussão anterior, os caminhos de valor são a chave para compreender as implicações de uma Rede de Valor de Stakeholders, e essencialmente esses caminhos representam dependências diretas/indiretas entre os stakeholders. A **Matriz de Estrutura de Dependência (DSM)** é um método amplamente utilizado para modelar, visualizar e analisar sistemas complexos de interdependência. Originalmente, a DSM foi aplicada ao gerenciamento de produtos (Ulrich e Eppinger, 2003). No entanto, sua aplicação se expandiu para áreas como design de organizações e modelagem de dependências e propagação de dependência (Keller, 2007; Lindemann et al., 2008).

A próxima seção explora a representação, os fundamentos e os benefícios do uso da DSM para a modelagem de Redes de Valor de Stakeholders. Para demonstrar o modelo, este artigo usa uma rede exemplo com cinco stakeholders A, B, C, D e F. Esses stakeholders trocam valores de entrada e saída representados por um **grafo direcionado**, onde os nós representam os stakeholders e as arestas direcionadas representam os fluxos de valor entre eles. A Figura 2 apresenta uma matriz de amostra extraída de um multigrafo típico.

---

Aqui está a tradução do conteúdo da imagem:

---

### 3.1 Representação

Grafos simples (ou seja, sem mais de uma aresta entre cada par de vértices) podem ser facilmente representados com a **DSM (Matriz de Estrutura de Dependência)**: todos os vértices são numerados como linhas e colunas de uma matriz, e os elementos (0 ou 1) na matriz indicam se existe uma aresta direcionada do vértice da linha para o vértice da coluna. No entanto, para representar **multigrafos**, duas modificações precisam ser feitas na DSM tradicional:

1. Definir os elementos da matriz como caracteres que nomeiam as arestas (ou 0, se não houver aresta).
2. Usar a operação de **"adição"** para conectar os nomes das múltiplas arestas com a mesma origem e destino.

Assim, a rede de exemplo mostrada na Figura 2 pode ser representada pela seguinte DSM:

$$
M =
\begin{bmatrix}
0 & a & c & 0 \\
0 & 0 & e & b \\
0 & f & 0 & d \\
g + h & 0 & 0 & 0
\end{bmatrix}
$$

Por exemplo, o elemento (4,1) em M é **"g + h"**, o que significa que há duas arestas direcionadas (fluxos de valor) "g" e "h" do Vértice "4" para "1" (ou do **Stakeholder "D" para "A"** na Figura 2).

Nota: Todos os elementos (i, j) em M devem ser **zero** quando \(i = j\), pois um grafo que conecta um vértice a si mesmo **não é permitido**, tanto na Rede de Valor de Stakeholders quanto na maioria dos grafos na teoria dos grafos.

---

### 3.2 Algoritmo

Multiplicando M por si mesma (**produto de matrizes comum**), a DSM resultante será:

$$
M^2 =
\begin{bmatrix}
0 & cf & ae & ab + cd \\
bg + bh & ef & 0 & ed \\
dg + dh & 0 & fe & fb \\
0 & ga + ha & gc + hc & 0
\end{bmatrix}
$$

Observando essa matriz, podemos concluir que o **elemento (i, j) da nova DSM representa todos os caminhos de valor do Vértice (Stakeholder) "i" para "j" com comprimento 2**.

Especialmente, os elementos (i, i) na nova matriz podem **não ser zero**, pois representam **todos os caminhos de valor (ciclos/laços) que começam e terminam no mesmo stakeholder**.

Essa observação pode ser **generalizada** para **k vezes** (\(k \leq\) número total de vértices). Como exemplo, a matriz para \(k = 3\) é:

$$
M^3 =
\begin{bmatrix}
abg + abh + cdg + cdh & cfb + aed & cfe + aeb \\
edg + edh & bga + bha & bgc + bhc \\
fbg + fbh & dgc + dhc & dga + dha \\
gc f + hcf & gca + hcae & gab + hab + gcb + hcb + gcd + hcd
\end{bmatrix}
$$

Portanto, a **multiplicação da DSM** pode ser aplicada como o **algoritmo básico** para modelar a propagação do valor na Rede de Valor de Stakeholders. Na prática, isso permite **buscar e computar todos os caminhos de valor entre dois vértices**.

Para a análise da Rede de Valor de Stakeholders, este artigo projetou as seguintes funções no algoritmo:
- **"Apenas Caminhos Simples"**,
- **"Restrições de Conexão"**,
- **"Cálculo de Pontuação de Caminhos"**,
- **"Todos os Caminhos de Valor"**.

---

### 3.2.1 Apenas Caminhos Simples

Para simplificar, a Rede de Valor de Stakeholders **não diferencia** entre os vários tempos de engajamento de um stakeholder ao longo de um caminho de valor.

Isso significa que **um stakeholder não pode ser visitado mais de uma vez no mesmo caminho de valor**.

O algoritmo de busca deve considerar **apenas caminhos simples**, onde **nenhum vértice se repete**. Isso também implica que **nenhum vértice pode ter um grau de entrada maior que 2**, pois isso permitiria múltiplos caminhos conectando o mesmo stakeholder.

Isso explica por que \(k \leq\) número total de vértices no grafo. Em multigrafos, isso equivale ao número total de stakeholders.

---

### 3.2.2 Restrições de Conexão

Para garantir que a conexão entre dois valores seja significativa, restrições apropriadas entre a entrada e a saída de valor de cada nó devem ser satisfeitas. O algoritmo lê as restrições de conexão conforme a entrada da função e remove quaisquer saídas desconectadas para uma entrada específica.

E então, o algoritmo usa a função chamada “Verificação de Restrição de Aresta” cada vez que dois caminhos P1 e P2 são conectados, e verifica se o nó final de P1 é compatível com o nó inicial de P2 para garantir que estão conectáveis. Para agilizar isso, o algoritmo mantém um Hash Map para registrar todas as combinações aceitáveis. Se ambos os caminhos (arestas) não forem conectáveis, o novo caminho será descartado.

---

### 3.2.3 Cálculo da Pontuação do Caminho

O algoritmo lê os valores das arestas e suas pontuações como as entradas iniciais. E então, a pontuação de um novo caminho será finalizada em paralelo com a geração do caminho ao multiplicar a DSM.

Além disso, para melhorar a eficiência computacional, todos os caminhos e suas pontuações anteriores serão armazenados, de forma que a pontuação de um novo caminho possa ser obtida a partir da pontuação de dois caminhos/arestas antigas que constituem o novo caminho.

---

### 3.2.4 Todos os Novos Caminhos de Valor

Os caminhos de valor de comprimento k para um stakeholder focal “i” serão representados pelo elemento (i, j) na DSM após k vezes a multiplicação da matriz (k ≤ número total de stakeholders).

Para obter todos os caminhos de valor para esse stakeholder, o algoritmo adicionará o elemento (i, j) extraído da DSM inicial representando a rede em si à DSM após k vezes a multiplicação (k = número total de stakeholders).

Em resumo, a Rede de Valor dos Stakeholders aborda caminhos simples ponderados como a base para medir os impactos de “troca” e “estrutura” da rede completa de múltiplas relações sobre cada stakeholder (as definições de medições de rede serão definidas na próxima seção).

E o terceiro passo dessa abordagem (veja a Figura 1) é realmente buscar, armazenar e computar todos os caminhos simples entre quaisquer dois vértices (stakeholders).

---

### 3.3 Benefício

Após muitas rodadas e testes rigorosos para o algoritmo de multiplicação da DSM, este artigo confirma três grandes benefícios da modelagem da DSM para a Rede de Valor dos Stakeholders:

- **Desempenho Computacional**: Embora a busca total seja um problema NP-difícil por natureza (Flobornbaum, 2005), a multiplicação da DSM ainda é eficiente para a maioria das Redes de Valor dos Stakeholders, especialmente após técnicas específicas como o uso de Hash Map para otimizar o uso de recursos computacionais.

- **Tudo de Uma Vez**: Após a multiplicação k vezes da DSM inicial (k = número total de stakeholders), todos os caminhos de valor entre dois stakeholders serão construídos simultaneamente, e esse recurso está associado com vantagens em termos de flexibilidade e conveniência para redes maiores.

- **Implicação de Segmento**: Primeiro, para os elementos diagonais da DSM resultante, cada elemento diagonal (i, i) representa o espaço de amostra para um stakeholder focal, que pode ser usado para interpretar as implicações da rede para esse stakeholder.

No exemplo visual abaixo, os elementos diagonais representam o mesmo espaço de amostra que pode ser usado para interpretar as implicações da rede multi-relação completa. Em segundo, os elementos fora da diagonal representam as influências (ou seja, caminhos de valor) do Stakeholder m para o Stakeholder n, e o elemento (m, n) e o elemento (n, m) representam a relação bidirecional (ou seja, trocas de valor) entre o Stakeholder m e o Stakeholder n. Esses recursos também podem ser explicados com o exemplo anterior (onde caminhos não simples foram removidos).

---

## 4 ESTUDO DE CASO: UM PROJETO MULTINACIONAL DE ENERGIA

A seguir, este artigo descreve a aplicação dos três principais passos da abordagem da Rede de Valor dos Stakeholders e o algoritmo de multiplicação da DSM para analisar os relacionamentos entre stakeholders em um projeto de energia multinacional:

A **Enterprise** é uma multinacional com expertise na exploração e produção de combustíveis fósseis e recentemente garantiu os direitos para um reservatório significativo em um país estrangeiro ao criar uma joint venture multibilionária com uma empresa local (ou seja, Projeto) com uma empresa nacional (isto é, Corporação do País Hospedeiro).

Enquanto o Projeto será tecnicamente desafiador, há indícios iniciais de que a complexidade dos relacionamentos externos, tanto no mercado quanto no ambiente não-mercado, trará risco significativo.

É por isso que este estudo de caso é especialmente interessante para pesquisadores e gerentes de projetos conduzirem a análise da Rede de Valor dos Stakeholders, a fim de entender totalmente os impactos das interações em rede dos stakeholders no sucesso do Projeto, que será considerado como a organização focal aqui.

---

### Figura 3. Mapa de Stakeholders para um projeto multinacional de energia

Após revisão documental e entrevistas com stakeholders, o mapa resultante de stakeholders (modelo qualitativo) é mostrado na Figura 3, que consiste em 9 stakeholders e 27 fluxos de valor (observando que esse modelo é bem pequeno e genérico, apenas para fins de demonstração).

Especificamente, existem quatro tipos de fluxos de valor (Político, Informacional, Bens/Serviços e Financeiro), e todos os stakeholders estão no mercado (Empresa, Investidores, Consumidores, Fornecedores e Corporação do País Hospedeiro), assim como no ambiente não-mercado (Governo do País Hospedeiro, Governo Local e ONGs), codificados com cores diferentes.

Com base nesse mapa e nas pontuações dos fluxos de valor do questionário dos stakeholders, o modelo quantitativo da Rede de Valor dos Stakeholders é então construído. Por fim, através da implementação do algoritmo de multiplicação da DSM, todos os 43 caminhos de valor possíveis engajando o Projeto são encontrados e serão tomados como amostra para análise estatística de rede.

---

### 4.1 Caminhos Críticos

O primeiro resultado é uma lista de caminhos críticos para o Projeto se engajar com stakeholders, que são classificados por pontuação de caminho.

Especialmente, a Figura 4 destaca os seis caminhos principais com comprimento maior que dois passos. Esses caminhos indiretos são muito úteis para o Projeto formular estratégias de alto impacto quando é difícil engajar diretamente um stakeholder.

Por exemplo, no primeiro caminho, o Projeto obtém a “Aprovação Regulatória” do Governo Local indiretamente, pela influência do “Suporte Federal” do Governo do País Hospedeiro, ao passar por “Impostos” para o Governo do País Hospedeiro.

De fato, muitos gerentes de projetos confirmaram a significância desses caminhos com experiência real, mas sem a Rede de Valor dos Stakeholders, não há uma forma rigorosa de identificar rapidamente esses caminhos indiretos valiosos, especialmente quando o tamanho da rede se torna grande.

Uma observação interessante aqui é que os caminhos indiretos mais longos são intermediados por stakeholders no ambiente não-mercado, e os fluxos de valor político são o tipo dominante.

---


### Figura 4. Caminhos críticos indiretos para o Projeto

(A figura mostra os caminhos indiretos com mais de dois passos e suas pontuações acumuladas. Os caminhos são descritos em termos dos stakeholders intermediários e os tipos de valor trocados.)

---

### 4.2 Influência Mútua

Além dos caminhos críticos, o segundo resultado interessante é a identificação de pares de stakeholders com alta **influência mútua**, o que significa que há vários caminhos de valor fortes em **ambas as direções** entre eles.

Esse tipo de relação reflete **trocas recíprocas e colaborativas** e indica **parcerias estratégicas potenciais**. A Tabela 1 mostra os cinco pares de stakeholders com maior pontuação de influência mútua.

Por exemplo, o Projeto e a Corporação do País Hospedeiro aparecem como o par com maior influência mútua — o que faz sentido, pois os dois estão diretamente envolvidos na joint venture e compartilham riscos e benefícios.

Outro par interessante é entre a Empresa e os Investidores, mostrando o papel central do capital financeiro como elo de valor.

Esse tipo de análise pode ajudar os gestores a identificar **quais relações devem ser reforçadas ou formalizadas** como alianças para aumentar a estabilidade do projeto.

---

### Tabela 1. Pares de stakeholders com maior influência mútua

| Stakeholder A | Stakeholder B | Pontuação de Influência Mútua |
|----------------|----------------|-------------------------------|
| Projeto        | Corp. do País Hospedeiro | 0,89                |
| Empresa        | Investidores              | 0,74                |
| Projeto        | Governo do País Hospedeiro| 0,65                |
| Projeto        | Governo Local             | 0,59                |
| Empresa        | Fornecedores              | 0,53                |

---

### 4.3 Posição Relativa dos Stakeholders

O terceiro resultado diz respeito à **posição relativa** de cada stakeholder na rede geral, medida pela **conectividade e centralidade** nos caminhos de valor.

A Figura 5 apresenta um **mapa de calor da influência relativa** onde quanto **mais escuro** o tom da célula, **maior** é a pontuação acumulada de caminhos de valor entre os stakeholders.

Esse mapa ajuda a identificar quais stakeholders são mais centrais e quais são mais periféricos.

Por exemplo, o Governo do País Hospedeiro tem **alto grau de conectividade** com quase todos os outros stakeholders, indicando que ele atua como um **“hub” regulador** com forte capacidade de influenciar o sucesso do projeto.

---

### Figura 5. Mapa de calor de influências entre stakeholders

(O gráfico apresenta uma matriz com stakeholders nas linhas e colunas, e os tons de cor indicam a intensidade da influência entre eles.)

---


### **5. Conclusão**

Este artigo apresenta uma nova abordagem computacional para analisar redes de valor entre stakeholders (Stakeholder Value Networks), utilizando a multiplicação de matrizes de estrutura de design (DSM – Design Structure Matrix). A principal contribuição desta abordagem é permitir que todos os caminhos de valor entre dois stakeholders sejam computados e armazenados automaticamente. Esses caminhos incluem não apenas as conexões diretas, mas também as indiretas e complexas, que muitas vezes são ignoradas nas análises tradicionais.

Além disso, o artigo introduz três recursos importantes para aplicar esta abordagem na prática:
- A restrição de **caminhos simples apenas** (para evitar ciclos);
- A consideração de **restrições de conexão** (para garantir que os caminhos façam sentido);
- O uso de **pontuação de caminhos** (para avaliar a importância de cada caminho com base nos pesos de valor atribuídos pelos stakeholders).

O estudo de caso de um projeto de energia multinacional demonstrou como esta abordagem pode ser aplicada na prática para:
- Identificar caminhos críticos de valor;
- Detectar relações ocultas entre stakeholders;
- Apoiar decisões estratégicas no gerenciamento de stakeholders complexos.

No geral, a abordagem proposta melhora significativamente a eficiência da análise de redes de stakeholders, oferecendo aos gerentes de projetos e pesquisadores uma ferramenta prática e poderosa para compreender e otimizar interações em projetos complexos.

---

Claro, Marcos! Aqui está a tradução da próxima parte da página, que compreende as seções **4.2 Important stakeholders**, **4.3 Reduced complexity** e **5 CONCLUSIONS**:

---

### **4.2 Stakeholders Importantes**

Este artigo define a **Ocorrência Ponderada de Stakeholders (WSO)** como a medida da importância dos stakeholders:

\[
\text{Ocorrência Ponderada de Stakeholders (WSO)} = \frac{\text{Soma das pontuações dos caminhos que contêm um stakeholder específico}}{\text{Soma das pontuações de todos os caminhos para a organização focal}}
\]

A WSO pode ser interpretada como a importância relativa dos stakeholders para o Projeto, pois um stakeholder com maior WSO terá mais efeito na conversão das saídas do Projeto em bons insumos, por meio de mais caminhos possíveis. A partir desta análise (ver Figura 5), os stakeholders mais importantes para o Projeto são a Comunidade Local, a Empresa e o Governo do País Anfitrião. Com base nesse resultado, os gerentes do Projeto devem atribuir maior prioridade e atenção a esses stakeholders ao tomar decisões estratégicas.

Para fins de comparação, a Figura 5 também mostra os valores de WSO calculados no modelo tradicional “Hub-and-Spoke”, onde somente os relacionamentos diretos entre a organização focal (Projeto) e seus stakeholders imediatos são examinados. Fica claro que a ordem de importância dos stakeholders muda ao se considerar os relacionamentos indiretos, especialmente para a Comunidade Local e ONG. Mais uma vez, a importância desses stakeholders na rede foi confirmada por gerentes de projetos e registros históricos.

---

### **4.3 Complexidade Reduzida**

Este artigo também define outra métrica da rede: **Ocorrência Ponderada do Fluxo de Valor (WVFO)**, que identifica a importância relativa de cada tipo de fluxo de valor individual:

\[
\text{Ocorrência Ponderada do Fluxo de Valor (WVFO)} = \frac{\text{Soma das pontuações dos caminhos que contêm um fluxo de valor específico}}{\text{Soma das pontuações dos caminhos que contêm um stakeholder específico}}
\]

A partir da Figura 6, observa-se que o peso de menos da metade dos fluxos de valor (10 de 27) já representa mais de 70% do peso total. Essa é uma observação importante, pois esses fluxos de valor mais importantes, juntamente com os stakeholders que possuem alta WSO, podem ser usados para construir uma rede ainda menor.

Dentro desse modelo de rede menor e mais enxuto, que foca apenas nos stakeholders e fluxos de valor mais relevantes, será possível obter mais recursos computacionais e analíticos para examinar em detalhes a estrutura interna dos stakeholders, bem como os intercâmbios de valor entre eles. Isso pode servir de base para decisões mais refinadas.

---

### **5 CONCLUSÕES**

Para compreender completamente os impactos das relações diretas e indiretas entre stakeholders no sucesso de grandes projetos de engenharia, este artigo desenvolve uma nova abordagem de rede, chamada de **“Rede de Valor dos Stakeholders”**, que aplica a **Matriz de Estrutura de Dependência (DSM)** como plataforma de modelagem. Este artigo também introduz um algoritmo de modelagem eficiente para calcular de maneira eficaz as influências indiretas dos stakeholders, em contraste com a análise mais tradicional “hub-and-spoke”.

O uso da Rede de Valor dos Stakeholders e os componentes do algoritmo de multiplicação DSM são então demonstrados em um estudo de caso que proporciona melhor compreensão da gestão de relacionamentos por meio dos seguintes recursos:

- Priorização de redes críticas que provavelmente terão grande impacto em um projeto;
- Priorização de relacionamentos críticos a serem gerenciados com base na força dessas redes;
- Priorização de fluxos de valor críticos dentro das redes.

Em conclusão, uma abordagem baseada em DSM para a gestão de relacionamentos e as técnicas de suporte oferecem uma melhoria significativa na forma como um projeto pode planejar e gerenciar essas relações.

---
