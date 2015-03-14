É um pacote LaTeX que implementa as especificidades das normas de confecção de trababalhos da Universidade Tuiuti do Paraná.

Este pacote usa o pacote ABNTeX.

**Atenção:** O abnTeX é considerado obsoleto e recomenda-se usar o [abnTeX2](https://code.google.com/p/abntex2/)! Caso você tenha interesse em portar este template para abnTeX2, por favor entre em contato.

## Antes de tudo ##

Para o uso deste pacote assume-se que o usuário tem noções básicas do que é LaTeX e de como ele funciona: como são os comandos, como fazer citações, etc.. Caso você não tenha lido nada a respeito ainda, recomendo dar uma olhada nos **tutoriais** apontados [nesta página](http://www.ime.eb.br/~pinho/pessoal/latex/).

## Como usar esse template? ##

  * Instale algum sistema TEX/LATEX: texlive, tetex, miktex, etc..
  * Baixe este modelo
  * Execute `make`
  * Veja o pdf gerado
  * Modifique o template para o seu trabalho
  * Profit

## Como instalar os pacotes de LATEX? ##

Em [Mandriva Linux](http://www.mandriva.com/):

  * Execute `urpmi texlive-latex latex-abntex make`

Não testei, mas eis os meus palpites para Ubuntu e Debian:

  * Instale `texlive-latex-base`, `texlive-latex-extra`, `abntex` e `make`.

Para Windows:

  * Instale o [MikTeX](http://miktex.org)
  * Siga as instruções de download instalação do ABNTEX [nesta página](http://sourceforge.net/apps/mediawiki/abntex/index.php?title=Instala%C3%A7%C3%A3o).
  * Fique atento para usar uma versão que seja igual ou superior à 0.9-beta2.

## Como baixar e usar o _abntex-utp_? ##

Para baixar o abntex-utp, é necessário usar a ferramenta [Mercurial](http://mercurial.selenic.com/), que é uma ferramenta de controle de versão de código.

### Em Linux ###

Para instalar em openSUSE:

**`sudo zypper in mercurial`**

Para instalar em Mandriva Linux:

**`urpmi mercurial`**

Em Ubuntu e Debian, instale `mercurial`.

Depois de ter o mercurial instalado, você deve baixar o projeto, executando:

```
  hg clone https://abntex-utp.googlecode.com/hg/ abntex-utp 
```

### Em Windows ###

Para Windows, instale o [TortoiseHG](http://tortoisehg.bitbucket.org/), que é uma ferramenta gráfica para utilizar o Mercurial. Clique com o botão direito em qualquer diretório aonde queira guardar o _abntex-utp_ e vá na opção `Clone`. Na opção Source Path adicione a URL https://abntex-utp.googlecode.com/hg/ e na opção Destination Path coloque o caminho de destino desejado. E voilá!

### Compilando ###

Em Linux, é só ir alterando `trabalho.tex` para ter o conteúdo do seu trabalho
e executando `make` para ter `trabalho.pdf`.

Se você deseja ver um trabalho _completo_ como exemplo, compile exemplo.tex.

Para Windows, abra o arquivo `trabalho.tex` (o MikTeX deve associar esse tipo
com o TeXworks) e clique no ícone que parece um botão de play, mas tem descrição
"Typeset". Com isso deve ser suficiente para ter o PDF gerado. Recomendo usar o
Notepad++ ou algum outro editor melhor que o TeXworks, especialmente se você
alterna o desenvolvimento entre Linux e Windows.

## Como reportar problemas ou pedir modificações? ##

É só criar uma _issue_ (na seção Issues deste projeto) e descrever o problema ou o pedido.

É importante lembrar que sejam dúvidas relacionadas ao abntex-utp especificamente, e não a questões relacionadas a como escrever documentos para o LaTeX.

Caso você tenha interesse em participar do desenvolvimento, ou tirar dúvidas, participe da [lista de discussão do grupo](http://groups.google.com.br/group/abntex-utp).