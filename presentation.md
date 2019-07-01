<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->

![](images/invite-logo.png)

O sistema operativo que nos protege

mesmo quando fomos hackeados

---

# Aviso ⚠️

1. O conhecimento que aqui passamos não subsitui treino por profissionais

2. É importante ter a noção que nada é 100% seguro

<!-- o objetivo é apenas dar a conhecer o que existe -->

---

# ✋ perguntas
Quando Quiserem

--- ---

# Contexto

<!-- esta secção introduz o contexto da apresentação: segurança
jornal -->

![](images/bansky-grafitti.jpg)

---

<img src="images/journalism-after-snowden-book.jpg" style="float: left" />

**Vigilância Digital**
- muito barata
- ubíqua

--- ---

# OPSEC

Segurança Operacional

---

# Assets

O que queremos proteger

---

- **Fontes Jornalísticas**
<!-- .element: class="fragment" -->
- documentos de investigações atuais
<!-- .element: class="fragment" -->
- e passadas
<!-- .element: class="fragment" -->

<br></br>

- comunicações sensíveis
<!-- .element: class="fragment" -->
- contas online
<!-- .element: class="fragment" -->

---

# Portas de Entrada

- navegar na net
<!-- .element: class="fragment" --> 
- abrir documentos desconhecidos
<!-- .element: class="fragment" --> 
- phishing 
<!-- .element: class="fragment" --> 
- roubo físico 
<!-- .element: class="fragment" --> 
- sistema operativo
<!-- .element: class="fragment" --> 

<!-- no caso do sistema operativo estamos a referirnos a malware que ja vem pré instalado no sistema como por exemplo o keylogger da microsoft https://www.privateinternetaccess.com/blog/2017/03/microsoft-windows-10-keylogger-enabled-default-heres-disable/ -->

---

# O Problema

---

<img src="images/windows-logo.png" style="width: 20%;padding-right: 20%"/>
<img src="images/macos-logo.png" style="width: 20%;"/>
<br></br>

 Desenhados para serem convenientes
 <!-- .element: class="fragment" -->  
 </br>
**não para serem seguros**
 <!-- .element: class="fragment" --> 

---

#### Fazemos tudo no mesmo sistema <!-- .element: class="fragment" --> 

documentos, emails, fotografias, etc.
<!-- .element: class="fragment" --> 

--- ---

<img src="images/qubes-logo.svg"></img>
# Qubes OS
como solução

---

É uma alternativa ao Windows

- gratuita
- software livre
- mais segura

---

# Único em termos de segurança

</br>Segurança por compatimentalização <!-- .element: class="fragment" --> 

---

Segurança por
### Compartimentalização

<span style="font-size: 500%">💻 </span> <!-- .element: class="fragment" --> 
<span style="font-size: 500%">💻 </span> <!-- .element: class="fragment" --> 
<span style="font-size: 500%">💻 </span> <!-- .element: class="fragment" --> 

---

# Domínios de Segurança


Tudo corre em máquinas virtuais

note:
**DEMO:** abrir dois qubes e mostrar os seus gestores de ficheiros
para demostrar como estes mostra ficheiros diferentes de facto.
  - chamar para a atençao o facto de cada qube ter a sua cor

---

organizado por
# cores
<span style="font-size: 800%">🗃</span>

📕 inseguro  &nbsp; 📗 investigação  &nbsp; 📘 offline

---

# 📕 inseguro

Para navegar na net por qualquer site

---

# 📗 investigação

Contem todos os documentos de uma investigação,emails, etc.

---

# 📘 offline

Onde armazenamos palavras-passe e outras credenciais

---

# Demo

Vamos ver isto em ação

--- ---

# Isolamento

Cada máquina virtual (qube) 

está isolada das outras

---

### 📁 Copiar ficheiros

<img src="images/copy-to-app-vm.png" style="width: 60%" />

---

# 📋 Clipboard


copiar `ctrl-c`

copiar partilhado: `ctrl-shift-c`
<!-- .element: class="fragment" --> 

colar partilhado: `ctrl-shift-v`
<!-- .element: class="fragment" --> 

colar `ctrl-v`

--- ---

# Proteção USB

Temos controlo sobre que máquinas têm acesso a que dispositivos

---

# 📸 Webcam

Nada tem acesso

sem o darmos explicitamente

---

# 🎙Microfone

idem.

--- ---

# Amnésia
<br>

É o que nos permite estar seguros
<!-- .element: class="fragment" --> 
mesmo que tenhamos sido hackeados
<!-- .element: class="fragment" --> 

---

# Como ?

</br>

