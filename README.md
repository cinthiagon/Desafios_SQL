# Formação SQL Database Specialist - Digital Innovation One (DIO)

## Desafio 001 - Modelagem EER de um banco de dados de E-commerce com os seguintes requisitos:

1. Produto:

   1.1. Vendido por uma única plataforma online; <br>
   1.2. Não pode ser vendido por terceiros; <br>
   1.3. Possui um único fornecedor; <br>
   1.4. Um ou + produtos podem compor um pedido; <br>

3. Estoque e fornecedor: 

    A desenvolver. 

4. Pedido:

   1.1. Criado pelo Cliente; <br>
   1.2. Informações de compra, endereço & status da entrega; <br>
   1.3. Pode ser cancelado; <br>
   1.4. Formas de pagamento; <br>
   1.5. Frete; <br>
   1.6. Status do pedido; <br>
   1.7. Código de Rastreio; <br>

5. Cliente:

   1.1. Pode ser Pessoa Física OU Jurídica (não os dois); <br>
   1.2. Endereço determina o valor do frete; <br>
   1.3. Pode fazer mais de um pedido; <br>
   1.4. Tem período de carência para acionar a devolução.<br>

   -------------------

## Desafio 002 - Modelagem EER de um banco de dados de um gerenciamento de oficina mecânica.

Agora você irá criar um esquema conceitual do zero. A partir da narrativa fornecida você será capaz de criar todas as entidades, relacionamentos e atributos. Caso encontre algo que não foi definido na narrativa, utilize a sua compreensão do contexto e deixe uma descrição no README do seu github. para verificação.

O esquema deverá ser adicionado a um repositório do Github para futura avaliação do desafio de projeto. Adicione ao Readme a descrição do projeto conceitual para fornecer o contexto sobre seu esquema.

**1. Objetivo: <br>**

Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida. <br>

**3. Narrativa: <br>**

   Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
   Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
   Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
   A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
   O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
   A mesma equipe avalia e executa os serviços
   Os mecânicos possuem código, nome, endereço e especialidade
   Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

_Agora é a sua vez de ser o protagonista! Implemente o desafio sugerido pela expert e suba seu projeto para um repositório próprio, com isso, você aumentará ainda mais seu portfólio de projetos no GitHub!_
