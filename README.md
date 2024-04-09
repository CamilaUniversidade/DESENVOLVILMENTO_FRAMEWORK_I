<h1 align="center"> :milky_way: DESENVOLVILMENTO DE FRAMEWORK I</h1>
<p align="center"><b>Repositório dedicado aos conteúdos de Desenvolvimento de Framework I</b></p>

<h2>Conteúdo</h2>
<ul>
  <li><a href="#1">Introdução</a></li>
  <li><a href="#2">GitHub, Git e VSCode</a></li>
  <li><a href="#3">Clean Code</a></li>
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
    <li><code> git branch </code> mostrar as branches e criar novas.</li>
    <li><code> git merge </code> mesclar as alterações feitas em dois branches distintos.</li>
    <li><code> git pull </code> atualizar a branch local com atualizações do equivalente remoto.</li>
    <li><code> git push </code> atualizar o repositório remoto com os commits feito localmente.</li>
  </ul>
</p>

<p>
  <b>VSCode</b>, ou Visual Studio Code, é um editor de código-fonte desenvolvido pela Microsoft. Ele é uma ferramenta que suporta várias linguagens de programação e oferece extensões que melhoram suas funcionalidades. Possui recursos como depuração integrada, controle de versão Git, terminal integrado e realce de sintaxe. 
</p>
<p>
  Para configurar VSCode como editor padrão para o Git, basta rodar o comando <code>git config --global core.editor "code-wait"</code>. Também há como definir o VSCode como editor padrão durante a instalação do Git, para usar basta rodar o comando <code>code .</code> dentro do repositório que deseja abrir e editar.
</p>
