# 1)
Apenas uma suite de testes, estou testando apenas um sistema, com 6 casos de teste diferentes. 

# 2)
Automatizados, apesar de não estarem integrados em uma pipeline de CI/CD as validações e assertions são feitas de forma automatica. 
Seriam considerados manuais, se fossem feitos utilizando o proprio sistema com um humano realizando as ações e verificando os resultados. 

# 3)
Os testes estão no meio da piramide pois são testes de api. Estariam no topo da piramide se fossem testes end to end. ou abaixo caso fossem testes de unidade.

# 4)
Ambos na minha suite de testes inclui tanto validações que testam o comportamento da api em termos de funcionalidade, como validar os campos da resposta. quanto validações que testam o desempenho da api como testes de performance, tempo esperado de resposta.

# 5)
Não, nenhum unico teste abrange todo o fluxo de vida de um dado. A suite pode ser rodada com alvo em um unido dado, sendo criado, recuperado, atualizado e excluido. Mas não temos informações sobre como o dado se comporta no backend ou no banco de dados. 

# 6) 
Devemos integrar essa suite de testes em uma pipeline de CI/CD como github actions, assim quando uma atualização na api for realizada poderemos realizar a mesma bateria de testes e verificar a sanidade da regressão. 