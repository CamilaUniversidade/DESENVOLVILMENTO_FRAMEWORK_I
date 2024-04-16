<h1 align="center"> :milky_way: DESENVOLVILMENTO DE FRAMEWORK I</h1>
<p align="center"><b>Repositório dedicado aos conteúdos de Desenvolvimento de Framework I</b></p>

<h2>Conteúdo</h2>
<ul>
  <li><a href="#1">Introdução</a></li>
  <li><a href="#2">GitHub, Git e VSCode</a></li>
  <li><a href="#3">Clean Code</a></li>
  <li><a href="#4">SOLID</a></li>
  <li><a href="#5">HTML</a></li>
  <li><a href="#6">CSS</a></li>
</ul>

<h2 id="1">:pencil: Introdução</h2>
<p>
  Um <b>framework</b> é uma estrutura ou conjunto de ferramentas que fornece funcionalidades para facilitar o desenvolvimento de software. Inclui uma variedade de tópicos, como:
  <ul>
    <li><b>Conceitos</b> - fundamentais por trás dos frameworks como arquitetura, componentes e princípios do design.</li>
    <li><b>Padrões de Projeto</b> - padrões comuns como MVC (Model-View-Controller), Clean Code, Factory e Observer.</li>
    <li><b>Desenvolvimento de APIs</b> - design e implementação de forma eficaz e como projetar endpoints.</li>
    <li><b>Gerenciamento de Dependências</b> - integração de bibliotecas de terceiros, resolução de conflitos e práticas para estabilidade.</li>
    <li><b>Testes e Documentação</b> - garantia de qualidade com testes unitários, de integração e de aceitação, além da documentação clara.</li>
    <li><b>Aspectos de Desempenho e Segurança</b> - técnicas de otimização e garantia de segurança contra vulnerabilidade.</li>
  </ul>
</p>

<h2 id="2">:wrench: GitHub, Git e VSCode</h2>
<p>
  <b>Git</b> é um sistema de controle de versão distribuído utilizado para rastrear mudanças no código fonte. Ele permite que os desenvolvedores trabalhem em projetos colaborativos, mesclando alterações e revertendo para versões anteriores. O Git trabalha junto com o <b>GitHub</b>, uma plataforma de hospedagem de código fonte. Ele oferece recursos adicionais como rastreamento de issues (problemas), pull requests, wiki e integração contínua. 
</p>

<p>
  Um <b>repositório</b> engloba toda a coleção de arquivos e pastas associados a um projeto, junto com o histórico de arquivos, também denominados <b>commits</b>. Os commits podem ser organizados em várias linhas de desenvolvimento chamadas <b>branches</b>. Um repositório Git também permite a interação com o histórico, clonagem de repositório, merge e comparação entre versões, através de comandos no Git Bash (terminal do Git).
</p>

<h3>Comandos Básicos no Git Bash</h3>
<p>
  <ul>
    <li><code> git init </code> inicializar um novo repositório Git e acompanhar um diretório existente.</li>
    <li><code> git clone </code> criar uma cópia local de um projeto que já existe remotamente.</li>
    <li><code> git add </code> preparar as alterações para incluí-las no histórico do projeto.</li>
    <li><code> git commit </code> salvar as alterações e conclui o processo de controle de alterações.</li>
    <li><code> git status </code> mostrar o status das arquivos como adicionados, modificados ou excluídos.</li>
    <li><code> git branch </code> mostrar as branches existentes no repositório.</li>
    <li><code> git checkout -b </code> criar e mudar para uma nova branch.</li>
    <li><code> git merge </code> mesclar as alterações feitas em dois branches distintos.</li>
    <li><code> git pull </code> atualizar a branch local com atualizações do equivalente remoto.</li>
    <li><code> git push </code> atualizar o repositório remoto com os commits feito localmente.</li>
    <li><code> git log </code> mostrar as commits e versões do repositório.</li>
  </ul>
</p>

<p>
  <b>VSCode</b>, ou Visual Studio Code, é um editor de código-fonte desenvolvido pela Microsoft. Ele é uma ferramenta que suporta várias linguagens de programação e oferece extensões que melhoram suas funcionalidades. Possui recursos como depuração integrada, controle de versão Git, terminal integrado e realce de sintaxe. 
