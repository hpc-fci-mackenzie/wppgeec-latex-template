# Rápida introdução à instalação do LaTeX
Este é um guia rápido de instalação do LaTeX nos sistemas *Windows* e *Linux*.



## Instalação do LaTeX

​	Em ambos os sistemas operacionais utilizaremos o *TeX Live*. Este é um pacote de aplicações de fácil instalação que possui bibliotecas, fontes e compiladores necessários para o desenvolvimento com o LaTeX.
​	Nossa recomendação é que seja feita a instalação completa do *TeX Live* no dois sistemas.

### Instalação no *Windows*
​	Para instalar o *TeX Live* no *Windows*, basta baixar o executável neste [link](http://mirror.ctan.org/systems/texlive/tlnet/install-tl-windows.exe) e seguir os passos de instalação.

### Instalação no *Linux*

​	Selecionamos para este tutorial de instalação as três distribuições *Linux* mais utilizadas: *Ubuntu*, *Centos* e *Fedora*.

​	Lembramos que todos os comandos apresentados nesta seção devem ser executados com privilégios administrativos.

#### *Ubuntu*
​	Para instalação do *TeX Live* nas versões mais recentes do Ubuntu, basta copiar e colar o comando abaixo.
```
apt-get install texlive-full
```

#### *CentOS 7*

​	Para instalação do *TeX Live* na versão mais recente do *CentOS*, basta copiar e colar o comando abaixo.
```
yum install texlive-*
```

#### *Fedora 28*

​	Para instalação do *TeX Live* na versão mais recente do *Fedora*, basta copiar e colar os comando abaixo.
```
dnf install texlive-scheme-full
```



## IDE's para LaTeX

​	Muitas são as IDE's existentes que facilitam o desenvolvimento em *LaTeX*. Eis [aqui](https://tex.stackexchange.com/questions/339/latex-editors-ides) uma lista delas. Neste tutorial apresentaremos o [TeXstudio](https://www.texstudio.org/) por ser multi-plataforma e de fácil integração com *TeX Live*.

​	É importante salientar que a instalação da IDE deve ser feita após o término da instalação completa do *TeX Live*. Desta forma as bibliotecas, as fontes e os compiladores serão encontrados de automaticamente pela IDE.

### Instalação no *Windows*

​	Para instalar o *TeXstudio* no *Windows*, basta baixar o executável neste [link](https://github.com/texstudio-org/texstudio/releases/download/2.12.10/texstudio-2.12.10-win-qt5.exe) e seguir os passos de instalação.

### Instalação no *Linux*

​	Selecionamos para esta seção as mesmas três distribuições *Linux* da seção anterior: *Ubuntu*, *Centos* e *Fedora*.

​	Lembramos mais uma vez que todos os comandos apresentados nesta seção devem ser executados com privilégios administrativos.

#### *Ubuntu*

​	Para instalação do *TeXstudio* nas versões mais recentes do Ubuntu, basta copiar e colar o comando abaixo.

```
apt-get install texstudio
```

#### *CentOS 7*

​	Para instalação do *TeXstudio* na versão mais recente do *CentOS*, é necessário baixar o arquivo de instalação a partir deste [link](http://download.opensuse.org/repositories/home:/jsundermeyer/CentOS_CentOS-7/x86_64/texstudio-qt4-2.12.10-4.1.x86_64.rpm) e executar o seguinte comando a partir do diretório onde o arquivo foi baixado.

```
yum install texstudio-qt4-2.12.10-4.1.x86_64.rpm
```

​	Ressaltamos que pode haver variações no nome do arquivo.

#### *Fedora 28*

​	Para instalação do *TeXstudio* na versão mais recente do *Fedora*, é necessário baixar o arquivo de instalação a partir deste [link](http://download.opensuse.org/repositories/home:/jsundermeyer/Fedora_28/x86_64/texstudio-2.12.10-3.1.x86_64.rpm) e executar o seguinte comando a partir do diretório onde o arquivo foi baixado.

```
dnf install texstudio-2.12.10-3.1.x86_64.rpm
```

​	Ressaltamos que pode haver variações no nome do arquivo.