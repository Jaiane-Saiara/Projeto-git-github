# Princípios de Desenvolvimento de Jogos

# Introdução

---

## **Bootcamps Dio**

**Organização**

Bootcamp > intensivo

- Matriz de eisenhower
- Cronograma (DIO)
- Pomodoro

**Materiais**

Rooms - [https://www.dio.me/articles/rooms](https://www.dio.me/articles/rooms)

Artigos - [https://www.dio.me/articles](https://www.dio.me/articles)

Sites - [https://stackoverflow.com/](https://stackoverflow.com/)

**Metodologia**

DIO (cursos + desafios de código + desafios de projeto + mentorias + certificados)

LEARN - Lógica, Especialista, Aprendizado, Reconhecimento e notoriedade.

HERO - humanidades, experiências, rooms, oportunidade.

ACT - aquisição, consolidação, transição

---

## Mercado e carreira em desenvolvimento de jogos

**Indústria de jogos**

Principais empresas de jogos: ABRA games

- Unit /C#
- Unreal /C++
- Godot /GDScript
- libGDX /Java

**Plataforma e tipos mais comuns**

- Entretenimento/ Educacional
- Mobile

**Iniciação da carreira**

- **Estudos**
- **Portfólio ( GitHub, art station, itch.io, site próprio e notion)**
- Pensa no objetivo (longos e curtos)
- Plano de aprendizado (menos de cinco anos) (motivação, processo e objetivos
- Desenvolver protótipos e projetos
- Networking

**Carreiras e cargos**

- **Programação ( gameplay, AI, Network, Ferramentas ex. unit, GFX/Shareds)**
- Arte gráfica (2d e 3d, animação, arte conceitual, UI/UX, tech art)
- Game Design ( prototipagem e idealização, arquitetura dos sistemas, balanceamento, UX e level design)
- Audio design (efeitos e trilha sonora, programação de audio)
- Narrativa
- Tester (QA)
- Produção
- Marketing

**Ferramentas** - The gamer inside brasil, ABRA GAMES

---

## Introdução ao desenvolvimento e criação de jogos

<aside>
<img src="https://www.notion.so/icons/circle-dashed_gray.svg" alt="https://www.notion.so/icons/circle-dashed_gray.svg" width="40px" /> **Etapas de desenvolvimento de jogos**

1. Idealização
2. Protótipo
3. Fatia vertical - validação dos itens anteriores
4. Início de produção - início da versão definitiva
5. Alpha(feature complete) - "esqueleto do jogo"
6. Beta(content complete) -
7. Versão final
8. Lançamento
</aside>

**Criação de jogos (Fases)**

- Conceito → qual será o tema do jogo, a história, quem serão as personagens e como será a estética
- Design → aqui, além dos aspectos visuais e sonoros, é preciso detalhar como será a mecânica do jogo, as regras e como se joga.
- Programação → nessa fase o algoritmo que descreve o passo a passo do jogo é codificado para alguma linguagem de programação e assim os computadores, celulares e consoles podem fazer a leitura para que possamos jogar.

<aside>
<img src="https://www.notion.so/icons/circle-dashed_gray.svg" alt="https://www.notion.so/icons/circle-dashed_gray.svg" width="40px" /> **A tétrade elementar dos jogos**

- Estética (identidade visual)
- Mecânica (Pens. computacional)
- História
- Tecnologia
</aside>

<aside>
<img src="https://www.notion.so/icons/circle-dashed_gray.svg" alt="https://www.notion.so/icons/circle-dashed_gray.svg" width="40px" /> **Publicação**

- Mobile (Play Store e App store)
- PC (Steam, epic games, **itch.io**)
- Web ( Kongregate, GameJolt)
- Consoles (Xbox, Switch)
</aside>

**Elementos básicos(Mecânica)**

Objetivo / Interação / obstáculos / regras / níveis / recompensa / emblemas

**Exemplo: Xadrez**

- Estética → têm aspectos visuais simples e cada peça remete à uma personagem.
- Mecânica → há regras para posicionar as peças e movimentá-las.
- Narrativa → não há uma história explícita sendo contada, mas o nome de cada peça faz referência aos reinos do período medieval.
- Tecnologia → o jogo é formado por um tabuleiro e 32 peças.

*Direitos autorais   *Inteligência artificial

---

## Versionamento de código com Git e GitHub

- **Conceitos git e github**
    - Downstream - é tudo que você pega do *git: clonar um repositório, fazer um pull.*
    - Upstream - é tudo que você insere no ***git***: criar um repositório no ***git***, fazer um commit, fazer um push.
    - Branch - Ramificação, ou seja um repositório paralelo.
    - Commit
    
- **Versionamento de código** - é uma maneira organizada de administrar mudanças no código, criando versões.
- **Sistema de controle de versões -** Registra o histórico de atualizações de um arquivo, gerencia quais foram as atualizações, organiza, controla e assegura
    
    **VCS Centralizado (CVCS) -** O servidor central contém todos os arquivos responsáveis pelo controle, é muito propício a perda de dados. Ex. CVS, Subversion
    
    **VCS Distribuído (DVCS) -** O repositório é duplicado localmente .Ex. Git, Mercurial
    

**Git (DVCS) com branching(ramificações) e merging (fusões) eficientes**

Servidor < banco de versões central

Repositório individual < banco de versões remoto

- Git pull ( puxa as alterações do repositório remoto para o local (busca e mescla)
- Credential.helper ( cache or store)

***Github (hospedagem de código com controle de versão com git)**

- **Configurações do Git:**
    - Config file location
        
        `--global              use global config file`
        
        `--system              use system config file`
        
        `--local               use repository config file`
        
        `--worktree            use per-worktree config file`
        
        `-f, --file <file>     use given config file`
        
        `--blob <blob-id>      read config from given blob object`
        
    - Action
        
        `--get                 get value: name [value-pattern]`
        
        `--get-all             get all values: key [value-pattern]`
        
        `--get-regexp          get values for regexp: name-regex [value-pattern]`
        
        `--get-urlmatch        get value specific for the URL: section[.var] URL`
        
        `--replace-all         replace all matching variables: name value [value-pattern]`
        
        `--add                 add a new variable: name value`
        
        `--unset               remove a variable: name [value-pattern]`
        
        `--unset-all           remove all matches: name [value-pattern]`
        
        `--rename-section      rename section: old-name new-name`
        
        `--remove-section      remove a section: name`
        
        `-l, --list            list all`
        
        `--fixed-value         use string equality when comparing values to 'value-pattern'`
        
        `-e, --edit            open an editor`
        
        `--get-color           find the color configured: slot [default]`
        
        `--get-colorbool       find the color setting: slot [stdout-is-tty]`
        
    - Type
        
        `-t, --type <type>     value is given this type`
        
        `--bool                value is "true" or "false"`
        
        `--int                 value is decimal number`
        
        `--bool-or-int         value is --bool or --int`
        
        `--bool-or-str         value is --bool or string`
        
        `--path                value is a path (file or directory name)`
        
        `--expiry-date         value is an expiry date`
        
    - Other
        
        `-z, --null            terminate values with NUL byte`
        
        `--name-only           show variable names only`
        
        `--includes            respect include directives on lookup`
        
        `--show-origin         show origin of config (file, standard input, blob, command line)`
        
        `--show-scope          show scope of config (worktree, local, global, system, command)`
        
        `--default <value>     with --get, use default value when missing entry`
        
    - Passo a passo
        
         `git config --list`
        
        1. Configurando seu nome de usuário e e-mail (globalmente):
        
         `git config --global user.name "Nome Sobrenome" 
         git config --global user.email seuemail@email.com`
        
        1. Configurando o nome da Branch Padrão:
        
         `git config --global init.defaultBranch main`
        

### ***Autenticação  (***[Autenticação GitHub](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-authentication-to-github))

<aside>
<img src="https://www.notion.so/icons/circle-dashed_gray.svg" alt="https://www.notion.so/icons/circle-dashed_gray.svg" width="40px" /> **p/Token**

1. `git clone + (código de acesso ao token) + senha` 
2. Salvando credencial na máquina:
permanete  `git config —global credential.helper store`
    
    temporário `git config —global credential.helper cache`
    
3. `git config —global show origin credential.helper` Encontrar credencial na máquina

</aside>

<aside>
<img src="https://www.notion.so/icons/circle-dashed_gray.svg" alt="https://www.notion.so/icons/circle-dashed_gray.svg" width="40px" /> **p/ Chave SSH**

Encontrando chaves existentes:  `ls -a ~/.ssh`

Gerar chave ssh: 

1. `ssh-keygen -t ed25519 -C "your_email@example.com"` *gerar arquivo da chave e escolher o algortimo
2. `> Enter a file in which to save the key (/c/Users/YOU/.ssh/id_ALGORITHM):[Press enter]` *local para arquivo da chave  > Inserir senha (passpharse)
3. `eval “$(ssh-agent -s)”` *executar ssh agent
4. `ssh-add ~/.ssh/id_ed25519`*adicionar chave privada >Inserir senha (passpharse)
5. *adicionar chave pública à conta do github
</aside>

### **Repositórios**

**Obter um repositório git**

- Transformando de um diretório local
- Clonando um repositório Git existente
- **Instruções para repositóio GitHub**
    1. Criar um novo repositório na linha de comand
    
    ```markdown
    echo "# DIO-resumos-git-github" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/Jaiane-Saiara/DIO-resumos-git-github.git
    git push -u origin main
    ```
    
    1. Enviar um repositório existente na linha de comando
    
    ```markdown
    git remote add origin https://github.com/Jaiane-Saiara/DIO-resumos-git-github.git
    git branch -M main
    git push -u origin main
    ```
    
    - O segundo comando força a mudança da branch Master para a Main

**Obtendo um repositório**

1. Criar uma pasta para transformar no repositório 

 `git clone “url do repositório”`

 `cd “repositórioclonado”`

1. Inicializar o repositório

 `git init` 

 `cd .git`  para (GIT_DIR!)  /  `cd ..` para main

1. Conectar o repositório remoto ao local

`git remote add origin “url”` - repositório local

`git clone “url” nome-do-repositório-local` - repositório remoto

ou `git clone “url” nome-do-repositório-local --branch "nome" --single branch` - repositório remoto (clonar apenas uma branch)

**Fazendo alterações no repositório**

`mkdir NomeDaPasta` - Criar uma pasta

`echo NomeDaPasta/ > .gitignore` - Ignorar uma pasta

`echo > .gitignore`  - Retornar a visibilidade da pasta

- arquivo **.gitkeep -** Convenção para reconhecer um diretório vazio

`git status`

`touch README.md` - criar arquivo vazio README em marckdown *podendo substituir o nome

`git add README.md` - adicionar o arquivo para a área de preparação

`git add .`   - adicioar todos os arquivos para a área de preparação

`git commit -m”NomeDoCommit”`  - criar um commit para o arquivo

`git log` - exibir commits

**Desfazendo alterações no repositório**

`rm -rf .git`  - remover o diretório .git

`git restore NomeDoArquivo` - restaurar versão anterior do arquivo editado

`git commit --amend -m “NovoNomeDoCommit”` - mudar a mensagem do commit anterior

`git commit --amend`  - abrir o editor

tecla esc + `:q` - fechar editor sem salvar alterações

tecla esc + `:wq` fechar o editor salvando alterações

`git reset --soft CódigoDoCommit` - Adicionar os arquivos posteriores ao commit selecionado á área de preparação

`git reset --mixed CódigoDoCommit` - Adicionar os arquivos anteriores a área de trabalho “untracked files”

`git reset --hard CódigoDoCommit` - Desfazer os arquivos do commit anterior

`git reflog` - Histórico das alterações

**Enviando e baixando aterações com o repositório remoto**

`git remote add origin` + link do repositório remoto

`git push -u origin main`*-u indica set upstream

No GitHub, digitar o atalho `.` no repositório abri o editor online

**Trabalhando com branches**

`echo "#commit-0-branch-main" > commit-0-branch-main.txt`  - criar um commit 

`git add .` - `git commit -m”commit 0”`

`git checkout -b “NomeDaBranch’` - mudar/criar nova branch

`git checkout “NomeDaBranch”` - retornar a branch anterior

`git branch -b` - lista do último commit de cada branches

`git merge NomeDaBranch` - mesclar a branch escolhida com a atual * para “importar” commits

`git branch` - lista de branchs

`git branch -d NomeDaBranch` - excluir a branch

- **Alguns comandos git**
    
    `git fetch` - baixar alterações (origin main) respectivamente repositório e branch
    
    `git merge` - mesclar alterações
    
    `git pull` = git fetch + git merge
    
    `git diff branch1/branch2` - exibir diferença entre as branchs escolhidas
    
    `git stash` - arquivar uma modifição
    
    `git stash list` - listar modificações arquivadas
    
    `git stash pop` - excluir a modificação da lista
    
    `git stash apply` - manter a modificação arquivada da lista
    

- **Materiais**
    
    
    [Material de apoio Git e GitHub - Elidiana Andrade](https://github.com/elidianaandrade/dio-curso-git-github/tree/main/materiais-de-apoio)
    
    [Tech Talk: Linus Torvalds on git](https://www.youtube.com/watch?v=4XpnKHJAok8)
    
    [Book - Pro Git](https://git-scm.com/book/en/v2)
    
    [Guia de Escrita no GitHub (Markdown)](https://docs.github.com/pt/get-started/writing-on-github)
    
    [Sintaxe Básica Markdowm](https://www.markdownguide.org/basic-syntax/)
    
    [Git fluence - AI](https://www.gitfluence.com/)
    
    [Padrões e nomeclaturas no Git](https://github.com/JuniorLima22/padroes-e-nomenclaturas-no-git)
    

---

# **Páginas HTML e CSS**

## Comunicação Cliente x Server

**Clients > Internet > Servidor >** WebSever > Database

**Client side - Front end**

- Velocidade de conexão
- Responsividade
- Navegadores <[https://www.w3schools.com/tags/ref_html_browsersupport.asp](https://www.w3schools.com/tags/ref_html_browsersupport.asp)>
- Aplicação web < Utilizam a internet como intermediador sem a necessidade de instalação >

Requisição http >

- Sistema operacional
- Servidores Web

**Linguagens de programação**

Dita conjunto de instruções para softwares

Server - PHP > JS > C# > Ruby > Java

Client - JS > (Chrome > node js) - V8 program (interpretação)

**Sever side - Back -end**

- Servidor < pode servir uma rede LAN

< Funciona como um computador central

Tipos

- Segurança
- Streaming
- Email
- Arquivos
- Webs

Servidor = Lógica + Física

Servidor Proxy - intermediador do client > internet

Servidor DNS - nome > IP lista (domínio)

- Internet vs intranet
- Hospedagens de sites > contratar um servidor
- Conexão FTP (enviar arquivos) Filizila

---

## Intro HTML - HyperText Markup Language

<aside>
<img src="https://www.notion.so/icons/circle-dashed_purple.svg" alt="https://www.notion.so/icons/circle-dashed_purple.svg" width="40px" /> A Linguagem de Marcação de Hipertexto (HTML) é uma linguagem de computador que compõe a maior parte das páginas da internet e dos aplicativos online. Um hipertexto é um texto usado para fazer referência a outros textos, enquanto uma linguagem de marcação é composta por uma série de marcações que dizem para os servidores da web qual é o estilo e a estrutura de um documento.

</aside>

**Tags -** são instruções que informam ao navegador como formatar o texto.

**Atributos -** palavras especiais usadas dentro da tag  para controlar o comportamento do elemento.

- **Tags básicas**

| https://www.w3schools.com/tags/tag_doctype.asp | Defines the document type |
| --- | --- |
| https://www.w3schools.com/tags/tag_html.asp | Defines an HTML document |
| https://www.w3schools.com/tags/tag_head.asp | Contains metadata/information for the document |
| https://www.w3schools.com/tags/tag_title.asp | Defines a title for the document |
| https://www.w3schools.com/tags/tag_body.asp | Defines the document's body |
| https://www.w3schools.com/tags/tag_hn.asp | Defines HTML headings |
| https://www.w3schools.com/tags/tag_p.asp | Defines a paragraph |
| https://www.w3schools.com/tags/tag_br.asp | Inserts a single line break |
| <blockquote> | Inserts a blockquote |
| <u> | underline |
| <i> | italic |
| <b> <strong> | Bold |
| <ol> <li> | Lista ordenada |
| <ul> <il> | Lista não ordenada |
| <sub> | Defines subscripted text |
| <sup> | Defines superscripted text |
| <font> | change font formatting depending on attribute |

- **Atributos básicos**

**id=”NomeDoId” -** É utilizado para identificar de forma única um elemento naquela página HTML

**src=”Link ou diretório da mídia"**
Comumente utilizado para indicar para a tag qual arquivo ou mídia utilizar.

**href=”Url” -** Para a tag , o atributo href especifica a URL da página para a qual o link vai.

---

**Tags e atributos de links**

1. Link self
2. Link abrir em outra página
3. Link com descrição de balão
4. Link no prórpio site

>>>>

```html
<a href="linkdosite">Textodolink</a>
<a href="linkdosite" target="_blank"> Textodolink</a>
<a href="linkdosite" title="Descriçãodobalão" target="_blank"> Textodolink</a>
<a href="Nomedoarquivo" title="Descriçãodobalão"> Textodolink</a>
```

---

## Formulário HTML

**Tag <form>**

**Atributo - Method**

Manda as informações na url -

`<form name="signup" method="GET">
</form>`

Não manda as informações pela url
`<form name="signup" method="POST">
</form >`

**Atributo - Autocomplete**

Retorna com as informações

`<form name="signup" aucomplete="on">
</form>`

Não retorna com as informações

`<form name="signup" aucomplete="off">
</form>`

---

**Tag <input>**

```html
<html> 
<body>
<form>

<label>Text: </label><input type="text" /><br>
<label>Number: </label><input type="number" min="0" step="5" max="99" /><br>
<label>Range: </label><input type="range" min="0" max="100" value="90" /><br>
<label>Color: </label><input type="color" /><br>
<label>E-mail: </label><input type="email" /><br>
<label>Url: </label><input type="url" /><br>
<label>Date: </label><input type="date" /><br>
<label>Week: </label><input type="week" /><br>
<label>Month: </label><input type="month" /><br>
<label>Checkbox: </label><input type="checkbox" /><br>
<label>Radio: </label><input type="radio" name="aceita" /><br>
<label>Hidden: </label><input type="hidden"/><br>
<label>File: </label><input type="file"/><br>
<label>Search: </label><input type="search"/><br>
<label>Button: </label><input type="submit" value="Enviar" /><br>

</form>
</body>
</html>
```

**Tag <checkbox> e <radio>**

 `method="get"` - envia só o último valor da lista> para considerar todos os valres do checkbox envia -se `name=”nomeescolhido[]”`

`disable` - desativar uma função ainda permitindo visibilidade

**Tag <button>**

```html
<form>
<body>
<form onsubmit="" method="get">
<label>Nome*: </label><input type="text" name="name"><br>
<label>Idade*: </label><input type="number" name="age"><br>
<label>Password*: </label><input type="password" name="password"><br>
<button type="submit">Enviar</button>
</form>
</body>
</html>
```

**Tag <select>**

```html
<body>
<form onsubmit="" method="get">
<label>Nome: </label><input type="text" name="name"><br>
<label>Cargo: </label>
<select name="role">
<option value="">Selecione o cargo</option>
<option selected value="gerente">Gerente</option>
<option value="diretor">Diretor</option>
<option value="presidente">Presidente</option>
</select>
<br>
<label>Assunto: </label><input type="text" name="subject"><br>
<button type="submit">Enviar</button>
</form>
</body>
</html>
```

**Tag <textarea>**

---

## Formatação HTML

**<font>**

```html
<body>
<font color="red" face="Arial, Tahoma">Programe</font> o seu futuro global agora!
</body>
</html>
```

**Tag <div> e <span>**

**div -** cria um bloco genérico para agrupar conteúdos

**span -** Ela é usada para modificar propriedades do texto, ou separar partes do texto

Diferenças - com a única diferença que enquanto a tag span serve ao código a nível de linha, a tag div serve ao código a nível de bloco

**Tag <fieldsets>** -agrupa elementos, dentro de um formulário web.
**Tag <embeds>** - incorpora conteúdo de terceiros no seu próprio blog ou sit**e
Tag <iframes>**

**Diferença -** o formato iframe é um código mais limpo e permite carregar websites inteiros, já o formato embed é o formato tradicional utilizado e aceito na maioria de sites e blogs e carrega apenas mídias.

```html
<body>
<h1>Embeds</h1>
<embed src="videoescolhido" width="400" height="250">

<h1>Alternativa com tag video </h1>
<video width="400" height="250">
<source src="trailer.mp4">
</video>

<h1>Iframe do site DIO </h1>
<video width="400" height="250">
<source src="trailer.mp4">
</video>

</body>
```

---

## Intro CSS - Cascading Style Sheets

<aside>
<img src="https://www.notion.so/icons/circle-dashed_purple.svg" alt="https://www.notion.so/icons/circle-dashed_purple.svg" width="40px" /> **CSS** é usado para estilizar elementos escritos em uma linguagem de marcação como **HTML**. O CSS separa o conteúdo da representação visual do site.

</aside>

Estrutura > Propriedade: valor

**Formas de declarar**

- CSS Inline *não muito utilizada - estilizar o código inline com a tag style
- CSS Interno - O CSS interno adiciona a tags <style> na seção <head> do seu documento HTML para padronização.
- **CSS Exetrno *mais utilizado - os códigos CSS ficam em um documento externo ao documento HTML sendo referenciada por um link**

```html
<link href="estilos/estilo.css" rel="stylesheet" />
```

### **Anatomia de um conjunto de regras CSS**

<aside>
<img src="https://www.notion.so/icons/circle-dashed_gray.svg" alt="https://www.notion.so/icons/circle-dashed_gray.svg" width="40px" /> **Partes da sintaxe:**

- Cada linha de comando deve ser envolvida em chaves (`{}`).
- Dentro de cada declaração, você deve usar dois pontos (`:`) para separar a propriedade de seus valores.
- Dentro de cada conjunto de regras, você deve usar um ponto e vírgula (`;`) para separar cada declaração da próxima.

Tipo >
Declaração  .
Propriedade >
Valor da propriedade >

***É recomendável que se use, sempre, o ponto-e-vírgula após cada declaração CSS**, pois no caso de futuramente ter que se acrescentar mais declarações na regra CSS não se corra o risco de esquecer eventual ponto-e-vírgula inicialmente omitido.

```css
/* Global values */
inherit;
initial;
revert;
revert-layer;
unset;
```

</aside>

*A técnica reset.css redefine padrões nos navegadores que sofrem alguma alteração

### Seletor

<aside>
<img src="https://www.notion.so/icons/circle-dashed_gray.svg" alt="https://www.notion.so/icons/circle-dashed_gray.svg" width="40px" /> Um seletor CSS é a primeira parte de uma regra CSS. É um padrão de elementos e outros termos que informam ao navegador quais elementos HTML devem ser selecionados para que os valores das propriedades CSS dentro da regra sejam aplicados a eles. O elemento ou elementos selecionados pelo seletor são chamados de assunto do seletor .

</aside>

* Configura um agrupamento de seletores

**Tag -** seleciona todos os elementos dentro da tag.

```css
<p>Esse parágrafo será azul.</p>
```

**Classe -** O seletor de classe seleciona elementos com base na classe CSS que possuem.

Exemp. `.exemplo { font-size: 20px; }`

```css
<p> class="exemplo" Este parágrafo terá tamanho de fonte 20px.</p>
```

**ID -** O seletor de ID é como um foco preciso em um único elemento que possui um ID específico.

Exemp. `#unico { background-color: yellow; }`

```css
<div id="unico"> O fundo deste div será amarelo.</div>
```

**Universal -** O seletor universal * pode afetar todos os elementos da sua página.

Exemp. 

```css
* {  margin: 0;
  padding: 0;
}
```

**Atributo -** O seletor de atributo seleciona elementos baseados nos atributos que eles possuem. Por exemplo, `a[target="_blank"] { color: red; }` irá colorir de vermelho todos os links que abrem em uma nova aba.

```css
<a href="https://www.exemplo.com" target="_blank">Este link será vermelho.</a>
```

---

### Combinadores

**Agrupamento de seletores**

Exemp.

```css
h1,
..special {
  color: blue;
}
```

```css
p, h3, span {
font-family: arial, sans-serif;
font-size: 12 px;
color: #000000;
background-color: #0000FF;
}
h3 { font-size: 16px;}

```

*A primeira regra determina para <h3> tamanho de fonte de 12px e após, vem a segunda regra que determina 16px para aquele tamanho. Pelo efeito cascata vale a segunda regra para o tamanho de fonte de <h3> e as demais propriedades conforme a primeira regra. Não foi preciso escrever a regra completa para <h3> em separado.

```css
p.texto {
font-family: arial, sans-serif;
font-size: 12 px;
color: #000000;
background-color: #0000FF;
```

*Agrupa o requisito para que só os elementos que tenham <p> e a classe “texto” obedeçam

**Combinador descendente** - permite estilizar elementos que são filhos diretos ou descendentes de outro elemento

Exemp. Estilizar um parágrafo dentro do containêr / estilizar uma lista

```css
<div class="container">
<h2>Título</h2>
<p> Parágrafo.</p> 
</div>

.container p {
font-style: italic;
}
```

```css
<ul class="menu">
<li>Item 1</li>
<li>Item 2</li>
</ul>

.menu li {
list-style: square;
}
```

**Combinador filho (>)** - seleciona todos os elementos que são filhos de um elemento especificado.

```css
div > p {
  background-color: yellow;
}
```

**Combinador Irmão (+) -**  é usado para selecionar um elemento que está diretamente após outro elemento específico.

```css
div + p {
  background-color: yellow;
}
```

---

### Dimensionamento e Espaçamento

![Untitled](Princi%CC%81pios%20de%20Desenvolvimento%20de%20Jogos%205ebed5f45258469cb8db08827754d346/Untitled.png)

*as propriedades `height`e `width`não incluem preenchimento, bordas ou margens! Eles definem a altura/largura da área dentro do preenchimento, borda e margem do elemento

As propriedades **height** e **width** podem ter os seguintes valores:>>>

`auto`- Este é o padrão. O navegador calcula a altura e a largura

`length` - Define a altura/largura em px, cm etc.

`%` - Define a altura/largura em porcentagem do bloco que contém

`initial` - Define a altura/largura para seu valor padrão

`inherit` - A altura/largura será herdada de seu valor pai

`max-width` é usada para definir a largura máxima de um elemento.

`min-width` - é usada para definir a largura mínima de um elemento.

`max-heigth` - é usada para definir a altura máxima de um elemento.

`min-heigth` - é usada para definir a altura mínima de um elemento.

Exemp. elemento <div> de 100px por 500 px

```css
div {
  height: 200px;
  width: 50%;
  background-color: powderblue;
}
```

Exemp. Definindo altura máxima

```css
div {
  max-width: 500px;
  height: 100px;
  background-color: powderblue;
}
```

**Margin - define a área de margem nos quatro lados do elemento *pode ter valores neativos**

Propriedades para especificar a margem para cada lado de um elemento:

 `margin-top` 

 `margin-right` 

 `margin-bottom`  

 `margin-left`

As propriedades de margin podem ter os seguintes valores:

**auto** - calcula a margem centralizada automaticamente
**comprimento(lenght)** - especifica uma margem em mededas, como,  px, pt, cm, etc.

**Initial** - assume o valor padrão para o elemento de acordo com o navegador;
**herdar(inherit)**- especifica que a margem deve ser herdada do elemento pai

Exemp. Valores únicos para todas as margens

```css
p {
  margin: 25px;
}
```

Exemp. margem herdada

```css
div {
  border: 1px solid red;
  margin-left: 100px;
}

p.ex1 {
  margin-left: inherit;
}
```

Valores individuais para as margens

```css
p {
  margin: 25px 50px 75px 100px;
}
```

*margem: 25px 50px 75px 100px;
a margem superior é de 25px
a margem direita é 50px
a margem inferior é de 75px
margem esquerda é 100px

Se houver menos que quatro valores, os já determinados vão seguir essa ordem.

Recolher margem -As margens superior e inferior dos elementos às vezes são recolhidas em uma única margem que é igual à maior das duas margens, quando as duas margens colapsam em uma única margem.

Exemp.

```css
h1 {
  margin: 0 0 50px 0;
}

h2 {
  margin: 20px 0 0 0;
}
```

No exemplo o elemento <h1> tem uma margem inferior de 50px e o elemento <h2> tem uma margem superior definida como 20px.

O senso comum parece sugerir que a margem vertical entre o <h1> e o <h2> seria um total de 70px (50px + 20px). Mas devido ao colapso da margem, a margem real acaba sendo 50px.

**Padding - distância interna entre um elemento e a sua borda.**

*os princípios de dimensionamento de padding segue os mesmos princípios de dimensionamento da margin, incluindo propriedades e ordem de medidas individuais

**Box sinzing - é essencialmente uma caixa que envolve cada elemento HTML**

Consiste no conjunto de contnent, margin, padding e border.

Exemp. Demonstração do modelo de caixa:

```css
div {
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}
```

Há a propriedade box sizing que constitui 2 valores:

box sizing: contnent box *é a operação comum somando os valores

box sizing: border box *redmensiona para que o total seja a largura e altura pré-definida

Exemp. 200 x 200 px.>>>

```css
div {
width: 200px; I
height: 200px;
color: white;
margin: 20px;
padding: 20px
}
}
#elemento-02 {
background: purple;
box-sizing: border-box;
```

---

### Cores, Sombra e Opacidade CSS

- Formas de definição:
- Cores pré-definidas - [https://www.w3schools.com/tags/ref_colornames.asp](https://www.w3schools.com/tags/ref_colornames.asp)
- Palavra chave “current color” - cor previamente definida
- Hexadecimal (HEX) -Tons de vermelho, verde e azul (00 a FF) na numeração hexadecimal
- RGB e RGBA - Tons de vermelho, verde e azul (de 0 a 255 ) e/ou transparência (0.0 a 1.0)
- HSL e HSLA - Matiz (0 a 359) , saturação e luminosidade (0 a 100%) e/ou

Transparência (0.0 a 1.0)

```css
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>
```

**Para sombras:**

Prop. Box shadow - [https://box-shadow.dev/](https://box-shadow.dev/)

Ordem de elemenstos - Horizontal offset > Vertical offset > Blur > Spread Radius > Color

Sintaxe: `box-shadow: none|h-offset v-offset blur spread color |inset|initial|inherit;`

```css
#example1 {
  box-shadow: 5px 10px;
}
```

filter: drop shadow - recomendado para imagens png

```css
img {
  width: 150px;
  -webkit-filter: drop-shadow(5px 5px 5px #222);
  filter: drop-shadow(5px 5px 5px #222);
}
```

Opacity 

```css
exemplo {
background-color:white;
border: 5px solid purple;
color: orange;
padding: 20px;
opacity: 0.5;
}
```

---

### Elementos, Background e Overflow

### Background

Propriedades de background do CSS/ exemplso

---

`background-color` 

background-color: lightblue;

---

`background-image` 

background-image: url("paper.gif");

---

`background-repeat` 

background-image: url("gradient_bg.png");
background-repeat: repeat-x;

---

`background-position`

background-position: *value*; 

value (px, position, percentage, intial ou inherit)

background-image: url("img_tree.png");
background-repeat: no-repeat;
background-position: right top;

Position y or x

div {

background-image: url('w3css.gif');

background-repeat: no-repeat;

background-position-y: center;

}

---

`background-origin`

Esta propriedade não tem efeito se [o anexo em segundo plano](https://www.w3schools.com/csSref/pr_background-attachment.php) for "fixo".

A imagem de fundo "paper.gif" começa no canto superior esquerdo da borda de preenchimento e a imagem de fundo "img_tree.gif" começa no canto superior esquerdo do conteúdo:

#example1 {

border: 10px dashed black;

padding: 25px;

background: url(img_tree.gif), url(paper.gif);

background-repeat: no-repeat;

background-origin: content-box, padding-box;

}

---

`background clip` *padding-box, contnent-box or border-box

div {

border: 10px dotted black;

padding: 15px;

background: lightblue;

background-clip: padding-box;

}

---

`background-attachment` *fixed, scroll, local, intial or inherit

background-image: url("img_tree.png");

background-repeat: no-repeat;

background-position: right top;

background-attachment: fixed;

---

`background`(propriedade abreviada)

background: #ffffff url("img_tree.png") no-repeat right top;

ordem:

background-color

background-image

background-repeat

background-attachment

background-position

---

`background-blend-mode` *normal, multiply, screen, overlay, darken, lighten, color-dodge, saturation, color, hue, exclusion, difference, soft-light, hard-light color-burn e/ou luminosity

.container {
display: block;
background-size: 100%;

linear-gradient(purple 0%, red 90%),
linear-gradient(to right, purple 0%, yellow 90%),
url('[https://s3-us-west-2.amazonaws.com/s.cdpn.io/14179/image.jpg](https://s3-us-west-2.amazonaws.com/s.cdpn.io/14179/image.jpg)') 30px,
url('[https://s3-us-west-2.amazonaws.com/s.cdpn.io/14179/image.jpg](https://s3-us-west-2.amazonaws.com/s.cdpn.io/14179/image.jpg)') 20px;
background-blend-mode: screen, difference, lighten;
background-size: 100%;
background-size: cover;
background-repeat: no-repeat;

---

`background-size` *auto, percentage, cover, contain ou length

#example1 {

background: url(mountain.jpg);

background-repeat: no-repeat;

background-size: auto;

}

#example2 {

background: url(mountain.jpg);

background-repeat: no-repeat;

background-size: 300px 100px;

}

---

### Overflow

A `overflow`propriedade especifica se o conteúdo deve ser recortado ou adicionadas barras de rolagem quando o conteúdo de um elemento for muito grande para caber na área especificada.

Possui os seguintes valores:

- `visible` - Padrão. Oconteúdo não é cortado, sendo renderizado fora da caixa do elemento
- `hidden` - O conteúdo será cortado e o restante do conteúdo ficará invisível
- `scroll` - É cortado e uma barra de rolagem é adicionada para ver o resto do conteúdo
- `autoscroll`- Semelhante a scrool mas adiciona barras de rolagem somente quando necessário

*O overflow só funciona para elementos de bloco com altura especificada.

Exemp.

```css
div {
  overflow: auto;
}
```

As propriedades `overflow-x` e `overflow-y` especificam se o excesso de conteúdo deve ser alterado apenas horizontalmente ou verticalmente (ou ambos). Há ainda o `overflow-wrap`, que Especifica se o navegador pode ou não quebrar linhas com palavras longas, caso elas ultrapassem seu contêiner.

---

### Imagem

**fill** - distorce para caber no tamanho definido

**contain** - adapta a imagem porém mantendo a proporção original

**cover** -  redmesiona ao tamanho máximo do conteiner, ultrapassando o espaço do elemento

**none** - manter tamanho original ignorando as dimensões do elemento pai

**scale-down** - escolhe a menor entre as opções anteriores

Object-fit 

Exemp.

```html
<style>
img {
width: 200px;
height: 300px;
border: 5px solid blue;
}
</style>

</head>
<body>
<h1>Propriedade <code>object-fit</code></h1>
<code>object-fit: fill;</code> (padrão)
<img src="linkdaimagem"
</body>
</html>
```

Object positon

Exemp. Imagem com 5px da esquerda e 10% do topo dentro da caixa de conteúdo:

```css
img.a {
  width: 200px;
  height: 400px;
  object-fit: none;
  object-position: 5px 10%;
  border: 5px solid red;
}
```

---

### Borda

<aside>
<img src="https://www.notion.so/icons/circle-dashed_gray.svg" alt="https://www.notion.so/icons/circle-dashed_gray.svg" width="40px" /> **Propriedades**

- border-style
- border-width
- border color
</aside>

### Estilo

A `border-style`propriedade especifica que tipo de borda exibir.

Os seguintes valores são permitidos:

`dotted` - Define uma borda pontilhada

`dashed` - Define uma borda tracejada

`solid` - Define uma borda sólida

`double` - Define uma borda dupla

`groove` - Define uma borda ranhurada 3D.

O efeito depende do valor da cor da borda

`ridge` - Define uma borda 3D estriada.

O efeito depende do valor da cor da borda

`inset` - Define uma borda de inserção 3D.

O efeito depende do valor da cor da borda

`outset` - Define uma borda inicial 3D.

O efeito depende do valor da cor da borda

`none` - Não define borda

`hidden` - Define uma borda oculta

### Tamanho

A propriedade `border-width` especifica a largura das quatro bordas.

A largura pode ser definida como um 

1. thin: borda fina 1px
2. medium: borda média 3px
3. thick: borda grossa 5px
4. length: unidade de medida CSS (px, pt, em, cm, ...)

Valores para borda

1. Superior - top
2. Direita - rigth
3. Inferior - bottom
4. Esquerda - left

*Os valores permitem que adicione valores diferentes para cada lado

Examp.

```css
p.dotted {border-style: dotted;}
p.dashed {border-style: dashed;}
p.solid {border-style: solid;}
p.double {border-style: double;}
p.groove {border-style: groove;}
p.ridge {border-style: ridge;}
p.inset {border-style: inset;}
p.outset {border-style: outset;}
p.none {border-style: none;}
p.hidden {border-style: hidden;}
p.mix {border-style: dotted dashed solid double;}
```

A `border-style`propriedade pode ter de um a quatro valores (para a borda superior, borda direita, borda inferior e borda esquerda).

### Cor

A `border-color` propriedade é usada para definir a cor das quatro bordas,  se não definido será a cor do elemento.

cor pode ser definida por: name, HEX, RGB, HCL ou transparent

Pode ser definida também para cada lado individualmente.

Exemp.

```css
p.one {
  border-style: solid;
  border-color: red green blue yellow;
}
```

 

/* red top, green right, blue bottom and yellow left */

### Border

A `border`propriedade é uma propriedade abreviada para as seguintes propriedades de borda individuais:

- `border-width`
- `border-color`
- `border-style`

Pode-se também definir propriedades especificando um lado da borada. ex. 

**border-left**

Exemp.

```css
p {
  border: 5px red solid ;
}
```

Pode-se também arredondar os cantos com border-radius. ex. **border-radius: 10px;**

Ou propor um arredondamento oval. ex. **border-radius: 30px/10px;**

Utilizando a porcentagem pode-se até formar um quadrado perfeito. ex.  **border-radius: 50%;**

### Border Image

`border-image-source` - Especifica o caminho para a imagem a ser usada como borda
`border-image-slice` - Especifica como fatiar a imagem da borda
`border-image-width` - Especifica as larguras da imagem da borda
`border-image-outset` - Especifica o quanto a área da imagem da borda se estende além da caixa da borda
`border-image-repeat` - Especifica se a imagem da borda deve ser repetida, arredondada ou esticada

---

### Texto

**Text-Transform - usada para especificar letras maiúsculas e minúsculas em um texto.**

`text-transform` (capitalize, uppercase, lowercase, none, full-width, full-size-kana)

**Text-Align - é usada para definir o alinhamento horizontal de um texto.**

Um texto pode ser alinhado como right, left, center, or justified

Exemp.

```css
h1 {
  text-align: center;
}
```

`text-align-last` propriedade especifica como alinhar a última linha de um texto.

Exemp.

```css
p.a {
  text-align-last: right;
}
```

As propriedades `direction`*rtl ou ltr e `unicode-bidi`podem ser usadas para alterar a direção do texto de um elemento

Exemp.

```css
p {
  direction: rtl;
  unicode-bidi: bidi-override;
}
```

A `vertical-align`propriedade define o alinhamento vertical de um elemento.

Exemp.

```css
img.a {
  vertical-align: baseline;
}
```

vertical-align: baseline|*length*|sub|super|top|text-top|middle|bottom|text-bottom|initial|inherit;

**Text-Decoration** 

Propriedades:

`text-decoration-line` (underline, overline, line-through, underline overline, underline line-through)

`text-decoration-color` (RGB, HSL, HEX)

`text-decoration-style` (solid, doule, dotted, dashed, wavy)

`text-decoration-thickness` (auto, from-front, pixels, percentage)

`text-decoration` 

Abreviatura Exemp.

```css
p {
  text-decoration: underline red double 5px;
}
```

**Text-Indent - define o comprimento do espaço vazio (recuo) colocado antes das linhas de texto em um bloco.**

```css
/* <length> values */
text-indent: 3mm;
text-indent: 40px;

/* <percentage> value
   relative to the containing block width */
text-indent: 15%;

/* Keyword values */
text-indent: 5em each-line;
text-indent: 5em hanging;
text-indent: 5em hanging each-line;
```

**letter-spacing** 

```css
/* Keyword value */
letter-spacing: normal;

/* <length> values */
letter-spacing: 0.3em;
letter-spacing: 3px;
letter-spacing: 0.3px;
```

**word-spacing**

```css
/* Keyword value */
word-spacing: normal;

/* <length> values */
word-spacing: 3px;
word-spacing: 0.3em;
```

**line-height** 

```css
/* Keyword value */
line-height: normal;

/* Unitless values: use this number 
multiplied by the 
element's font size */
line-height: 3.5;

/* <length> values */
line-height: 3em;

/* <percentage> values */
line-height: 34%;
```

**white-space**

```css
/* Single keyword values */
white-space: normal;
white-space: nowrap;
white-space: pre;
white-space: pre-wrap;
white-space: pre-line;
white-space: break-spaces;

/* white-space-collapse and 
text-wrap shorthand values */
white-space: collapse balance;
white-space: preserve nowrap;
```

**word break**

```css
/* Keyword values */
word-break: normal;
word-break: break-all;
word-break: keep-all;
word-break: auto-phrase; 
/* experimental */
word-break: break-word; 
/* deprecated */
```

**Word wrap**

```css
/* Keyword values */
word-wrap: normal;
word-wrap: break-word;
```

*A `overflow-wrap`propriedade atua da mesma forma que a propriedade não padrão `word-wrap`. A `word-wrap`propriedade agora é tratada pelos navegadores como um alias da propriedade padrão.

**Writing mode**

```css
/* Keyword values */
writing-mode: horizontal-tb;
writing-mode: vertical-rl;
writing-mode: vertical-lr;
writing-mode: sideways-lr;
writing-mode: sideways-rl;
```

**Text Overflow**

```css
text-overflow: clip;
text-overflow: ellipsis ellipsis;
text-overflow: clip clip
text-overflow: clip ellipsis
text-overflow: ellipsis ellipsis
text-overflow: ellipsis " [..]"
```

---

### Fontes

### Regras CSS

A [regra](https://developer.mozilla.org/en-US/docs/Web/CSS/At-rule) [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) é usada para importar regras de estilo de outras folhas de estilo válidas. Uma regra *deve* ser definida no topo da folha de estilo, antes de qualquer outra regra (exceto [@charset](https://developer.mozilla.org/en-US/docs/Web/CSS/@charset) e [@layer](https://developer.mozilla.org/en-US/docs/Web/CSS/@layer) ) e declarações de estilo, ou será ignorada.

**@font-face - A diretiva @font-face permite importar uma fonte a partir de um arquivo externo e utilizá-la como uma fonte nativa nas páginas HTML.**

```css
@font-face {
  font-family: Barrio;
  src: url(../fonts/Barrio-Regular.ttf)
}

h1 {
  font-family: Barrio;
}
```

Exemp. fonte local

```css
@font-face {
  font-family: [nome];
  src: local([nome da fonte local]), url([caminho]);
}
```

Exemp. importada **(@import-url)**

```css
@import url('https://fonts.googleapis.com/css?family=Open+Sans&display=swap');
* {
font-family: Roboto;
}
```

Exemp. Pode-se também especificar fontes alternativas. Neste exemplo, a cópia local do usuário de "Helvetica Neue Bold" é usada; se o usuário não tiver essa fonte instalada (tanto o nome completo da fonte quanto o nome Postscript são tentados), então a fonte para download chamada "MgOpenModernaBold.ttf" será usada:

```css
@font-face {
  font-family: "MyHelvetica";
  src: local("Helvetica Neue Bold"), local("HelveticaNeue-Bold"),
    url("MgOpenModernaBold.ttf");
  font-weight: bold;
}
```

| Propriedades | Valor | Descrição |
| --- | --- | --- |
| font-family | name | Obrigatório. O nome da fonte |
| src | URL | Obrigatório, Define a url em que se encontra a fonte |
| font-stretch | normal, condensed, ultra-condensed, extra-condensed, semi-condensed, expanded, semi-expanded, extra-expanded, ultra-expanded | Opcional. Define como a fonte deve ser esticada. O valor padrão é "normal” |
| font-style | normal, italic, oblique | Opcional. Define como a fonte deve ser estilizada. O valor padrão é "normal” |
| font-display | auto, block, swap, fallback, optional | Opcional. Determina como uma fonte é exibida com base em se e quando ela foi baixada e está pronta para uso. |
| font-weight | normal, bold, 100, 200, 300, 400, 500, 600, 700, 800, 900, lighter, bolder | Opcional. Define o negrito da fonte. O valor padrão é "normal” |
| unicode-range | unicode-range | Opcional. Define o intervalo de caracteres Unicode suportados pela fonte. O valor padrão é "U+0-10FFFF” |

**Font-variant - permite definir todas as variantes de fonte de uma fonte. (normal ou small-caps)**

Exemp. 

```css
p.small {
  font-variant: small-caps;
}
```

---