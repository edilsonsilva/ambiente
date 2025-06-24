# Preparação de ambiente
Criar uma máquina virtual para instalar as ferramentas e dependências para o 
estudo de algoritmo e lógica de programação

## Criar o diretório base
Vamos criar um diretório para guardar a nossa máquina virutal. Será criado no 
Drive D. Nomeada com o nome do usuário.

<img src="criar-diretorio-d.png">

## Preparação da máquina virtual
### Vamos usar a ferramenta de virtualização chamada Virutal Box

<img src="tela-virtualbox.png">

<a href="https://www.virtualbox.org/wiki/Downloads"> Faça o download aqui </a>


## Criando a máquina virtual

<img src="nova-maquina-virtual.png">

## Configuração da máquina virtual

<img src="configuracao-hardware.png">

## Configuração do disco

<img src="configuracao-disco.png">

## Resumo da Instalação

<img src="resumo-da-instalacao.png">

## Iniciando a instalação 
<img src="iniciando-instalacao.png">

## Configurar idioma e teclado

<img src="configuracao-idioma-teclado.png">

## Resumo da configuração Ubuntu

<img src="resumo-da-configuracao-ubuntu.png">

## Configuração usuário

<img src="configuracao-usuario.png">

## Pós instalação:

Para atualizar o sistema iremos usar os seguintes comandos:

```shell
sudo apt update -y
```

```shell
sudo apt upgrade -y
``` 

ou

```shell
sudo apt update -y && sudo apt upgrade -y 
```

## Intalação do cockpit

Ferramenta para gerenciar o servidor, por meio de um 
ambinte grafico online

<img src="tela-cockpit.png">

#### comando para instalar o cockpit

```shell
sudo apt install cockpit -y
```