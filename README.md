# Castelo Animado - Site Informativo

Projeto desenvolvido para apresentar informacoes sobre o filme **Castelo Animado**, seus personagens, curiosidades.

## Objetivo

Projetar e desenvolver um site completo. Tema escolhido foi o filme Castelo animado de 2004. 

## Escopo

- Secao inicial com destaque para o filme.
- Secao de personagens com cards, imagens e descricao.
- Secao de curiosidades sobre origem, producao e mensagem do filme.
- Secao sobre o Studio Ghibli, sua identidade e o Ghibli Park.
- Modais "Saiba mais" para detalhamento de cada conteudo.
- Animacoes vinculadas a rolagem da pagina.
- Navegacao por links internos no menu.
- Footer com credito do desenvolvedor.

## Pilares do Projeto

- **Clareza visual:** informacoes organizadas em cards e modais para facilitar leitura.
- **Consistencia:** secoes, titulos, cards e botoes seguem o mesmo padrao visual.
- **Responsividade:** uso do grid do Bootstrap para adaptar os cards em diferentes telas.
- **Acessibilidade:** modais Bootstrap com estrutura semantica, botoes claros e textos com contraste.
- **Experiencia do usuario:** animacoes suaves, navegacao por ancora e conteudo progressivo.

## Paleta de Cores

- Azul escuro: `#102a43`
- Azul textual: `#243b53`
- Verde suave: `#375f44`
- Azul claro: `#e7f3f8`
- Verde claro: `#eef6f1`
- Branco de apoio: `#f8f9fa`
- Branco translúcido: `rgba(255, 255, 255, 0.78)`

A paleta foi escolhida seguindo os conceitos da Heuristicas de Nielsen

## Tipografia

O projeto utiliza a tipografia padrao do Bootstrap, baseada em fontes do sistema. Essa escolha favorece:

- boa legibilidade;
- carregamento rapido;
- consistencia entre navegadores;
- aparencia limpa e familiar.

Os pesos variam entre `500`, `600`, `700` e `800` para criar hierarquia entre titulo, subtitulo, descricao e botoes.

## Frameworks e Tecnologias

- **React:** construcao da interface por componentes.
- **TypeScript:** tipagem dos componentes, props e funcoes de animacao.
- **Vite:** ambiente de desenvolvimento e build.
- **Bootstrap:** grid responsivo, navbar, botoes, cards e modais.
- **React Icons:** icone da navbar.
- **CSS customizado:** fundos, gradientes, animacoes, contraste e ajustes visuais.

## Estrutura Principal

- `src/main.tsx`: renderizacao das secoes e dados dos cards.
- `src/components/Nav.tsx`: menu de navegacao.
- `src/components/Card.tsx`: card principal da primeira secao.
- `src/components/InfoCard.tsx`: card reutilizavel para personagens, curiosidades e studio.
- `src/components/ModaInfo.tsx`: modal de detalhamento.
- `src/scrollAnimation.ts`: animacao de entrada e controle do link ativo da navbar.
- `src/style.css`: estilos globais, secoes, cards, modais e responsividade.

## Como Executar

```bash
npm install
npm run dev
```

Para gerar a versao de producao:

```bash
npm run build
```
