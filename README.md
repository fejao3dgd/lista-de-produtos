# Lista de Produtos

Vitrine estática de produtos (camisas e moletons com estampas de programação/TI e outros), organizada por categoria.

*Não é uma loja*: não há carrinho, cadastro, pagamento ou backend. Cada card mostra imagem, nome e preço, e o botão "Ver Camisa" apenas redireciona para a página do produto na loja oficial do produto externa, onde a compra de fato acontece.

## O que é

Uma página de catálogo em HTML e CSS puros, pensada como vitrine/curadoria: reúne produtos de vários sites, organizados por categoria, para facilitar a navegação de quem está procurando entre produtos.

## Estrutura


.
├── index.html                  # Página inicial com as categorias
├── style.css                   # Estilos globais (tema escuro)
├── categories/
│   ├── shirt-list.html         # Vitrine de camisas
│   └── hoodie-list.html        # Vitrine de moletons
└── image/
    ├── shirt-icon.png          #icones usados 
    ├── hoodie-icon.png


## Como funciona

1. index.html — tela inicial com as categorias: camisas e moletons e outras.
2. Ao escolher uma categoria, o usuário vê os produtos em cards (imagem, nome, preço).
3. Clicar em "Ver Camisa" abre a página de compra no site oficial da loja, externo — a vitrine não processa nada, só direciona.
4. Botão "VOLTAR" retorna para a tela de categorias.

## Como rodar

Sem build, sem dependências. Basta abrir index.html no navegador.

## Limitações atuais

- Sem JavaScript: nenhuma busca, filtro ou ordenação.
- Produtos, preços e links são fixos no HTML — adicionar/editar um item exige mexer direto no código.
- Não tem carrinho nem checkout: é vitrine pura, a venda é 100% no site externo.

## Possíveis evoluções

- Adicionar busca/filtro por categoria e faixa de preço.