</p>
<p>
  Para configurar VSCode como editor padrão para o Git, basta rodar o comando <code>git config --global core.editor "code-wait"</code>. Também há como definir o VSCode como editor padrão durante a instalação do Git, para usar basta rodar o comando <code>code .</code> dentro do repositório que deseja abrir e editar.
</p>

<h2 id="3">:dash: Clean Code</h2>
<p>
  <b>Clean Code</b> é o conceito de escrever códigos de forma lara, legível e de fácil compreensão. Há alguns pontos-chave no Clena Code, como: 
  <ul>
    <li><b>Legibilidade:</b> escolha de palavras claras e descritivas para variáveis, funções e classes.</li>
    <li><b>Simplicidade:</b> código simples e direto ao ponto, reduzindo a probabilidade a erros.</li>
    <li><b>Convenções de Estilo:</b> seguir formatação de código, espaçamento e padrões de nomeclatura.</li>
    <li><b>Refatoração:</b> revisar e melhorar o código continuamente, eliminando duplicação, simplificando estruturas e mantendo atualizado.</li>
  </ul>
  <b>Robert C. Martin</b> publicou, em 2008, o livro <b>Clean Code</b>, um estudo dos princípios e práticas que tornam o código claro e simples. O livro aborda temas como a nomenclatura significativa, funções e métodos, comentários e documentação, além da formatação e estilo, tudo com o objetivo de transformar o código em um projeto de software de sucesso.
</p>

<h2 id="4">SOLID</h2>
<p>
  <b>Princípios SOLID</b>, um conjunto de diretrizes para escrever código limpo, modular e de fácil manutenção.
  <ul>
    <li>
      <b>S</b>ingle responsibility principle - Princípio da Responsabilidade Única.
      <ul><li>Cada classe deve ter apenas uma responsabilidade, facilitando a manutenção, reutilização e testabilidade do código.</li></ul>
    </li>
  </ul>
  <ul>  
    <li>
      <b>O</b>open/closed principle - Princípio do Aberto/Fechado
      <ul><li>As entidades de software devem estar abertas para extensão, mas fechadas para modificação, ou seja, novos recursos podem ser adicionados sem alterar o código.</li></ul>
    </li>
  </ul>
  <ul>
    <li>
      <b>L</b>iskov substitution principle - Princípio da Substituição de Liskov
      <ul><li>Para garantir o uso correto da herança, as classes derivadas devem ser substituíveis por suas classes base sem afetar a integridade do sistema.</li></ul>
    </li>
  </ul>
  <ul>
    <li>
      <b>I</b>nterface segregation principle - Princípio da Segregação de Interfaces
      <ul><li>As interfaces devem ser específicas para os clientes que utilizam.</li></ul>
    </li>
  </ul>
  <ul>
    <li>
      <b>D</b>ependenvy inversion principle - Princípio da Inversão de Dependência
      <ul><li>Os módulos de alto nível não devem depender de módulos de baixo nível, ambos devem depender de abstrações, tornando o código mais flexível e fácil de testar.</li></ul>
    </li>
  </ul>
</p>

<h2 id="5">:speech_balloon: HTML</h2>
<p>
  <b>HTML</b> é uma linguagem de marcação padrão para documentos projetados para exibição em um navegador da web. <br>Um documento HTML tem uma <b>estrutura básica:</b>
</p>

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Título da página</title>
    </head>
    <body>
        Conteúdo da página
    </body>
