# *Projeto Individual Final*

Nossa equipe teve diversas ideias para a criação do que seria o nosso site e nossa API, alguns deram ideias parecidas e ouros deram ideias diferente, nossa squad 3 se reuniu com o objetivo de pensar e criar algo que fosse de interessante para o governo ou algum órgão de educação que fosse acessível e de fácil acesso para todas as idades para a compreensão de todo público, principalmente com aqueles que apresentam alguma dificuldade em interagir com tecnologias diversas.
Aqui a baixo irei mostrar as diversas ideias que teve na equipe:

•	**Uma das ideias**: Uma ideia de criar uma API, que organizasse e auxiliasse o publico no geral a encontrar shoppings/cinemas, poder comprar os ingressos, comprar alimentos, brindes e claro que mostrasse quais filmes estarão em cartaz e de extra que mostrasse datas de próximos lançamentos que terão ainda no ano.

•	**Outra ideia foi**: Uma ideia de criar um site com API focado em realização de provas relacionadas a órgãos de educação e de pré-militar.

•	**Ideia final**: Foi a ideia escolhida, que estamos utilizando e que irá ser apresentada no projeto final.


# [ API ] Programadores Cariocas
### 📑 Descrição
Desenvolvimento da <em>**API REST**</em> no **padrão MVC** que retorna informações das entidades de um aplicatico de administrção que efetua todas as operações **CRUD**: `polos`, `candidatos`, `resultados`, `zonas` e `login`.

**[ Tecnologias ]**

<samp>
  
- <em>Node.js</em> | <em>MySQL</em> | <em>Express</em> | <em>Postman</em> | <em>CORS</em> | <em>Nodemon</em>
  
</samp>

## Rotas CRUD

### [ 1 ] <em>polos</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
| **`GET`** | **/polos** | Retorna todos os polos. |
|  **`GET`** | **/polos/id** | Retorna um polo específico. |
|  **`POST`** | **/polos** | Cria um novo polo. |
|  **`PUT`** | **/polos/id** | Altera os dados de um polo. |
|  **`DELETE`** | **/polos/id** | Remove um polo. |
  
### [ 2 ] <em>candidatos</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/candidatos** | Retorna todos os candidatos. |
|  **`GET`** | **/candidatos/id** | Retorna um candidato específico. |
|  **`POST`** | **/candidatos** | Cria um novo candidato. |
|  **`PUT`** | **/candidatos/id** | Altera os dados de um candidato. |
|  **`DELETE`** | **/candidatos/id** | Remove um candidato. |
  
  
### [ 3 ] <em>resultados</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/resultados** | Retorna todos os resultados. |
|  **`GET`** | **/resultados/id** | Retorna um resultado específico. |
|  **`POST`** | **/resultados** | Cria um novo resultado. |
|  **`PUT`** | **/resultados/id** | Altera os dados de um resultado. |
|  **`DELETE`** | **/resultados/id** | Remove um resultado. |


### [ 4 ] <em>zonas</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/zonas** | Retorna todas as zonas. |
|  **`GET`** | **/zonas/id** |  Retorna uma zona específica. |
|  **`POST`** | **/zonas** | Cria uma nova zona. |
|  **`PUT`** | **/zonas/id** | Altera os dados de uma zona. |
|  **`DELETE`** | **/zonas/id** | Remove uma zona. |
  

### [ 5 ] <em>login</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
| **`POST`** | **/login** | Realiza o login na API e retorna um token JWT. |
