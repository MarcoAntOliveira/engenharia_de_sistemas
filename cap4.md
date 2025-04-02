Este capítulo descreve as atividades nos processos de design de sistemas listados na FIGURA 2.1-1. O capítulo está dividido em seções correspondentes aos processos de 1 a 4 listados na FIGURA 2.1-1. As tarefas dentro de cada processo são discutidas em termos de entradas, atividades e saídas. Orientações adicionais são fornecidas com exemplos relevantes para projetos da NASA.

Os processos de design de sistemas são interdependentes, altamente iterativos e recursivos, resultando em um conjunto validado de requisitos e em uma solução de design que atende a um conjunto de expectativas das partes interessadas. Existem quatro processos de design de sistemas: desenvolvimento das expectativas das partes interessadas, requisitos técnicos, decomposições lógicas e soluções de design.

A relação recursiva entre os quatro processos de design de sistemas é ilustrada. Esses processos começam com uma equipe de estudo coletando e esclarecendo as expectativas das partes interessadas, incluindo os objetivos da missão, restrições, fatores determinantes do design, objetivos operacionais e critérios para definir o sucesso da missão.

Esse conjunto de expectativas das partes interessadas e requisitos de alto nível é utilizado para impulsionar um ciclo iterativo de design, onde uma arquitetura/concepção inicial, o conceito de operações e os requisitos derivados são desenvolvidos. Esses três produtos devem ser consistentes com
outras palavras, esses elementos devem estar alinhados entre si e passarão por várias iterações e decisões de design para garantir essa consistência. Uma vez que essa consistência é alcançada, análises permitem que a equipe do projeto valide o design proposto em relação às expectativas das partes interessadas.

Uma validação simplificada busca responder às seguintes perguntas: O sistema funcionará como esperado? O sistema é viável dentro das restrições de orçamento e cronograma? O sistema fornece a funcionalidade e atende às necessidades operacionais que justificaram sua aprovação e financiamento? Se a resposta a qualquer uma dessas perguntas for "não", será necessário fazer ajustes no design ou nas expectativas das partes interessadas, reiniciando o processo.

Esse ciclo continua até que o sistema—incluindo arquitetura, conceito de operações (ConOps) e requisitos—atenda às expectativas das partes interessadas.

O nível de detalhamento do design deve ser suficiente para permitir a verificação analítica do projeto em relação aos requisitos. O design deve ser viável e credível quando avaliado por uma equipe de revisão independente experiente e deve ter profundidade suficiente para apoiar a modelagem de custos e a avaliação operacional.

Assim que o sistema atende às expectativas das partes interessadas, a equipe de estudo formaliza os produtos como referência e se prepara para a próxima fase. Muitas vezes, níveis intermediários de decomposição são validados como parte do processo.

No próximo nível de decomposição, os requisitos derivados (e alocados) formalizados tornam-se o conjunto de requisitos de alto nível para os elementos decompostos, e o processo recomeça. Esses processos de design de sistemas são aplicados principalmente na Pré-Fase A e continuam até a Fase C.
Os processos de design de sistemas durante a Pré-Fase A focam na produção de um design viável que levará à aprovação da Formulação. Durante a Fase A, são explorados designs alternativos e maior maturidade analítica para otimizar a arquitetura do sistema. A Fase B resulta em um design preliminar que atende aos critérios de aprovação. Na Fase C, são concluídos os designs detalhados para construção.

Esta é uma descrição simplificada com o objetivo de demonstrar a relação recursiva entre os processos de design de sistemas. Esses processos devem servir como orientação e ser adaptados por cada equipe de estudo, dependendo do tamanho do projeto e do nível hierárquico da equipe.

As próximas seções descrevem cada um dos quatro processos de design de sistemas e seus produtos associados para uma determinada missão da NASA.
![alt text](images/image-4.png)
### 4.1 Definição das Expectativas das Partes Interessadas

O Processo de Definição das Expectativas das Partes Interessadas é o processo inicial dentro do mecanismo de Engenharia de Sistemas (SE), estabelecendo a base sobre a qual o sistema será projetado e o produto será desenvolvido. O principal objetivo desse processo é identificar quem são as partes interessadas e como elas pretendem usar o produto. Isso geralmente é realizado por meio de cenários de uso (às vezes chamados de Missões de Referência de Design – DRMs) e do Conceito de Operações (ConOps).

#### 4.1.1 Descrição do Processo

A FIGURA 4.1-1 apresenta um diagrama típico do fluxo do Processo de Definição das Expectativas das Partes Interessadas, identificando as entradas, saídas e atividades típicas consideradas para definir essas expectativas.

As entradas típicas necessárias para esse processo incluem:

- **Expectativas Iniciais do Cliente:** São as necessidades, metas, objetivos, desejos, capacidades e outras restrições fornecidas pelo cliente para o produto dentro do nível do produto. Para produtos de nível superior (produto final), essas são as expectativas do cliente original que solicitou o produto. Para um produto final dentro da hierarquia do produto, são as expectativas do destinatário do item final quando for transferido.

- **Outras Expectativas das Partes Interessadas:** Representam as expectativas de partes interessadas-chave além do cliente. Por exemplo, essas partes podem incluir a equipe de testes que receberá o produto transferido (produto final e produtos habilitadores) ou os instrutores responsáveis por treinar os operadores, bem como os gerentes responsáveis pelo produto nesse nível.

- **Requisitos Derivados do Cliente:** São requisitos repassados ou alocados a partir de um nível superior (ou seja, requisitos do sistema principal). Eles ajudam a estabelecer as expectativas do cliente para esse nível.

#### 4.1.1.2 Atividades do Processo

##### 4.1.1.2.1 Identificação das Partes Interessadas

Uma "parte interessada" é um grupo ou indivíduo afetado pelo produto ou projeto, ou que tem algum interesse nele. Os principais envolvidos em um projeto/produto são chamados de partes interessadas-chave. Uma dessas partes interessadas-chave é sempre o objetivos estratégicos são então traduzidos em requisitos técnicos e funcionais para o sistema a ser desenvolvido.

A compreensão profunda das expectativas das partes interessadas é essencial no processo de engenharia de sistemas. Isso evita ambiguidades e desalinhamentos entre as necessidades do cliente e a solução projetada. Quando todas as partes concordam com as funções, características, comportamentos, aparência e desempenho do produto, cria-se um entendimento mais realista sobre o que será entregue. Além disso, esse alinhamento reduz a possibilidade de mudanças significativas nos requisitos ao longo do ciclo de vida do projeto, evitando retrabalho e custos adicionais.

As expectativas podem ser coletadas por meio de entrevistas, discussões, pesquisas, grupos de marketing, e-mails, Declarações de Trabalho (SOWs), requisitos iniciais do cliente ou outros métodos. Durante esse processo, os stakeholders especificam o estado final desejado e as restrições para alcançar os objetivos, como orçamento, prazos, suporte ao ciclo de vida, metas de desempenho e restrições operacionais.

