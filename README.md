# Curso de Python - Escola de verão do IAG - 2016

**Professores:** Marcelo Bianchi, Victor Sacek e Leonardo Uieda


## Leitura recomendada

Software Carpentry: http://software-carpentry.org

Scipy Lecture Notes: http://www.scipy-lectures.org

Pilgrim, M. (2004), Dive Into Python, Apress, Berkeley, CA : New York.
[[disponível online](http://www.diveintopython.net/)]


## Rodando os notebooks online

Use o botão abaixo para abrir os notebooks do curso 
usando o [Binder](http://mybinder.org/):

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/marcelobianchi/verao2016) 

Você poderá rodar os notebooks e editá-los sem instalar nada no seu computador.
Porém, seu trabalho **não ficará salvo**!


## Instalando no seu computador

Você vai precisar instalar uma distribuição do Python.
Não é recomendado utilizar o Python do site oficial ou o sistema (no caso de
Linux).
A maneira mais fácil de instalar o Python e todas as bibliotecas científicas
que vamos usar é usando o [Anaconda](https://www.continuum.io/downloads#all).
Entre no site, baixe e instale.
**Atenção: baixe o Python 2.7**.

Depois de instalar o Anaconda, abra um terminal (ou `cmd.exe` no Windows) e
rode o comando:

    conda install numpy scipy matplotlib numba jupyter basemap pillow mayavi pip future

Isso garantirá que todas as bibliotecas estão na versão mais recente.

Em seguida, rode o comando abaixo para instalar o [Fatiando a
Terra](http://www.fatiando.org):

    pip install https://github.com/fatiando/fatiando/archive/master.zip


