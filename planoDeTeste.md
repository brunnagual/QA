# 1. UI TESTING

1.2.1 Login com diferentes tipos de usuários disponíveis

---

standard_user:
-

- Faz o login corretamente

1.2.2 Ordenação e filtragem de produtos:
- Ordena corretamente.

1.2.3 Fluxo completo de compra (do carrinho até finalização):
- Finaliza até o carrinho de compras.

1.2.4 Remoção de itens do carrinho:
- Consigo remover do carrinho.

1.2.5 Navegação entre páginas:
- Navergação entre as paginas funcionando corretamente.

1.2.6 Logout:
- Logout realizado com sucesso.

----
locked_out_user
-
- Retorna com erro já na pagina inicial e não permite o login.

![img.png](img.png)

----
problem_user
- 
- Contém apenas foto de cachorro.

![img_4.png](img_4.png)

1.2.2 Ordenação e filtragem de produtos:
- Não filtra e nem ordena.

1.2.3 Fluxo completo de compra (do carrinho até finalização):
- Não consigo cadastrar usuário ele não deixa colocar o sobrenome.

![img_18.png](img_18.png)

1.2.4 Remoção de itens do carrinho:
- Permite remover o item corretamente

1.2.5 Navegação entre páginas:
- Navegação funciona.

1.2.6 Logout:
- Logout realizado com sucesso.

----
performance_glitch_user
-

1.2.2 Ordenação e filtragem de produtos:
- Ele filtra e ordena mas com lentidão.

1.2.3 Fluxo completo de compra (do carrinho até finalização):
- Funcionando mas com lentidão.

![img_19.png](img_19.png)

1.2.4 Remoção de itens do carrinho:
- Funcionando.

1.2.5 Navegação entre páginas:
- Contém erro no JS, mas não interfere na navegação.

![img_1.png](img_1.png)

1.2.6 Logout:
- Logout realizado com sucesso.

----
error_user
-

- Possui um erro que ocorre em todos os usuários, na descrição do produto informa o código da pagina.

![img_2.png](img_2.png)

1.2.2 Ordenação e filtragem de produtos:
- Não ordena retorna com erro.

![img_5.png](img_5.png)

1.2.3 Fluxo completo de compra (do carrinho até finalização):
- Não permite cadastrar o sobrenome e por esse motivo não permite avançar o status da compra.

![img_20.png](img_20.png)

1.2.4 Remoção de itens do carrinho:
- É possivel remover os itens.

1.2.5 Navegação entre páginas:
- Funcionando.

1.2.6 Logout:
- Logout realizado com sucesso.

----
visual_user
-
![img_3.png](img_3.png)

1.2.2 Ordenação e filtragem de produtos:
- Funcionando.

1.2.3 Fluxo completo de compra (do carrinho até finalização):

![img_22.png](img_22.png)

1.2.4 Remoção de itens do carrinho:
- Consigo remover o item do carrinho.

1.2.5 Navegação entre páginas:
- O checkout está com bug visual indo para o canto superior da tela

![img_21.png](img_21.png)

1.2.6 Logout:
- Logout realizado com sucesso.

----
# 2. API TESTING

2.2.1.1 Gerar token de autenticação:
- Token gerado com sucesso.

![img_6.png](img_6.png)

2.2.1.2 Tentar gerar token com credenciais inválidas:
- Requisição bloqueada corretamente.

![img_7.png](img_7.png)

2.2.2 Gestão de reservas:
-
2.2.2.1 Criar uma nova reserva:
- Reserva criada com sucesso.

![img_8.png](img_8.png)

2.2.2.2 Buscar uma reserva específica:
- Reserva localizada corretamente.

![img_11.png](img_11.png)

2.2.2.3 Listar todas as reservas:
- Reservas listadas com sucesso.

![img_12.png](img_12.png)

2.2.2.4 Atualizar uma reserva existente:
- Atualização proibida.

![img_13.png](img_13.png)

2.2.2.5 Deletar uma reserva:
- Deleção proibida.

![img_14.png](img_14.png)


2.2.3 Filtros e buscas:
2.2.3.1 Buscar reservas por nome:
- Funcionando corretamente.

![img_15.png](img_15.png)

2.2.3.2 Buscar reservas por data de check-in:
- Funcionando corretamente.
  ![img_16.png](img_16.png)

2.2.3.3 Buscar reservas por data de check-out:
- Funcionando corretamente.

![img_17.png](img_17.png)

----
1.3.1.3 Sugestões de melhorias de UX/UI.

- Encontramos algumas inconsistências em alguns usuários onde a navegação não estava funcionando corretamete. E também identificamos que para casos de sites de compras talvez não seja o mais interessante utilizar o menu sanduiche.

1.3.1.4 Lista de bugs encontrados (se houver).

Na navegação em um dos logins possui um bug que dificulta a navegação.

- Imagens incorretas em determinados usuários.
- Erros de ordenação e filtragem para alguns usuários.
- Persistência de itens no carrinho após logout.

![img_23.png](img_23.png)

1.3.1.5 Análise de riscos da aplicação:

- Identificamos uma falha de segurança expos todos os id existentes, isso pode comprometer e ocorrer um vazamento de dados.

![img_10.png](img_10.png)

- Foi feito teste passando o mesmo id de uma reserva criada, mas teve um bom resultado

![img_9.png](img_9.png).

1.3.2.1 Testes de responsividade:

- Testes preliminares foram realizados com sucesso, interface responsiva.

1.3.2.2 Testes de acessibilidade:
- Testes preliminares indicam que a acessibilidade está processada no backend.
