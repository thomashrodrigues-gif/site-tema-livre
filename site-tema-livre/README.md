# Site Bossa Nova Brasil

* **Tema Escolhido:** A História e Evolução da Bossa Nova
* **Estudante:** Nome do Estudante
* **Turma:** DS25 M1
* **Unidade Curricular:** Programação de Aplicativos
* **Docente:** Ewerton de Oliveira Cercal

## Descrição do Projeto
O projeto consiste em um site estruturado estritamente em HTML semântico, apresentando a origem, os artistas marcantes e a discografia fundamental da Bossa Nova. O site conta com formulários funcionais de cadastro e contato, tabelas explicativas e navegação acessível.

## Como Abrir o Projeto
1. Clone este repositório para o seu computador local.
2. Abra a pasta raiz do projeto.
3. Clique duas vezes em qualquer arquivo `.html` (ex: `index.html`) para abri-lo diretamente em seu navegador web.

## Estrutura de Páginas
* **`index.html`**: Página inicial que apresenta o tema, introduz os pilares do gênero e lista álbuns essenciais.
* **`sobre.html`**: Apresentação detalhada com sumário ancorado, artigos históricos, notas e um glossário com termos musicais.
* **`dados.html`**: Apresentação da discografia fundamental em formato de tabela acessível com totalizadores.
* **`cadastro.html`**: Formulário de inscrição para o Clube do Vinil, com campos validados nativamente.
* **`contato.html`**: Informações de atendimento da associação fictícia e formulário de mensagens.

## Acessibilidade e Testes de Teclado
* Link "Pular para o conteúdo" em todas as páginas como primeiro elemento navegável do `<body>`.
* Atributo `aria-current="page"` no menu principal indicando a página ativa.
* Estrutura hierárquica clara de títulos (`<h1>` até `<h3>`) sem saltos de nível.
* Uso sistemático do atributo `alt` em imagens informativas e `alt=""` para imagem decorativa.
* **Resultado do Teste de Teclado:** Toda a navegação foi testada exclusivamente com a tecla `Tab`, `Shift + Tab` e `Enter`. Todos os links, campos de formulário e botões receberam foco visível e funcional em ordem lógica, permitindo o preenchimento e navegação sem uso do mouse.

## Fontes e Licenças
* **Pesquisa de Conteúdo:** Wikipédia (Verbete Bossa Nova) e IMMB (Instituto Memória Musical Brasileira).
* **Imagens (`/img`):**
  * `violao.jpg`: Unsplash (Licença Livre Unsplash).
  * `partitura.jpg`: Unsplash (Licença Livre Unsplash).
  * `decorativo.jpg`: Unsplash (Licença Livre Unsplash).

## Decisões Semânticas de Arquitetura
* Utilizou-se `<section>` para dividir temas principais em cada documento.
* Os blocos de conteúdo textual autônomo na página `sobre.html` foram marcados com `<article>`.
* A seção de curiosidades rápidas foi marcada com `<aside>` por conter dados periféricos ao texto central.