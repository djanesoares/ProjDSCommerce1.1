Projeto Spring Boot - DSCommerce

Foi desenvolvido um sistema em Java com framework Spring Boot para ser utilizado nos curso como apoio no processo de aprendizado. A concepção e implementação do sistema seguiram as seguintes premissas:

•	O sistema contou com um modelo de domínio abrangente, explorando diversos tipos de relacionamentos entre entidades de negócio, como muitos-para-um e muitos-para-muitos.

•	Durante o desenvolvimento, foram aplicados conhecimentos fundamentais das disciplinas introdutórias, reforçando a base técnica necessária.

•	O sistema implementou as principais funcionalidades esperadas, incluindo telas de cadastro e fluxos completos de casos de uso.

2. Visão geral do sistema
O sistema deve possui um cadastro de usuário, produtos e suas categorias.
Cada usuário possui nome, email, telefone, data de nascimento e uma senha de acesso. Os dados dos produtos são: nome, descrição, preço e imagem.

O sistema apresenta um catálogo de produtos, os quais podem ser filtrados pelo nome do produto.
A partir desse catálogo, o usuário pode selecionar um produto para ver seus detalhes e para decidir se o adiciona a um carrinho de compras.
 O usuário pode incluir e remover itens do carrinho de compra, bem como alterar as quantidades de cada item. Uma vez que o usuário decida encerrar o pedido, o pedido deve então ser salvo no sistema com o status de "aguardando pagamento".

 3. Modelo conceitual
  <img width="604" height="262" alt="image" src="https://github.com/user-attachments/assets/0c7c7eae-f69f-49f7-8717-bcc8d7b78277" />

  <img width="570" height="266" alt="image" src="https://github.com/user-attachments/assets/fb297812-cc6d-4313-b365-a234a195da70" />

  <img width="958" height="498" alt="image" src="https://github.com/user-attachments/assets/e01a8af2-1aec-4326-bcff-fc77d92a6ba3" />

  <img width="955" height="493" alt="image" src="https://github.com/user-attachments/assets/749f3e02-ce53-4008-98fb-5c46fac09071" />