A Figura 4.1-2 ilustra como as informações evoluem para um conjunto de requisitos de alto nível, destacando caminhos de validação. Essas informações são fundamentais para garantir que o sistema atenda aos objetivos estratégicos da missão, que podem variar dependendo da categoria da missão. Por exemplo, missões científicas são geralmente impulsionadas pelos planos estratégicos da Diretoria de Missão Científica da NASA, enquanto missões de exploração podem ser determinadas por diretrizes presidenciais. Essa clareza de propósito ajuda a equipe do projeto a trabalhar em direção a uma visão comum e a garantir que as decisões de design estejam alinhadas com os objetivos estratégicos.


garantir que todas as expectativas sejam identificadas e documentadas desde o início, para evitar mudanças tardias e dispendiosas no projeto.

Os objetivos definidos formam a base para o desenvolvimento da missão, portanto, devem ser claramente articulados. Além disso, o projeto deve considerar todas as restrições aplicáveis. Uma restrição é uma condição que precisa ser atendida, podendo ser imposta por fatores externos, como mecânica orbital, sistemas legados que precisam ser utilizados, regulamentações, limitações tecnológicas ou restrições orçamentárias. Os conceitos operacionais e as restrições devem estar incluídos na definição das expectativas dos stakeholders, pois determinam como o sistema deve ser operado para atingir os objetivos da missão.

É fundamental envolver os stakeholders em todas as fases do projeto. Esse envolvimento deve ser estruturado como um ciclo de feedback contínuo, o que aumenta significativamente as chances de sucesso da missão. Essa participação ativa constrói a confiança no produto final e facilita a validação e aceitação do sistema pelo público-alvo.

O engenheiro de sistemas deve interagir com diferentes comunidades especializadas, como aquelas envolvidas na proteção de ativos espaciais, integração de sistemas humanos, garantia da qualidade e confiabilidade. Isso garante que todas as expectativas relevantes sejam capturadas, evitando surpresas no ciclo de vida do projeto. Por exemplo, a proteção de ativos espaciais pode exigir criptografia adicional para comandos de link direto, blindagem extra para sistemas de radiofrequência ou o uso de frequências diferentes—alterações que podem ser caras se forem identificadas tarde demais no processo.

Para definir metas e objetivos, é necessário extrair dos stakeholders suas necessidades, desejos, capacidades, interfaces externas, suposições e restrições. Chegar a um conjunto acordado de objetivos pode ser um processo longo e desafiador. No entanto, a iteração proativa com os stakeholders ao longo de todo o processo de engenharia de sistemas é essencial para garantir um entendimento comum sobre o que deve ser feito e quais recursos serão necessários para realizar a missão com sucesso.
Os principais stakeholders e suas respectivas autoridades decisórias devem ser identificados para facilitar a resolução de conflitos durante o projeto. A definição clara das Necessidades, Metas e Objetivos (NGOs) garante que todas as partes envolvidas – implementadores, clientes e outros stakeholders – estejam alinhadas desde o início quanto ao problema a ser resolvido e ao seu escopo. É importante ressaltar que os NGOs não são requisitos contratuais nem especificações de projeto.

### Definições de Necessidades, Metas e Objetivos (NGOs)

- **Necessidade:** Uma única afirmação que impulsiona todo o desenvolvimento do sistema. Ela deve estar relacionada ao problema que precisa ser resolvido, mas não apresentar uma solução. A necessidade deve ser singular, pois tentar atender a múltiplas necessidades simultaneamente pode resultar na falha em atender as expectativas dos stakeholders.

- **Metas:** Representam um detalhamento da necessidade e estabelecem um conjunto de expectativas específicas para o sistema. Elas abordam questões críticas identificadas durante a avaliação do problema. Não precisam ser quantitativas ou mensuráveis, mas devem permitir a avaliação se o sistema as atendeu.

- **Objetivos:** Definem níveis específicos de desempenho que o sistema deve alcançar, estando sempre associados a uma meta. Para que sejam eficazes, os objetivos devem atender aos seguintes critérios:
  1. **Especificidade:** Devem ser claros o suficiente para que desenvolvedores, clientes e testadores os compreendam. Devem focar nos resultados que o sistema precisa atingir, sem definir a forma de implementação.
  2. **Mensurabilidade:** Devem ser quantificáveis e verificáveis, permitindo o monitoramento do sucesso do sistema.
  3. **Realismo:** Devem ser desafiadores, porém atingíveis. Caso um objetivo não possa ser definido com precisão desde o início, pode ser marcado como “A Ser Determinado” (TBD) até que estudos adicionais sejam concluídos.
  4. **Foco nos resultados:** Devem enfatizar os resultados esperados, e não os métodos utilizados para alcançá-los.

É essencial lembrar que objetivos não são requisitos. Eles são identificados na fase preliminar do projeto (pré-Fase A) e auxiliam na formulação do conjunto final de requisitos, os quais são os únicos elementos contratuais e verificáveis contra o sistema final implementado.

As expectativas dos stakeholders capturadas nesse processo são consideradas iniciais e podem ser refinadas conforme o desenvolvimento do conceito operacional e a obtenção de um consenso final entre as partes interessadas.
### Estabelecimento do Conceito de Operações (ConOps) e Estratégias de Suporte

Após a definição inicial das expectativas dos stakeholders, o desenvolvimento de um **Conceito de Operações (ConOps)** garante que a equipe técnica compreenda completamente as expectativas e como o produto pode satisfazê-las. Esse processo pode levar ao refinamento das expectativas iniciais, caso sejam identificadas lacunas ou ambiguidades. O ConOps fornece uma visão livre de implementação sobre o comportamento esperado do sistema, capturando suas características operacionais e a interação dos usuários com ele.

Além disso, as **estratégias de suporte** englobam provisions para **fabricação, testes, implantação, operação, manutenção e descarte do sistema**.

O ConOps desempenha um papel fundamental no desenvolvimento dos **requisitos e da arquitetura** do projeto, ajudando a definir elementos essenciais para os usuários e servindo como base para documentos operacionais subsequentes, como:
- Plano de operações
- Plano de lançamento e órbita inicial
- Manual operacional

Ele também **fundamenta o planejamento operacional de longo prazo**, influenciando aspectos como instalações, alocação de funções entre humanos e sistemas, cronogramas de rede e dimensionamento da equipe.

### Importância do ConOps no Desenvolvimento do Sistema

O ConOps é um **motor essencial para os requisitos do sistema** e deve ser considerado desde as fases iniciais do projeto. A análise detalhada dos casos de uso frequentemente revela requisitos e funções de design que poderiam ser negligenciados. Por exemplo, a necessidade de comunicação durante uma fase específica da missão pode exigir a inclusão de uma antena adicional, que não seria necessária na operação nominal.

O ConOps deve abordar todos os cenários operacionais significativos, incluindo **operações fora do normal**. Para garantir sua completude, ele deve considerar:
- Modos de operação normais e degradados
- Estratégias de gerenciamento de falhas
- Interação humana e necessidades de treinamento
- Arquitetura de comando e dados
- Infraestrutura operacional
- Suporte logístico (reabastecimento, manutenção e montagem)
- Níveis de pessoal e habilidades necessárias
- Eventos críticos

