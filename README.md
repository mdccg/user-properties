# user-properties

## Sumário

- [user-properties](#user-properties)
  - [Sumário](#sumário)
  - [Motivação](#motivação)
  - [Pilha de tecnologia](#pilha-de-tecnologia)
  - [Como rodar](#como-rodar)
    - [Pré-requisitos](#pré-requisitos)
    - [Passo a passo](#passo-a-passo)
  - [Referências bibliográficas](#referências-bibliográficas)

## Motivação

O presente repositório consiste em um manipulador de arquivos de propriedades. Um arquivo de propriedades, por sua vez, é um arquivo de formato PROPERTIES que utiliza a estrutura chave-valor para armazenamento de dados, semelhante à estrutura de dados tabela de dispersão, além de separar as informações por quebra de linha. Ele pode ser usado para, por exemplo, "passar configurações para uma determinada aplicação que necessitada de configurações externas e a mesma em si não pode ser alterada." (GOMES[<sup>[1]</sup>](#referencia-bibliografica-1), 2012)

Este repositório em si consiste em uma refatoração do [repositório do professor](https://github.com/sidneyroberto/LP2_2022_2/tree/main/exemplo-polimorfismo) e foi criado do zero para ajudar alguns discentes que não puderam estar presentes na aula expositiva em questão. O passo a passo dele foi gravado utilizando o Google Meet e disponibilizado no YouTube para os mesmos. Portanto, nem o repositório nem o vídeo abaixo foram apresentados como requisitos para obtenção da nota parcial das atividades da unidade curricular Linguagem de Programação II; todavia, foi o segundo repositório de código criado para esta unidade curricular do [Curso Superior de TSI do IFMS](https://www.ifms.edu.br/campi/campus-aquidauana/cursos/graduacao/sistemas-para-internet/sistemas-para-internet).

<iframe width="560" height="315" src="https://www.youtube.com/embed/jP5yrSPpMiY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Pilha de tecnologia

As seguintes tecnologias foram utilizadas para desenvolver este app:

| Papel | Tecnologia |
|-|-|
| Ambiente de execução | [Node](https://nodejs.org/en/) |
| Linguagem de programação | [TypeScript](https://www.typescriptlang.org/) |
| Framework de teste | [Jest](https://jestjs.io/pt-BR/) |

## Como rodar

### Pré-requisitos

- [Node](https://nodejs.org/en/download/);
- [Yarn](https://yarnpkg.com/) (opcional).

### Passo a passo

1. Clone o repositório de código em sua máquina;
   
2. Abra um shell de comando de sua preferência (prompt de comando, PowerShell, terminal _etc_.);

3. Instale as dependências do projeto através do seguinte comando:

```console
$ npm install
```

Caso esteja utilizando o gerenciador de pacotes Yarn, execute o seguinte comando como alternativa:

```console
$ yarn
```

4. Finalmente, execute o seguinte comando para iniciar o app:

Para npm:

```console
$ npm run test
```

Para Yarn:

```console
$ yarn test
```

## Referências bibliográficas

<span id="referencia-bibliografica-1">[1]</span> GOMES, Robson Fernando. **Utilizando arquivos de propriedades no Java**. [_S_. _l_.]: DevMedia, 24 ago. 2012. Disponível em: https://www.devmedia.com.br/utilizando-arquivos-de-propriedades-no-java/25546. Acesso em: 20 jan. 2023.