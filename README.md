# Django site de receitas
Nome: João Roizen Fontana - 1710431

## Sobre:

Foi criado um WebSite de receitas, onde os usuários podem compartilhar receitas, ver receitas novas e comentar.

## Escopo:

O WebSite permite que os usuários vejam receitas salvas de outros usuários e comentem nelas. Além disso, os usuários podem criar uma conta para publicarem suas próprias receitas, podendo editar/atualizar elas e deletar.

Obs: pelo fato de  conter as quatro operações básicas em banco de dados (CRUD) na administração das receitas de cada usuário, onde eles podem criar, editar, deletar e ler as receitas, não foi implementado a parte de edição da conta do usuário, como mudança de senha, a fim de simplificar um pouco pois realizei o projeto sozinho.

### Modo de uso:

O WebSite foi pensado como um local onde usuários vão para conhecer receitas novas e compartilhar, então ao entrar no site a página inicial é um conjunto de todas as receitas, contendo o título dela e o usuário que a criou. Mesmo sem estar logado, é possível ver as receitas e comentar nelas, pois dessa maneira acredito que cumpra da melhor maneira o propósito proposto. 

Caso o usuário queiro compartilhar uma receita sua, ele utiliza a barra de navegação para ir a sessão de 'Register' para criar sua conta, onde ele vai fornecer um Username e uma senha, ele também pode ir a parte de 'Login' e clicar em 'Cadastre-se' para realizar o mesmo processo.

Uma vez que ele esteja logado em sua conta, esse usuário agora pode compartilhar a sua receita, indo na parte de 'Adicionar Receita' na barra de navegação, onde ele irá dar um título e o passo a passo da sua receita. Agora, ele também pode editar, apenas as suas receitas, para atualizar ou corrigir alguma questão e ele pode também deletar ela caso queira. As opção ficam claras na página inicial, onde apenas as receitas postadas por ele terão a opção de editar e deletar.
