# Cantinho da Lu

Loja virtual feita com HTML, CSS, JavaScript e Bootstrap.

## Sobre o projeto

O Cantinho da Lu é uma loja virtual desenvolvida com HTML, CSS, JavaScript e Bootstrap. O site apresenta um catálogo de produtos de beleza, artigos para casa e roupas, e permite que o cliente entre em contato diretamente com a vendedora para fazer seu pedido.

## Objetivo

O Cantinho da Lu foi criado para facilitar a vida de quem vende e de quem compra. Para a vendedora, é uma vitrine online que divulga os produtos de forma organizada. Para o cliente, é um catálogo com visual limpo e navegação fácil, que permite escolher o que deseja e entrar em contato direto para fechar o pedido.

## Público Alvo

O Cantinho da Lu é voltado para pessoas que amam se cuidar e buscam produtos práticos e de qualidade para o dia a dia, como beleza, itens para casa e roupas. É ideal para quem prefere escolher com calma, de onde estiver, e já falar direto com a vendedora.

## Tecnologias utilizadas

- HTML5
- CSS3
- Bootstrap 5

## Estrutura do site

O site possui as seguintes áreas:

- **Cabeçalho:** apresenta a logo da loja, o menu de categorias por marca, o carrinho e a barra de pesquisa.
- **Menu:** permite navegar pelas marcas O Boticário, Natura, Avon e DeMillus e suas categorias de produtos.
- **Barra de promoção:** apresenta os cupons de desconto para compras acima de R$ 199 e R$ 299.
- **Banner:** apresenta imagens em destaque em um carrossel com troca automática.
- **Mais vendidos:** apresenta os produtos mais procurados, com imagem, descrição, preço e botão de compra.
- **Promoções do dia:** apresenta produtos em oferta com preços especiais.
- **Benefícios:** apresenta um carrossel com destaques dos produtos e do cuidado pessoal.
- **Rodapé:** apresenta informações sobre a loja, links de navegação, ajuda, contato e redes sociais.


## Estrutura de pastas

LojaVirtual/
├── Public/
│   └── Assents/     
├── index.html
├── Style.css
└── README.md

## Responsividade

O site foi desenvolvido para se adaptar a diferentes tamanhos de tela, como celulares, tablets e computadores, usando o sistema de grid e os componentes do Bootstrap.

## Acessibilidade

- **Idioma definido:** a página declara `lang="PT-BR"`, o que ajuda leitores de tela a pronunciarem o texto corretamente.
- **Estrutura semântica:** uso de `header`, `nav`, `main`, `section` e `footer`, além de títulos hierárquicos (`h2`, `h3`, `h5`).
- **Textos alternativos:** a logo, os ícones de carrinho e lupa e as imagens dos produtos possuem o atributo `alt`.
- **Rótulos para leitores de tela:** botões e links sem texto visível, como o menu hambúrguer e os ícones de redes sociais, possuem `aria-label`.
- **Campo de busca:** o formulário usa `role="search"` para ser identificado como área de pesquisa.
- **Navegação por teclado:** menus, dropdowns e carrosséis do Bootstrap podem ser usados com o teclado.
- **Layout responsivo:** o conteúdo se adapta a diferentes telas, o que também ajuda quem usa zoom ou dispositivos menores.

  ## Dificuldades encontradas

- **Organizar os cards de produtos:** manter todos os cards com o mesmo tamanho, com imagem, descrição, preço e botão alinhados. Resolvi usando o grid do Bootstrap (`row`, `col`) junto com `h-100` e `mt-auto`, que mantêm a altura igual e o botão sempre na base do card.
- **Ajustar imagens de tamanhos diferentes:** as fotos dos produtos tinham proporções variadas e deformavam nos cards. Resolvi com `height: 250px` e `object-fit: contain`, que mantêm a proporção sem cortar a imagem.
- **Menu fixo cobrindo o conteúdo:** ao usar `fixed-top` na barra de navegação, ela passou a cobrir o início da página. Foi preciso ajustar o espaçamento superior no CSS.
- **Paleta de cores:** manter uma identidade visual rosa e consistente no cabeçalho, nos cards, nos botões e no rodapé, combinando o CSS próprio com as classes do Bootstrap.

## Melhorias futuras

Pretendo evoluir o projeto com as seguintes melhorias:

- **Integração com o WhatsApp:** adicionar um botão nos produtos para o cliente enviar o pedido direto para a vendedora, já com o nome do item.
- **Banco de dados:** armazenar produtos, preços e clientes, para não precisar alterar o código a cada mudança no catálogo.
- **API:** criar uma API para conectar o site ao banco de dados e carregar os produtos de forma dinâmica.
- **Login e cadastro de clientes:** permitir que o cliente tenha uma conta, com dados e histórico de compras salvos.
- **Sistema de pedidos:** registrar e acompanhar os pedidos feitos pelo site.
- **Controle de estoque e prazos:** mostrar a disponibilidade dos produtos e o prazo estimado de entrega.
- **Pagamentos online:** permitir pagar pelo próprio site, com opções como Pix e cartão.
- **Segurança:** proteger os dados dos clientes, com senhas criptografadas e conexão segura (HTTPS).


