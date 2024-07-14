# NLW JOURNEY - Trilha Python

<p align="center">
	<img alt="Status Concluído" src="https://img.shields.io/badge/STATUS-CONCLU%C3%8DDO-brightgreen">
</p>

## Descrição

O projeto Journey tem como objetivo ajudar o usuário a organizar viagens à trabalho ou lazer. O usuário pode criar uma viagem com nome, data de início e fim. Dentro da viagem o usuário pode planejar sua viagem adicionando atividades para realizar em cada dia.

## Sobre o projeto

Este projeto foi criado para o **NLW JOURNEY | Trilha Python | Rocketseat**, que ocorreu do dia 8 a dia 12 de julho de 2024. \
Nele foi criado a parte do back-end em Python com orientação do Rafael "Lhama" Ferreira.

## Tecnologias Utilizadas

-   **Linguagem**: Python 3.10.12 -  ![Python](https://img.shields.io/badge/Python-3.10-yellow)
-   **Framework**: Flask 3.0.3- ![Flask](https://img.shields.io/badge/Flask-3.0-green)
-   **Banco de Dados**: SQLite 3.31.1 - ![SQLite](https://img.shields.io/badge/SQLite-3.31-blue)
-   **Testes**: Pytest 8.2.2 - ![Pytest](https://img.shields.io/badge/Pytest-8.2-brightgreen)
-   **Ferramenta de Simulação de Requisições**: Postman - ![Postman](https://img.shields.io/badge/Postman-11.2.0-orange)


## Funcionalidades

-   **Planejamento de Viagens**: Adição, busca e confirmação de viagens planejadas.
-   **Gerenciamento de Participantes**: Convites de acompanhantes via e-mail e confirmação de presença dos convidados.
-   **Listagem de Atividades**: Planejamento das atividades a serem realizadas em cada destino.
-  **Cadastro de links úteis**:  Cadastro de links úteis para o planejamento da viagem.
## Utilização

### Endpoints

Aqui estão alguns dos principais endpoints da aplicação:

-   **POST /trips**: Cria uma nova viagem.
-   **GET /trips/tripId**: Busca a viagem pelo ID.
-   **POST /trips/tripId/invites**: Adiciona convidados à viagem selecionada.
-   **PATCH /participants/participantId/confirm**: Confirma a presença do participante
  
## Desenvolvedor

<table align="center">
<tr>
<td> 
<div align="center">
<img style="width: 150px; border-radius: 50%;" src="https://avatars.githubusercontent.com/u/97572894?s=400&u=b5eb6786f593b03cd61e0cd6b65b1bbafb8e2a95&v=4" alt="msjjrdev"/><br />
<a href="https://github.com/msjrdev">Manoel Silva Junior</a> 
</div>  
</td>
</tr>
</table>