Sistema apenas guarda documentos
<!-- .element: class="fragment" --> 

Usa uma cópia fresca assim que reiniciamos
<!-- .element: class="fragment" --> 

---

# Instalar programas

tem que ser feito numa máquina **template**

---

# 🗑 Máquinas Descartávies

![](images/sketchy-attachment.png)

---

<span style="font-size: 600%">📄</span> 

# Ver documentos 
em Segurança

---

<span style="font-size: 600%">📄</span> 

# Editar documentos 
em Segurança

---

# Windows

Também é possível correr programas do windows

---

<!-- .slide: data-background-image="images/windows-qubes.png" -->

--- ---

# Navegação Anónima

Com a ajuda da rede <img style="width:10%" src="images/tor-logo.png"/>

<img src="images/internet.png"/>

---

# Porquê?
Para não revelar o que se está a investigar

---

# Rede Tor

![](images/tor-diagram.svg)

--- ---

# Caso de Uso


--- ---

<!-- SECURE DROP -->
<!-- .slide: data-background-image="images/securedrop-hexagons-background.png" -->

<img src="images/securedrop-logo-box.png" style="width:30%"/></br>
<img src="images/securedrop-logo.png" style="width:60%"/>

---

<!-- .slide: data-background-image="images/securedrop-news-orgs.png" -->

---

<!-- .slide: data-background-image="images/securedrop-hexagons-background.png" -->
<!-- .h1: color="red" -->


<img src="images/securedrop-workstation.png" style="width:60%"/>

# Securedrop Workstation


--- ---

# Notas Finais

---

<img style="width: 50%" src="images/qubes-divine.png"/>

---

<!-- .slide: data-background-image="images/opened-boxes-header.png" -->

Nem tudo
#  são rosas
<br>

- requer formção <!-- .element: class="fragment" --> 
- segurança cria obstáculos à utilização <!-- .element: class="fragment" --> 
- requer computador moderno e potente <!-- .element: class="fragment" --> 
- bateria dura pouco  <!-- .element: class="fragment" --> 

---

É preciso
# medir os riscos
<br>

- proteção de fontes <!-- .element: class="fragment" --> 
- manipulação segura de ficheiros <!-- .element: class="fragment" --> 
- segurança do(a) jornalista <!-- .element: class="fragment" --> 

---

muito
# Obrigado

--- ---

# mais recursos

---

# REVEAL.JS TEMPLATE
<!-- .element: class="no-toc-progress" --> <!-- slide not in toc progress bar -->

### [reveal.js][3] presentation written in [markdown][4] set up with [fabric][5] & [fabsetup][6]

