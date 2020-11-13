![logo](/uploads/4314307b69d1017bf8b22767856e3ff4/logo.jpg)

<h1 align="center">Plataforma Cadastro Positivo</h1>

## Proposta Comercial

A nossa proposta é desenvolver um dashboard que funcionará como uma linha do tempo. O objetivo é que o usuário da plataforma possa analisar sua vida financeira baseada em dados que englobam o passado, presente e futuro de sua vida financeira. Os recursos principais do dashboard serão os seguintes:
- Valor do score atual
- Banner com artigos informativos para os usuários
- Gráfico com valores em porcentagem, informando se as contas do cliente foram pagas dentro ou fora do prazo, se ainda estão em aberto ou se estão atrasadas, a partir da escolha de um determinado mês e ano.
- Gráfico com o histórico do score
- Tabela informando o quanto do orçamento do usuário foi designado para cada tipo de despesa em um determinado mês, que será escolhido pelo mesmo.
<p>Com essas informações, a sequência de linha do tempo proposta funcionará da seguinte forma:
Passado: será designado pelo gráfico de histórico, onde o usuário poderá saber em qual momento de sua vida a sua análise de crédito esteve melhor ou pior.
Presente: o score atual trará essa informação, onde o cliente poderá saber como agir dependendo do valor que o mesmo receberá como retorno ao fazer sua consulta.
Futuro: a interface contará com um banner, que irá permitir acesso a artigos que podem ajudar no planejamento financeiro do usuário. Caso o mesmo tenha score baixo, ele terá acesso a dicas de gestão financeira e de como sair das dívidas. Caso o seu score for alto, existem também artigos com informações de dicas de investimento e de como funcionam as taxas bancárias, com o intuito de evitar despesas desnecessárias.

## Descrição do Projeto

A equipe desenvolverá um trabalho em parceria com o Spc, onde será desenvolvida uma plataforma para que usuários possam consultar informações referentes ao seu cadastro positivo. Este trabalho será feito pelos alunos do 3° semestre do curso de Banco de Dados, da Fatec de São José dos Campos, cumprindo os objetivos propostos pela organização do projeto integrador.

Índice
=================
<!--ts-->
   * [Proposta Comercial](#proposta-comercial)
   * [Descrição do Projeto](#descricao-do-projeto)
   * [Índice](#indice)
   * [Status do Projeto](#status-do-projeto)
   * [Features](#features)
   * [Entregas](#entregas)
   * [Requisitos](#requisitos)
      * [Funcionais](#funcionais)
      * [Não Funcionais](#nao-funcionais)
   * [User Stories](#user-stories)
   * [Equipe](#equipe)
   * [Como Instalar o Projeto na Máquina](#como-instalar-o-projeto-na-maquina)
   * [Tecnologias](#tecnologias)
<!--te-->

## Status do Projeto

<h4 align="center"> 
	🚧  Dashboard Spc 🔧 Em Desenvolvimento...  🚧
</h4>

### Features

- [X] Tela de login
![login](/uploads/032e0b5978781b1971c642e3fc565159/login.gif)
- [ ] Autenticação de usuário (falta inserir captcha)
- [ ] Cadastro de novos usuários (falta corrigir formatação css)
- [ ] Score do cadastro positivo (falta alinhamento do velocímetro na página e integração back end)
- [X] Banner com artigos de utilidade pública
![banner](/uploads/7efa39a769f5df3cfcb50b79b5fda60e/banner.gif)

- [X] Histórico do score do usuário

![histórico](/uploads/2f3675e13f300756f68110f7b8919673/histórico.gif)
- [X] Gráfico com o status das contas

![status](/uploads/e3f0f45645d6f61041f475892e6da444/status.gif)
- [ ] Gráfico com os tipos de contas (falta corrigir bug do html)

### Entregas

| Sprint | Data  | Vídeo                                       |
|--------|-------|---------------------------------------------|
| 0      | 27/09 | https://www.youtube.com/watch?v=udTstj6BMCI |
| 1      | 18/10 | https://www.youtube.com/watch?v=lQFAUZnjNhA |
| 2      | 08/11 | https://www.youtube.com/watch?v=JHuPgc0dNwY |
| 3      | 29/11 |                                             |

### Requisitos

#### Funcionais

| Requisitos Funcionais                          | Código | Prioridade | Sprint |
|------------------------------------------------|--------|------------|--------|
| Autenticação dos dados                         | RF01   | 1          | 1      |
| Tela com valor atual do score                  | RF02   | 1          | 1      |
| Faq (perguntas frequentes)                     | RF03   | 2          | 1      |
| Visualização do status de pagamento das contas | RF04   | 1          | 2      |
| Gráfico com descrição de consumo               | RF05   | 1          | 2      |
| Histórico do score do usuário                  | RF06   | 1          | 3      |
| Conexão com banco de dados                     | RF07   | 1          | 3      |

#### Não Funcionais

| Requisitos Não Funcionais                  | Código | 
|--------------------------------------------|--------|
| Dashboard interativo                       | RNF01  |
| Seguir as diretrizes da Lgpd               | RNF02  |
| Banco de dados relacional (my sql)         | RNF03  |
| Infraestrutura para grande volume de dados | RNF04  |
| Utilização de linguagem java               | RNF05  |
| Proteção dos dados do usuário              | RNF06  |

#### User Stories

![User_Stories](/uploads/9524d6eece558203eafcc5b9c61385ab/User_Stories.PNG)

##### Equipe:

##### Fabrício Adriel
* [Git Lab](https://gitlab.com/fabricioadriel)
* [Linkedin](linkedin.com/in/fabricioadriel)
* RA: 1460281923009

##### Felipe Santos
* [Git Lab](https://gitlab.com/felipefsc)
* [Linkedin](https://www.linkedin.com/in/felipe-santos-454060187/)
* RA: 1460281923011

##### Gabriela Momilli
* [Git Lab](https://gitlab.com/gabsmomilli)
* [Linkedin](linkedin.com/in/gabriela-momilli-105b1a184)
* RA: 1460281923058

##### Gilberto Souza
* [Git Lab](https://gitlab.com/gilberto.santos10)
* [Linkedin](linkedin.com/in/gilberto-santos-jr)
* RA: 1460281723021

#### Como Instalar o projeto na máquina:

- Selecione uma pasta de sua preferência, através do comando "cd Pasta Escolhida"
- Abra o terminal clicando dentro de uma pasta com o botão direito e selecione a opção git bash here
- Utilize a função git clone https://gitlab.com/tecno-code/dashboard-spc para instalar os arquivos no seu computador

### 💻 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- Html
- Css
- Javascript
- Jquery
- Bootstrap
- Sql
- Java