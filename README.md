# Template para cursos com JupyterBook  

>Este template é baseado no template preparado por @firasm em https://github.com/firasm//jupyterbook_course_template ([site para ver o template aplicado](https://firasm.github.io/jupyterbook_course_template/about/syllabus.html)).

Este é um repositório  template para tornar super simples para qualquer pessoa criar um site de curso e publicar usando GitHub Pages.
Não precisa configurar nada, são três passos. **Queremos ajuda para terminar de traduzir este template, mandem PRs ou peçam permissão para editar direto**.

## Sobre o site pronto

A cada commit no ramo master do seu repositório o site vai ser gerado novamente, no exemplo inicial a atualização estava levando certa de 70 segundos para acontecer.

## Como usar este template

### 1. Visit this [template repository](https://github.com/firasm/jupyterbook_course_template) with the GH account you want to use and click "Use this template".

![](https://github.com/firasm/bits/blob/master/jb-step1.png)

### 2. Fill in the info for the new repository, make sure it's a public repository and you include all branches (this will make sure the `gh-pages` branch is deployed.

![](https://github.com/firasm/bits/blob/master/jb-step2.png)

### 3. Wait for the GH Action to complete, and then visit your deployed website here: https://firasm.github.io/jupyterbook_course_template. That's it!

![](https://github.com/firasm/bits/blob/master/jb-step3.png)

## Features

1. Support for executing code in a browser using [thebe](https://thebe.readthedocs.io/en/latest/) and [mybinderorg](https://mybinder.org)!

1. Structured book with markdown file stubs aligning with a course structure for a 13 week course. Fully versioned using GitHub, automatically deployed using GH Actions to either GH or your own server. Can also be extended with a testing framework for extra peace of mind.

1. [Examples of how to use IFrames](https://firasm.github.io/jupyterbook_course_template/class/topic1.html#) to embed web content, @phet_sims, @sli.do polls, videos, and other content. 

1. Powerful built-in annotation and commenting features with [hypothes.is](http://hypothes.is) and [utteranc.es](http://utteranc.es). Annotate your syllabus, course readings, and any other content.

1. Add persistent checkboxes so students can track their progress through notebooks, exercises and readings. 

1. Allow students to download pages of the site in PDF, link to the source code on your repo, or open in a mybinder notebook. 

1. The JupyterBook can be embedded into Canvas using the Redirect tool so students never have to leave their LMS.

## Cecklist de edições para você fazer no seu site

There are a few things you need to do to adapt this template for your course.
I might miss a few things, so this list is a work in progress:

1. In the `_config.yml` file:

	- [ ] Set title of the book (exemplo: Physics 111)
	- [ ] Update author (exemplo: Firas Moosvi)
	- [ ] Update logo image (images/logo.png)
	- [ ] Add Google Analytics ID (Optional)
	- [ ] Enable/Disable Hypothes.is (remove the line to remove the hypothes.is integration)
	- [ ] Configure Utteranc.es repository (Choose one of Hypothesis or Utteranc.es)
	- [ ] Adjust `extra_footer` to control License of course materials

1. In the `_toc.yml` file:
	- [ ] Arrange the table of contents to add/remove files
	
1. In the `about` and `class` folders:
	- [ ] Edit the .md and .ipynb files with your course content

## Atribuição e agradecimentos

- Obrigado @firasm pelo template!
- Obrigado a [Tomas Beuzen](https://github.com/TomasBeuzen) pelo GH Actions workflow that deploys JupyterBooks using GH pages.
- Obrigado a todo o [Jupyter Project](https://jupyter.org/about)
- Finally, a big thanks to the [JupyterBook community](https://github.com/executablebooks/jupyter-book/graphs/contributors) for my incessant issues, questions, and PR requests on documentation changes.
