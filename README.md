# Camisa 10 - Back-end

## Descrição do site:

#### O camisa 10 é um site voltado para os amantes das principais ligas de futebol do mundo. Nele é possível consultar os jogos do dia e as classificações dos seguintes campeonatos:
* Campeonato Brasileiro Série A
* Premier League
* Ligue 1
* Bundesliga
* Serie A
* Eredivisie
* Primeira Liga
* Primera Division 

## API Rest desenvolvida:
#### Para o Camisa 10, foi desenvolvida uma API REST em Django, com as seguintes urls: 
* api/user/<str:user_name>/ (GET - retorna o usuario e a senha salvos no banco de dados)
* api/user (POST - cria um novo usuário no banco de dados)
* api/user/delete (DELETE - deleta um usuário do banco de dados)
* api/favorite/<str:user_name> (GET - retorna uma lista dos favoritos daquele usuário salvos no banco de dados)
* api/favorite (POST - posta um favorito ligado a um usuário)
* api/favorite/delete (DELETE - deleta um favorito do banco de dados)

## Acesso ao backend:
#### É possível acessar o site na seguinte url:
* http://camisa10-backend.herokuapp.com

## Alunos:
* José Rafael Martins Fernandes
* Lucca Barufatti Velini Sanches
