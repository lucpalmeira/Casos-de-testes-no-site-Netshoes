Nesse projeto será feito um caso de teste funcional (teste de caixa preta)no site de compras da Netshoes utilizando a técnica BDD. Será uma descrição simples porém de valor para o usuários reais. Será descrito um comportamento do sistema a partir da perspectiva do usuário.

- Como um cliente da Netshoes.
- Eu quero acessar o site.
- Para que eu possa efetuar compras.

CENÁRIO 1: login com e-mail inválido

- Dado que estando na tela de login
- Quando preencher o campo de usuário com e-mail sem o @
- Então o sistema irá exibir no campo de usuário "e-mail inválido"

CENÁRIO 2: login com e-mail e senha válido

- Dado que estando na tela de login
- Quando preencher o campo de usuário com e-mail e senha
- Então serei direcionado para a página de compras.

CENÁRIO 3: Adicionar produtos no carrinho

- Dado que eu escolha o produto desejado
- Quando clicar no produto
- E clicar em comprar
- E escolher mais produtos
- Então os produtos escolhidos estarão em uma única compra

CENÁRIO 4: Remover produtos do carrinho

- Dado que eu acesse o ícone do carrinho
- Quando clicar em remover todos os produtos adicionados
- Então deverá exibir a mensagem: "seu carrinho está vazio"
