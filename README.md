## Exercício – Página de Receita (Frontend Mentor)

### Objetivos do exercício

Este exercício teve como objetivo aplicar os conhecimentos adquiridos em HTML, CSS, SASS e Node em um projeto prático, utilizando um desafio proposto pelo Frontend Mentor. A proposta consistia em reconstruir uma página de receita com base apenas em imagens fornecidas (versões mobile e desktop), sem acesso ao design no Figma, o que exigiu um olhar atento para detalhes visuais como cores, tipografia, espaçamento e hierarquia de conteúdo.

### Escolha do desafio e motivação

A escolha desse exercício surgiu da necessidade de colocar em prática os fundamentos de marcação e estilização que venho estudando há algum tempo. Eu queria testar se conseguiria construir um layout realista a partir de uma referência visual, mesmo sem acesso direto aos arquivos de design. A ausência do Figma foi um desafio intencional: a ideia era justamente treinar a capacidade de observar e interpretar um layout apenas por imagem.

### Tecnologias utilizadas

* **HTML5** para estruturação semântica do conteúdo
* **CSS3** para estilização base
* **SASS** para organização e modularização dos estilos
* **Node.js** para instalação de ferramentas de desenvolvimento, como plugins de SASS

### Processo de desenvolvimento

#### Estruturação inicial

A página foi dividida nas seguintes seções principais:

* **Hero**: inclui a imagem do prato, o título e a descrição da receita.
* **Preparação**: traz um destaque visual para tempo e porções.
* **Ingredientes**: lista não ordenada com os itens necessários.
* **Instruções**: sequência numerada dos passos da receita.
* **Nutrição**: apresenta uma tabela com dados nutricionais.

#### Organização do layout

O layout foi construído com **Flexbox** em direção de coluna, seguindo a abordagem **mobile-first**. A versão desktop apresenta um `body` com fundo verde claro e um `container` branco, centralizado, com cantos arredondados para se aproximar do modelo visual fornecido.

Os elementos principais foram centralizados com largura de 90% para manter a fluidez. A imagem principal ocupa 100% da largura na versão mobile, conforme o layout de referência.

#### Definição de cores e fontes sem Figma

Como o projeto não disponibiliza os arquivos do Figma para usuários gratuitos, precisei importar as imagens no próprio Figma e utilizar a ferramenta de conta-gotas para descobrir os códigos de cor. Os tamanhos de fonte foram estimados com base no texto padrão (16px) indicado no desafio e nas proporções visuais dos títulos e listas.

#### Compilação e ambiente com Node

Utilizei o Node.js para configurar o ambiente de desenvolvimento, instalando pacotes que permitiram compilar o SASS e organizar melhor os arquivos CSS. A estrutura de arquivos seguiu o padrão modular, com separação de estilos por seções e elementos.

### Dificuldades encontradas

#### Construção da tabela (seção Nutrição)

A parte mais desafiadora foi a construção da tabela de dados nutricionais. Apesar de conhecer a estrutura básica do elemento `<table>`, percebi que não tinha prática suficiente para aplicá-la com segurança. Levei mais tempo nessa parte e tive dúvidas sobre a melhor forma de organizar e estilizar a tabela de forma responsiva.

#### Interpretação visual

Sem acesso aos estilos no Figma, foi necessário interpretar as fontes, tamanhos e pesos “no olho”, o que exigiu diversas tentativas até alcançar um resultado visualmente próximo do esperado.

### Responsividade

A responsividade foi alcançada com poucas regras adicionais. O uso de largura relativa (90%) e o ajuste da imagem para 100% garantiram que os elementos se adaptassem bem às diferentes larguras de tela. A disposição em coluna no mobile funcionou bem, e o layout no desktop foi centralizado com espaçamento adequado.

### Pontos de atenção para estudos futuros

* Revisar e praticar mais a construção de tabelas HTML com foco em boas práticas e acessibilidade.
* Estudar formas mais eficientes de estimar proporções de design quando não se tem acesso ao layout original.
* Aprofundar o uso de SASS em estruturas maiores, explorando mixins, variáveis e partials.

### **Resumo do exercício**

Este foi um exercício valioso para consolidar os conhecimentos em HTML, CSS e SASS, além de testar a capacidade de interpretar e traduzir um layout visual em código. Trabalhar sem o Figma exigiu mais atenção aos detalhes e reforçou a importância de desenvolver o olhar técnico. A dificuldade com a tabela apontou um ponto claro para revisitar nos estudos, mas no geral o projeto foi bem executado e reforçou o aprendizado de práticas reais do dia a dia de quem trabalha com front-end.

## Estudar
* Desestruturação Java Script
* WSL - Linux no windows