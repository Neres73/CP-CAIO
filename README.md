# 🏠 Airbnb Clone — Página de Anúncio em HTML e CSS

Landing page estática que reproduz um anúncio real de apartamento do Airbnb, feita para o checkpoint de Front-end Design da FIAP.

**🔗 Ver online:** https://neres73.github.io/CP-CAIO/

---

## Sobre o projeto

O objetivo era aplicar os fundamentos de front-end vistos em aula reconstruindo a estrutura e o visual de uma página real, sem framework e sem JavaScript: só HTML semântico e CSS.

## O que a página tem

- **Cabeçalho** com logo, busca e menu
- **Título do anúncio** e **galeria com cinco fotos** do imóvel
- **Descrição** e **detalhes da hospedagem** (tipo de acomodação, hóspedes, quartos e banheiros)
- **Comodidades** do imóvel
- **Avaliações** de hóspedes
- **Rodapé**

## Como foi feito

- **HTML5 semântico**: `header`, `main`, `section` e `footer`
- **CSS externo** em `style.css`, com tipografia **Poppins** do Google Fonts
- **Flexbox** para a barra de navegação e os alinhamentos, e **CSS Grid** para a galeria de fotos e as avaliações
- **Mobile first**: o layout base é para celular e se reorganiza a partir de 768px de largura

## Estrutura

```
├── index.html
├── style.css
├── apartamento/   # fotos do imóvel e das avaliações
├── icone/         # ícones de navegação
└── imgs/          # logo e ícones do cabeçalho
```

## Como rodar

Não precisa de instalação: abra o `index.html` no navegador ou acesse o link do GitHub Pages.

---

**Integrantes:** Gustavo Neres dos Santos (RM561785) · Rafaell Santiago Martins da Silva (RM563486)

Projeto acadêmico. A marca, as imagens e o conteúdo do anúncio pertencem ao Airbnb e ao anfitrião do [anúncio original](https://www.airbnb.com.br/rooms/30497949) e foram usados apenas para fins de estudo.