</html>
```

<p>Para montar uma página, há tags de <b>Estrutura</b>, sendo elas: </p>
<ul>
  <li><code> < header > </code> é o cabeçalho de uma página ou de uma seção dentro da página. Costuma conter logotipo, título, barra de navegação e links.</li>
  <li><code> < nav > </code> define um conjunto de links de navegação. Útil para acessibilidade, sumário e afins.</li>
  <li><code> < footer > </code> o rodapé da página. Costuma conter informações do autor, direitos autorais, termos de uso, política de privacidade e informações de contato.</li>
  <li><code> < article > </code> usada para encapsular um conteúdo autônomo. Como postagens de blogs, notícias e comentários.</li>  
  <li><code> < section > </code> define uma sessão em uma página. Geralmente agrupa conteúdos temáticos, de forma identificável e em grupo com outras tags.</li>
  <li><code> < aside > </code> representa uma seção de um conteúdo que costuma tangenciar de outros, como barras laterais.</li>  
  <li><code> < form > </code> para criar um formulário de entrada do usuário, com atributos como <em>action</em> e <em>method</em>.</li>
</ul>

<p>Além das estruturas, há as tags de <b>Componentes</b>, sendo elas:</p>
<ul>
  <li><code> < h1 / h2 / h3 / h4 / h5 / h6 > </code> para os títulos, do nível 1 ao 6.</li>
  <li><code> < p > </code> para parágrafos de texto.</li>
  <li><code> < a > </code> para inserir links, através do <em>href</em>.</li>
  <li><code> < img > </code> para inserir imagens, através do <em>src</em>, e com a opção de legenda alternativa, com <em>alt</em>.</li>
  <li><code> < video > </code> para inserir vídeos, através do <em>src</em>, e um atributo de <em>controls</em>.</li>
  <li><code> < audio > </code> para inserir áudios, através do <em>src</em>, e atributos <em>controls</em>, <em>autoplay</em>, <em>loop</em> e <em>muted</em>.</li>
  <li><code> < ul > </code> e <code> < li > </code> para listas não ordenadas, sendo <em>li</em> um item da lista.</li>
  <li><code> < ol > </code> e <code> < li > </code> para listas ordenadas, sendo <em>li</em> um item da lista, e o atributo <em>type</em>, para definir 1, A, a, I, i.</li>
  <li><code> < table > </code> para inserir tabelas em uma página.</li>
  <li><code> < tr > </code> define as linhas da tabela.</li>
  <li><code> < th > </code> define uma célula de cabeçalho da tabela.</li>
  <li><code> < td > </code> define uma célula da tábela.</li>
  <li><code> < div > </code> para as divisões de uma página, para fins de estilo e estrutura.</li>
  <li><code> < span > </code> para estilizar uma parte de um texto.</li>
  <li><code> < strong > </code> ou <code> < b > </code> para definir o texto como negrito.</li>
  <li><code> < em > </code> para definir o texto como itálico.</li>
  <li><code> < code > </code> para inserir um bloco de código.</li>
  <li><code> < br > </code> para quebra de linha.</li>
  <li><code> < hr > </code> para quebra de linha com uma divisão horizontal.</li>
  <li><code> < iframe > </code> para incorporar outro documento HTML, através do <em>src</em>.</li>
  <li><code> < input > </code> para criar campos de entrada de dados interativos, com atributos <em>type</em> de e-mail, name, value, id, number.</li>
  <li><code> < button > </code> para inserir botões clicáveis em uma página.</li>
  <li><code> < select > </code> e <code> < option > </code> para inserir listas suspensas, sendo <em>options</em> as opções da lista.</li>
  <li><code> < datalist > </code> e <code> < option > </code> para inserir listas de sugestões, sendo <em>options</em> as opções da lista.</li>
  <li><code> < textarea > </code> para inserir uma área de texto, com <em>rows</em> sendo as linhas, <em>cols</em> as colunas, <em>name</em> para o nome da área de texto.</li>
  <li><code> < label > </code> para fornecer um rótulo a elementos como <em>input</em>, <em>meter</em>, <em>textarea</em>.</li>
</ul>

<h2 id="6">CSS</h2>
<p>
  CSS, ou <b>Cascading Style Sheets</b>, é uma linguagem de estilo usada para descrever a aparência de um documento escrito em HTML ou XML. <b>Sass, Less e Stylus</b> são alguns pré-processadores CSS, são ferramentas que permitem escrever CSS de maneira mais eficiente e com recursos adicionais. Há algumas configurações principais que o CSS permite fazer, sendo:
</p>
<ul>
  <li><b>Layout</b><br></li>
  
  ```css
  div {
      margin: 0 auto;
      width: 50%;
  }
  ```

  <li><b>Cores e Fundos</b></li>

  ```css
  body {
      background-color: #f0f0f0;
      color: #333;
  }
  ```

  <li><b>Tipografia</b></li>

  ```css
  p {
      font-family: 'Roboto', sans-serif;
      font-size: 1em;
      line-height: 1.5;
  }
  ```

  <li><b>Animações e Transições</b></li>

  ```css
  button:hover {
      background-color: #ddd;
      transition: background-color 0.3s ease;
  }
  ```

  <li><b>Seletores Avançados</b></li>

  ```css
  ul li:nth-child(even) {
      background-color: lightgray;
  }
  ```
</ul>
