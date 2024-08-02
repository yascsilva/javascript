# Atividade de Pesquisa: Introdução ao JavaScript

![image](https://github.com/user-attachments/assets/9645ffec-56d0-4ba2-8042-a11dca671499)

## O que é JavaScript?
*JavaScript (JS)* é uma linguagem de programação de alto nível, interpretada e orientada a objetos, amplamente utilizada para criar páginas web interativas. Em termos simples, o JavaScript permite que páginas web "ganhem vida", respondendo às ações do usuário e tornando a experiência online mais dinâmica e envolvente.


### História e Evolução do JavaScript
- **Criação:** O JavaScript foi criado por Brendan Eich em 1995, inicialmente com o nome de Mocha, e depois renomeado para LiveScript. A Netscape, empresa de navegadores da época, adotou a linguagem e a rebatizou como JavaScript, buscando aproveitar a popularidade da linguagem Java.
- **Padronização:** Em 1996, o JavaScript foi padronizado pela ECMA International como ECMAScript, o que ajudou a unificar as implementações da linguagem nos diferentes navegadores.
- **Evolução:** Ao longo dos anos, o JavaScript passou por diversas atualizações e evoluções, introduzindo novas funcionalidades e aprimorando a linguagem. A cada nova versão do ECMAScript, a linguagem se tornou mais poderosa e expressiva.
- **Popularidade:** O JavaScript se tornou a linguagem de programação mais utilizada no mundo, com um vasto ecossistema de frameworks e bibliotecas, como React, Angular e Vue.js, que facilitam o desenvolvimento de aplicações web complexas.
- **Novos paradigmas:** O JavaScript evoluiu para suportar novos paradigmas de programação, como a programação funcional e orientada a objetos, tornando-a uma linguagem ainda mais versátil e adaptável a diferentes estilos de desenvolvimento.

### Principais marcos na evolução do JavaScript:

- **ECMAScript 5:** Introduziu novas funcionalidades como getters e setters, métodos de array, JSON e strict mode.
- **ECMAScript 6 (ES6):** Uma grande atualização que trouxe módulos, classes, arrow functions, promises e muitas outras melhorias.
- **ECMAScript 2017, 2018, 2019 e além:** Continuaram a adicionar novas funcionalidades e aprimorar a linguagem, como async/await, destructuring, spread operator e decorators.

## Características Básicas do JavaScript

**O que são Variáveis?**

Variáveis são como recipientes que armazenam dados em JavaScript. Você pode pensar nelas como rótulos que se referem a valores específicos. Esses valores podem mudar ao longo do tempo, daí o nome "variável".

### Como são declaradas?

Em JavaScript, você usa as palavras-chave **let**, **const** ou **var** para declarar uma variável. Cada uma tem suas particularidades:

- **let**: Permite redeclarar o valor da variável dentro de seu escopo, mas não permite redeclarar a variável em si. É a mais utilizada nas versões modernas do JavaScript.
- **const:** Declara uma constante, ou seja, o valor da variável não pode ser alterado após sua inicialização.
- **var:** Era a forma tradicional de declarar variáveis, mas seu uso é menos recomendado devido a algumas peculiaridades de escopo.

![Captura de tela 2024-08-02 100745](https://github.com/user-attachments/assets/d44fac6c-23cb-4502-93b0-00f309cdf584)

### Tipos de Dados em JavaScript
JavaScript é uma linguagem de tipagem dinâmica, o que significa que você não precisa declarar explicitamente o tipo de uma variável. O tipo é inferido automaticamente pelo interpretador.

### Principais tipos de dados:

- **Number:** Representa números, tanto inteiros quanto decimais.
- **String:** Representa texto, envolvido em aspas simples ou duplas.
- **Boolean:** Representa valores lógicos, true (verdadeiro) ou false (falso).
- **null:** Representa a ausência intencional de um valor.
- **undefined:** Representa uma variável que foi declarada, mas ainda não recebeu um valor.
- **Object:** Representa uma coleção de pares chave-valor, onde as chaves são strings e os valores podem ser de qualquer tipo.
- **Array:** Uma lista ordenada de valores, onde cada valor pode ser de qualquer tipo.
- 
![Captura de tela 2024-08-02 095959](https://github.com/user-attachments/assets/736ba7e0-5d68-453b-bc87-f59ac6b07ac5)

### Funções em JavaScript

Funções são blocos de código reutilizáveis que executam uma tarefa específica. Elas recebem um nome e podem receber argumentos (entradas) e retornar um valor (saída).

**Como são criadas?**

Existem duas formas principais de criar funções em JavaScript:

**Declaração de função:**

![Captura de tela 2024-08-02 100448](https://github.com/user-attachments/assets/ce0c65f1-0747-48cd-9f43-5fcf60a8da8f)

**Expressão de função:**

![Captura de tela 2024-08-02 100527](https://github.com/user-attachments/assets/88d31c7d-0332-468f-9147-69bd721e3030)

**Exemplo de uso:**

![Captura de tela 2024-08-02 101238](https://github.com/user-attachments/assets/82531e77-beed-46b3-8fda-d633a3703551)

### Características importantes das funções:

- **Argumentos:** Valores que são passados para a função quando ela é chamada.
- **Retorno:** O valor que a função retorna quando é executada.
- **Escopo:** O conjunto de variáveis e funções que estão disponíveis dentro de uma função.

As funções são um conceito fundamental em programação e são amplamente utilizadas em JavaScript para modularizar o código e criar aplicações mais complexas.

## JavaScript no Navegador 

O *JavaScript* é a linguagem que transforma páginas web estáticas em experiências dinâmicas e interativas. Ele faz isso interagindo diretamente com o DOM (Document Object Model), que é uma representação em forma de árvore de um documento HTML.

### O HTML: A Estrutura
- **O esqueleto:** O HTML define a estrutura básica de uma página web, como títulos, parágrafos, listas, tabelas, etc. Ele cria os elementos que o JavaScript irá manipular.

### O CSS: A Apresentação
- **A maquiagem:** O CSS estiliza a página, definindo cores, fontes, layout e outros aspectos visuais. Ele determina como os elementos HTML devem ser apresentados na tela.

### O JavaScript: A Interatividade
- **A alma:** O JavaScript é a linguagem que "dá vida" aos elementos HTML e CSS. Ele permite que você:
- **Selecione elementos:** Encontre elementos específicos no DOM usando métodos como *getElementById()*, *querySelector()*, etc.
- **Modifique conteúdo:** Altere o texto, HTML ou atributos de um elemento.
- **Aplique estilos:** Modifique as propriedades CSS de um elemento dinamicamente.
- **Crie novos elementos:** Adicione novos elementos ao DOM.
- **Remova elementos:** Retire elementos do DOM.
- **Gerencie eventos:** Responda a ações do usuário, como cliques, movimentos do mouse, etc.

## O que é o DOM?
O *DOM* é uma representação em forma de árvore de um documento HTML. Cada elemento HTML, como *<div//>, <p//>, <button//>*, etc., é um objeto no DOM. Esses objetos possuem propriedades e métodos que permitem manipulá-los com JavaScript.

**Por exemplo:**

- **Propriedades:** *textContent, innerHTML, style, className*, etc.
- **Métodos:** *appendChild(), removeChild(), createElement(), getElementById()*, etc.

**Como o JavaScript Interage com o DOM?**

- **Selecionando elementos:** O JavaScript pode selecionar elementos HTML específicos usando métodos como getElementById(), querySelector(), querySelectorAll(), etc.
- **Manipulando conteúdo:** Uma vez selecionado, você pode modificar o conteúdo do elemento usando as propriedades textContent ou innerHTML.
- **Alterando estilos:** O JavaScript pode alterar os estilos CSS de um elemento acessando a propriedade style e modificando as propriedades CSS diretamente.
- **Criando novos elementos:** Você pode criar novos elementos HTML usando o método createElement() e, em seguida, adicioná-los à árvore DOM.
- **Adicionando e removendo elementos:** O JavaScript pode adicionar ou remover elementos da árvore DOM usando os métodos appendChild(), removeChild(), etc.
- **Gerenciando eventos:** O JavaScript pode adicionar ouvintes de eventos a elementos, permitindo que você execute código quando um evento ocorre (como um clique, um mouseover, etc.).

**Exemplo Prático:**

![Captura de tela 2024-08-02 102850](https://github.com/user-attachments/assets/07719f91-9339-48aa-9270-1f638c8e5277)


## As principais ferramentas e ambientes utilizados para desenvolvimento em JavaScript são:

**Editores de Código:**

- **Visual Studio Code:** O mais popular, gratuito e altamente personalizável, com diversas extensões.
- **Sublime Text:** Leve e rápido, com foco em personalização.
- **Atom:** Criado pelo GitHub, com interface amigável e customizável.
- **WebStorm:** IDE completo e poderoso, especialmente para JavaScript e tecnologias web.

**Ambientes de Desenvolvimento Integrados (IDEs):**

- **WebStorm:** Já mencionado, oferece um ambiente completo para desenvolvimento web.
- **Visual Studio:** IDE da Microsoft, com suporte a diversas linguagens, incluindo JavaScript.
- **Eclipse:** IDE altamente personalizável, com plugins para desenvolvimento web.

**Navegadores:**

- **Consoles:** Para executar código, inspecionar o DOM e depurar.
- **Ferramentas de desenvolvedor:** Para analisar o desempenho, simular dispositivos e outras funcionalidades.

**Outras Ferramentas:**

- **npm:** Gerenciador de pacotes para instalar bibliotecas e frameworks.
- **Webpack:** Empacotador de módulos para otimizar o código.
- **Babel:** Transpilador para converter código JavaScript moderno para versões mais antigas.
- **Linters:** Ferramentas para analisar o código e identificar erros.

## Recursos para Aprender JavaScript

#### Plataformas de cursos online
- Coursera, edX, Udemy, Platzi, Alura: Oferecem cursos completos, desde o básico até tópicos avançados, com diferentes formatos e preços.

#### Documentação oficial
- A documentação oficial do Mozilla Developer Network (MDN Web Docs) é uma referência completa e confiável para JavaScript, HTML e CSS.

#### Canais no YouTube
- Canais como Curso em Vídeo, DevMedia e The Net Ninja possuem diversos tutoriais e cursos gratuitos.

#### Livros
- Livros clássicos e bem avaliados incluem Eloquent JavaScript, JavaScript: The Good Parts e a série You Don't Know JS.

#### Plataformas interativas
- Codecademy, freeCodeCamp e Exercism oferecem cursos e exercícios práticos.

#### Comunidades e fóruns
- Stack Overflow e Reddit são ótimos lugares para tirar dúvidas e discutir com outros desenvolvedores.

#### Dicas para o seu aprendizado:

- Pratique regularmente: A prática leva à perfeição.
- Comece pelos fundamentos: Entenda os conceitos básicos antes de avançar.
- Construa projetos: Aplique seus conhecimentos em projetos reais.
- Participe de comunidades: Interaja com outros desenvolvedores.
- Use ferramentas de desenvolvimento: Utilize editores de código como o Visual Studio Code.
