# 🎬 CineTech — Locadora Digital de Filmes

O **CineTech** é um projeto front-end de uma locadora digital de filmes. A interface permite explorar um catálogo organizado por gêneros, visualizar sinopses e navegar por uma seção dedicada a produtos temáticos.

O projeto foi desenvolvido com **HTML5 e CSS3**, com foco em uma apresentação visual inspirada em plataformas de entretenimento, navegação simples e adaptação para diferentes tamanhos de tela.

## ✨ Funcionalidades

- **Menu de navegação fixo** com links para as seções da página.
- **Carrossel de destaque** com banners informativos e transições automáticas.
- **Catálogo de filmes** organizado por categorias:
  - Ação
  - Aventura
  - Comédia
  - Terror
  - Ficção científica
  - Animação
- **Cards de filmes** com pôsteres, informações e sinopses.
- **Efeitos visuais ao passar o mouse**, incluindo troca de imagem e exibição da sinopse.
- **Layout responsivo**, com ajustes para desktops, tablets e celulares.
- **Seção de loja** para apresentar produtos temáticos.
- **Identidade visual escura**, com destaques em vermelho.

> **Observação:** o projeto é uma interface front-end. Os botões de disponibilidade, reserva ou compra não representam, por si só, uma integração com sistema de estoque, pagamentos ou reservas.

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura e conteúdo da página.
- **CSS3** — layout, cores, animações, efeitos de interação e responsividade.

O projeto não exige frameworks ou instalação de dependências para ser visualizado localmente.

## 📁 Estrutura do projeto

Organize os arquivos de forma semelhante à estrutura abaixo, mantendo os nomes e caminhos das imagens utilizados no HTML:

```text
CineTech/
├── index.html
├── style.css
└── imagens/
    ├── cinetech.png
    ├── loja.png
    ├── locadoraInterior.jfif
    └── ...
```

O catálogo utiliza várias imagens. Inclua também as demais imagens referenciadas no HTML e confira se os nomes dos arquivos e as letras maiúsculas/minúsculas correspondem exatamente aos caminhos definidos no código.

## 🚀 Como executar

1. Faça o download ou clone este repositório.
2. Confira se o arquivo principal está nomeado `index.html`.
3. Mantenha o arquivo `style.css` e a pasta de imagens nos caminhos esperados pelo HTML.
4. Abra `index.html` no navegador.

### Executar com Git

```bash
git clone URL_DO_SEU_REPOSITORIO
cd NOME_DO_REPOSITORIO
```

Depois, abra o arquivo `index.html` no navegador. Substitua `URL_DO_SEU_REPOSITORIO` e `NOME_DO_REPOSITORIO` pelos dados do seu repositório.

## 🎨 Personalização

- **Cores:** ajuste as variáveis CSS declaradas em `:root`, como `--bg-main`, `--accent-red` e `--text-primary`.
- **Filmes:** edite os cards no `index.html`, alterando títulos, anos, gêneros, sinopses e imagens.
- **Banners:** troque as imagens de fundo das classes `.slide-1`, `.slide-2` e `.slide-3` no `style.css`.
- **Responsividade:** ajuste as media queries no final do arquivo `style.css`.

## 📌 Melhorias futuras

- Implementar busca e filtros de filmes.
- Integrar os botões de disponibilidade a um sistema real de catálogo e estoque.
- Criar um fluxo funcional de reservas.
- Integrar a loja a um carrinho e a um sistema de pagamento.
- Melhorar a acessibilidade e o suporte à navegação por teclado.

##
Desenvolvido como projeto front-end para explorar HTML, CSS, organização de conteúdo e design responsivo.