Os **cenários operacionais** oferecem uma visão dinâmica das operações do sistema, detalhando como ele deve funcionar nos diferentes modos e transições, incluindo:
- **Interação com interfaces externas**
- **Resposta a riscos e falhas previstas**
- **Ações durante falhas e suas mitigações**

No contexto de missões de exploração, diversos **Modelos de Referência de Missão (DRMs)** podem compor o ConOps, e a análise de desempenho deve garantir que os requisitos do sistema satisfaçam todos os cenários previstos.

Para mais detalhes sobre o desenvolvimento do ConOps, consulte a **Seção 4.1.2.1 do NASA Expanded Guidance for Systems Engineering**, disponível em:
[https://nen.nasa.gov/web/se/doc-repository](https://nen.nasa.gov/web/se/doc-repository).

### Definição das Expectativas dos Stakeholders em Declarações Aceitáveis

Após o desenvolvimento do **Conceito de Operações (ConOps)** e a resolução de quaisquer lacunas ou ambiguidades, as expectativas dos stakeholders podem ser formalmente documentadas. Essa documentação geralmente inclui:
- **NGOs (Non-Governmental Objectives)**
- **Critérios de sucesso da missão**
- **Fatores determinantes do projeto (design drivers)**

Essas informações podem ser registradas em **documentos, planilhas, modelos ou outras formas adequadas ao projeto**.

### Fatores Determinantes do Projeto

Os **design drivers** são fortemente influenciados pelo **ConOps**, considerando aspectos como:
- **Ambiente operacional**
- **Órbita da missão**
- **Duração da missão**

No caso de **missões científicas**, os fatores determinantes incluem, no mínimo:
- **Data de lançamento**
- **Duração da missão**
- **Órbita**
- **Considerações operacionais**

Caso diferentes órbitas sejam consideradas, um **ConOps separado** deve ser desenvolvido para cada uma delas.

Já para **missões de exploração**, os fatores incluem:
- **Destino da missão**
- **Duração da missão**
- **Sequência operacional e mudanças de configuração do sistema**
- **Interações da tripulação**
- **Atividades de manutenção e reparo**
- **Treinamento necessário**
- **Atividades de exploração in situ**

### Critérios de Sucesso da Missão

Os **critérios de sucesso da missão** definem os objetivos essenciais para a missão ser considerada bem-sucedida. Eles podem incluir:
- **Missões científicas** → Realização de descobertas científicas
- **Missões de exploração tripuladas** → Cumprimento de um roteiro exploratório
- **Missões de demonstração tecnológica** → Teste bem-sucedido de uma nova tecnologia

Esses critérios também especificam o **nível de qualidade** esperado para as medições científicas ou atividades exploratórias planejadas.

### Medidas de Efetividade (MOEs)

As **Medidas de Efetividade (MOEs)** são métricas que avaliam o sucesso da missão de acordo com os **objetivos definidos pelos stakeholders**. Elas são estabelecidas do ponto de vista do stakeholder e, muitas vezes, são sinônimas dos **critérios de sucesso da missão**.

As **MOEs são desenvolvidas juntamente com os NGOs e a documentação das expectativas dos stakeholders**. Informações adicionais sobre MOEs podem ser encontradas na **Seção 6.7.2.4 do NASA Expanded Guidance for SE**, disponível em:
[https://nen.nasa.gov/web/se/doc-repository](https://nen.nasa.gov/web/se/doc-repository).

### Rastreabilidade das Expectativas

A documentação das expectativas dos stakeholders deve incluir a **origem de cada expectativa**. Dependendo do contexto, essas expectativas podem ser rastreadas até:
- **NGOs**
- **Requisitos de níveis superiores do projeto**
- **Planos estratégicos organizacionais**

O uso de uma **ferramenta de gerenciamento de requisitos** facilita a captura e rastreamento dessas informações.

### Formalização e Revisão

Uma vez que as expectativas dos stakeholders e o ConOps são finalizados, é necessário obter um **compromisso formal** dos envolvidos. Isso pode incluir **assinaturas** ou outras formas de aceitação.

Para garantir esse alinhamento, é comum a realização de uma **revisão conceitual**, que pode ser formal ou informal, dependendo da **complexidade do sistema** (ver Seção 6.7). Durante essa revisão, os seguintes elementos são apresentados, discutidos e refinados:
- Expectativas dos stakeholders (e.g., NGOs)
- Medidas de Efetividade (MOEs)
- Conceito de Operações (ConOps)

### Formalização das Expectativas dos Stakeholders

#### 4.1.1.2.9 Estabelecimento da Linha de Base das Expectativas

Após a concordância entre os stakeholders e a equipe técnica sobre as expectativas (como **NGOs e MOEs**) e o **ConOps**, essas informações são **formalizadas como baseline**.

Qualquer alteração posterior requer um processo de **aprovação formal ou informal**, dependendo da natureza do projeto. Esse processo garante que qualquer modificação seja avaliada cuidadosamente por ambas as partes.

---

#### 4.1.1.2.10 Registro dos Produtos de Trabalho

Além da documentação das expectativas dos stakeholders e do **ConOps**, é essencial capturar e registrar os seguintes produtos de trabalho:
- **Decisões-chave tomadas ao longo do processo**
- **Justificativa e suposições que sustentam as decisões**
- **Lições aprendidas durante o desenvolvimento**

Isso ajuda a manter a rastreabilidade das decisões e facilita futuras revisões do projeto.

---

### 4.1.1.3 Saídas do Processo

Os principais resultados da captura das expectativas dos stakeholders incluem:

✅ **Expectativas Validadas dos Stakeholders**
- Conjunto acordado de necessidades, objetivos e restrições do produto.
- Pode estar na forma de documentos textuais, modelos gráficos ou tabelas.

✅ **Conceito de Operações (ConOps)**
- Descrição detalhada de como o sistema será operado ao longo do seu ciclo de vida.
- Permite compreender as metas do sistema e alinhar as expectativas dos stakeholders.
- Exemplos incluem documentos de ConOps, modelos operacionais e Missão de Referência de Projeto (**DRM – Design Reference Mission**).

✅ **Estratégias de Suporte a Produtos Habilitadores**
- Identificação de suporte necessário para fabricação, teste, implantação, manutenção e descarte do sistema.
- Especificação de produtos auxiliares que precisam ser desenvolvidos para viabilizar o sistema final.

✅ **Medidas de Efetividade (MOEs)**
- Conjunto de critérios que avaliam o sucesso do sistema com base nas expectativas dos stakeholders.
- Caso essas medidas não sejam atendidas, o sistema será considerado **inaceitável** pelos stakeholders.

---

#### Outros possíveis produtos gerados:

📌 **Alocação de Funções entre Humanos e Sistemas**
- Define a interação entre os operadores humanos, software e hardware do sistema.
- Especifica responsabilidades dos humanos dentro do sistema, incluindo:
  - Montagem
  - Operações terrestres
  - Logística
  - Manutenção (em solo e em voo)
  - Operações em voo
- Essencial para sistemas onde os operadores humanos desempenham um papel crítico, como **missões espaciais tripuladas**.

---

### 4.1.2 Diretrizes para Definição das Expectativas dos Stakeholders

Para mais detalhes sobre:
- **Desenvolvimento do Conceito de Operações (com exemplos práticos)**
- **Proteção de ativos espaciais**
- **Identificação de stakeholders em cada fase do projeto**

Consulte a **Seção 4.1.2 do NASA Expanded Guidance for Systems Engineering** disponível em:
[https://nen.nasa.gov/web/se/doc-repository](https://nen.nasa.gov/web/se/doc-repository).
### 4.2 Definição de Requisitos Técnicos

#### **Objetivo do Processo**
O processo de **Definição de Requisitos Técnicos** transforma as expectativas dos stakeholders em uma definição clara do problema e, posteriormente, em um conjunto completo de **requisitos técnicos validados**. Esses requisitos devem ser expressos como declarações de obrigação (**“shall” statements**) e servir de base para a **solução de design** dentro da **Estrutura de Decomposição do Produto (PBS)** e seus produtos habilitadores.

A definição de requisitos é **recursiva e iterativa**, abrangendo desde requisitos de **alto nível dos stakeholders** até requisitos específicos de **componentes individuais**. Esses requisitos devem descrever com precisão:
✅ **Entradas e saídas do sistema**
✅ **Relações entre entradas e saídas**
✅ **Restrições e interações com operadores, mantenedores e outros sistemas**

Os documentos de requisitos são essenciais para organizar e comunicar essas informações para **clientes, stakeholders e a equipe técnica**.

---

### ⚠️ **Importante!**
A equipe **não deve confiar apenas nos requisitos documentados** para projetar e construir o sistema. **A comunicação contínua e iterativa com os stakeholders** é essencial para garantir um entendimento mútuo e evitar a implementação incorreta de uma interpretação equivocada dos requisitos.

Esse processo de **validação iterativa** é **crítico para o sucesso do projeto** e deve garantir que os produtos e resultados desenvolvidos **correspondam exatamente às expectativas**.

---

## 4.2.1 **Descrição do Processo**
A Figura 4.2-1 apresenta um diagrama típico do **Processo de Definição de Requisitos Técnicos**, detalhando os principais **inputs, outputs e atividades** envolvidas.

---

### **4.2.1.1 Entradas do Processo**
Os principais insumos necessários para a definição dos requisitos técnicos incluem:

✅ **Expectativas dos Stakeholders (Baseline)**
- Necessidades, objetivos, restrições, interfaces externas e premissas acordadas.

✅ **Conceito de Operações (Baseline - ConOps)**
- Descrição de como o sistema será operado ao longo de seu ciclo de vida para atender às expectativas dos stakeholders.
- Inclui **cenários operacionais, casos de uso e Missões de Referência de Projeto (DRMs)**.
- Pode estar documentado em diferentes formatos, como **textos, gráficos, vídeos, modelos e simulações**.

✅ **Estratégias de Suporte a Produtos Habilitadores (Baseline)**
- Identificação dos produtos auxiliares necessários para **desenvolver, testar, produzir, operar e descartar** o produto final.
- Inclui também como o **suporte será garantido durante todo o ciclo de vida do sistema**.

✅ **Medidas de Efetividade (MOEs)**
- Definição dos critérios essenciais para que o projeto seja considerado um **sucesso**.
- Foram identificadas no **processo de definição das expectativas dos stakeholders**.
- Se os requisitos técnicos não atenderem a esses critérios, o sistema pode ser rejeitado pelos stakeholders.

---

Essa abordagem garante que os requisitos técnicos sejam **claros, bem documentados e alinhados com as expectativas do projeto**, minimizando riscos e garantindo uma implementação eficiente. 🚀

a definir os limites do projeto e a evitar alterações em componentes críticos.

### **4.2.1.1 (Continuação) - Outras Entradas Úteis**
Além dos insumos já mencionados, outros fatores podem ser relevantes para a definição dos requisitos técnicos:

✅ **Alocação de Funções entre Humanos e Sistemas**
- Define as interações entre hardware, software e operadores humanos, além da infraestrutura de suporte.
- Essencial quando os operadores humanos são **componentes críticos do sistema**.
- Deve abranger todas as interações entre humanos e sistema, incluindo:
  - **Montagem**
  - **Operações em solo**
  - **Logística**
  - **Manutenção em voo e em solo**
  - **Operações durante a missão**

---

## **4.2.1.2 Atividades do Processo**

### **4.2.1.2.1 Definição de Restrições, Expectativas Funcionais e Comportamentais**
Para entender o problema técnico e definir os limites do design, os requisitos de alto nível e as expectativas são analisados por meio das seguintes atividades:

✅ **Definição de Restrições**
- Restrições que **o design deve obedecer** e que limitam como o sistema será utilizado.
- Essas restrições geralmente **não podem ser alteradas** por meio de análises de trade-off.

✅ **Identificação de Elementos Sob Controle de Design**
- Identifica os componentes que já estão **projetados e não podem ser modificados**.
- Ajuda a definir **limites rígidos para o projeto**, evitando mudanças indesejadas em elementos críticos.

Essa abordagem garante que o desenvolvimento do sistema **permanecerá dentro dos parâmetros técnicos e operacionais aceitáveis**, reduzindo riscos e facilitando a validação com os stakeholders. 🚀

### **4.2.1.2.1 (Continuação) - Definição de Restrições, Expectativas Funcionais e Comportamentais**

✅ **Áreas para Trade-offs**
- Identificação de aspectos do projeto onde **análises comparativas** (trade-offs) podem ser feitas para restringir o espaço de soluções de design.

✅ **Identificação de Sistemas Externos e de Suporte**
- Determinação de sistemas externos e produtos habilitadores com os quais o sistema deve interagir.
- Definição das **interfaces físicas e funcionais** (mecânicas, elétricas, térmicas, humanas, etc.).

✅ **Definição de Expectativas Funcionais e Comportamentais**
- Baseia-se no **ConOps (Concept of Operations)**.
- Define como o sistema será operado e os possíveis cenários de uso.

---

### **4.2.1.2.2 Definição de Requisitos**

📌 **Os requisitos do projeto incluem:**
✔ **Requisitos funcionais** → O que o sistema precisa fazer.
✔ **Requisitos de desempenho** → Quão bem o sistema deve executar suas funções.
✔ **Requisitos de interface** → Como os produtos interagem entre si.

✅ **Requisitos de Cruzamento**
- Existem requisitos que atravessam **múltiplas fronteiras do produto**, como:
  - **Requisitos ambientais**
  - **Fatores de segurança**
  - **Ergonomia e fatores humanos**
  - **Normas de Design e Construção (D&C)**
  - **Outros requisitos de confiabilidade e manutenção ("-ilities")**

✅ **Expressão Quantitativa do Desempenho**
- Cada função do sistema deve ser **quantificada** para indicar **como** e **quão bem** precisa ser realizada.

Essa abordagem garante que os requisitos são **completos, bem definidos e alinhados às expectativas dos stakeholders**, permitindo um desenvolvimento mais eficiente e validado. 🚀
### **4.2.1.2.3 Definição de Requisitos em Formato Aceitável**

✅ **Uso de "Shall" Statements**
Os requisitos devem ser expressos como declarações completas utilizando **"shall"**, garantindo que cada declaração tenha um único propósito.

✅ **Captura da Justificativa**
Cada requisito deve incluir uma **racionalização** para garantir que sua finalidade e contexto sejam claramente compreendidos.

✅ **Identificação de Requisitos-Chave (KDRs)**
Os **Key Driving Requirements (KDRs)** são requisitos que possuem **grande impacto no custo e cronograma** do projeto.
- Eles podem ter qualquer nível de prioridade.
- Compreender o impacto dos KDRs permite uma melhor **gestão dos requisitos** e suas consequências no design.

✅ **Metadados dos Requisitos**
É essencial capturar **metadados** sobre cada requisito para referência futura.
- Ferramentas de **gerenciamento de requisitos** frequentemente oferecem opções para armazenar essas informações.

✅ **Validação dos Requisitos**
- Deve ser feita uma **verificação rigorosa** para garantir que os requisitos correspondam às expectativas dos stakeholders.
- Apêndices C e E fornecem **diretrizes e checklists** para escrita e validação de requisitos.

📌 **Benefícios de um Documento de Requisitos Bem-Escrito**
- Facilita a **comunicação** entre stakeholders e equipe técnica.
- Reduz riscos de **interpretações erradas**.
- Melhora o **controle de mudanças** e a **gestão do projeto**.
Aqui está a tradução do texto:

---

## Estrutura subjacente e relacionamentos de hardware, software, humanos no loop, pessoal de suporte, comunicações, operações, etc., que possibilitam a implementação dos requisitos da Agência, diretoria de missão, programa, projeto e níveis subsequentes.

As atividades de arquitetura de sistemas impulsionam a divisão dos elementos e requisitos do sistema em funções e requisitos de nível inferior até o ponto em que o trabalho de design possa ser realizado. Interfaces e relacionamentos entre subsistemas e elementos particionados também são definidos.

Uma vez que os requisitos funcionais e restrições de alto nível (ou requisitos "pai") tenham sido estabelecidos, o projetista do sistema usa a análise funcional para começar a formular uma arquitetura conceitual do sistema.

A **arquitetura do sistema** pode ser vista como a organização estratégica dos elementos funcionais do sistema, dispostos de forma a permitir que os papéis, relacionamentos, dependências e interfaces entre os elementos sejam claramente definidos e compreendidos.

Ela é estratégica ao focar na estrutura geral do sistema e em como seus elementos se encaixam para contribuir para o todo, em vez de se concentrar no funcionamento específico dos elementos. Isso permite que os elementos sejam desenvolvidos separadamente, garantindo que funcionem juntos de maneira eficaz para atender aos requisitos de alto nível.

Assim como outros elementos da **decomposição funcional**, o desenvolvimento de uma boa arquitetura de sistema é um processo **criativo, recursivo, colaborativo e iterativo**. Esse processo combina uma compreensão clara dos objetivos finais do projeto e suas restrições com um bom conhecimento dos diversos meios técnicos para entregar os produtos finais.

Focando nos fins do projeto, nos requisitos e restrições de alto nível, o arquiteto do sistema deve desenvolver **pelo menos uma, mas de preferência várias arquiteturas conceituais** capazes de atingir os objetivos do programa.

Cada conceito de arquitetura envolve:
- Especificação dos elementos funcionais (o que cada parte faz).
- Definição de suas relações entre si (interfaces).
- **ConOps** (Concept of Operations), ou seja, como os diferentes segmentos, subsistemas, elementos, pessoal e unidades operarão juntos no sistema, distribuídos em diferentes locais e ambientes desde o início das operações até o fim da missão.

O processo de desenvolvimento das arquiteturas conceituais deve ser **recursivo e iterativo**, com feedback frequente de partes interessadas, revisores externos, projetistas de subsistemas e operadores. Isso aumenta as chances de alcançar os objetivos desejados do programa e reduz a probabilidade de **atrasos e custos excessivos**.

Nos estágios iniciais do desenvolvimento, **várias arquiteturas conceituais são geradas**. No entanto, **restrições de custo e cronograma** eventualmente limitam o tempo que um programa ou projeto pode manter múltiplas arquiteturas em consideração.

Para todos os programas da NASA, o design da arquitetura é concluído durante a **Fase de Formulação**. Para a maioria dos projetos e programas altamente integrados, a definição final de uma única arquitetura ocorre na **Fase A**.

Mudanças na arquitetura de alto nível podem ocorrer ocasionalmente à medida que a decomposição para níveis inferiores torna o design, custo ou cronograma mais complexos. No entanto, conforme ilustrado na Figura 2.5-1, **quanto mais tarde no processo de desenvolvimento uma mudança ocorre, mais cara ela se torna**.

Além da criatividade dos arquitetos, várias **ferramentas** podem ser utilizadas para desenvolver a arquitetura de um sistema. Essas ferramentas incluem:
- Modelagem e simulação.
- Ferramentas de análise funcional.
- Estruturas de arquitetura (como o **DODAF** – Department of Defense Architecture Framework).
- Estudos comparativos de alternativas técnicas (**trade studies**).

Um conceito de busca é desenvolvido e **modelos analíticos** da arquitetura, seus elementos e operações são aprimorados conforme o projeto evolui. A decomposição funcional, o desenvolvimento de requisitos e os estudos comparativos alimentam continuamente a arquitetura em desenvolvimento, refinando-a à medida que os requisitos são detalhados e o design amadurece.

---

### **4.3.1.2.2 – Alocar Requisitos Técnicos, Resolver Conflitos e Estabelecer a Arquitetura Base**

A **análise funcional** é o principal método utilizado no desenvolvimento da arquitetura de sistemas e na decomposição dos requisitos funcionais. Ela é um **processo sistemático** de identificação, descrição e relacionamento das funções que um sistema deve desempenhar para atender a seus objetivos.

A análise funcional **liga os requisitos do sistema às funções, estudos comparativos, características de interface e justificativas**. Geralmente, ela é baseada no **ConOps** (Conceito de Operação) do sistema.

Os **três passos principais** da análise funcional são:

1. **Traduzir** os requisitos de alto nível em funções que o sistema deve executar.
2. **Decompor** e **alocar** essas funções em níveis inferiores da estrutura do produto.
3. **Identificar e descrever** as interfaces entre as funções e subsistemas.

Esse processo envolve a análise de cada requisito do sistema para identificar todas as funções que precisam ser desempenhadas para atendê-lo. Cada função identificada é descrita em termos de:
- **Entradas e saídas**
- **Modos de falha e consequências das falhas**
- **Requisitos de interface**

A análise é repetida **de cima para baixo**, garantindo que todas as funções menores estejam corretamente relacionadas às funções principais. As funções são organizadas em uma **sequência lógica**, permitindo que qualquer uso operacional especificado do sistema possa ser rastreado de ponta a ponta.

Esse processo é **recursivo e iterativo**, continuando até que todos os níveis desejados da arquitetura do sistema tenham sido analisados, definidos e formalizados. Como há **múltiplas formas de decompor funções**, o resultado depende muito da criatividade, habilidades e experiência dos engenheiros que realizam a análise.

Por exemplo, há várias formas de comunicação com a tripulação:
- Rádio Frequência (**RF**)
- Laser
- Internet

À medida que a análise avança e o sistema é melhor compreendido, os engenheiros devem **manter a mente aberta** e estar dispostos a revisar requisitos e decisões previamente estabelecidas. Quando mudanças ocorrem, elas devem ser **propagadas para baixo** na arquitetura e em suas subfunções, com o processo recursivo continuando até que o sistema esteja completamente definido e os requisitos sejam **viáveis, verificáveis e consistentes**.

Somente **quando esse processo estiver completo**, a arquitetura do sistema e seus requisitos devem ser formalizados.

---

### **4.3.1.2.3 – Capturar Produtos de Trabalho**

Os produtos gerados durante o **processo de decomposição lógica** devem ser armazenados, juntamente com:
- **Decisões-chave tomadas**
- **Justificativas das decisões**
- **Premissas adotadas**
- **Lições aprendidas**

---

### **4.3.1.3 – Resultados**

Os principais resultados do **Processo de Decomposição Lógica** incluem:

- **Modelos de decomposição lógica**, que definem o relacionamento entre requisitos, funções e comportamentos.
- **Modelos de arquitetura do sistema**, que representam a estrutura e os relacionamentos entre os elementos do sistema (hardware, software, humanos no loop, suporte, comunicações, operações etc.).
- **Base para a divisão e alocação dos componentes do sistema.**

---
Aqui está a tradução do trecho solicitado:

---

**Tradução de Requisitos para Níveis Inferiores até o Ponto em que o Trabalho de Projeto Possa ser Realizado**

- **Requisitos Técnicos Derivados:** São requisitos que surgem a partir das definições da arquitetura selecionada e que não foram explicitamente declarados nos requisitos base que serviram de entrada para este processo. Tanto os requisitos base quanto os derivados são alocados à arquitetura e às funções do sistema.

- **Produtos do Trabalho de Decomposição Lógica:** São os outros produtos gerados pelas atividades deste processo para o produto e para a verificação do produto. Esse processo pode ser refinado ainda mais, dependendo da necessidade de definição de subsistemas adicionais do produto final.

### **4.3.2 Orientação para a Decomposição Lógica**
Consulte a Seção 4.3.2 e o Apêndice F no documento **NASA Expanded Guidance for Systems Engineering** em [https://nen.nasa.gov/web/se/doc-repository](https://nen.nasa.gov/web/se/doc-repository) para mais orientações sobre:
- Estruturas de Decomposição do Produto
- Técnicas de Análise Funcional

---

### **4.4 Definição da Solução de Projeto**
O **Processo de Definição da Solução de Projeto** é utilizado para traduzir os requisitos de alto nível derivados das expectativas das partes interessadas e os resultados do **Processo de Decomposição Lógica** em uma solução de projeto.

Isso envolve a transformação dos modelos definidos na decomposição lógica e seus conjuntos de requisitos técnicos derivados em **soluções alternativas**. Essas soluções alternativas são analisadas por meio de estudos de viabilidade detalhados, resultando na escolha de uma alternativa preferida.

A alternativa preferida é então completamente definida em uma solução final de projeto que atenda aos requisitos técnicos. Essa definição da solução de projeto é utilizada para gerar as especificações do produto final, que são empregadas na produção.

---

### **4.4.1 Descrição do Processo**
A **FIGURA 4.4-1** apresenta um diagrama típico do fluxo do **Processo de Definição da Solução de Projeto**, identificando as entradas, saídas e atividades essenciais a serem consideradas.

#### **4.4.1.1 Entradas**
Para iniciar o **Processo de Definição da Solução de Projeto**, são necessárias várias entradas fundamentais:

- **Requisitos Técnicos:** São as necessidades dos clientes e das partes interessadas traduzidas em um conjunto completo de requisitos validados para o sistema, incluindo todos os requisitos de interface.

- **Modelos de Decomposição Lógica:** Os requisitos são analisados e decompostos por meio de diversos métodos (por exemplo, função, tempo, comportamento, fluxo de dados, estados, modos, arquitetura do sistema, etc.) para obter uma compreensão mais detalhada das interações e comportamentos do sistema. (Consulte a definição de **modelo** no Apêndice B.)

---

A realização de um sistema ao longo de seu ciclo de vida envolve uma **sucessão de decisões** entre diferentes alternativas. Se essas alternativas forem claramente definidas e bem diferenciadas em termos de **custo-benefício**, o engenheiro de sistemas pode tomar decisões com confiança.

Para obter avaliações suficientemente detalhadas para permitir boas decisões, muitas vezes é necessário aprofundar-se no espaço de possíveis designs mais do que já foi feito, como ilustrado na **FIGURA 4.4-2**.

No entanto, é importante notar que essa ilustração não representa nem o ciclo de vida do projeto, que engloba o desenvolvimento do sistema desde sua concepção até sua descontinuação, nem o processo de desenvolvimento do produto, pelo qual o design do sistema é desenvolvido e implementado.

---

Cada etapa de **"criação de conceitos"** na **FIGURA 4.4-2** envolve um ciclo **recursivo e iterativo** de projeto, orientado pelas expectativas das partes interessadas. Nessa etapa:
- Uma arquitetura preliminar ("straw man architecture/design") é desenvolvida.
- O **ConOps** (Conceito de Operações) é definido.
- Os requisitos derivados são estabelecidos.
- Restrições programáticas, como custo e cronograma, são consideradas.

Esses três elementos devem ser **consistentes entre si** e podem exigir várias iterações e decisões de projeto para alcançar essa consistência. Esse ciclo recursivo e iterativo é ilustrado na **FIGURA 4.0-1**.

Além disso, a etapa de "criação de conceitos" também envolve a avaliação das **capacidades tecnológicas disponíveis** e dos **riscos identificados** com base em experiências anteriores de programas/projetos.

É essencial haver **interação contínua** entre o **processo de desenvolvimento tecnológico**, processos transversais como **integração de sistemas humanos** e o próprio **processo de design**, para garantir que o projeto reflita a **realidade das tecnologias disponíveis** e evite a dependência excessiva de tecnologias imaturas.

Além disso, o estado de qualquer tecnologia considerada essencial para o projeto deve ser **monitorado de perto**, e seu impacto no desempenho do conceito deve ser cuidadosamente avaliado.

Essa interação é facilitada por **avaliações periódicas** do design em relação à maturidade da tecnologia necessária para implementá-lo. (Consulte a **Seção 4.4.2.1** no documento **NASA Expanded Guidance for Systems Engineering** para uma discussão mais detalhada sobre a avaliação da tecnologia.)

Esses elementos tecnológicos normalmente existem em **níveis inferiores** na **Estrutura de Decomposição do Produto (PBS - Product Breakdown Structure)**.

Embora o desenvolvimento do conceito de design por meio da integração de elementos de nível inferior faça parte do **processo de engenharia de sistemas**, existe sempre o risco de que o **processo de cima para baixo** (top-down) não acompanhe o **processo de baixo para cima** (bottom-up).

Portanto, **as questões de arquitetura do sistema devem ser resolvidas cedo**, para que o sistema possa ser **modelado com realismo suficiente** para permitir **estudos de viabilidade confiáveis**.

À medida que o sistema se torna realidade, seus detalhes se tornam mais claros—**mas também mais difíceis de modificar**.
Aqui está a tradução do trecho:

---

### Tradução:

A decomposição dos requisitos para níveis inferiores deve ser feita até o ponto em que o trabalho de design possa ser realizado.

**Requisitos Técnicos Derivados:** Esses são requisitos que surgem a partir das definições da arquitetura selecionada e que não foram explicitamente declarados nos requisitos base que serviram como entrada para esse processo. Tanto os requisitos base quanto os requisitos derivados são alocados à arquitetura e funções do sistema.

**Produtos de Trabalho da Decomposição Lógica:** São outros produtos gerados pelas atividades deste processo para o produto e para a verificação do produto. Esse processo pode ser refinado ainda mais, dependendo da necessidade de definir subsistemas adicionais do produto final.

### 4.3.2 Orientação para a Decomposição Lógica
Consulte a Seção 4.3.2 e o Apêndice F no **Guia Expandido da NASA para Engenharia de Sistemas** (disponível em: [https://nen.nasa.gov/web/se/doc-repository](https://nen.nasa.gov/web/se/doc-repository)) para orientações adicionais sobre:

- Estruturas de Decomposição do Produto
- Técnicas de Análise Funcional

---

### 4.4 Definição da Solução de Design

O Processo de Definição da Solução de Design é usado para traduzir os requisitos de alto nível derivados das expectativas das partes interessadas e das saídas do Processo de Decomposição Lógica em uma solução de design. Isso envolve a transformação dos modelos de decomposição lógica e seus conjuntos associados de requisitos técnicos derivados em soluções alternativas.

Essas soluções alternativas são analisadas por meio de estudos comparativos detalhados, que resultam na seleção de uma alternativa preferida. Essa alternativa preferida é então totalmente definida em uma solução de design final que atenda aos requisitos técnicos.

A definição da solução de design é usada para gerar as especificações do produto final, que serão utilizadas na produção.

#### 4.4.1 Descrição do Processo
A **FIGURA 4.4-1** fornece um diagrama de fluxo típico para o Processo de Definição da Solução de Design e identifica entradas, saídas e atividades típicas a serem consideradas na definição da solução de design.

##### 4.4.1.1 Entradas
Várias entradas fundamentais são necessárias para iniciar o Processo de Definição da Solução de Design:

- **Requisitos Técnicos:** São as necessidades dos clientes e das partes interessadas, traduzidas em um conjunto completo de requisitos validados para o sistema, incluindo todos os requisitos de interface.
- **Modelos de Decomposição Lógica:** Os requisitos são analisados e decompostos por um ou mais métodos (por exemplo, função, tempo, comportamento, fluxo de dados, estados, modos, arquitetura do sistema, etc.) para obter uma compreensão mais abrangente de suas interações e comportamentos. (Veja a definição de um modelo no Apêndice B.)

A realização de um sistema ao longo de seu ciclo de vida envolve uma sucessão de decisões entre diferentes alternativas. Se as alternativas forem bem definidas e compreendidas o suficiente para serem diferenciadas em termos de custo-benefício, o engenheiro de sistemas poderá tomar decisões com confiança.

Para obter avaliações suficientemente detalhadas para permitir boas decisões, muitas vezes é necessário aprofundar a análise das possíveis soluções de design, conforme ilustrado na **FIGURA 4.4-2**.

Entretanto, é importante perceber que essa ilustração não representa o ciclo de vida do projeto, que engloba o desenvolvimento do sistema desde sua concepção até sua desativação, nem o processo de desenvolvimento do produto pelo qual o design do sistema é desenvolvido e implementado.

Cada etapa de "criação de conceitos" na **FIGURA 4.4-2** envolve um ciclo de design recursivo e iterativo, orientado pelo conjunto de expectativas das partes interessadas. Esse processo inclui o desenvolvimento de uma arquitetura preliminar ("straw man architecture"), um Conceito de Operação (**ConOps**) e requisitos derivados, além da consideração de restrições programáticas como custo e cronograma.

Esses três elementos devem ser consistentes entre si e podem exigir várias iterações e decisões de design para atingir essa consistência. Esse ciclo de design recursivo e iterativo é ilustrado na **FIGURA 4.0-1**.

Além disso, cada etapa de "criação de conceitos" na **FIGURA 4.4-2** também inclui uma avaliação das capacidades potenciais oferecidas pelo estado da tecnologia em constante evolução, bem como dos riscos identificados com base na análise de projetos anteriores e lições aprendidas.

É essencial que haja uma interação contínua entre o processo de desenvolvimento tecnológico, processos transversais como integração de sistemas humanos e o processo de design. Isso garante que o design reflita as realidades da tecnologia disponível e evita uma dependência excessiva de tecnologias imaturas.

Além disso, o estado de qualquer tecnologia considerada essencial deve ser monitorado de perto, e deve-se ter cuidado ao avaliar seu impacto no desempenho do conceito. Essa interação é facilitada por meio de avaliações periódicas da maturidade da tecnologia necessária para implementar o design. (Consulte a Seção 4.4.2.1 no **Guia Expandido da NASA para Engenharia de Sistemas** para uma discussão mais detalhada sobre avaliação tecnológica.)

Esses elementos tecnológicos normalmente estão em níveis inferiores na **Estrutura de Decomposição do Produto (PBS - Product Breakdown Structure)**. Embora o desenvolvimento de conceitos de design pela integração de elementos de nível inferior faça parte do processo de engenharia de sistemas, há sempre o risco de que o processo de cima para baixo não acompanhe o processo de baixo para cima.

Portanto, questões relacionadas à arquitetura do sistema devem ser resolvidas antecipadamente para que o sistema possa ser modelado com realismo suficiente para permitir estudos comparativos confiáveis.

À medida que o sistema é implementado, suas características tornam-se mais claras—mas também mais difíceis de modificar. Veja o aumento do "Custo para Mudar a Direção do Design" na **FIGURA 2.5-1**.

O objetivo da engenharia de sistemas é garantir que o **Processo de Definição da Solução de Design** ocorra de forma a levar a um sistema final funcional, seguro e economicamente viável, respeitando as restrições de cronograma.

A ideia básica é que, antes de tomar decisões difíceis de reverter, as alternativas devem ser cuidadosamente e iterativamente avaliadas, especialmente com relação à maturidade da tecnologia necessária e às expectativas das partes interessadas para operações eficientes e eficazes.

##### 4.4.1.2.2 Criar Conceitos de Design Alternativos
Uma vez compreendido o que o sistema deve realizar, é possível desenvolver diferentes maneiras de atingir esses objetivos.

Isso pode envolver diferentes alocações funcionais e a integração de opções de subsistemas disponíveis, que podem incorporar tecnologias com diferentes níveis de maturidade.

Idealmente, deve-se definir o maior número possível de alternativas plausíveis, levando em consideração o estágio atual do refinamento sucessivo do design.

No processo de desenvolvimento, um problema comum para o engenheiro de sistemas é que os designers tendem a se apegar aos seus próprios designs, perdendo a objetividade. O engenheiro de sistemas deve se manter um "observador externo" para garantir uma avaliação mais objetiva, especialmente ao considerar a maturidade tecnológica dos subsistemas e componentes necessários para a implementação.

O desenvolvimento de conceitos alternativos de design envolve a avaliação contínua das capacidades oferecidas pelo estado da tecnologia. A interação entre o processo de desenvolvimento tecnológico e o design é essencial para garantir que o design esteja alinhado com as tecnologias disponíveis.

Se os requisitos forem definidos sem compreender completamente os recursos necessários para o desenvolvimento da tecnologia, o projeto estará em risco. A avaliação tecnológica deve ser realizada iterativamente até que os requisitos e os recursos disponíveis estejam alinhados dentro de um nível de risco aceitável.

---

Aqui está a tradução do texto:

---

Durante o ciclo de vida da solução de design selecionada, deve-se iniciar a aquisição ou o desenvolvimento dos produtos habilitadores e da equipe necessária. As datas em que os produtos habilitadores serão necessários devem ser identificadas de forma realista nos cronogramas do projeto, incorporando uma margem de segurança adequada. Em seguida, devem ser firmados compromissos concretos na forma de contratos, acordos e/ou planos operacionais para garantir que os produtos habilitadores estejam disponíveis quando necessários para apoiar as atividades da fase do ciclo de vida do produto. Os requisitos dos produtos habilitadores são documentados como parte do pacote de dados técnicos do Processo de Definição da Solução de Design.

Uma câmara de teste ambiental é um exemplo de produto habilitador cuja utilização seria adquirida no momento apropriado durante a fase de testes de um sistema de voo espacial.

Dispositivos de teste especiais ou dispositivos especiais de manuseio mecânico são exemplos de produtos habilitadores que precisariam ser desenvolvidos pelo projeto. Como esses itens podem ter tempos de desenvolvimento longos e as instalações podem estar sobrecarregadas, é fundamental identificar os produtos habilitadores e garantir os compromissos para sua disponibilidade o mais cedo possível na fase de design.

### 4.4.1.2.10 Estabelecimento da Base da Solução de Design

Conforme ilustrado anteriormente na FIGURA 4.0-1, quando a solução de design do sistema selecionado atende às expectativas das partes interessadas, a equipe de estudo estabelece a base dos produtos e se prepara para a próxima fase do ciclo de vida. Devido à natureza recursiva do refinamento sucessivo, os níveis intermediários de decomposição frequentemente são validados e estabelecidos como parte do processo. No próximo nível de decomposição, os requisitos estabelecidos tornam-se o conjunto de requisitos de alto nível para os elementos decompostos, e o processo recomeça.

Estabelecer uma base para uma determinada solução de design permite que a equipe técnica se concentre em um único design entre todas as alternativas possíveis. Este é um ponto crítico no processo de design, pois define uma direção clara e garante que todos na equipe de design estejam focados no mesmo conceito. Quando se trabalha com sistemas complexos, torna-se difícil para os membros da equipe projetarem suas partes do sistema se o design estiver constantemente mudando. A solução de design estabelecida é documentada e colocada sob controle de configuração, incluindo os requisitos do sistema, especificações e descrições da configuração.

Embora estabelecer uma base para o design seja benéfico para o processo de desenvolvimento, há um risco caso isso ocorra muito cedo no Processo de Definição da Solução de Design. A fase inicial de exploração de alternativas deve ser livre e aberta a uma ampla variedade de ideias, conceitos e implementações. Se a base for estabelecida muito cedo, a natureza criativa da exploração conceitual será prejudicada. Portanto, esse processo deve ocorrer apenas nas etapas finais da Definição da Solução de Design.

### 4.4.1.3 Saídas

As saídas do Processo de Definição da Solução de Design são as especificações e planos que são repassados para os processos de realização do produto. Eles contêm a documentação necessária para projetar, construir, treinar e codificar conforme o baseline aprovado para o sistema.

Conforme mencionado anteriormente, o escopo e o conteúdo da descrição completa do design devem ser apropriados para a fase do ciclo de vida do produto, os critérios de sucesso da fase e a posição do produto na Estrutura Analítica do Produto (PBS).

As saídas do Processo de Definição da Solução de Design incluem os seguintes itens:

- **Especificação do Sistema:** Contém a base funcional do sistema resultante do Processo de Definição da Solução de Design. Esta especificação fornece diretrizes, restrições e requisitos do sistema suficientes para que os engenheiros de design comecem a desenvolver o projeto.
- **Especificações das Interfaces Externas do Sistema:** Descrevem a base funcional para o comportamento e características de todas as interfaces físicas que o sistema tem com o mundo externo, incluindo interfaces estruturais, térmicas, elétricas, de sinal e interfaces homem-sistema.
- **Especificações do Produto Final:** Contêm os requisitos detalhados para a construção e codificação do produto final. Esses requisitos são declarações exatas sobre materiais, dimensões e qualidade do trabalho para a fabricação, instalação ou montagem do produto final.
- **Especificações das Interfaces do Produto Final:** Contêm requisitos detalhados para a construção e codificação das interfaces lógicas e físicas do produto final com elementos externos, incluindo interfaces homem-sistema.
- **Requisitos dos Produtos Habilitadores:** Detalham todos os produtos habilitadores necessários. Esses produtos incluem suporte ao ciclo de vida, infraestrutura, equipe, logística e serviços que facilitam o uso e operação do produto final ao longo do seu ciclo de vida. Eles são considerados parte do sistema, pois o produto final e seus produtos habilitadores são interdependentes.
- **Plano de Verificação do Produto:** Desenvolvido através do Processo de Planejamento Técnico, este plano detalha todas as atividades de verificação do produto final. Dependendo do escopo do produto, o plano pode abranger atividades de qualificação, aceitação, pré-lançamento, operação e descarte para hardware e software de voo.
- **Plano de Validação do Produto:** Também gerado através do Processo de Planejamento Técnico, este plano detalha todas as atividades de validação do produto final em relação às expectativas das partes interessadas. O plano identifica o tipo de validação, os procedimentos e o ambiente de validação necessários para confirmar que o produto final atende às expectativas dos stakeholders.
- **Procedimentos de Logística e Operação:** Incluem diretrizes para manuseio, transporte, manutenção, armazenamento de longo prazo e considerações operacionais específicas para a solução de design adotada.

Outras saídas podem incluir:

- **Plano de Integração dos Sistemas Humanos:** Deve ser atualizado para indicar a quantidade, habilidades e treinamento necessário para os humanos ao longo do ciclo de vida do sistema.

### 4.4.2 Diretrizes para a Definição da Solução de Design

Para mais informações sobre:

- avaliação de tecnologia,
- avaliação da capacidade humana, e
- integração de especialidades de engenharia no processo de engenharia de sistemas,

consulte a Seção 4.4.2 no **NASA Expanded Guidance for Systems Engineering**, disponível em:
[https://nen.nasa.gov/web/se/doc-repository](https://nen.nasa.gov/web/se/doc-repository)

---

Se precisar de ajustes ou de um resumo mais curto, me avise! 😊
