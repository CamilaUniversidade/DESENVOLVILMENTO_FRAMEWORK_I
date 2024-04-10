<h1 align="center"> :milky_way: DESENVOLVILMENTO DE FRAMEWORK I</h1>
<p align="center"><b>Repositório dedicado aos conteúdos de Desenvolvimento de Framework I</b></p>

<h2>Conteúdo</h2>
<ul>
  <li><a href="#1">Introdução</a></li>
  <li><a href="#2">GitHub, Git e VSCode</a></li>
  <li><a href="#3">Clean Code</a></li>
  <li><a href="#4">Tags em HTML</a></li>
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

<h2 id="4">:speech_balloon: HTML</h2>
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
</ul>
