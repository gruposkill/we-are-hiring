
# Teste Full Stack

O teste consiste em criar uma API REST que busca usuarios pelo nome e username a partir de uma palavra chave. 
Faça o download do arquivo [users.csv.gz](https://raw.githubusercontent.com/gruposkill/we-are-hiring/master/go/users.csv.gz) que contém o banco de dados que deve ser usado na busca. 
Ele contém os IDs, nomes e usernames dos usuários.

###### Exemplo
| ID                                   | Nome              | Username             |
|--------------------------------------|-------------------|----------------------|
| 03a3723c-0302-4aa5-98ba-d20b2b342f10 | Jair Nascimento   | jairnascimento       |
| 9e351986-1f5c-4640-b99b-70540397c78b | Tamiris Canassa   | tamiriscanassa       |
| 8198fe2f-5905-4c5c-addd-c7367faf9be9 | Waleria Vanessa   | waleria.vanessa      |


Também são fornecidas duas listas de usuários que devem ser utilizadas para priorizar os resultados da busca. 
 - A lista 1 tem mais prioridade que a lista 2. Ou seja, se dois usuarios casam com os criterios de busca, aquele que está na lista 1 deverá ser exibido primeiro em relação àquele que está na lista 2. Os que não estão em nenhuma das listas são exibidos em seguida.

As listas podem ser encontradas na raiz deste repositório ([lista1.txt](https://raw.githubusercontent.com/gruposkill/we-are-hiring/master/go/lista1.txt) e [lista2.txt](https://raw.githubusercontent.com/gruposkill/we-are-hiring/master/go/lista2.txt)).
Os resultados devem ser retornados paginados de 15 em 15 registros.

-----

### Requisitos

- Criar um frontend (em Vue.js) para realizar a busca com uma UX elaborada
- Criar uma solução de autenticação entre o frontend e o backend
- O backend deve ser escrito em NodeJS
- Utilizar o Docker
