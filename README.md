Prova para desenvolvedor Júnior

Estou precisando de um sistema de fluxo de estoque de produtos, que eu possa dar baixa no estoque e repor os produtos, preciso que tenha o cadastro dos fornecedores dos produtos, produtos, compra de produto, baixa de produto no estoque.

Regras para o cadastro do produtos tabela produto: 
1 – Produtos não podem ser duplicados; 
2 – Verificar os campos obrigatório na base de dados;

Regras para o cadastro de usuários tabela usuario: 
1 – Usuário não podem ser duplicados; 
2 – Verificar os campos obrigatório na base de dados;

Regras para o cadastro do fornecedores tabela fornecedor: 
1 – CPF não podem ser duplicados; 
2 – Verificar os campos obrigatório na base de dados;

Regras para o compra de produtos tabela compra: 
1 – O sistema cadastra somente 50 unidade de cada item por dia caso tente cadastrar mais não pode permitir; 
2 – Ao fazer a compra, cadastrar na tabela ( produto_estoque ) quantidade de produtos que irão ter no estoque no campo ( quantidade );

Regras para a baixa do produto no estoque: 
1 – Ele não pode solicitar baixa ultrapassando a quantidade de produto que tem no estoque; 
2 – Ao fazer a solicitação de baixa, cadastrar na tabela ( produto_estoque ) quantidade de produtos que irão ter no estoque no campo ( quantidade_baixa )

Use no client-side framework como Bootstrap e para envio dos dados para o servidor use Jquery.js ou Angular.js. Na parte do server-side, use uma linguagem ou algum framework de sua preferência para criar uma pequena api, onde irá receber suas requisições.

Crie um banco de dados no Mysql com o SQL que está no repositório.

OBS.: o envio dos dados dos formulários e a listagem na tabela deverá ser feito via Jquery.js ou Angular.js. Crie as telas pensando no usuário final. Então não basta apenas fazer o cadastro de qualquer jeito. Pense em aspectos como usabilidade, layout etc.

Ao terminar sua prova envie o seu repositorio da prova para fazer a avaliação. Coloque um README para informar o que é necessario para executar o seu código.
