# TrabalhoS206
Repositorio para os arquivos do trabalho de S206


### 
Os arquivos da colection e da run dos testes estão no repositorio. 
Para Rodar os casos individualmente deve se atentar a alguns detalhes para os metodos de delete e put.

-Ambos os metodos precisam de receber um Id como parametro no final da url. Pode ser usado o Id retornado pela chamada de "CreateBooking"
-Ambos os metodos precisam do token retornado pelo primeiro request, "CreateToken" Basta substituir o token atual nos headers pelo novo gerado. 
O token dura 5 min pelos meus testes. 

### 
Para executar o relatorio de testes basta criar um novo token, e atualizar os Ids nos metodos de put e delete caso ja tenham sido executados antes. Com isso pode selecionar a opção "Run collection" clicando com o botão direito na collection.

## Link para api utilizada: https://restful-booker.herokuapp.com/apidoc/index.html