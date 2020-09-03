# Template para cursos com JupyterBook  

>Este template é baseado no template preparado por @firasm em https://github.com/firasm//jupyterbook_course_template ([site para ver o template aplicado](https://firasm.github.io/jupyterbook_course_template/about/syllabus.html)).

Este é um repositório  template para tornar super simples para qualquer pessoa criar um site de curso e publicar usando GitHub Pages.
Não precisa configurar nada, são três passos. 

#### Queremos ajuda para terminar de traduzir este template, mandem PRs ou peçam permissão para editar direto

    TO DO:
    [ ] Rola enxugar o texto  para um formato de curso mais genérico, em vez dessa cara de disciplina de universidade americana.
    [ ] Fazer uns logos e imagens mais genéricos/neutros para o exemplo de curso
    [ ] Publicar um site exemplo do template em PT-BR (não sei ainda qual o melhor jeito de fazer isso para ir atualizando)

## Sobre o site pronto 

A cada commit no ramo master do seu repositório o site vai ser gerado novamente, no exemplo inicial a atualização estava levando cerca de 70 segundos para acontecer.

## Como usar este template

### 1. Visite este repositório [template repository](https://github.com/villares/jupyterbook_course_template) estando logado na conta do GitHub que você quer usar e clique no botão "Use this template".

![](https://github.com/firasm/bits/blob/master/jb-step1.png)

### 2. Preencha as informações do novo repositório, garanta que ele seja um repositório público (*public*) e que sejam incluídos todos os *branches* (isso garante que o branch `gh-pages` será implantado)

![](https://github.com/firasm/bits/blob/master/jb-step2.png)

### 3. Espere que a ação automática *GitHub Action* termine, e então visite o site em: <br><seu nome de usuário>.github.io/<nome do seu repositório>. É isso!

![](https://github.com/firasm/bits/blob/master/jb-step3.png)

## Funcionalidades

1. Permite a execução de código no navegador usando [thebe](https://thebe.readthedocs.io/en/latest/) e [mybinderorg](https://mybinder.org)!

1. Structured book with markdown file stubs aligning with a course structure for a 13 week course. Com controle de versão totalmente no GitHub, automaticamente implantado por meio de GitHub Actions ou no GitHub Pages ou no seu servidor.. Can also be extended with a testing framework for extra peace of mind.

1. [Examples of how to use IFrames](https://firasm.github.io/jupyterbook_course_template/class/topic1.html#) to embed web content, @phet_sims, @sli.do polls, videos, and other content. 

1. Powerful built-in annotation and commenting features with [hypothes.is](http://hypothes.is) and [utteranc.es](http://utteranc.es). Annotate your syllabus, course readings, and any other content.

1. Add persistent checkboxes so students can track their progress through notebooks, exercises and readings. 

1. Allow students to download pages of the site in PDF, link to the source code on your repo, or open in a mybinder notebook. 

1. The JupyterBook can be embedded into Canvas using the Redirect tool so students never have to leave their LMS.

## Cecklist de edições para você fazer no seu site

Tem algumas coisas que você precisa fazer para adaptar este template para o seu curso.
Avise se esquemos de mencionar alguma delas nesta lista (*I might miss a few things, so this list is a work in progress*):

1. No arquivo `_config.yml`:

	- [ ] Defina o título do site (*title*, exemplo: Physics 111)
	- [ ] Atualize a autoria (*author*, exemplo: Allison Parrish)
	- [ ] Atualize a imagem do logo (`images/logo.png`)
	- [ ] Acrescente um Google Analytics ID (Opcional)
	- [ ] Habilite/Desabilite Hypothes.is (remova a linga para remover a integração com [hypothes.is](https://hypothes.is))
	- [ ] Configure um repositório Utteranc.es (Escolha entre Hypothesis ou Utteranc.es)
	- [ ] Ajuste o `extra_footer` para indicar o licenciamento do material.

1. No arquivo `_toc.yml`:
	- [ ] Organize o sumário (*Table Of Contents*) para acrescentar ou remover itens
	
1. Nas pastas `about` e `class`:
	- [ ] Edite os arquivos .md e .ipynb com os conteúdos do seu curso.

## Atribuição e agradecimentos

- Obrigado @firasm pelo template!
- Obrigado a [Tomas Beuzen](https://github.com/TomasBeuzen) pelo GH Actions workflow that deploys JupyterBooks using GH pages.
- Obrigado a todo o [Jupyter Project](https://jupyter.org/about)
- Finally, a big thanks to the [JupyterBook community](https://github.com/executablebooks/jupyter-book/graphs/contributors) for my incessant issues, questions, and PR requests on documentation changes.