created by [theno](https://github.com/theno) | 2017-01-05 | [online][1] | [src][2]


[1]: https://theno.github.io/revealjs_template
[2]: https://github.com/theno/revealjs_template

[3]: http://lab.hakim.se/reveal-js/
[4]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
[5]: http://www.fabfile.org/
[6]: https://github.com/theno/fabsetup

---

## Basic Idea

The browser and the web server; what was the web by the way? HTTP,
HTML, URLs; IP packets

--- ---

## reveal.js

> "A framework for easily creating __beautiful presentations__ using HTML."
>
> -- <cite>https://github.com/hakimel/reveal.js</cite>

<div class="fragment" />

* It's basically a static website displayed in a *browser*
  * Works better with *Chrome* than *Firefox*
* <!-- .element: class="fragment" -->
  __Markdown support__ -> *easy editing*:
  * <!-- .element: class="fragment" --> Don't bother with HTML syntax
  * <!-- .element: class="fragment" --> Write slides in a markdown file

---

## reveal.js supports Markdown

Writing slides in Markdown is easy:

```markdown
## reveal.js

> "A framework for easily creating beautiful presentations using HTML."
>
> -- <cite>https://github.com/hakimel/reveal.js</cite>

* It's basically a website displayed in a browser
* Works better with Chrome than Firefox
* Markdown support -> easy editing:
  * Don't bother with xml syntax
  * Write slides in a markdown file
```

---

## reveal.js: Showroom

Some reveal.js presentations:
* *"Official"* demo: http://lab.hakim.se/reveal-js
* http://slid.es/gsklee/functional-programming-in-5-minutes
* http://www.adidahiya.com/design.html
* http://slides.drublic.de/awesome-code
* http://hoebel.net/presentations_archive/saltstack/saltstack.html

More demos: https://github.com/hakimel/reveal.js/wiki/Example-Presentations

---  ---

# 2. fabric and fabsetup

---

# fabric

> "Fabric is a Python (2.5-2.7) library and command-line tool
> for streamlining the use of SSH for application deployment
> or systems administration tasks."
>
> -- <cite>http://www.fabfile.org/</cite>

<div class="fragment" />

__`>>shell-deploy-scripts on steroids!<<`__

---

## fab and fabfile.py

* __`fabfile.py`__ contains the fabric tasks
  * Bash commands _"written"_ in Python (2.5 - 2.7)
* Command __`fab`__ executes a task

---

example __`fabfile.py`__:

```python
from fabric.api import env, run, task

@task
def show_ips():
    ips = run('/bin/hostname -I')
    print('IPs of {}:\n  {}'.format(env.host, ips))
```

<div class="fragment" />

__`fab`__ uses the fabfile of the current dir:

```bash
> ls
fabfile.py
```

<div class="fragment" />

```bash
> fab show_ips  -H user@example_host
[example_host] Executing task 'ip_addresses'
[example_host] run: hostname -I
[example_host] out: 1.2.3.4

IPs of mobi12.uni.cx:
  1.2.3.4

  Done.  Disconnecting from example_host... done.
```

---

# fabsetup

Collection of __fabric tasks__:
* set up an [owncloud server][7]
* set up an own android app repository (own [F-Droid server][8])
* set up a linux desktop:
  eg. [configure vim, tmux, solarized colors][9] *(dotfiles on steroids!)*
* set up ...
* <!-- .element: class="fragment" -->
 __set up everything you need for a *reveal.js* presentation__:
 ```sh
 fab setup.revealjs
 ```

[7]: https://github.com/theno/fabsetup/blob/master/howtos/owncloud.md
[8]: https://github.com/theno/fabsetup/blob/master/howtos/f-droid-repo.md
[9]: https://github.com/theno/fabsetup/blob/master/howtos/no-sudo.md

--- ---

# 3. fab setup.revealjs

---

## A reveal.js Template

boilerplate for getting started on a nice reveal.js presentation:
* reveal.js code installed (comes with built-in plugins)
* Additional reveal.js plugins installed
* __`index.html`__ prepared accordingly
* All slides are defined in __`slides.md`__

---

## Set It Up

* install __fabsetup__:
```sh
sudo apt-get install  git  fabric              #
mkdir -p ~/repos  &&  cd ~/repos
git clone https://github.com/theno/fabsetup
```

* run fabric task __`setup.revealjs`__:
```sh
cd ~/repos/fabsetup
fab setup.revealjs  -H localhost
```

---

## fab setup.revealjs

*Asks for:*
 * Presentation base directory
 * Title
 * Sub-title
 * Short description

---

## fab setup.revealjs

*Optionally:*
 * Create github repo
 * Download npm libs

*When running again (also optional):*
 * Re-install reveal.js codebase

---

[howto](https://github.com/theno/fabsetup/blob/master/howtos/revealjs.md)

---

## Boilerplate File Structure

```sh
~/repos/my_presi> tree
.
├── .git/
├── .gitignore
│
├── README.md   <-- Short description and usage
│
├── slides.md   <-- All slides are defined here
├── index.html  <-- Configuration
├── img/
│   └── thanks.jpg  <-- good place for images
│
└── reveal.js/   <--.
    ├── css/         `-- reveal.js code "hidden" in a subdir
    ├── js/               (keeps the basedir clean)
    ├── plugin/
    ...
    ├── img -> ../img                \
    ├── reveal.js -> ../reveal.js     |_ symbolic links in order
    ├── slides.md -> ../slides.md     |   to run `npm start`
    └── index.html -> ../index.html  /
```

---

*template features*

---

## Plugins Built-In

All the built-in plugins are enabled in the __`index.html`__:
* __[marked.js, markdown.js][10]__: Markdown support
* __[highlight.js][11]__: Code syntax highlighting
* __zoom.js__: Zoom in and out with `ALT+click`
* __[notes.js][13]__: Speaker notes
* __[math.js][14]__: Formatting math expressions

[10]: https://github.com/hakimel/reveal.js/#markdown
[11]: https://github.com/hakimel/reveal.js/#code-syntax-highlighting
[13]: https://github.com/hakimel/reveal.js/#speaker-notes
[14]: https://github.com/hakimel/reveal.js/#mathjax

---

## Additional Plugins

This additional plugins will be installed and set up, too:
* __[menu.js][15]__: Slideout menu (slide index, change theme and transition)
* __[toc-progress.js][16]__: *"LaTeX Beamer-like progress indicator"*
* __[title-footer.js][17]__: *"Footer showing title of presentation"*

[15]: https://github.com/denehyg/reveal.js-menu#revealjs-menu
[16]: https://github.com/e-gor/Reveal.js-TOC-Progress
[17]: https://github.com/e-gor/Reveal.js-Title-Footer

---

## Customizations in reveal.js

* Don't Capitalize Titles (NO FULL UPPERCASE HEADINGS)
* Images are displayed without border

---

## Special Markdown Slide dividers

*Two dividers exist:*
* New horizontal slide: `\n----  ----\n`
* New vertical slide: `\n----\n`

*Win-win:*
* ["Raw"][18] `slides.md`: Easy to read and edit
* Horizontal lines in [rendered Markdown][19]: Easy to read, too

[18]: https://raw.githubusercontent.com/theno/revealjs_template/master/slides.md
[19]: https://github.com/theno/revealjs_template/blob/master/slides.md

---

## Create PDF

*cumbersome.*
* With [decktape](https://github.com/astefanutti/decktape)

```sh
cd ~/bin/decktape/active && \                                               #
./phantomjs decktape.js --size 1280x800 URL ~/repos/my_presi/my_presi.pdf
```

* Or just print the `slides.md` rendered by github into a PDF:
  https://github.com/theno/revealjs_template/blob/master/slides.md

---

* [Printing with chromium](https://github.com/hakimel/reveal.js#pdf-export)
  (or chrome) does not work well:
  https://theno.github.io/revealjs_template/?print-pdf#/

Note:
URL can be of:
* localhost:8000
* github.io page

---

## Shortcut

Checkout the template presentation repo:
```sh
git clone https://github.com/theno/revealjs_template  ~/repos/my_presi
```

Then:
* Adjust `<title>reveal.js template</title>` in __`index.html`__
* Edit __`slides.md`__
* Add symbolic link:
  ```sh
  cd ~/repos/my_presi  &&  ln -snf ../reveal.js  reveal.js/reveal.js
  ```

---  ---

# 4. Publishing at github.io

---

## Publishing as github page

A github repo (with `index.html`) can be rendered into a github.io page

1. Add remote repo at github.com <br>
   *(automated in fabsetup task setup.revealjs)*

1. [Configure][20] entry point for github.io page <br>
   *(manually, select "master branch")*


[20]: https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/
[1_]: https://theno.github.io/revealjs_template
[2_]: https://github.com/theno/revealjs_template

--- ---

# 5. Conclusion and Outlook

---

## Conclusion

* Presentations with __reveal.js__ are fancy and nice
* Writing slides in __Markdown__ is easy
* __fabric__ is a framework for powerfull setup scripts
* __fabsetup__ is a collection of fabric tasks

---

__`fab setup.revealjs`__ (one of this tasks):
  Creates the boilerplate of your presentation:
  * Clean basedir (reveal.js codebase hidden in a subdir)
  * Slides are written in a __Markdown file__
  * Usefull plugins enabled (eg. __footer, toc, menu__)
  * Versioning with __git__
  * Publishing at __github.io__

__`>>just edit the slides.md<<`__  <!-- .element: class="fragment" -->

---

## Outlook

* Publishing with own webserver
  * Implement restricted access
* Custom design
  * Create themes / corporate design
* Explore [more plugins][21]
* [Customize][23] fabsetup task `setup.revealjs`

---

Alternative:

[prez][22] -- *"Opiniated Reveal slideshow generator with nice
PDF output and ability to treat notes as first-class content."*

[21]: https://github.com/hakimel/reveal.js/wiki/Plugins,-Tools-and-Hardware
[22]: https://github.com/byteclubfr/prez
[23]: https://github.com/theno/fabsetup/blob/master/howtos/fabsetup_custom.md

---

## References

* reveal.js: [http://lab.hakim.se/reveal-js](http://lab.hakim.se/reveal-js/)
  * at github: [https://github.com/hakimel/reveal.js](https://github.com/hakimel/reveal.js)

---

* markdown: [https://daringfireball.net/projects/markdown](https://daringfireball.net/projects/markdown/)
  * cheatsheet: [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

---

* fabric: [http://www.fabfile.org](http://www.fabfile.org/)
  * at github: [https://github.com/fabric/fabric](https://github.com/fabric/fabric)

---

* fabsetup: [https://github.com/theno/fabsetup](https://github.com/theno/fabsetup)
  * revealjs [howto](https://github.com/theno/fabsetup/blob/master/howtos/revealjs.md)

--- ---

<!-- .slide: data-state="no-toc-progress" --> <!-- don't show toc progress bar on this slide -->

### *Thank You for Your attention!*
<!-- .element: class="no-toc-progress" -->

![](img/thanks.jpg)
