## Rafaela Godoy Pratas
Bem-vindo ao Rafaela Godoy Pratas! Este projeto tem como objetivo criar e-commerce de venda de pratas.

***Instalação***

Para executar este projeto localmente, siga estas etapas:

**1** Clone este repositório em sua máquina local.

git clone https://github.com/luizarn/rafaelagodoypratas-back.git

**2** Acesse o diretório do projeto.

cd rafaelagodoypratas-back

**3** Instale as dependências necessárias.

npm install

**4** ajuste as variáveis de ambiente seguindo o .env.example.

**5** Inicie o projeto.
npm run dev

***Funcionalidades***

Aqui estão algumas das principais funcionalidades oferecidas por este e-commerce:

* Autenticação: Os usuários precisam estar logados para realizar compras e adicionar produtos ao carrinho.
* Administração: Os administradores têm acesso a uma página exclusiva onde podem visualizar todos os produtos da loja, bem como um resumo das informações de cada produto, incluindo nome, categoria, tag, estoque, destaque, lançamento, preço e descrição. Nessa página, os administradores também podem adicionar(o upload da imagem é feito via S3 na AWS), editar e excluir produtos.
* Compra de produtos: Os usuários logados podem adicionar produtos ao carrinho e realizar a compra(o MVP ainda não traz a funcionanidade de calcular o frete e efetuar o pagamento).
* Restrição de acesso: Apenas os usuários logados podem acessar determinadas funcionalidades, como adicionar produtos ao carrinho e realizar compras.
* Controle de estoque: O sistema mantém controle do estoque dos produtos, garantindo que apenas produtos em estoque possam ser adicionados ao carrinho.

  Essas são apenas algumas das funcionalidades disponíveis no site de venda de pratas. Sinta-se à vontade para explorar e descobrir mais recursos enquanto navega pela aplicação.

Segue link do repositório do **front-end** do projeto: https://github.com/luizarn/rafaelagodoypratas-front

