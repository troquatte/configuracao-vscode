<h1>Meus Plugins e Configurações VSCODE e AMBIENTE</h1>
<p>Gosto de deixar meu ambiente organizado então resolvi deixar tudo organizado aqui no GITHUB.</p>

<h2>Ambiente</h2>
<h3>DEVDOCS</h3>
<p>Programa com a documentação de várias liguagens WEB</p>

<h2>VSCODE</h2>

<h3>Color Highlight</h3>
<p>Esta extensão estiliza as cores css / web encontradas em seu documento.</p>

<h3>Dracula Official</h3>
<p>Thema bacana para VSCODE.</p>

<h3>EditorConfig for VS Code</h3>
<p>Se você trabalha com outros usuários, essa extensão padroniza os códigos com todos os desenvolvedores.</p>

<h3>ESLint</h3>
<p>Padroniza um estilo de código para todo o nosso Código.</p>

<h3>Prettier - Code formatter</h3>
<p>Pacote VS Code para formatar seu JavaScript / TypeScript / CSS usando o Prettier.</p>

<h3>Rocketseat React Native</h3>
<p>Este projeto visa a disponibilização de um conjunto de Snippets ou atalhos para criação de componentes e arquivos de configuração em aplicações React Native.</p>

<h3>Rocketseat ReactJS</h3>
<p>Este projeto visa a disponibilização de um conjunto de Snippets ou atalhos para criação de componentes e arquivos de configuração em aplicações ReactJS.</p>

<h3>vscode-icons</h3>
<p>Icones para arquivos no VSCODE</p>
<code>Use: Shift + Comand + p ( Procure por ) =>icons: Activate VSCode Icons </code>

<h3>nodemon + sucrase -D</h3>
<p>NodeMon reload de uma aplicação node e sucrase muda para nova sintax js</p>
<p>Crie um arquivo chamado nodemon.json e insira o código a baixo.</p>
<code>{
  "execMap": {
    "js": "sucrase-node"
  }
}
</code>

<h3>settings.json</h3>
<p>Nesse arquivo do vscode deixo configurado o json a baixo:</p>
<p>Baixe a fonte fira code</p>
<code>
{
  "workbench.colorTheme": "Dracula",
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
  "editor.fontSize": 18,
  "editor.lineHeight": 24,
  "editor.formatOnSave": true,
  "editor.rulers": [80, 120],
  "editor.tabSize": 2,
  "editor.renderLineHighlight": "gutter",
  "terminal.integrated.fontSize": 14,
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "javascript.updateImportsOnFileMove.enabled": "never",
  "breadcrumbs.enabled": true,
  "editor.parameterHints.enabled": false,
  "prettier.eslintIntegration": true,
  "workbench.iconTheme": "vscode-icons"
}
</code>
