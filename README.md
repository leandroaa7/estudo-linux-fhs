# Introdução ao Filesystem Hierarchy Standard
## Resumo das funcionalidades dos diretórios principais do Linux
### Todas as distribuições linux possuem um padrão em seus diretórios da pasta root (/). Segue abaixo um pouco sobre cada diretório

<hr>

<center>

## Índice

| Diretórios
| :----
| bin
| boot
| dev
| etc
| home
| lib
| media
| mnt
| opt
| proc
| root


</center>
<br>
<hr>

## Diretório **/bin**
 
### É onde está localizado os **executáveis** do sistema, ls, chmod, cd etc.

### *Para localizar um comando como o ls basta digitar o comando abaixo*

` which ls `

<hr>

## Diretório **/boot**

###  É onde está todas as configurações de **boot** do sistema, e alguns drivers responsáveis pelo processo de boot.
### - *As configurações do **grub** estão localizadas neste diretório*

### - *Possue também o arquivo vmLinuz que é o arquivo de **Kernel***


## Diretório **/dev**

<hr>

### Diretório onde está localizado todos os **dispositivos**, sda (disco do sistema ) por exemplo. Ao conectar um pen-drive é criado uma entrada neste diretório.

<hr>

## Diretório **/etc**

### Diretório de **configuração** do sistema.

### *Geralmento quando instalamos um programa no linux ele cria um diretório aqui com os respectivos arquivos de configuração.*

<hr>

## Diretório **/home**


### Diretório onde ficam os **usuários** do sistema.

<hr>

## Diretório **/lib** e **/lib64**

### Diretório onde ficam as **bibliotecas** do sistema, programas que são importados por outros.
### - São arquivos terminados em .so ou .a
### - Auxiliam na integração do software com o S.O
### - [LEITURA](https://gnulinuxbrasil.com.br/2017/08/25/o-que-sao-bibliotecas-ou-libraries/)

<hr>

## Diretório **/media**

### Onde serão **montados** os dispositivos, pen-drive, DVDs, etc 

<hr>

## Diretório **/mnt**

### similar ao /media porém pode ser montado algo além de dispositivos e é um ponto de montagem **temporário**


<hr>

## Diretório **/opt**

### Abreviação de optional, diretório onde fica os **softwares opcionais**, pacotes separados, programas que já possuem executável.
### Exemplo: chrome, Insomnia, containerd (docker) etc

<hr>

## Diretório **/proc**

### É um diretório e, quase, um sistema de arquivos. Responsável por **armazenar informações do sistema** 
### Cada pasta é um PID do sistema. Se você abrir um programa e pegar o seu PID você irá localizá-lo em /proc
### É possível também visualizar informações de hardware, como processador (cpuinfo) etc 
### *Para localizar o PID do seu programa execute o comando abaixo*

` ps aux | grep SEU_PROGRAMA_DESEJADO`

<hr>

## Diretório **/root**

### seria o **/home do superusuário** ou usuário root

<hr>

## Diretório **/run**

### É 



