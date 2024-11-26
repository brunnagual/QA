1. UI TESTING

1.2.1 Login com diferentes tipos de usuários disponíveis

standard_user: 
-
Faz o login corretamente

1.2.2 Ordenação e filtragem de produtos: Ordena corretamente.

1.2.3 Fluxo completo de compra (do carrinho até finalização): Finaliza até o carrinho de compras.

1.2.4 Remoção de itens do carrinho: Consigo remover do carrinho.

1.2.5 Navegação entre páginas: Navergação entre as paginas funcionando corretamente.

1.2.6 Logout: Também desloga.

----
locked_out_user
-
![img.png](img.png)

1.2.6 Logout: Apenas desloga.

----
problem_user
- 
Contém apenas foto de cachorro.

![img_4.png](img_4.png)

1.2.2 Ordenação e filtragem de produtos:  Não filtra e nem ordena.

1.2.3 Fluxo completo de compra (do carrinho até finalização):
Não consigo cadastrar usuário ele não deixa colocar o sobrenome.

![img_18.png](img_18.png)

1.2.4 Remoção de itens do carrinho: Permite remover o item corretamente

1.2.5 Navegação entre páginas: Navegação funciona.

1.2.6 Logout: Também desloga.

----
performance_glitch_user
-

1.2.2 Ordenação e filtragem de produtos: Ele filtra e ordena mas com lentidão.

1.2.3 Fluxo completo de compra (do carrinho até finalização): Funcionando mas com lentidão.

![img_19.png](img_19.png)

1.2.4 Remoção de itens do carrinho: Funcionando.

1.2.5 Navegação entre páginas: Contém erro no JS, mas não interfere na navegação.

![img_1.png](img_1.png)

1.2.6 Logout: Também desloga.

----
error_user
-
Possui um erro que ocorre em todos os usuários, na descrição do produto informa o código da pagina.

![img_2.png](img_2.png)

1.2.2 Ordenação e filtragem de produtos: Não ordena retorna com erro.

![img_5.png](img_5.png)

1.2.3 Fluxo completo de compra (do carrinho até finalização): Não permite cadastrar o sobrenome e por esse motivo não permite avançar o status da compra.

![img_20.png](img_20.png)

1.2.4 Remoção de itens do carrinho: É possivel remover os itens.

1.2.5 Navegação entre páginas: Funcionando.

1.2.6 Logout: Também desloga.

----
visual_user
-
![img_3.png](img_3.png)

1.2.2 Ordenação e filtragem de produtos: Funcionando.

1.2.3 Fluxo completo de compra (do carrinho até finalização):

![img_22.png](img_22.png)

1.2.4 Remoção de itens do carrinho: Consigo remover o item do carrinho.

1.2.5 Navegação entre páginas: O checkout está com bug visual indo para o canto superior da tela

![img_21.png](img_21.png)

1.2.6 Logout: Também desloga.

----
2. API TESTING

2.2.1.1 Gerar token de autenticação: Foi possivel gerar o token sem divergências

![img_6.png](img_6.png)

2.2.1.2 Tentar gerar token com credenciais inválidas: Bloqueou corretamente.

![img_7.png](img_7.png)

2.2.2 Gestão de reservas:
-
2.2.2.1 Criar uma nova reserva: Reserva criada

![img_8.png](img_8.png)

2.2.2.2 Buscar uma reserva específica: Foi possivel buscar corretamente.

![img_11.png](img_11.png)

2.2.2.3 Listar todas as reservas: Foi possível listar todas as reservas.

![img_12.png](img_12.png)

2.2.2.4 Atualizar uma reserva existente: Está proibido

![img_13.png](img_13.png)

2.2.2.5 Deletar uma reserva: Está Proibido

![img_14.png](img_14.png)


2.2.3 Filtros e buscas:
2.2.3.1 Buscar reservas por nome: Funcionando corretamente.

![img_15.png](img_15.png)

2.2.3.2 Buscar reservas por data de check-in: Funcionando corretamente.
![img_16.png](img_16.png)

2.2.3.3 Buscar reservas por data de check-out: Funcionando corretamente.

![img_17.png](img_17.png)

----
1.3.1.3 Sugestões de melhorias de UX/UI.

Encontramos u
1.3.1.4 Lista de bugs encontrados (se houver).

Na navegação em um dos logins possui um bug que dificulta a navegação.

Ocorreram alguns bugs na aplicação bugs visuais também encontramos alguns bugs quanto as imagens mostradas nos itens e na descrição dos itens. Todos detalhados separadamento em cada usuário.

Também identifiquei um bug que ao logar já entra com um item no carrinho. Quando adiciona, desloga e loga novamente o item permanece.

![img_23.png](img_23.png)

1.3.1.5 Análise de riscos da aplicação:

Falha se segurança expos todos os id existentes, isso pode comprometer e ocorrer um vazamento de dados.

![img_10.png](img_10.png)

Foi feito teste passando o mesmo id de uma reserva criada, mas teve um bom resultado

![img_9.png](img_9.png).

1.3.2.1 Testes de responsividade:

Foi feito teste de responsividade e vimos que está funcionando.

1.3.2.2 Testes de acessibilidade:

Tentei testar a acessibilidade mas parece estar sendo processado no backend.




