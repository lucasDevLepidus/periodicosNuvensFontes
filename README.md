# Periódicos em nuvens

Uma solução completa oferecida pela [Lepidus Tecnologia](https://lepidus.com.br/) para melhor atender equipes de editores científicos de periódicos online. Para isso, utilizamos como base o consagrado [Sistema Eletrônico de Editoração de Revistas (SEER)](https://periodicos.emnuvens.com.br/o-que-e/seer/) ou [Open Journal Systems (OJS)](https://github.com/pkp/ojs)

## Sobre esse projeto

Esse projeto se trata da criação do novo site do [periódico em nuvens](https://periodicos.emnuvens.com.br/), utilizando o framework [Hugo](https://gohugo.io/)

## Instalação do Hugo
Para realizar a instalação desse projeto na sua maquina, tenha certeza que você tenha o `hugo` instalado em sua maquina. Caso não tenha instalado o Hugo na sua maquina, basta executar esse comando no terminal:

```sh
sudo apt-get install hugo
```

## Execução desse projeto

1. Realize o clone desse projeto:

```sh
git clone https://github.com/lepidus/site-do-pen
```

2. Feito o clone do repositório, entre dentro da pasta baixada, e rode o comando:

```sh
git submodule update --remote --merge
```

Para atualizar os sub-módulos do tema

3. Após execução do comando acima, execute o comando:

```sh
hugo server
```
Para iniciar o projeto. Feito isso, basta acessar o endereço local: `localhost:1313` para visualizar a aplicação.

**OBS:** Para alguns casos de segurança, dependendo do sistema operacional, será necessário rodar o comando acima com a permissão de super usuário, logo o comando será:

```sh
sudo hugo server
```